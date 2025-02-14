<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Day</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: pink;
            font-family: Arial, sans-serif;
            flex-direction: column;
            text-align: center;
        }
        .heart {
            color: red;
            font-size: 50px;
            animation: heartbeat 1s infinite alternate;
        }
        @keyframes heartbeat {
            from { transform: scale(1); }
            to { transform: scale(1.2); }
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            border: none;
            background-color: red;
            color: white;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
        }
    </style>
</head>
<body>
    <h1>Happy Valentine's Day! ❤️</h1>
    <div class="heart">❤️</div>
    <button onclick="changeText()">Click Me</button>
    <p id="message">Will you be my Valentine? 💖</p>
    
    <script>
        function changeText() {
            document.getElementById("message").innerText = "Yay! You are the best! 💕";
        }
    </script>
</body>
</html>
