<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona Agnieszki Michalik</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }

        #message {
            font-size: 1.5em;
            margin-bottom: 20px;
        }

        #button {
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
        }

        #result {
            font-size: 1.2em;
            margin-top: 20px;
            display: none;
        }
    </style>
</head>

<body>
    <div id="message">Oto strona Agnieszki Michalik, Doktora Pomagania Uniwersytetu Wrocławskiego. Żeby umówić się na wizytę, kliknij poniższy przycisk.</div>
    <button id="button" onclick="showResult()">Kliknij, by sobie pomóc</button>
    <div id="result">Brak terminów. Doktor A. Michalik jest obecnie na wakacjach i ma chillere, pal gume.</div>

    <script>
        function showResult() {
            var resultDiv = document.getElementById("result");
            resultDiv.style.display = "block";
        }
    </script>
</body>

</html>
