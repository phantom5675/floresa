<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sunflower Animation</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #1a1a1a;
        }
        .container {
            position: relative;
            background-color: #fffae6;
            width: 400px;
            height: 300px;
            border-radius: 20px;
            text-align: center;
            font-family: Arial, sans-serif;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }
        .container h2 {
            margin-top: 20px;
            font-size: 24px;
            color: #333;
        }
        svg {
            position: absolute;
            bottom: 20px;
            left: 50%;
            transform: translateX(-50%);
        }
    </style>
</head>
<body>
    <div class="container">
        <h2>Te AMOO mi chef preciosa ❤️</h2>
        <svg width="100" height="150" viewBox="0 0 100 150">
            <!-- Tallo -->
            <rect x="48" y="50" width="4" height="80" fill="green" />
            <!-- Hojas -->
            <ellipse cx="40" cy="80" rx="15" ry="8" fill="green" />
            <ellipse cx="60" cy="90" rx="15" ry="8" fill="green" />
            <!-- Pétalos -->
            <circle cx="50" cy="40" r="20" fill="yellow" stroke="orange" stroke-width="3" />
            <!-- Centro de la flor -->
            <circle cx="50" cy="40" r="10" fill="brown" />
        </svg>
    </div>
</body>
</html>
