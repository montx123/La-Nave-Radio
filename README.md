

La casa de los Extraterrestres!!!

<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>La Nave Radio</title>
  <style>
    body {
      background-color: #000;
      color: #fff;
      font-family: 'Segoe UI', sans-serif;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      min-height: 100vh;
      margin: 0;
      padding: 20px;
    }

    img {
      max-width: 300px;
      height: auto;
      margin-bottom: 40px;
      filter: drop-shadow(0 0 10px #0ff);
    }

    .player {
      background-color: #111;
      padding: 20px;
      border-radius: 16px;
      box-shadow: 0 0 15px #0ff4;
      width: 100%;
      max-width: 400px;
      text-align: center;
    }

    audio {
      width: 100%;
      margin-top: 10px;
    }

    h1 {
      font-size: 20px;
      margin-bottom: 10px;
      color: #0ff;
    }
  </style>
</head>
<body>

  <!-- Logo -->
  <img src="la_nave_logo.png" alt="Logo La Nave Radio">

  <!-- Reproductor -->
  <div class="player">
    <h1>Transmitiendo en vivo</h1>
    <audio controls>
      <source src="https://stream.zeno.fm/utaaqemlboovv" type="audio/mpeg">
      Tu navegador no soporta el audio.
    </audio>
  </div>

</body>
</html>
>
