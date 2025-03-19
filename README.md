
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Painel Futurista</title>
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <style>
        body {
            background-color: black;
            color: #1E3A8A; /* Azul escuro */
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
            text-shadow: 0 0 5px #1E3A8A, 0 0 10px #102A62;
            animation: glow 1.5s infinite alternate;
        }

        .button {
            display: block;
            width: 80%;
            max-width: 300px;
            margin: 10px auto;
            padding: 15px;
            background: black;
            color: #1E3A8A;
            border: 2px solid #1E3A8A;
            border-radius: 15px;
            font-size: 18px;
            font-weight: bold;
            text-decoration: none;
            box-shadow: 0 0 10px #102A62;
            transition: 0.3s, transform 0.3s;
            animation: float 2s infinite alternate;
        }

        .button:hover {
            background: #1E3A8A;
            color: white;
            transform: scale(1.1);
            box-shadow: 0 0 20px #1E3A8A;
        }

        /* Efeito neon piscando */
        @keyframes glow {
            from { text-shadow: 0 0 5px #1E3A8A; }
            to { text-shadow: 0 0 20px #1E3A8A; }
        }

        /* Efeito de flutuação nos botões */
        @keyframes float {
            from { transform: translateY(0px); }
            to { transform: translateY(5px); }
        }
    </style>
</head>
<body>
    <div id="particles-js"></div>

    <div class="container">
        <h1>$ucesso & Di$ciplina ./∞</h1>
        <a href="#" class="button">T.me/+553199949999</a>
        <a href="#" class="button">Caos Store - Referência</a>
        <a href="#" class="button">Caos Bot - Registros</a>
        <a href="#" class="button">Caos Bot - Kit Bico</a>
        <a href="#" class="button">Caos Bot - Pagamentos</a>
    </div>

    <!-- Configuração das partículas -->
    <script>
        particlesJS("particles-js", {
            "particles": {
                "number": { "value": 80, "density": { "enable": true, "value_area": 800 } },
                "color": { "value": "#1E3A8A" },
                "shape": { "type": "circle" },
                "opacity": { "value": 0.8, "random": false },
                "size": { "value": 4, "random": true },
                "line_linked": {
                    "enable": true,
                    "distance": 150,
                    "color": "#102A62",
                    "opacity": 0.8,
                    "width": 1
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
