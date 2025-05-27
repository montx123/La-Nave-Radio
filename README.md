<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title></title>
  <style>
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
      color: white;
      padding: 10px 20px;
      border-radius: 5px;
      text-decoration: none;
      font-weight: bold;
      transition: background-color 0.3s ease;
      font-size: 1em;
    }

    a.whatsapp-button:hover {
      background-color: #1ebe57;
    }

    footer {
      margin-top: 40px;
      font-size: 0.8em;
      color: #888;
    }

    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&display=swap');
  </style>
</head>
<body>
  <img src="https://i.ibb.co/4Mr7zYm/La-Nave-Radio-Logo.png" alt="La Nave Radio Logo" class="logo" />
  <p>Transmitiendo en vivo...</p>

  <audio controls autoplay>
    <source src="https://stream.zeno.fm/utaaqemlboovv" type="audio/mpeg" />
    Tu navegador no soporta la transmisión de audio.
  </audio>

  <a href="https://wa.me/5493624878775" target="_blank" class="whatsapp-button" aria-label="WhatsApp">
    <svg xmlns="http://www.w3.org/2000/svg" width="20" height="20" fill="white" viewBox="0 0 24 24" style="margin-right: 10px;" >
      <path d="M20.52 3.48A11.86 11.86 0 0012 0a11.93 11.93 0 00-9.18 18.58l-2.28 6.12 6.33-2.1A11.93 11.93 0 0024 12c0-3.2-1.27-6.21-3.48-8.52zm-8.52 17.1a9.88 9.88 0 01-5.3-1.56l-.38-.23-3.16 1.04 1.07-3.07-.25-.39a9.95 9.95 0 01-1.55-5.36c0-5.52 4.5-10 10-10s10 4.48 10 10-4.5 10-10 10z"/>
      <path d="M16.2 14.3c-.3-.15-1.76-.87-2.03-.97s-.47-.15-.67.15-.77.97-.95 1.17-.35.22-.65.07a8.48 8.48 0 01-2.5-1.54 9.48 9.48 0 01-1.75-2.17c-.18-.31 0-.48.13-.63.12-.12.28-.3.43-.45a1.9 1.9 0 00.3-.5.56.56 0 000-.52c-.07-.15-.67-1.62-.92-2.23s-.47-.52-.65-.52-.38-.07-.58-.07-.52.08-.8.38a3.41 3.41 0 00-1.12 2.66c0 1.58.82 3.11 1.86 3.98a7.56 7.56 0 003.56 1.82 3.2 3.2 0 002.6-.64 2.58 2.58 0 00.83-1.97c0-.34-.23-.48-.52-.64z"/>
    </svg>
    Escribinos por WhatsApp
  </a>

  <footer>
    &copy; 2025 La Nave Radio. Todos los derechos reservados.
  </footer>
</body>
</html>
