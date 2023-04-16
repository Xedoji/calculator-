
<!DOCTYPE html>
<html>
<head>
    <title>Calculator</title>
    <link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
    <div id="calculator">
        <input type="text" id="screen">
        <div class="row">
            <button onclick="addToScreen('7')">7</button>
            <button onclick="addToScreen('8')">8</button>
            <button onclick="addToScreen('9')">9</button>
            <button onclick="addToScreen('/')">/</button>
        </div>
        <div class="row">
            <button onclick="addToScreen('4')">4</button>
            <button onclick="addToScreen('5')">5</button>
            <button onclick="addToScreen('6')">6</button>
            <button onclick="addToScreen('*')">*</button>
        </div>
        <div class="row">
            <button onclick="addToScreen('1')">1</button>
            <button onclick="addToScreen('2')">2</button>
            <button onclick="addToScreen('3')">3</button>
            <button onclick="addToScreen('-')">-</button>
        </div>
        <div class="row">
            <button onclick="addToScreen('0')">0</button>
            <button onclick="addToScreen('.')">.</button>
            <button onclick="calculate()">=</button>
            <button onclick="addToScreen('+')">+</button>
        </div>
        <div class="row">
            <button onclick="clearScreen()">Clear</button>
        </div>
    </div>

    <script src="script.js"></script>
</body>
</html>
