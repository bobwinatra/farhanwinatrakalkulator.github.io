<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Membuat Kalkulator Sederhana</title>
    <link rel="stylesheet" href="theme.css">
</head>
<body>
    <div id="calculator">
        <input type="text" id="layar" class="calculator-screen" value="" disabled>

        <div class="calculator-keys">

            <button type="button" class="operator" value="+">+</button>
            <button type="button" class="operator" value="-">-</button>
            <button type="button" class="operator" value="*">&times;</button>
            <button type="button" class="operator" value="/">&divide;</button>

            <button type="button" value="7">7</button>
            <button type="button" value="8">8</button>
            <button type="button" value="9">9</button>

            <button type="button" value="4">4</button>
            <button type="button" value="5">5</button>
            <button type="button" value="6">6</button>

            <button type="button" value="1">1</button>
            <button type="button" value="2">2</button>
            <button type="button" value="3">3</button>
            <button type="button" value="0">0</button>

            <button type="button" value="." class="decimal">.</button>
            <button type="button" value="sin">sin</button>
            <button type="button" value="cos">cos</button>
            <button type="button" value="tan">tan</button>
            <button type="button" value="all-clear" class="all-clear">AC</button>
            <button class="equal-sign" value="=">=</button>

        </div>
    </input>

    <script src="script.js"></script>
</body>
</html>
