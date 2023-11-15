<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Strona Agnieszki Michalik</title>
    <style>
        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            text-align: center;
            margin: 50px;
            background-color: #f4f4f4;
            color: #333;
        }

        #container {
            max-width: 600px;
            margin: 0 auto;
            padding: 20px;
            background-color: #fff;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
        }

        #message {
            font-size: 1.5em;
            margin-bottom: 20px;
            color: #007bff;
        }

        #button {
            padding: 10px 20px;
            font-size: 1em;
            cursor: pointer;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 4px;
        }

        #button:hover {
            background-color: #0056b3;
        }

        #result {
            font-size: 1.2em;
            margin-top: 20px;
            display: none;
            color: #dc3545;
        }
    </style>
</head>

<body>
    <div id="container">
        <div id="message">Oto strona Agnieszki Michalik, Doktora Pomagania Uniwersytetu Wrocławskiego. Żeby umówić się na wizytę, kliknij poniższy przycisk.</div>
        <button id="button" onclick="showResult()">Kliknij, by sobie pomóc</button>
        <div id="result">Brak terminów. Doktor A. Michalik jest obecnie na wakacjach i ma chillere, pal gume.</div>
    </div>

    <script>
        function showResult() {
            var resultDiv = document.getElementById("result");
            resultDiv.style.display = "block";
        }
    </script>
</body>

</html>
