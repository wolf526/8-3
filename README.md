<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng 8/3 Bé Yêu ❤️</title>
    <style>
        body {
            background: linear-gradient(180deg, #ffb6c1, #ffcccc, #ffe6e6);
            background-attachment: fixed;
            text-align: center;
            font-family: 'Arial', sans-serif;
            padding-top: 50px;
            position: relative;
            overflow: hidden;
            height: 100vh;
            margin: 0;
        }
        h1 {
            color: #ff4d4d;
            font-size: 50px;
            text-shadow: 2px 2px 5px rgba(255, 0, 0, 0.3);
            animation: glow 1.5s infinite alternate;
        }
        p {
            color: #d63384;
            font-size: 22px;
            font-weight: bold;
        }
        .container {
            background: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 15px;
            box-shadow: 0px 0px 15px rgba(255, 0, 0, 0.3);
            display: inline-block;
        }
        .heart {
            position: absolute;
            color: #ff4d4d;
            font-size: 25px;
            animation: fall linear infinite;
        }
        @keyframes glow {
            from { text-shadow: 2px 2px 10px rgba(255, 0, 0, 0.5); }
            to { text-shadow: 4px 4px 20px rgba(255, 0, 0, 0.8); }
        }
        @keyframes fall {
            from { transform: translateY(-10vh) scale(1); opacity: 1; }
            to { transform: translateY(100vh) scale(0.5); opacity: 0; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Chúc Mừng 8/3, Bé Yêu ❤️</h1>
        <p>Chúc em luôn xinh đẹp, hạnh phúc và tràn đầy yêu thương! Anh yêu em nhiều lắm! 💖</p>
    </div>
    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.innerHTML = "❤️";
            document.body.appendChild(heart);
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
            heart.style.fontSize = (Math.random() * 10 + 15) + "px";
            setTimeout(() => { heart.remove(); }, 5000);
        }
        setInterval(createHeart, 200);
    </script>
</body>
</html>
