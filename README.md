# Biznovate
Consulting
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Выбор услуги</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Biznovate Consulting</h1>
        <nav>
            <ul>
                <li><a href="index.html">Главная</a></li>
                <li><a href="services.html">Услуги</a></li>
                <li><a href="contact.html">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <section>
        <h2>Консультация по бизнес-стратегии</h2>
        <p>Подробное описание услуги, включающее советы по оптимизации бизнес-процессов, улучшению стратегии и увеличению прибыли.</p>
        <p><strong>Цена: 5000 рублей</strong></p>

        <form action="payment.html" method="POST">
            <label for="name">Ваше имя:</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Ваш email:</label>
            <input type="email" id="email" name="email" required>

            <button type="submit">Перейти к оплате</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Biznovate Consulting</p>
    </footer>
</body>
</html>
