# phy
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servo Control</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <h2>Servo Motor Control</h2>
    
    <div class="control-container">
        <div class="control">
            <label for="knob1">Knob 1:</label>
            <input type="range" id="knob1" min="0" max="90" value="0" oninput="updateServo(1, this.value)">
            <span id="knob1Value">0°</span>
        </div>
        <div class="control">
            <label for="knob2">Knob 2:</label>
            <input type="range" id="knob2" min="0" max="90" value="0" oninput="updateServo(2, this.value)">
            <span id="knob2Value">0°</span>
        </div>
        <div class="control">
            <label for="knob3">Knob 3:</label>
            <input type="range" id="knob3" min="0" max="90" value="0" oninput="updateServo(3, this.value)">
            <span id="knob3Value">0°</span>
        </div>
        <br>
        <div class="control">
            <label for="slider1">Slider 1:</label>
            <input type="range" id="slider1" min="0" max="90" value="0" oninput="updateServo(4, this.value)">
            <span id="slider1Value">0°</span>
        </div>
        <div class="control">
            <label for="slider2">Slider 2:</label>
            <input type="range" id="slider2" min="0" max="90" value="0" oninput="updateServo(5, this.value)">
            <span id="slider2Value">0°</span>
        </div>
        <div class="control">
            <label for="slider3">Slider 3:</label>
            <input type="range" id="slider3" min="0" max="90" value="0" oninput="updateServo(6, this.value)">
            <span id="slider3Value">0°</span>
        </div>
        <br>
        <button onclick="resetServos()">Reset</button>
  i ann  </div>

    <script src="script.js"></script>
</body>
</html>
