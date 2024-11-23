<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Murakkab Sayt</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Mening Murakkab Saytim</h1>
        <nav>
            <ul>
                <li><a href="#home">Bosh sahifa</a></li>
                <li><a href="#about">Haqida</a></li>
                <li><a href="#services">Xizmatlar</a></li>
                <li><a href="#contact">Bog'lanish</a></li>
            </ul>
        </nav>
    </header>
    <section id="home">
        <h2>Xush kelibsiz!</h2>
        <p>Bizning saytimizga tashrif buyurganingiz uchun tashakkur.</p>
    </section>
    <section id="about">
        <h2>Biz haqimizda</h2>
        <p>Bu bo'limda bizning maqsadlarimiz va faoliyatimiz haqida ma'lumot topasiz.</p>
    </section>
    <section id="services">
        <h2>Xizmatlar</h2>
        <ul>
            <li>Web-sayt ishlab chiqish</li>
            <li>Mobil ilovalar yaratish</li>
            <li>SEO optimizatsiya</li>
        </ul>
    </section>
    <section id="contact">
        <h2>Bog'lanish</h2>
        <form id="contactForm">
            <label for="name">Ism:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Xabar:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Yuborish</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2024 Mening Saytim. Barcha huquqlar himoyalangan.</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
