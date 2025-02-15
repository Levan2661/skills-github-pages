<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Маркетплейс | Acc Hub</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        body {
            background: linear-gradient(to bottom, #000, #ffcc00);
            color: white;
            font-family: Arial, sans-serif;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
            background: black;
        }
        .logo {
            font-size: 24px;
            font-weight: bold;
            color: #ffcc00;
        }
        nav ul {
            list-style: none;
            display: flex;
            gap: 15px;
        }
        nav ul li a {
            color: white;
            text-decoration: none;
        }
        .sell-btn {
            background: #ffcc00;
            color: black;
            padding: 10px 15px;
            border: none;
            cursor: pointer;
        }
        .banner {
            background: url('banner-image.jpg') no-repeat center center/cover;
            text-align: center;
            padding: 50px 20px;
            position: relative;
        }
        .banner h1 {
            font-size: 28px;
            font-weight: bold;
            margin-bottom: 10px;
        }
        .banner p {
            font-size: 18px;
            margin-bottom: 20px;
        }
        .banner .sell-btn {
            background: blue;
            color: white;
            padding: 15px 25px;
            font-size: 18px;
            border-radius: 5px;
        }
        .game-icons {
            display: flex;
            justify-content: center;
            gap: 15px;
            margin-top: 20px;
        }
        .game-icons img {
            width: 70px;
            height: 70px;
            border-radius: 10px;
        }
    </style>
</head>
<body>
    <header>
        <div class="logo">Acc Hub</div>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="games.html">Игры</a></li>
                <li><a href="accounts.html">Аккаунты</a></li>
                <li><a href="items.html">Предметы</a></li>
                <li><a href="profile.html">Профиль</a></li>
                <li><a href="#" onclick="openLoginModal()">Войти</a></li>
            </ul>
        </nav>
    </header>
    
    <section class="banner">
        <h1>Стать продавцом</h1>
        <p>Зарабатывайте на продаже товаров и услуг</p>
        <button class="sell-btn">Начать продажу</button>
        <div class="game-icons">
            <a href="standoff2.html"><img src="standoff2.png" alt="Standoff 2"></a>
            <a href="roblox.html"><img src="roblox.png" alt="Roblox"></a>
            <a href="pubg.html"><img src="pubg.png" alt="PUBG Mobile"></a>
            <a href="telegram.html"><img src="telegram.png" alt="Telegram"></a>
            <a href="brawlstars.html"><img src="brawlstars.png" alt="Brawl Stars"></a>
        </div>
    </section>
    
    <main>
        <section class="account-list">
            <div class="account">
                <h3>Аккаунт Standoff 2</h3>
                <p>Цена: 450 ₽</p>
                <button onclick="location.href='buy-standoff2.html'">Купить</button>
            </div>
            <div class="account">
                <h3>Аккаунт PUBG Mobile</h3>
                <p>Цена: 13000 ₽</p>
                <button onclick="location.href='buy-pubg.html'">Купить</button>
            </div>
            <div class="account">
                <h3>Аккаунт Roblox</h3>
                <p>Цена: 800 ₽</p>
                <button onclick="location.href='buy-roblox.html'">Купить</button>
            </div>
            <div class="account">
                <h3>Аккаунт Fortnite</h3>
                <p>Цена: 2000 ₽</p>
                <button onclick="location.href='buy-fortnite.html'">Купить</button>
            </div>
        </section>
    </main>
    
    <footer>
        <p>&copy; 2025 Acc Hub. Все права защищены.</p>
    </footer>
</body>
</html>
