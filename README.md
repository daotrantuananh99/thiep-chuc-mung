
```html
<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Chúc mừng sinh nhật</title>

    <style>
        body {
            margin: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            font-family: Arial, sans-serif;
            background: linear-gradient(135deg, #ffd6e7, #c9e7ff);
            color: #8b2856;
        }

        .card {
            width: 80%;
            max-width: 400px;
            padding: 30px 20px;
            background: rgba(255,255,255,0.85);
            border-radius: 24px;
            box-shadow: 0 8px 25px #0002;
        }

        h1 {
            font-size: 30px;
        }

        p {
            font-size: 18px;
            line-height: 1.7;
        }

        button {
            padding: 12px 22px;
            border: none;
            border-radius: 25px;
            background: #ff6392;
            color: white;
            font-size: 17px;
        }

        #message {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>

<body>
    <div class="card">
        <h1>🎂 Chúc mừng sinh nhật! 🎂</h1>

        <p>
            Chúc bạn luôn vui vẻ,<br>
            hạnh phúc và gặp nhiều may mắn! 💖
        </p>

        <button onclick="showMessage()">
            Nhấn vào đây 💌
        </button>

        <p id="message">
            Mong rằng mọi điều tốt đẹp nhất
            sẽ đến với bạn! 🌷
        </p>
    </div>

    <script>
        function showMessage() {
            document.getElementById("message").style.display = "block";
        }
    </script>
</body>
</html>
```