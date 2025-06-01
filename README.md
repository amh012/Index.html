<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <title>Untuk Kamu, Sayang 💖</title>
  <style>
    body {
      background: linear-gradient(to right, #ffe6f0, #fff0f5);
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      padding: 30px;
      color: #ff3399;
    }

    h1 {
      font-size: 3em;
      animation: glow 2s ease-in-out infinite alternate;
    }

    @keyframes glow {
      from {
        text-shadow: 0 0 10px #ff3399;
      }
      to {
        text-shadow: 0 0 20px #ff0066, 0 0 30px #ff3399;
      }
    }

    img {
      width: 300px;
      border-radius: 15px;
      box-shadow: 0 0 20px #ff99cc;
      margin: 20px auto;
    }

    .heart {
      font-size: 5em;
      animation: beat 1s infinite;
    }

    @keyframes beat {
      0%, 100% {
        transform: scale(1);
      }
      50% {
        transform: scale(1.2);
      }
    }

    .btn {
      background-color: #ff66b2;
      border: none;
      color: white;
      padding: 12px 24px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      margin-top: 20px;
    }

    .btn:hover {
      background-color: #ff3385;
    }
  </style>
</head>
<body>
  <h1>Hai Sayang! 😘</h1>
  <p>Kalau kamu coklat, aku pengen jadi wafer biar kita terus dibungkus jadi satu 💞</p>
  
  <div class="heart">❤️</div>

  <img src="https://github.com/amh012/Index.html/blob/main/4D348237-75B4-4CC7-B0EF-12A9A2AEB35F.png" alt="Pasangan lucu">
  
  <p>Aku nggak butuh kopi, cukup senyum kamu yang bikin aku melek terus ☕💕</p>

  <button class="btn" onclick="alert('Aku sayang kamu lebih dari aku sayang WiFi 😘')">Klik kalau sayang balik!</button>

  <!-- Musik romantis autoplay -->
  <audio autoplay loop>
    <source src="https://github.com/amh012/Index.html/blob/main/2019-07-01_-_Love_Spell_-_David_Fesliyan.mp3" type="audio/mpeg">
  </audio>
</body>
</html>
