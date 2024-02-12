<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Peut-on se reparler?</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-between;
            min-height: 100vh; /* 100% de la hauteur de la fenêtre visible */
            background-color: #f9f2f4; /* Couleur de fond rose clair */
            border: 2px solid #ff69b4; /* Bordure rose autour de la page */
            padding: 20px; /* Espace à l'intérieur de la bordure */
        }

        h1 {
            color: #ff69b4; /* Couleur rose */
            margin-top: 0; /* Supprime la marge par défaut du titre */
        }

        .flower-frame {
            border: 10px solid #ff69b4; /* Bordure rose autour de l'image */
            border-radius: 20px; /* Coins arrondis de la bordure */
            overflow: hidden; /* Masque pour s'assurer que les coins arrondis sont respectés */
        }

        img {
            width: 300px; /* Taille de l'image */
            height: 200px;
            margin-bottom: 20px; /* Espace en bas de l'image */
        }

        button {
            padding: 10px 20px;
            font-size: 16px;
            margin: 10px;
            cursor: pointer;
        }

        #buttonContainer {
            display: flex;
            justify-content: center; /* Centre les boutons horizontalement */
        }

        #buttonYes, #buttonNo {
            background-color: #4caf50; /* Couleur verte pour le bouton Oui */
            color: white;
            border: none;
        }

        #buttonNo {
            background-color: #ff3333; /* Couleur rouge pour le bouton Non */
        }
    </style>
</head>
<body>
    <h1>Peut-on se reparler?</h1>
    <div class="flower-frame">
        <img src="R.jpg" alt="Image de R">
    </div>
    <div id="buttonContainer">
        <button id="buttonYes" onclick="redirectToYouuhou()">Oui</button>
        <button id="buttonNo">Non</button>
    </div>

    <script>
        function redirectToYouuhou() {
            window.location.href = 'youuhou.html';
        }
    </script>
</body>
</html>
