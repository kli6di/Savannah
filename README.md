
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Salut gros crane</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            min-height: 100vh;
            background-color: #ffb6c1; /* Fond rose */
            margin: 0;
        }

        h1 {
            color: #ff69b4; /* Couleur rose pour le titre */
            font-size: 28px;
            text-align: center;
        }

        button {
            padding: 15px 30px;
            font-size: 18px;
            margin: 10px;
            cursor: pointer;
            background-color: #ff69b4; /* Couleur rose pour les boutons */
            color: white;
            border: none;
        }
    </style>
</head>
<body>
    <h1>Salut gros crane, t'es incroyablement sucrée, pouvons-nous discuter?</h1>
    
    <button onclick="redirectYes()">Oui</button>
    <button onclick="redirectNo()">Non</button>

    <script>
        function redirectYes() {
            window.location.href = 'lets goo.html';
        }

        function redirectNo() {
            window.location.href = 'grayPage.html';
        }
    </script>
</body>
</html>
