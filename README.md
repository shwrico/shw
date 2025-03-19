<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel Hacker</title>
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <style>
        body {
            background-color: black;
            color: yellow;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            overflow: hidden;
        }

        /* Fundo animado */
        #particles-js {
            position: fixed;
            width: 100%;
            height: 100%;
            top: 0;
            left: 0;
            z-index: -1;
        }

        .container {
            position: relative;
            margin-top: 50px;
            z-index: 1;
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
            animation: float 2s infinite alternate;
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

        /* Efeito de flutuação nos botões */
        @keyframes float {
            from { transform: translateY(0px); }
            to { transform: translateY(-5px); }
        }
    </style>
</head>
<body>

    <!-- Fundo animado -->
    <div id="particles-js"></div>

    <div class="container">
        <h1>$ucesso & Di$ciplina ./∞</h1>

        <a href="http://T.me/+5531999499999" class="button">T.me/+5531999499999</a>
        <a href="https://t.me/caosstore_referencia" class="button">Caos Store - Referência</a>
        <a href="https://caoslogs_bot" class="button">Caos Bot - Registros</a>
        <a href="https://CaosKitBico_bot" class="button">Caos Bot - Kit Bico</a>
        <a href="https://caospagamentos_bot" class="button">Caos Bot - Pagamentos</a>
    </div>

    <script>
        particlesJS("particles-js", {
            "particles": {
                "number": { "value": 100 },
                "color": { "value": "#ffff00" },
                "shape": { "type": "circle" },
                "opacity": {
                    "value": 0.8,
                    "random": true,
                    "anim": { "enable": true, "speed": 1 }
                },
                "size": {
                    "value": 5,
                    "random": true,
                    "anim": { "enable": true, "speed": 5 }
                },
                "line_linked": {
                    "enable": true,
                    "distance": 150,
                    "color": "#ffff00",
                    "opacity": 0.8,
                    "width": 2
                },
                "move": {
                    "enable": true,
                    "speed": 2,
                    "direction": "none",
                    "random": false,
                    "straight": false,
                    "out_mode": "out",
                    "bounce": false
                }
            },
            "interactivity": {
                "detect_on": "canvas",
                "events": {
                    "onhover": { "enable": true, "mode": "repulse" },
                    "onclick": { "enable": true, "mode": "push" }
                },
                "modes": {
                    "repulse": { "distance": 100, "duration": 0.4 },
                    "push": { "particles_nb": 4 }
                }
            },
            "retina_detect": true
        });
    </script>

</body>
</html>
