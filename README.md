# Dilmurod725.github.io<!DOCTYPE html>
<html lang="uz">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Treyding sirlarini o'rganing va muvaffaqiyatli investor bo'ling.">
    <title>Treyding Sirlari</title>

    <style>
        /* CSS kodlari shu yerda */
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            line-height: 1.6;
        }

        header {
            background: #333;
            color: #fff;
            padding: 1rem 0;
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        header h1 {
            margin: 0;
        }

        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
        }

        nav ul li {
            margin-left: 20px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
        }

        .hero {
            background: #007bff;
            color: #fff;
            padding: 2rem 0;
            text-align: center;
        }

        .hero .btn {
            background: #fff;
            color: #007bff;
            padding: 0.5rem 1rem;
            text-decoration: none;
            border-radius: 5px;
        }

        .about, .blog, .contact {
            padding: 2rem 0;
        }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: auto;
        }

        .articles {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 1rem;
        }

        article {
            border: 1px solid #ddd;
            padding: 1rem;
            border-radius: 5px;
        }

        footer {
            background: #333;
            color: #fff;
            text-align: center;
            padding: 1rem 0;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>Treyding Sirlari</h1>
            <nav>
                <ul>
                    <li><a href="#home">Bosh sahifa</a></li>
                    <li><a href="#about">Haqida</a></li>
                    <li><a href="#blog">Maqolalar</a></li>
                    <li><a href="#contact">Kontakt</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="container">
            <h2>Treydingni o'rganing va muvaffaqiyatga erishing!</h2>
            <p>Bizning platformamiz orqali treydingning barcha sirlarini o'rganing.</p>
            <a href="#about" class="btn">Batafsil</a>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>Biz haqimizda</h2>
            <p>"Treyding Sirlari" platformasi yangi boshlovchilar va professional treyderlar uchun mo'ljallangan. Biz sizga bilim va tajribani ulashamiz.</p>
        </div>
    </section>

    <section id="blog" class="blog">
        <div class="container">
            <h2>Maqolalar</h2>
            <div class="articles">
                <article>
                    <h3>Treydingning asosiy qoidalari</h3>
                    <p>Treydingda muvaffaqiyatga erishish uchun bilishingiz kerak bo'lgan asosiy qoidalar.</p>
                    <a href="#">Batafsil o'qish</a>
                </article>
                <article>
                    <h3>Risklarni boshqarish</h3>
                    <p>Kapitalingizni qanday himoya qilish va xavflarni kamaytirish haqida bilib oling.</p>
                    <a href="#">Batafsil o'qish</a>
                </article>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Kontakt</h2>
            <form action="#" method="post">
                <label for="name">Ismingiz:</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Xabar:</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <button type="submit">Yuborish</button>
            </form>
        </div>
    </section>

    <footer>
        <div class="container">
            <p>&copy; 2025 Treyding Sirlari. Barcha huquqlar himoyalangan.</p>
        </div>
    </footer>

    <script>
        // JavaScript kodlari shu yerda
        document.querySelector("form").addEventListener("submit", function (e) {
            e.preventDefault();
            alert("Xabaringiz muvaffaqiyatli yuborildi!");
        });
    </script>
</body>
</html><section id="brokers" class="brokers">
    <div class="container">
        <h2>Bizning Hamkorlarimiz</h2>
        <p>Quyidagi brokerlarga o'tish uchun havolalarni bosing:</p>
        <ul>
            <li><a href="https://www.xm.com" target="_blank">XM Brokeriga o'tish</a></li>
            <li><a href="https://www.libertex.com" target="_blank">Libertex Brokeriga o'tish</a></li>
            <li><a href="https://www.roboforex.com" target="_blank">RoboForex Brokeriga o'tish</a></li>
        </ul>
    </div>
</section>

<style>
    .brokers a {
        color: #007bff;
        text-decoration: none;
        font-weight: bold;
    }

    .brokers a:hover {
        color: #0056b3;
        text-decoration: underline;
    }

    .brokers ul {
        list-style-type: none;
        padding: 0;
    }

    .brokers li {
        margin: 10px 0;
    }
</style>
