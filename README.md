
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy New Year</title>
    <style>
        body {
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4, #fbc2eb);
            font-family: Arial, sans-serif;
            overflow: hidden;
        }
        .container {
            text-align: center;
            color: #fff;
        }
        h1 {
            font-size: 3rem;
            opacity: 0;
            animation: fadeIn 3s ease-in-out forwards;
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(50px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        h1 span {
            display: inline-block;
            animation: colorChange 2s infinite alternate;
        }
        @keyframes colorChange {
            from { color: #ffeb3b; }
            to { color: #00e676; }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy New Year<br> More Success and Blessings This Year<br> <span>By Isa Arab</span></h1>
    </div>
</body>
</html>