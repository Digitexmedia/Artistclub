# Artistclub

<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>About Rodger Fox</title>
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@600&family=Kalam&display=swap" rel="stylesheet">
  <style>
    html, body {
      margin: 0;
      padding: 0;
      height: 100%;
      overflow: hidden;
      font-family: 'Orbitron', sans-serif;
      color: white;
    }
    #background-animation {
      position: fixed;
      top: 0;
      left: 0;
      width: 100vw;
      height: 100vh;
      z-index: -1;
      background: linear-gradient(-45deg, #1a1a2e, #0f3460, #53354a, #903749);
      background-size: 400% 400%;
      animation: gradientFlow 15s ease infinite;
    }
    @keyframes gradientFlow {
      0% {
        background-position: 0% 50%;
      }
      50% {
        background-position: 100% 50%;
      }
      100% {
        background-position: 0% 50%;
      }
    }
    main {
      padding: 2rem;
      overflow-y: auto;
      height: 100vh;
      background: rgba(0, 0, 0, 0.6);
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin-bottom: 2rem;
    }
    nav a {
      color: white;
      background: linear-gradient(45deg, #ff416c, #ff4b2b);
      padding: 0.5rem 1rem;
      border-radius: 8px;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      transform: scale(1.05);
    }
    header {
      text-align: center;
      margin-bottom: 2rem;
    }
    header h1 {
      font-size: 3rem;
      font-family: 'Kalam', cursive;
    }
    .about-content {
      max-width: 900px;
      margin: 0 auto;
      font-family: 'Kalam', cursive;
      background-color: rgba(0, 0, 0, 0.4);
      padding: 2rem;
      border-radius: 16px;
      box-shadow: 0 0 20px rgba(255, 255, 255, 0.1);
      animation: fadeInUp 2s ease-out;
    }
    .about-content img {
      max-width: 100%;
      border-radius: 12px;
      margin: 1rem 0;
      animation: pulse 10s infinite ease-in-out;
    }
    .about-content p {
      font-size: 1.2rem;
      line-height: 1.8;
    }
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(40px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    @keyframes pulse {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.02);
      }
    }
  </style>
</head>
<body>
  <div id="background-animation"></div>
  <main>
    <nav>
      <a href="index.html">🏠 Home</a>
      <a href="shop.html">🛍 Shop</a>
      <a href="contact.html">📞 Contact</a>
      <a href="https://open.spotify.com/artist/717HmnSffVU331xg4IIYFO?si=oXD9a2J6SVext74Jys-0uA" target="_blank">🎧 Stream</a>
    </nav><header>
  <h1>🎤 About Rodger Fox</h1>
</header>

<div class="about-content">
  <img src="https://via.placeholder.com/800x400?text=Rodger+Fox+Live" alt="Rodger Fox performing" />
  <p>
    Rodger Fox is more than an artist — he's a movement. Born with a mic in his hand and a story in his soul, Rodger has risen to be one of the most inspiring voices of this generation. His music is not just rhythm and rhymes — it's a reflection of passion, purpose, and pain turned into power.
  </p>
  <p>
    From underground performances to major streaming platforms, Rodger continues to ignite audiences with electrifying energy and heartfelt lyrics. His merchandise reflects his vision: authentic, bold, and unforgettable.
  </p>
  <img src="https://via.placeholder.com/800x400?text=Behind+the+Scenes" alt="Behind the scenes" />
  <p>
    Whether he's on stage or in the studio, Rodger Fox represents creativity, resilience, and the spirit of every artist fighting to make their voice heard. Welcome to the journey. Wear it. Stream it. Live it.
  </p>
</div>

  </main>
</body>
</html>
