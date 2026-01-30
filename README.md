<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <title>MODE OFF | Boutique Officielle</title>
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #000;
            color: #fff;
        }

        header {
            text-align: center;
            padding: 50px 20px;
            background: #000;
        }

        header h1 {
            font-size: 48px;
            color: #00a6c7;
            letter-spacing: 3px;
            margin-bottom: 10px;
        }

        header p {
            color: #ccc;
        }

        section {
            padding: 50px 20px;
            max-width: 1200px;
            margin: auto;
        }

        h2 {
            text-align: center;
            margin-bottom: 30px;
            color: #00a6c7;
        }

        .about {
            text-align: center;
            color: #ddd;
            line-height: 1.7;
        }

        .shop {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 30px;
        }

        .product {
            background: #111;
            border-radius: 12px;
            padding: 20px;
            text-align: center;
        }

        .product img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 15px;
        }

        .price {
            font-size: 20px;
            color: #00a6c7;
            margin: 10px 0;
            font-weight: bold;
        }

        select {
            padding: 10px;
            border-radius: 6px;
            border: none;
            margin-bottom: 15px;
        }

        .btn {
            display: inline-block;
            background: #25D366;
            color: #000;
            padding: 15px 25px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
        }

        .qr {
            text-align: center;
            margin-top: 40px;
        }

        footer {
            background: #000;
            border-top: 1px solid #222;
            text-align: center;
            padding: 30px 20px;
            color: #aaa;
        }
    </style>
</head>

<body>

<header>
    <h1>MODE OFF</h1>
    <p>Distance • Silence • Paix</p>
</header>

<section>
    <h2>À propos de MODE OFF</h2>
    <p class="about">
        MODE OFF est une marque de vêtements basée sur l’état d’esprit.
        Prendre ses distances, couper le bruit, choisir la paix.
        Chaque pièce représente une identité forte et assumée.
    </p>
</section>

<section>
    <h2>Boutique</h2>

    <div class="shop">
        <div class="product">
            <img src="tshirt-front.jpg" alt="T-shirt MODE OFF face avant">
            <img src="tshirt-back.jpg" alt="T-shirt MODE OFF face arrière">

            <h3>T-shirt MODE OFF</h3>
            <p>Design exclusif : Distance / Silence / Paix</p>
            <p class="price">6 000 FCFA</p>

            <label for="size">Taille :</label><br>
            <select id="size">
                <option>S</option>
                <option>M</option>
                <option>L</option>
                <option>XL</option>
                <option>XXL</option>
            </select><br><br>

            <a class="btn" 
               href="https://wa.me/2250545024251?text=Bonjour%20MODE%20OFF,%20je%20souhaite%20commander%20le%20T-shirt%20MODE%20OFF%20à%206000%20FCFA."
               target="_blank">
               Commander sur WhatsApp
            </a>
        </div>
    </div>
</section>

<section class="qr">
    <h2>Scanner pour accéder à la boutique</h2>
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=200x200&data=https://mode-off.com" alt="QR Code MODE OFF">
</section>

<footer>
    <p>🙏 Merci pour votre confiance</p>
    <p>© 2026 – MODE OFF | Boutique Officielle</p>
</footer>

</body>
</html>
