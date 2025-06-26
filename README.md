<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Advanced Tic Tac Toe</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <div class="container">
    <h1>Tic Tac Toe</h1>

    <div id="mode-select">
      <button onclick="setMode('2player')">2 Player</button>
      <button onclick="setMode('computer')">Vs Computer</button>
    </div>

    <div id="level-select" style="display: none;">
      <button onclick="setLevel('easy')">Easy</button>
      <button onclick="setLevel('medium')">Medium</button>
      <button onclick="setLevel('hard')">Difficult</button>
    </div>

    <div id="status">Player Turn: <span id="turn">X</span></div>

    <div id="game-board">
      <div class="cell" data-index="0"></div>
      <div class="cell" data-index="1"></div>
      <div class="cell" data-index="2"></div>
      <div class="cell" data-index="3"></div>
      <div class="cell" data-index="4"></div>
      <div class="cell" data-index="5"></div>
      <div class="cell" data-index="6"></div>
      <div class="cell" data-index="7"></div>
      <div class="cell" data-index="8"></div>
    </div>

    <div id="result"></div>
    <button id="reset">🔁 New Game</button>
  </div>

  <script src="script.js"></script>
</body>
</html>
