
<!DOCTYPE html>
<html lang='nl'>
<head>
    <meta charset='UTF-8'>
    <meta name='viewport' content='width=device-width, initial-scale=1.0'>
    <title>Koffiepunten & Campushelden</title>
    <style>
        body {
            background-color: #fff4e6;
            font-family: 'Arial', sans-serif;
            color: #3c1e0a;
            text-align: center;
            padding: 20px;
        }
        h1 {
            color: #ff6600;
            font-size: 2.5em;
            animation: fadeIn 2s ease-in;
        }
        .coffee {
            width: 150px;
            animation: float 3s ease-in-out infinite;
        }
        .scoreboard {
            margin-top: 30px;
            animation: fadeIn 3s ease-in;
        }
        .student {
            font-size: 1.2em;
            margin: 10px;
            animation: fadeInUp 1s ease-in;
        }
        @keyframes fadeIn {
            from {opacity: 0;}
            to {opacity: 1;}
        }
        @keyframes fadeInUp {
            from {opacity: 0; transform: translateY(20px);}
            to {opacity: 1; transform: translateY(0);}
        }
        @keyframes float {
            0% {transform: translateY(0);}
            50% {transform: translateY(-10px);}
            100% {transform: translateY(0);}
        }
    </style>
</head>
<body>
    <h1>Koffiepunten & Campushelden</h1>
    <img src='dowloaden.png' alt='Kopje koffie' class='coffee'>
    <div class='scoreboard'>
        <h2>Scorebord</h2>
        <div class='student'>Emma Jansen: 120 punten</div>
        <div class='student'>Ravi de Groot: 95 punten</div>
        <div class='student'>Lotte Vermeer: 80 punten</div>
        <div class='student'>Daan Willems: 75 punten</div>
        <div class='student'>Sophie Bakker: 60 punten</div>
    </div>
</body>
</html>
