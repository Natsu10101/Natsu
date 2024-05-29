<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ma Page Anime</title>
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
            padding: 20px 0;
            text-align: center;
        }
        nav {
            text-align: center;
            background-color: #444;
            padding: 10px 0;
        }
        nav a {
            margin: 0 15px;
            text-decoration: none;
            color: #fff;
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
            position: relative;
            width: 100%;
        }
        #chatbot {
            position: fixed;
            bottom: 20px;
            right: 20px;
            width: 300px;
            background-color: #fff;
            border: 2px solid #333;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        #chatbot-header {
            background-color: #333;
            color: #fff;
            padding: 10px;
            text-align: center;
        }
        #chatbot-messages {
            height: 200px;
            overflow-y: auto;
            padding: 10px;
        }
        .chatbot-message {
            margin: 5px 0;
        }
        .user-message {
            text-align: right;
        }
        #chatbot-input {
            display: flex;
            padding: 10px;
            border-top: 1px solid #333;
        }
        #chatbot-input input {
            flex: 1;
            padding: 5px;
        }
        #chatbot-input button {
            padding: 5px 10px;
            background-color: #333;
            color: #fff;
            border: none;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <header>
        <h1>Bienvenue sur ma page Anime</h1>
    </header>
    <nav>
        <a href="#home">Accueil</a>
        <a href="#recommended">Anime Recommandés</a>
        <a href="#blog">Blog</a>
        <a href="#contact">Contact</a>
    </nav>
    <div class="container">
        <section id="home" class="section">
            <h2>Accueil</h2>
            <p>Bienvenue sur ma page personnelle dédiée aux anime ! Ici, je partage mes recommandations, mes critiques et bien plus encore.</p>
        </section>
        <section id="recommended" class="section">
            <h2>Anime Recommandés</h2>
            <div class="anime-border">
                <h3>1. Attack on Titan</h3>
                <p>Une histoire épique de survie dans un monde où l'humanité est menacée par des titans géants.</p>
            </div>
            <div class="anime-border">
                <h3>2. My Hero Academia</h3>
                <p>Un jeune garçon sans pouvoir dans un monde où presque tout le monde en a un, mais qui rêve de devenir un héros.</p>
            </div>
            <div class="anime-border">
                <h3>3. One Punch Man</h3>
                <p>Les aventures d'un héros incroyablement puissant qui peut vaincre n'importe quel adversaire avec un seul coup de poing.</p>
            </div>
        </section>
        <section id="blog" class="section">
            <h2>Blog</h2>
            <div class="anime-border">
                <h3>Dernier Article: Les Meilleurs Anime de 2024</h3>
                <p>Découvrez ma liste des meilleurs anime de cette année, avec des critiques détaillées et des recommandations personnelles.</p>
                <a href="https://monblog.com">Lire plus</a>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contact</h2>
            <p>Vous pouvez me contacter par email à <a href="mailto:email@exemple.com">email@exemple.com</a> ou me suivre sur les réseaux sociaux ci-dessous.</p>
        </section>
    </div>
    <footer>
        &copy; 2024 Mon Nom. Tous droits réservés.
    </footer>

    <div id="chatbot">
        <div id="chatbot-header">
            <h3>Chat avec moi</h3>
        </div>
        <div id="chatbot-messages"></div>
        <div id="chatbot-input">
            <input type="text" id="chatbot-input-field" placeholder="Écris un message...">
            <button onclick="sendMessage()">Envoyer</button>
        </div>
    </div>

    <script>
        function sendMessage() {
            const inputField = document.getElementById('chatbot-input-field');
            const message = inputField.value;
            if (message.trim() === '') return;
            displayMessage(message, 'user-message');
            inputField.value = '';
            setTimeout(() => {
                displayMessage(generateBotResponse(message), 'bot-message');
            }, 1000);
        }

        function displayMessage(message, className) {
            const messagesContainer = document.getElementById('chatbot-messages');
            const messageElement = document.createElement('div');
            messageElement.className = 'chatbot-message ' + className;
            messageElement.textContent = message;
            messagesContainer.appendChild(messageElement);
            messagesContainer.scrollTop = messagesContainer.scrollHeight;
        }

        function generateBotResponse(message) {
            const responses = [
                "Salut ! Comment puis-je t'aider aujourd'hui ?",
                "Tu aimes quel genre d'anime ?",
                "As-tu vu le dernier épisode de One Piece ?",
                "N'hésite pas à me poser des questions sur les anime !",
                "Quel est ton anime préféré ?"
            ];
            return responses[Math.floor(Math.random() * responses.length)];
        }
    </script>
</body>
</html>
