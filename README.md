<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <title>СпортМаркет</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f2f5;
        }

        header {
            background-color: #2b7a78;
            color: white;
            padding: 20px;
            text-align: center;
        }

        nav {
            background-color: #def2f1;
            padding: 10px;
            text-align: center;
        }

        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #3aafa9;
            font-weight: bold;
        }

        .container {
            padding: 20px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-around;
        }

        .product-card {
            background-color: white;
            border: 1px solid #ccc;
            border-radius: 8px;
            width: 250px;
            margin: 10px;
            text-align: center;
            box-shadow: 2px 2px 8px rgba(0,0,0,0.1);
        }

        .product-card img {
            width: 100%;
            height: auto;
            border-bottom: 1px solid #ccc;
        }

        .product-card h3 {
            margin: 10px 0;
        }

        .product-card p {
            padding: 0 10px 10px;
        }

        footer {
            background-color: #2b7a78;
            color: white;
            text-align: center;
            padding: 15px;
            margin-top: 30px;
        }

        form {
            background-color: #ffffff;
            padding: 20px;
            margin: 20px auto;
            width: 300px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }

        form input, form textarea {
            width: 100%;
            margin-bottom: 10px;
            padding: 8px;
            box-sizing: border-box;
        }

        form input[type="submit"] {
            background-color: #3aafa9;
            color: white;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>

<header>
    <h1>СпортМаркет</h1>
    <p>Товары для спорта и активного отдыха</p>
</header>

<nav>
    <a href="#">Главная</a>
    <a href="#">Категории</a>
    <a href="#">О нас</a>
    <a href="#">Контакты</a>
</nav>

<div class="container">
    <div class="product-card">
        <img src="https://via.placeholder.com/250x150?text=Кроссовки" alt="Кроссовки">
        <h3>Кроссовки Nike</h3>
        <p>Удобные и лёгкие кроссовки для бега.</p>
        <p><strong>Цена: 500 MDL</strong></p>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/250x150?text=Мяч+футбольный" alt="Мяч">
        <h3>Футбольный мяч Adidas</h3>
        <p>Профессиональный мяч для тренировок и игр.</p>
        <p><strong>Цена: 200 MDL</strong></p>
    </div>

    <div class="product-card">
        <img src="https://via.placeholder.com/250x150?text=Гантели" alt="Гантели">
        <h3>Набор гантелей</h3>
        <p>Регулируемые гантели 10–30 кг для дома и зала.</p>
        <p><strong>Цена: 800 MDL</strong></p>
    </div>
</div>

<form>
    <h2>Связаться с нами</h2>
    <input type="text" placeholder="NICOLAI" required>
    <input type="email" placeholder="nik.md94@mail.ru" required>
    <textarea placeholder=" Мы ждем Вас" rows="4" required></textarea>
    <input type="submit" value="Отправить">
</form>

<footer>
    <p>&copy; 2025 СпортМаркет. Все права защищены.</p>
</footer>

</body>
</html>
