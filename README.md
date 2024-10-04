<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            margin: 0;
            background-image: url('https://example.com/photo.jpg'); /* Замените на свою ссылку */
            background-size: cover;
            background-position: center;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            color: white;
        }

        header {
            text-align: center;
            background-color: rgba(0, 0, 0, 0.5);
            padding: 20px;
            border-radius: 8px;
        }

        .links ul {
            list-style-type: none;
            padding: 0;
        }

        .links li {
            display: inline;
            margin: 0 15px;
        }

        button {
            margin: 5px;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }

        @media (max-width: 768px) {
            .links li {
                display: block; /* Вертикальное расположение на мобильных устройствах */
                margin: 10px 0;
            }
        }
    </style>
</head>
<body>

<header>
    <nav>
        <div class="logo"><h1>Logo</h1></div>
        <div class="links">
            <ul>
                <li><a class="active" href="#">Home</a></li>
                <li><a href="#">About</a></li>
                <li><a href="#">Services</a></li>
                <li><a href="#">Contact</a></li>
            </ul>
        </div>
        <div class="login-sec">
            <button>Login</button>
        </div>
    </nav>

    <div class="home-content">
        <h2>Landing Page</h2>
        <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Eum, eveniet.</p>
        <button id="try-now">Try now</button>
        <button id="explore">EXPLORE</button>
    </div>
</header>

</body>
</html>
