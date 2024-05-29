<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Page Personnelle</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f5f5f5;
            color: #333;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            margin: 20px 0;
            text-align: center;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #333;
            font-weight: bold;
        }
        .container {
            width: 80%;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            font-family: 'Trebuchet MS', sans-serif;
        }
        .section {
            margin-bottom: 40px;
        }
        .anime-border {
            border: 2px solid #333;
            padding: 10px;
            margin: 20px 0;
        }
        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
            position: fixed;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page personnelle</h1>
    </header>
    <nav>
        <a href="#about">À propos</a>
        <a href="#sport">Sport</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>À propos de moi</h2>
            <p>Passionné de sport et d'anime/manga, j'aime partager mes expériences et mes connaissances à travers mon blog. Bienvenue sur ma page personnelle où vous pourrez découvrir mes centres d'intérêt et mes projets.</p>
        </section>
        <section id="sport" class="section">
            <h2>Sport</h2>
            <div class="anime-border">
                <p>Le sport est une grande partie de ma vie. J'adore le football, le basketball, et le running. Voici quelques-uns de mes exploits sportifs et événements auxquels j'ai participé.</p>
            </div>
        </section>
        <section id="blog" class="section">
            <h2>Mon Blog</h2>
            <div class="anime-border">
                <p>Bienvenue sur mon blog ! Ici, je partage mes réflexions sur le sport, des analyses de matchs, des conseils d'entraînement, ainsi que des critiques et recommandations d'anime/manga.</p>
            </div>
            <a href="https://monblog.com">Visitez mon blog</a>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Vous pouvez me contacter par email à <a href="mailto:email@exemple.com">email@exemple.com</a> ou me suivre sur les réseaux sociaux ci-dessous.</p>
        </section>
    </div>
    <footer>
        &copy; 2024 Mon Nom. Tous droits réservés.
    </footer>
</body>
</html>
