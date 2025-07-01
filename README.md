<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <title>DINNS STORE</title>
  <style>
    body {
      background: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
    }
    .rainbow-text {
      font-size: 3em;
      font-weight: bold;
      background-image: linear-gradient(90deg, red, orange, yellow, green, cyan, blue, violet);
      background-size: 400%;
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      animation: rainbow 5s linear infinite;
      white-space: nowrap;
    }

    @keyframes rainbow {
      0% { background-position: 0%; }
      100% { background-position: 400%; }
    }
  </style>
</head>
<body>
  <div class="rainbow-text">DINNS STORE</div>
</body>
</html>
