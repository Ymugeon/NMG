<!DOCTYPE html>
<html lang="de">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meine Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }
        header, nav, section, footer {
            padding: 20px;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
        }
        nav {
            background-color: #444;
            color: #fff;
            text-align: center;
        }
        nav a {
            color: #fff;
            margin: 0 15px;
            text-decoration: none;
        }
        #bilder {
            background-color: #f4a261;
            color: #fff;
        }
        #blog {
            background-color: #2a9d8f;
            color: #fff;
        }
        #kontakt {
            background-color: #e76f51;
            color: #fff;
        }
        #arbeit {
            background-color: #264653;
            color: #fff;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 20px;
        }
        .bilder-gallery img {
            max-width: 100%;
            height: auto;
            margin: 10px 0;
        }
        .blog-post {
            margin-bottom: 20px;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Willkommen auf meiner Website</h1>
    </header>
    <nav>
        <a href="#bilder">Bilder</a>
        <a href="#blog">Blog</a>
        <a href="#kontakt">Kontakt</a>
        <a href="#arbeit">Arbeit</a>
    </nav>
    <section id="bilder" class="container">
        <h2>Bilder</h2>
        <div class="bilder-gallery">
            <img src="bild1.jpg" alt="Logo 1">
            <img src="bild2.jpg" alt="Logo 2">
            <img src="bild3.jpg" alt="Logo 3">
        </div>
    </section>
    <section id="blog" class="container">
        <h2>Blog</h2>
        <div class="blog-post">
            <h3>News 14.06.2024</h3>
            <p>Hier ein paar Beispiellogos, von mir.</p>
        </div>
        <div class="blog-post">
            <h3>News 15.06.2024</h3>
            <p>In Arbeit...</p>
        </div>
    </section>
    <section id="kontakt" class="container">
        <h2>Kontakt</h2>
        <form action="#">
            <label for="name">Name:</label><br>
            <input type="text" id="name" name="name"><br>
            <label for="email">Email:</label><br>
            <input type="email" id="email" name="email"><br>
            <label for="nachricht">Nachricht:</label><br>
            <textarea id="nachricht" name="nachricht" rows="4" cols="50"></textarea><br>
            <input type="submit" value="Senden">
        </form>
    </section>
    <section id="arbeit" class="container">
        <h2>Arbeit</h2>
        <p>Informationen über meine Arbeit und Projekte.</p>
    </section>
    <footer>
        <p>&copy; 2024 Meine Website</p>
    </footer>
</body>
</html>
