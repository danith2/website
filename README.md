<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Link Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 400px;
            margin: 50px auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: translateY(-20px); }
            to { opacity: 1; transform: translateY(0); }
        }
        .profile-img {
            width: 100px;
            height: 100px;
            background: black;
            border-radius: 50%;
            margin: 0 auto 15px;
            animation: scaleUp 1s ease-in-out;
        }
        @keyframes scaleUp {
            from { transform: scale(0.8); }
            to { transform: scale(1); }
        }
        h2 {
            margin: 0;
        }
        .social-links {
            margin-top: 20px;
            background: #eaeaea;
            padding: 15px;
            border-radius: 10px;
        }
        .social-links a {
            display: flex;
            align-items: center;
            text-decoration: none;
            color: black;
            background: white;
            padding: 10px;
            border-radius: 5px;
            margin: 10px 0;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease-in-out;
        }
        .social-links a:hover {
            transform: scale(1.05);
        }
        .social-links a img {
            width: 24px;
            height: 24px;
            margin-right: 10px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="profile-img"></div>
        <h2>COpyRight</h2>
        <p>Graphic Designer</p>
        
        <div class="social-links">
            <h3>MY SOCIAL MEDIA</h3>
            <a href="https://www.facebook.com/share/19Hm2jidtD/?mibextid=wwXIfr" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/5/51/Facebook_f_logo_%282019%29.svg" alt="Facebook">
                Dänit
            </a>
            <a href="#" target="_blank">
                <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Telegram_logo.svg" alt="Telegram">
                COpyRight
            </a>
        </div>
    </div>
</body>
</html>
