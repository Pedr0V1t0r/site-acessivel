<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Turismo Acessível</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f8ff;
      color: #333;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #00509e;
      color: white;
      padding: 20px;
      text-align: center;
    }
    nav {
      display: flex;
      justify-content: center;
      background-color: #0073e6;
      padding: 10px 0;
    }
    nav a {
      color: white;
      text-decoration: none;
      margin: 0 15px;
      font-weight: bold;
    }
    nav a:focus {
      outline: 3px solid #ffcc00;
      outline-offset: 2px;
    }
    main {
      padding: 20px;
    }
    h1, h2 {
      color: #00509e;
    }
    .atrativo {
      border: 2px solid #00509e;
      border-radius: 10px;
      padding: 15px;
      margin-bottom: 25px;
      background-color: #e0f0ff;
    }
    img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
    }
    .descricao {
      font-size: 16px;
      margin-top: 10px;
    }
    .acessibilidade {
      font-size: 14px;
      margin-top: 5px;
      color: #004080;
    }
    button {
      background-color: #00509e;
      color: white;
      border: none;
      padding: 10px 15px;
      margin-top: 10px;
      border-radius: 5px;
      cursor: pointer;
    }
    button:focus {
      outline: 3px solid #ffcc00;
      outline-offset: 2px;
    }
    video {
      width: 100%;
      max-width: 600px;
      border-radius: 8px;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<header>
  <h1>Turismo Acessível ♿</h1>
  <p>Experiências turísticas para todos</p>
</header>

<nav>
  <a href="#praia">Praias</a>
  <a href="#museu">Museus</a>
  <a href="#videos">Vídeos</a>
</nav>

<main>
  <section id="praia" class="atrativo">
    <h2>Praia Azul</h2>
    <img src="praia.jpg" alt="Praia com areia branca e pessoas usando cadeiras de rodas adaptadas">
    <p class="descricao">A Praia Azul possui rampas de acesso e cadeiras de rodas adaptadas para turistas com mobilidade reduzida.</p>
    <p class="acessibilidade">Acessível para cadeirantes ♿ | Banheiros adaptados | Rampas de acesso</p>
    <button>Saiba Mais</button>
  </section>

  <section id="museu" class="atrativo">
    <h2>Museu Histórico</h2>
    <img src="museu.jpg" alt="Museu com sinalização tátil e audiodescrição disponível">
    <p class="descricao">O Museu Histórico oferece audiodescrição para deficientes visuais e sinalização tátil em todas as salas.</p>
    <p class="acessibilidade">Audiodescrição disponível | Sinalização tátil | Guias treinados</p>
    <button>Visite o Museu</button>
  </section>

  <section id="videos" class="atrativo">
    <h2>Vídeo Turístico</h2>
    <video controls>
      <source src="turismo.mp4" type="video/mp4">
      Seu navegador não suporta vídeos HTML5.
    </video>
    <p class="descricao">Vídeo com legendas e descrição de atrações turísticas acessíveis.</p>
  </section>
</main>

</body>
</html>
