<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            background-color: #ffccd5;
            margin: 0;
            overflow: hidden;
        }
        h1 {
            margin-top: 50px;
            font-size: 30px;
            color: #d6336c;
        }
        .road {
            position: absolute;
            bottom: 50px;
            width: 100%;
            height: 100px;
            background: #333;
        }
        .car {
            position: absolute;
            width: 150px;
            height: 80px;
            background: red;
            border-radius: 20px;
            bottom: 70px;
            left: -200px;
            animation: drive 5s linear infinite;
        }
        .wheel {
            position: absolute;
            width: 30px;
            height: 30px;
            background: black;
            border-radius: 50%;
            bottom: -15px;
        }
        .wheel1 { left: 20px; }
        .wheel2 { right: 20px; }
        @keyframes drive {
            0% { left: -200px; }
            100% { left: 110%; }
        }
        .message, .phrase, .thankyou, .effort, .attentive, .consideration, .bestfriend, .patience, .boyfriend, .signature {
            display: none;
            font-size: 24px;
            color: #d6336c;
            margin-top: 20px;
        }
        button {
            margin-top: 20px;
            padding: 10px 20px;
            font-size: 18px;
            background-color: #d6336c;
            color: white;
            border: none;
            cursor: pointer;
            border-radius: 5px;
        }
        button:hover {
            background-color: #b61e50;
        }
    </style>
</head>
<body>

    <h1>Presiona el botón para una sorpresa</h1>
    <button onclick="mostrarFrases()">Ver mensaje</button>

    <p class="phrase" id="phrase1">Desde que te conocí, mi mundo es más bonito...</p>
    <p class="phrase" id="phrase2">Cada momento contigo es especial...</p>
    <p class="phrase" id="phrase3">No puedo imaginar un día sin ti...</p>
    <p class="message">Guillermo Ezequiel, ¿quieres ser mi San Valentín? ❤️</p>
    <p class="thankyou">Gracias por ser tan dulce y lindo conmigo 💕</p>
    <p class="effort">Por esforzarte cada día a ser el hombre indicado para mí</p>
    <p class="attentive">Por siempre ser atento y dulce conmigo 💖</p>
    <p class="consideration">Por tenerme en cuenta en cada ocasión ✨</p>
    <p class="bestfriend">Gracias por ser mi mejor amigo 🥰</p>
    <p class="patience">Por tenerme tanta paciencia y tratarme con tanto amor 💗</p>
    <p class="boyfriend">Gracias por ser mi novio 💖</p>
    <p class="signature">Atte: Nahiara 💗</p>

    <div class="road">
        <div class="car">
            <div class="wheel wheel1"></div>
            <div class="wheel wheel2"></div>
        </div>
    </div>

    <!-- Incrustar el video de YouTube -->
    <iframe width="560" height="315" src="https://www.youtube.com/embed/Wma8yX5W8yU?si=7zgbyJBmHJh8kavM" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

    <script>
        function mostrarFrases() {
            setTimeout(() => { document.getElementById('phrase1').style.display = 'block'; }, 1000);
            setTimeout(() => { document.getElementById('phrase2').style.display = 'block'; }, 3000);
            setTimeout(() => { document.getElementById('phrase3').style.display = 'block'; }, 5000);
            setTimeout(() => { document.querySelector('.message').style.display = 'block'; }, 7000);
            setTimeout(() => { document.querySelector('.thankyou').style.display = 'block'; }, 9000);
            setTimeout(() => { document.querySelector('.effort').style.display = 'block'; }, 11000);
            setTimeout(() => { document.querySelector('.attentive').style.display = 'block'; }, 13000);
            setTimeout(() => { document.querySelector('.consideration').style.display = 'block'; }, 15000);
            setTimeout(() => { document.querySelector('.bestfriend').style.display = 'block'; }, 17000);
            setTimeout(() => { document.querySelector('.patience').style.display = 'block'; }, 19000);
            setTimeout(() => { document.querySelector('.boyfriend').style.display = 'block'; }, 21000);
            setTimeout(() => { document.querySelector('.signature').style.display = 'block'; }, 23000);
        }
    </script>

</body>
</html>
