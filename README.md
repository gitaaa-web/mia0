<!DOCTYPE html>
<html>

<html>
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>MIA CHAN</title>

  <style>
    .butterfly {
  width: 40px;
  height: 40px;
  background-image: url('https://imgur.com/lzXTWSo.png'); /* Gambar kupu-kupu */
  background-size: contain;
  background-repeat: no-repeat;
  position: absolute;
  animation: fly 10s linear infinite;
  z-index: 1;
  pointer-events: none;
}

.butterfly1 {
  top: 30%;
  left: -50px;
  animation-delay: 0s;
}

.butterfly2 {
  top: 60%;
  left: -100px;
  animation-delay: 3s;
}

.butterfly3 {
  top: 80%;
  left: -80px;
  animation-delay: 5s;
}

@keyframes fly {
  0% { transform: translateX(0) translateY(0) rotate(0deg); }
  50% { transform: translateX(100vw) translateY(-100px) rotate(180deg); }
  100% { transform: translateX(200vw) translateY(0) rotate(360deg); }
}

  button {
    background-color: #ff69b4;
    color: white;
    border: none;
    padding: 10px 20px;
    border-radius: 25px;
    font-size: 16px;
    cursor: pointer;
    margin-top: 20px;
  }

  button:hover {
    background-color: #ff1493;
  }
</style>
<style>
  .instagram-link {
    display: inline-block;
    margin-top: 20px;
    font-size: 20px;
    text-decoration: none;
    color: white;
    background-color: #ff69b4;
    padding: 10px 20px;
    border-radius: 5px;
    transition: background-color 0.3s ease;
  }
  
.mood-container {
position: fixed;
bottom: 20px;
right: 20px;
z-index: 2;
transform: scale(0.6); /* Ukurannya dikecilin */
  transform-origin: bottom right;
}
</style>
  </style>

  
</head>
<body>
  <!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>MIA CHAN</title>
  <style>
    body, html {
      margin: 0;
      padding: 0;
      font-family: 'Arial', sans-serif;
      overflow: hidden;
    }
    video.bg-video {
      position: fixed;
      top: 0;
      left: 0;
      min-width: 100%;
      min-height: 100%;
      object-fit: cover;
      z-index: -1;
    }
    .overlay {
      background-color: transparent;
      min-height: 100vh;
      padding-top: 50px;
      color: white;
      text-align: center;
    }
    .profile {
      width: 120px;
      height: 120px;
      border-radius: 50%;
      border: 3px solid white;
      object-fit: cover;
    }
    h1 {
      font-size: 2.5em;
      margin: 10px 0 5px;
    }
    p.bio {
      font-size: 1.2em;
      margin-bottom: 30px;
    }
    .links a {
      display: block;
      margin: 10px auto;
      width: 200px;
      padding: 10px;
      background-color: rgba(255, 255, 255, 0.1);
      border: 1px solid white;
      border-radius: 25px;
      text-decoration: none;
      color: white;
      transition: background 0.3s;
    }
    .links a:hover {
      background-color: white;
      color: black;
    }
    audio {
      display: none;
    }
  </style>
</head>
<body>
  <video class="bg-video" autoplay muted loop playsinline>
    <source src="https://f.uguu.se/LAsntMxl.mp4" type="video/mp4" />
  </video>

  <div class="overlay">
    <img src="https://i.imgur.com/lGjBX20.jpeg" alt="Foto Profil" class="profile" />
    <h1>MIA CHAN</h1>
    <p class="bio">いつもあなたのそばにいる私です ❤️</p>

<div class="links">
  <a href="https://chat.whatsapp.com/DxP4nYO502hJVj8rZ9xXEu" target="_blank">Grup WhatsApp</a>
  <a href="https://www.instagram.com/chuchu100_/" target="_blank">Instagram</a>
</div>

    
<button
onclick="document.getElemenById( 'bg-music').play()">▶ Play Music</button>
 <audio id="bg-music">
      <source src="https://h.uguu.se/LlyqWcme.mp3" type="audio/mpeg">
      Your browser does not support the audio element.
    </audio>
  </div>
  <!-- Kupu-kupu animasi -->
<div class="butterfly butterfly1"></div>
<div class="butterfly butterfly2"></div>
<div class="butterfly butterfly3"></div>
</body>
</html>
<title>Visualisasi Mood</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      color: white;  /* Teks default berwarna putih */
    }
    .mood-container {
      text-align: center;
      padding: 20px;
      border-radius: 10px;
    }
    .mood-btn {
      padding: 15px 30px;
      margin: 10px;
      border: none;
      font-size: 18px;
      cursor: pointer;
      border-radius: 5px;
      transition: transform 0.3s ease;
    }
    .mood-btn:hover {
      transform: scale(1.1);
    }
    #mood-message {
      font-size: 24px;
      font-weight: bold;
      margin-top: 20px;
    }
    #mood-icon {
      font-size: 50px;
      margin-top: 20px;
    }
  </style>
</head>
<body>
  <div class="mood-container">
    <h2>Bagaimana perasaanmu hari ini?</h2>
    <button class="mood-btn" id="happy" style="background-color: #ff0000;  /* Merah */;">Bahagia</button>
    <button class="mood-btn" id="sad" style="background-color: #607d8b;">Sedih</button>
    <button class="mood-btn" id="neutral" style="background-color: #4caf50;">Netral</button>
    <div id="mood-message"></div>
    <div id="mood-icon"></div>
  </div>

  <script>
    const happyBtn = document.getElementById('happy');
    const sadBtn = document.getElementById('sad');
    const neutralBtn = document.getElementById('neutral');
    const moodMessage = document.getElementById('mood-message');
    const moodIcon = document.getElementById('mood-icon');

    happyBtn.addEventListener('click', () => {
      moodMessage.textContent = "Senang mendengarnya! Teruskan dengan semangat!";
      moodMessage.style.color = '#ff0000';  // Teks bahagia berwarna merah
      moodIcon.innerHTML = '😊';  // Ikon bahagia
    });

    sadBtn.addEventListener('click', () => {
      moodMessage.textContent = "KASIAN BANGET.";
      moodMessage.style.color = '#607d8b';  // Teks sedih berwarna abu-abu
      moodIcon.innerHTML = '😢';  // Ikon sedih
    });

    neutralBtn.addEventListener('click', () => {
      moodMessage.textContent = "OK DEH!";
      moodMessage.style.color = '#4caf50';  // Teks netral berwarna hijau
      moodIcon.innerHTML = '😐';  // Ikon netral
      });
  </script>
</body>
</html>

  <script>
    

  </script>
</body>
</html>
