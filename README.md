	
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <title>Página da Ana Paula</title>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/p5.js/1.4.0/p5.js"></script&gt;
  <style>
    body {
      background-color: green;
      color: white;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    #canvas-container {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    h1 {
      font-size: 2.5em;
      display: inline-block;
      margin-right: 20px; /* Espaçamento entre o título e a imagem */
    }

    img {
      max-width: 400px; /* Diminui a imagem para 200px de largura */
      height: auto;
      vertical-align: middle;
    }
  </style>
</head>

<body>
  <div id="canvas-container">
    <h1>Essa é uma página de teste</h1>
    <img src="AluraStart.jpg" alt="Imagem da Alura Start">
  </div>
  <script src="sketch.js"></script>
</body>
</html>
