<!DOCTYPE html>
<html lang="pl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Pobierz plik</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin-top: 100px;
      background-color: #f4f4f4;
    }
    h1 {
      color: #333;
    }
    p {
      color: #555;
    }
    .download-btn {
      display: inline-block;
      padding: 12px 25px;
      margin-top: 20px;
      background-color: #4CAF50;
      color: white;
      text-decoration: none;
      font-size: 18px;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .download-btn:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>

  <h1>Pobierz plik</h1>
  <p>Kliknij przycisk poniżej, aby pobrać plik:</p>

  <a class="download-btn" href="N.txt" download>Pobierz plik</a>

</body>
</html>
