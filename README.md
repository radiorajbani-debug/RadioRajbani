 <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Online Radio RajBani</title>

  <!-- Favicon -->
  <link rel="icon" type="image/png" sizes="32x32" href="favicon-32.png">
  <link rel="icon" type="image/png" sizes="192x192" href="favicon-192.png">
  <link rel="apple-touch-icon" href="favicon-512.png">

  <!-- PWA Manifest -->
  <link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="#ff0000">

  <!-- Styles -->
  <style>
    body {
      margin: 0;
      background-color: #000;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: 'Segoe UI', sans-serif;
      color: #fff;
    }
    .logo-container {
      text-align: center;
      animation: fadeIn 2s ease-in-out;
    }
    .logo-container img {
      max-width: 300px;
      width: 80%;
      height: auto;
      filter: drop-shadow(0 0 10px #ff0000);
    }
    .title {
      font-size: 2em;
      font-family: 'Brush Script MT', cursive;
      margin-top: 20px;
      color: #f0f0f0;
    }
    .tagline {
      font-size: 1.2em;
      color: red;
      margin-top: 10px;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.9); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="logo-container">
    <img src="logo.jpeg" alt="Online Radio RajBani Logo" />
    <div class="title">Online Radio RajBani</div>
    <div class="tagline">The King's Voice On Air</div>
  </div>
</body>
</html>
[3:04 am, 01/10/2025] Biplob Bhuiyan: {
  "name": "Online Radio RajBani",
  "short_name": "RajBani",
  "start_url": "/index.html",
  "display": "standalone",
  "background_color": "#000000",
  "theme_color": "#ff0000",
  "description": "The King's Voice On Air — A spiritually immersive online radio experience.",
  "icons": [
    {
      "src": "favicon-192.png",
      "sizes": "192x192",
      "type": "image/png"
    },
    {
      "src": "favicon-512.png",
      "sizes": "512x512",
      "type": "image/png"
    }
  ]
}
