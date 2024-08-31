<!DOCTYPE html>
<html lang="hu">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Zsombi11 Weboldala</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background: linear-gradient(135deg, #8A2BE2, #32CD32, #8A2BE2);
            background-size: 400% 400%; /* Növelt háttérméret a simább átmenetért */
            animation: gradientAnimation 20s ease infinite;
            color: #f1f1f1;
            text-align: center;
            padding: 20px;
            margin: 0;
            overflow: hidden;
        }
        .container {
            max-width: 600px;
            margin: 40px auto;
            background-color: rgba(0, 0, 0, 0.8);
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 0 30px rgba(0, 0, 0, 0.5);
            position: relative;
            z-index: 1;
        }
        h1 {
            font-size: 2.5em;
            color: #8A2BE2;
            margin: 0 0 10px 0;
            text-shadow: 0 0 15px rgba(138, 43, 226, 0.7);
        }
        p {
            font-size: 1.1em;
            line-height: 1.6;
            color: #ddd;
        }
        .links {
            margin-top: 20px;
        }
        .link-button {
            display: inline-block;
            background-color: rgba(138, 43, 226, 0.8);
            color: white;
            padding: 12px 25px;
            margin: 10px 5px;
            text-decoration: none;
            border-radius: 25px;
            transition: background-color 0.3s, transform 0.3s;
            box-shadow: 0 4px 10px rgba(138, 43, 226, 0.3);
        }
        .link-button:hover {
            background-color: #6A1B9A;
            transform: translateY(-5px);
        }
        .background-shapes {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: 0;
            overflow: hidden;
        }
        .shape {
            position: absolute;
            background-color: rgba(138, 43, 226, 0.2);
            border-radius: 10px;
            animation: float 10s infinite ease-in-out;
            box-shadow: 0 0 15px rgba(138, 43, 226, 0.3);
        }
        .shape:nth-child(1) {
            width: 100px;
            height: 100px;
            top: 10%;
            left: 20%;
            animation-duration: 12s;
        }
        .shape:nth-child(2) {
            width: 150px;
            height: 150px;
            top: 60%;
            left: 60%;
            transform: rotate(45deg);
            animation-duration: 14s;
        }
        .shape:nth-child(3) {
            width: 80px;
            height: 80px;
            top: 70%;
            left: 30%;
            animation-duration: 17s;
        }
        .shape:nth-child(4) {
            width: 130px;
            height: 130px;
            top: 40%;
            left: 50%;
            background-color: rgba(138, 43, 226, 0.1);
            animation-duration: 16s;
        }
        .star {
            position: absolute;
            width: 4px;
            height: 4px;
            background-color: white;
            border-radius: 50%;
            animation: twinkle 5s infinite ease-in-out;
            box-shadow: 0 0 5px rgba(255, 255, 255, 0.5);
        }
        .star:nth-child(6) {
            top: 20%;
            left: 50%;
            animation-duration: 6s;
        }
        .star:nth-child(7) {
            top: 50%;
            left: 20%;
            animation-duration: 8s;
        }
        .star:nth-child(8) {
            top: 80%;
            left: 70%;
            animation-duration: 7s;
        }
        .star:nth-child(9) {
            top: 30%;
            left: 10%;
            animation-duration: 9s;
        }
        .star:nth-child(10) {
            top: 60%;
            left: 90%;
            animation-duration: 6s;
        }
        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-20px);
            }
        }
        @keyframes twinkle {
            0%, 100% {
                opacity: 1;
            }
            50% {
                opacity: 0.5;
            }
        }
        @keyframes gradientAnimation {
            0%, 100% {
                background-position: 0% 50%;
            }
            50% {
                background-position: 100% 50%;
            }
        }
    </style>
</head>
<body>
    <div class="background-shapes">
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="shape"></div>
        <div class="star"></div>
        <div class="star"></div>
        <div class="star"></div>
        <div class="star"></div>
        <div class="star"></div>
    </div>
    <div class="container">
        <h1>Zsombi11 Weboldala</h1>
        <p>Sziasztok! Zsombi vagyok, nincs nagy célom a TikTok live-ok gyártásával, mint hogy minél több emberhez eljusson és egy nagy közösséget építsek fel!</p>
        <div class="links">
            <a href="https://discord.gg/4QKyccf5tG" class="link-button">Discord</a>
            <a href="https://www.youtube.com/@Zsombi_11" class="link-button">YouTube</a>
            <a href="https://discord.gg/pGHvhtpx92" class="link-button">GGplanet</a>
        </div>
    </div>
</body>
</html>
