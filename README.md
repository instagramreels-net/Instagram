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
        }

        @keyframes gradientMove {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .message {
            font-size: 28px;
            font-weight: bold;
            margin-top: 20px;
            text-shadow: 2px 2px 5px rgba(0, 0, 0, 0.7);
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

        /* Instagram logo in the top-right corner */
        .instagram-logo {
            position: fixed;
            top: 15px;
            right: 15px;
            width: 40px;
            height: 40px;
            z-index: 1000;
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

    <!-- Instagram Logo in the top-right corner -->
    <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram Logo" class="instagram-logo">

    <!-- Message -->
    <p class="message">🚀 idc.saksham sent you this 🚀</p>
</body>
</html>
