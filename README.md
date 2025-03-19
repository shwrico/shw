
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel Hacker</title>
    <style>
        body {
            background-color: black;
            color: yellow;
            font-family: Arial, sans-serif;
            text-align: center;
        }
        .container {
            margin-top: 50px;
        }
        .profile-img {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            border: 3px solid yellow;
            box-shadow: 0 0 15px yellow;
        }
        h1 {
            font-size: 24px;
            text-shadow: 0 0 5px yellow, 0 0 10px yellow;
            animation: glow 1.5s infinite alternate;
        }
        .button {
            display: block;
            width: 80%;
            max-width: 300px;
            margin: 10px auto;
            padding: 15px;
            background: black;
            color: yellow;
            border: 2px solid yellow;
            border-radius: 15px;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            box-shadow: 0 0 10px yellow;
            transition: 0.3s, transform 0.3s;
            animation: pulse 1.5s infinite alternate;
        }
        .button:hover {
            background: yellow;
            color: black;
            transform: scale(1.1);
        }

        /* Efeito neon piscando */
        @keyframes glow {
            from { text-shadow: 0 0 5px yellow; }
            to { text-shadow: 0 0 20px yellow; }
        }
        
        /* Efeito de leve movimentação nos botões */
        @keyframes pulse {
            from { box-shadow: 0 0 10px yellow; }
            to { box-shadow: 0 0 20px yellow; }
        }
    </style>
</head>
<body>

    <div class="container">
        <img src="sua-imagem.jpg" class="profile-img" alt="Imagem de Perfil">
        <h1>$ucesso & Di$ciplina ./∞</h1>
        
        <a href="http://T.me/+5531999499999" class="button">T.me/+5531999499999</a>
        <a href="https://t.me/caosstore_referencia" class="button">Caos Store - Referência</a>
        <a href="https://caoslogs_bot" class="button">Caos Bot - Logs</a>
        <a href="https://CaosKitBico_bot" class="button">Caos Bot - Kit Bico</a>
        <a href="https://caospagamentos_bot" class="button">Caos Bot - Pagamentos</a>
    </div>

</body>
</html>
