
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title></title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');

    body {
      margin: 0;
      font-family: 'Orbitron', sans-serif;
      background-color: #000000;
      color: #00f0ff;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      height: 100vh;
      background-image: radial-gradient(#1a1a1a 1px, #000 1px);
      background-size: 40px 40px;
    }

    img.logo {
      width: 220px;
      margin-bottom: 20px;
      border-radius: 10px;
    }

    p {
      font-size: 1.3em;
      margin: 10px 0 30px;
      color: #00f0ff;
    }

    audio {
      width: 90%;
      max-width: 320px;
      border-radius: 5px;
    }

    a.whatsapp-button {
      margin-top: 20px;
      display: inline-flex;
      align-items: center;
      background-color: #25D366;
      color: #fff;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s ease;
    }

    a.whatsapp-button:hover {
      background-color: #1ebc59;
    }

    .whatsapp-button img {
      width: 20px;
      height: 20px;
      margin-right: 10px;
    }

    footer {
      margin-top: 40px;
      font-size: 0.8em;
      color: #888;
    }
  </style>
</head>
<body>
  <!-- Nueva portada -->
  <img src="https://iili.io/3mmHogI.jpg" alt="La Nave Radio Logo" class="logo" />
  
  <p>Transmitiendo en vivo...</p>

  <audio controls autoplay>
    <source src="https://stream.zeno.fm/utaaqemlboovv" type="audio/mpeg" />
    Tu navegador no soporta la transmisión de audio.
  </audio>

  <!-- Botón WhatsApp oficial -->
  <a href="https://wa.me/5493624878775" target="_blank" class="whatsapp-button">
    <img src="https://upload.wikimedia.org/wikipedia/commons/5/5e/WhatsApp_icon.png" alt="WhatsApp" />
    Escribinos por WhatsApp
  </a>

  <footer>
    &copy; 2025 La Nave Radio. Todos los derechos reservados.
  </footer>
</body>
</html>
