<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Futbol Arama Sitesi</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      background: #111;
      font-family: Arial, sans-serif;
      color: #fff;
    }
    .box {
      text-align: center;
    }
    h1 {
      margin-bottom: 25px;
    }
    button {
      width: 220px;
      padding: 15px;
      margin: 10px 0;
      font-size: 18px;
      border: none;
      border-radius: 8px;
      background: #1db954;
      color: #000;
      cursor: pointer;
    }
    button:hover {
      background: #17a64a;
    }
  </style>
</head>
<body>

  <div class="box">
    <h1>Futbolcu Ara</h1>

    <button onclick="window.open('https://www.google.com/search?q=icardi','_blank')">
      Icardi
    </button>

    <button onclick="window.open('https://www.google.com/search?q=osimhen','_blank')">
      Osimhen
    </button>

    <button onclick="window.open('https://www.google.com/search?q=mbappe','_blank')">
      Mbappé
    </button>
  </div>

</body>
</html>
