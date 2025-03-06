<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc Mừng 8/3 Bé Yêu ❤️</title>
    <style>
        body {
            background-color: #ffe6e6;
            text-align: center;
            font-family: Arial, sans-serif;
            padding-top: 50px;
            position: relative;
            overflow: hidden;
        }
        h1 {
            color: #ff4d4d;
            font-size: 40px;
        }
        p {
            color: #d63384;
            font-size: 20px;
        }
        .heart {
            position: absolute;
            color: #ff4d4d;
            font-size: 20px;
            animation: fall linear infinite;
        }
        @keyframes fall {
            from { transform: translateY(-10vh); opacity: 1; }
            to { transform: translateY(100vh); opacity: 0; }
        }
    </style>
</head>
<body>
    <h1>Chúc Mừng 8/3, Bé Yêu ❤️</h1>
    <p>Chúc em luôn xinh đẹp, hạnh phúc và tràn đầy yêu thương! Anh yêu em nhiều lắm! 💖</p>
    <script>
        function createHeart() {
            const heart = document.createElement("div");
            heart.classList.add("heart");
            heart.innerHTML = "❤️";
            document.body.appendChild(heart);
            heart.style.left = Math.random() * 100 + "vw";
            heart.style.animationDuration = (Math.random() * 3 + 2) + "s";
            setTimeout(() => { heart.remove(); }, 5000);
        }
        setInterval(createHeart, 300);
    </script>
</body>
</html>.
