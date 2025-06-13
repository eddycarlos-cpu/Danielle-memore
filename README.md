# Danielle-memore
Em memória de Danielle 
<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <title>Em Memória de Danielle</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Georgia', serif;
      background-color: #f5f5f5;
      color: #222;
    }

    header {
      background-color: #000;
      color: white;
      text-align: center;
      padding: 30px 10px;
    }

    header h1 {
      font-size: 2em;
      margin: 0;
    }

    header p {
      font-size: 1.1em;
      margin: 5px 0 0;
      font-style: italic;
    }

    .main-photo {
      width: 100%;
      max-height: 450px;
      object-fit: cover;
      display: block;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
      padding: 20px;
    }

    .tribute {
      background: white;
      padding: 25px;
      border-radius: 6px;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      line-height: 1.8;
    }

    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(140px, 1fr));
      gap: 10px;
      margin-top: 30px;
    }

    .gallery img {
      width: 100%;
      height: 140px;
      object-fit: cover;
      border-radius: 4px;
      filter: grayscale(60%);
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #555;
    }

    @media(max-width:600px) {
      header h1 { font-size: 1.5em; }
    }
  </style>
</head>
<body>

<header>
  <h1>Em Memória de Danielle</h1>
  <p>16 de novembro de 2004 – 23 de janeiro de 2025</p>
</header>

<img src="principal.jpg" alt="Foto da Danielle" class="main-photo">

<div class="container">
  <div class="tribute">
    <p>
      Danielle não era apenas alguém que passou pela vida… ela marcou cada canto por onde andou.  
      Com seu sorriso cheio de Cristo, dizia: <em>"eu faço os outros sorrirem porque Cristo vive em mim."</em>
    </p>

    <p>
      Jovem adventista, ativa no clube de desbravadores, apaixonada pela natureza, pelas viagens e pelos acampamentos. Seu amor por Deus transbordava em pequenos gestos, em olhares, em silêncios.
    </p>

    <p>
      Hoje, deixamos aqui um espaço de saudade — e gratidão. Pela vida que ela teve, pela luz que espalhou, pela fé que viveu.
    </p>
  </div>

  <div class="gallery">
    <img src="foto2.jpg" alt="Danielle sorrindo">
    <img src="foto3.jpg" alt="Danielle no campo">
    <img src="foto4.jpg" alt="Danielle e flores">
    <img src="foto5.jpg" alt="Danielle em viagem">
  </div>
</div>

<footer>
  “Preciosa é à vista do Senhor a morte dos seus santos.” – Salmo 116:15
</footer>

</body>
</html>
