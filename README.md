<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>H.E. Sunucusu</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-image: url('https://www.minecraft.net/content/dam/archive/www-minecraft-net/images/home/home-hero-bg.jpg'); /* Arka plan resmi */
            background-size: cover;
            color: #f4f4f4;
            text-align: center;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: rgba(0, 0, 0, 0.7);
            padding: 20px;
        }
        h1 {
            font-size: 3em;
            margin: 0;
        }
        section {
            background-color: rgba(0, 0, 0, 0.6);
            padding: 20px;
            margin: 20px;
            border-radius: 10px;
        }
        form {
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            max-width: 500px;
            margin: 0 auto;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: none;
            border-radius: 5px;
        }
        button {
            background-color: #4CAF50;
            color: white;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #45a049;
        }
        footer {
            padding: 10px;
            background-color: rgba(0, 0, 0, 0.8);
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

<header>
    <h1>H.E. Minecraft Sunucusu</h1>
    <p>Gerçekçi Minecraft modları (elektrik, kazma, balta ve daha fazlası)</p>
</header>

<section>
    <h2>Sunucu Hakkında</h2>
    <p>H.E. sunucusu, gerçekçi modlar ile Minecraft deneyimini daha da zenginleştiriyor! Elektrik sistemleri, gelişmiş araçlar ve zorlu hayatta kalma koşulları seni bekliyor. Kazma, balta ve diğer aletleri daha verimli kullan ve oyun dünyasını keşfet.</p>
</section>

<section>
    <h2>Sunucuya Katıl</h2>
    <form action="https://example.com/form-submission" method="POST">
        <label for="name">İsim:</label>
        <input type="text" id="name" name="name" placeholder="Adınız" required>

        <label for="email">E-posta:</label>
        <input type="email" id="email" name="email" placeholder="E-posta adresiniz" required>

        <label for="message">Mesajınız:</label>
        <textarea id="message" name="message" placeholder="Sunucuya katılma isteğinizi yazın" required></textarea>

        <button type="submit">Gönder</button>
    </form>
</section>

<footer>
    <p>H.E. Minecraft Sunucusu © 2024 | Tüm hakları saklıdır</p>
</footer>

</body>
</html>
