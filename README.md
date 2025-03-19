
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel Hacker</title>
    <style>
        @keyframes pulsar {
            0% { box-shadow: 0 0 10px yellow; }
            50% { box-shadow: 0 0 20px yellow; }
            100% { box-shadow: 0 0 10px yellow; }
        }

        @keyframes digitar {
            from { width: 0; }
            to { width: 100%; }
        }

        body {
            background-color: black;
            color: yellow;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .container {
            margin-top: 50px;
        }

        h1, .shw {
            font-size: 24px;
            color: yellow;
            text-shadow: 3px 3px 5px black;
            overflow: hidden;
            white-space: nowrap;
            border-right: 2px solid yellow;
            display: inline-block;
            width: 0;
            animation: digitar 3s steps(30, end) forwards;
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
            text-shadow: 2px 2px 5px black;
            animation: pulsar 1.5s infinite alternate;
            transition: 0.3s;
        }

        .button:hover {
            background: yellow;
            color: black;
        }
    </style>
</head>
<body>

    <div class="container">
        <h2 class="shw">shw</h2>
        <h1>$ucesso & Di$ciplina ./∞</h1>
        
        <a href="http://T.me/+5531999499999" class="button">T.me/+5531999499999</a>
        <a href="https://t.me/caosstore_referencia" class="button">Caos Store - Referência</a>
        <a href="https://caoslogs_bot" class="button">Caos Bot - Logs</a>
        <a href="https://CaosKitBico_bot" class="button">Caos Bot - Kit Bico</a>
        <a href="https://caospagamentos_bot" class="button">Caos Bot - Pagamentos</a>
    </div>

</body>
</html>
