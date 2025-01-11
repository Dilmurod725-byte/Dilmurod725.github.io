<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Treyding Haqida Ma'lumotlar</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <nav>
            <ul>
                <li><a href="#home">Bosh Sahifa</a></li>
                <li><a href="#about">Treyding Haqida</a></li>
                <li><a href="#brokers">Eng Yaxshi Brokerlar</a></li>
                <li><a href="#contact">Aloqa</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h1>Treyding Haqida Ma'lumotlar Saytiga Xush Kelibsiz</h1>
        <p>Treyding va brokerlar haqida barcha ma'lumotlarni shu yerda topishingiz mumkin!</p>
    </section>

    <section id="about">
        <h2>Treyding Haqida</h2>
        <p>Treyding - bu moliyaviy vositalarni sotib olish va sotish jarayonidir. Quyidagi turdagi treyding haqida ko'proq bilib oling:</p>
        <ul>
            <li><strong>Forex Treyding:</strong> Valyutalar bozorida sotib olish va sotish.</li>
            <li><strong>Aktsiyalar Treydingi:</strong> Kompaniyalar aksiyalarini sotib olish va sotish.</li>
            <li><strong>Kripto Treyding:</strong> Bitcoin, Ethereum kabi raqamli valyutalar bilan treyding.</li>
        </ul>
    </section>

    <section id="brokers">
        <h2>Eng Yaxshi Treyding Brokerlari</h2>
        <p>Quyida eng mashhur treyding brokerlarining ro'yxati keltirilgan:</p>
        <ul>
            <li><a href="https://www.ig.com" target="_blank">IG Markets</a></li>
            <li><a href="https://www.eToro.com" target="_blank">eToro</a></li>
            <li><a href="https://www.plus500.com" target="_blank">Plus500</a></li>
            <li><a href="https://www.oxfordtrading.com" target="_blank">Oxford Trading</a></li>
            <li><a href="https://www.cmcmarkets.com" target="_blank">CMC Markets</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Aloqa</h2>
        <p>Agar sizda savollar bo'lsa yoki yordam kerak bo'lsa, biz bilan bog'laning!</p>
        <form action="submit_form.php" method="post">
            <label for="name">Ismingiz:</label><br>
            <input type="text" id="name" name="name" required><br><br>
            <label for="email">Email manzilingiz:</label><br>
            <input type="email" id="email" name="email" required><br><br>
            <label for="message">Xabaringiz:</label><br>
            <textarea id="message" name="message" required></textarea><br><br>
            <input type="submit" value="Yuborish">
        </form>
    </section>

    <footer>
        <p>&copy; 2025 Treyding Haqida Ma'lumotlar. Barcha huquqlar himoyalangan.</p>
    </footer>

    <script src="script.js"></script>
</body>
</html>
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: white;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-size: 18px;
}

section {
    padding: 20px;
    margin: 20px;
    background-color: white;
    border-radius: 8px;
}

section h1, section h2 {
    color: #333;
}

footer {
    text-align: center;
    background-color: #333;
    color: white;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

form {
    display: flex;
    flex-direction: column;
}

form input, form textarea {
    margin-bottom: 10px;
    padding: 10px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

form input[type="submit"] {
    background-color: #333;
    color: white;
    cursor: pointer;
}

form input[type="submit"]:hover {
    background-color: #555;
}
// Misol JavaScript: Formani yuborish uchun (boshqa xususiyatlar uchun kengaytirish mumkin)
document.querySelector('form').addEventListener('submit', function(event) {
    event.preventDefault(); // Demo uchun forma yuborilishini to'xtatish
    alert('Sizning xabaringiz yuborildi!');
});
