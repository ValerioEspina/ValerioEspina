### Hi there! Welcome to my github

 Currently a fullstack & aws student


<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Juego del Dinosaurio</title>
    <style>
        body { text-align: center; }
    </style>
</head>
<body>
    <h1>Juego del Dinosaurio</h1>
    <p>Haz clic en la pantalla y presiona la barra espaciadora para jugar.</p>
    <div id="game" style="position: relative; width: 600px; height: 150px; border: 1px solid #ccc;"></div>

    <script>
        document.addEventListener('keydown', function(event) {
            if (event.keyCode === 32) {
                event.preventDefault();
                startGame();
            }
        });

        function startGame() {
            var element = document.getElementById('game');
            element.innerHTML = '<iframe src="https://elgoog.im/t-rex/" width="600" height="150" frameborder="0"></iframe>';
        }
    </script>
</body>
</html>

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
