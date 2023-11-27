<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Игровое лобби</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      background-color: #f0f0f0;
    }

    .lobby-container {
      text-align: center;
    }

    h1 {
      color: #333;
    }

    button {
      padding: 10px 20px;
      font-size: 16px;
      margin: 10px;
      cursor: pointer;
      background-color: #4caf50;
      color: white;
      border: none;
      border-radius: 5px;
    }

    input {
      padding: 8px;
      margin: 5px;
    }
  </style>
</head>
<body>

<div class="lobby-container">
  <h1>Добро пожаловать в игровое лобби!</h1>
  <button onclick="joinGame()">Присоединиться к игре</button>
  <button onclick="createGame()">Создать новую игру</button>
</div>

<script>
  function joinGame() {
    var playerName = prompt("Введите ваше имя:");
    if (playerName) {
      alert("Игрок " + playerName + " присоединился к игре!");
      // Дополнительная логика для присоединения к игре с использованием имени игрока
    }
  }

  function createGame() {
    var gameName = prompt("Введите название игры:");
    if (gameName) {
      alert("Игра " + gameName + " создана!");
      // Дополнительная логика для создания новой игры с использованием названия игры
    }
  }
</script>

</body>
</html>
