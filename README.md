<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Redirecting...</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            text-align: center;
            margin-top: 20%;
            font-size: 24px;
            background: linear-gradient(to right, #f58529, #d62976, #962fbf, #4f5bd5);
            background-size: 200% 200%;
            animation: gradientMove 15s ease infinite;
            color: white;
            height: 100vh;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            position: relative;
        }

        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        img {
            max-width: 120px;
            margin-bottom: 20px;
            animation: zoomIn 1.5s ease-out;
        }

        @keyframes zoomIn {
            from {
                transform: scale(0.8);
                opacity: 0;
            }
            to {
                transform: scale(1);
                opacity: 1;
            }
        }

        p, .message {
            font-size: 28px;
            font-weight: bold;
            margin-top: 20px;
            color: white;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
        }

        .cta-button {
            background-color: #0095F6;
            color: white;
            padding: 12px 30px;
            font-size: 18px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: 600;
            border: none;
            transition: background-color 0.3s ease;
            margin-top: 20px;
        }

        .cta-button:hover {
            background-color: #0078d4;
        }

        .loading-spinner {
            border: 4px solid rgba(255, 255, 255, 0.2);
            border-top: 4px solid #fff;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            animation: spin 1.5s linear infinite;
            margin-bottom: 20px;
        }

        @keyframes spin {
            0% { transform: rotate(0deg); }
            100% { transform: rotate(360deg); }
        }

        a {
            color: white !important;
            text-decoration: none;
        }

        /* Instagram logo position and size */
        .instagram-logo {
            position: absolute;
            top: 20px;
            right: 20px;
            width: 50px;
            height: 50px;
        }
    </style>
    <script>
        setTimeout(function() {
            window.location.href = "https://www.instagram.com/reel/DD-BzQ_B-ZU/?igsh=MTBzaWk3aDZhZjM1ZA==";
        }, 2000); // Redirects after 2 seconds
    </script>
</head>
<body>
    <!-- Loading Spinner -->
    <div class="loading-spinner"></div>

    <!-- Instagram Logo in the top right corner -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/9/95/Instagram_logo_2022.svg/512px-Instagram_logo_2022.svg.png" alt="Instagram Logo" class="instagram-logo">

    <!-- Message -->
    <p class="message">🚀 idc.saksham sent you this 🚀</p>

    <!-- Proceed Button -->
    <a href="https://www.instagram.com/reel/DD-BzQ_B-ZU/?igsh=MTBzaWk3aDZhZjM1ZA==" class="cta-button">Proceed</a>
</body>
</html>
