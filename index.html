<html lang="tr">
<head>
  <meta charset="UTF-8">
  <title>Doğum Günün Kutlu Olsun!</title>
  <style>
    body {
      text-align: center;
      background: #fff5f7;
      font-family: Arial, sans-serif;
      overflow: hidden;
      transition: background 1s;
    }
    .cake {
      font-size: 120px;
      margin-top: 150px;
      cursor: pointer;
      animation: float 3s ease-in-out infinite;
    }
    @keyframes float {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-20px); }
    }

    /* Zarf */
    .envelope {
      font-size: 100px;
      cursor: pointer;
      display: none;
      margin-top: 50px;
      animation: bounce 2s infinite;
    }
    @keyframes bounce {
      0%, 100% { transform: translateY(0); }
      50% { transform: translateY(-15px); }
    }

    /* Mesaj Kutusu */
    .note {
      display: none;
      margin: 20px auto;
      padding: 20px;
      max-width: 500px;
      background: white;
      border-radius: 12px;
      box-shadow: 0 0 15px rgba(0,0,0,0.3);
      font-size: 18px;
      text-align: left;
      line-height: 1.5;
      animation: slideUp 1s forwards;
    }
    @keyframes slideUp {
      from { transform: translateY(100%); opacity: 0; }
      to { transform: translateY(0); opacity: 1; }
    }

    /* 🎶 Müzik Çalar */
    .music-player {
      position: fixed;
      bottom: 100px; /* daha yukarı alındı */
      left: 50%;
      transform: translateX(-50%);
      background: rgba(255, 255, 255, 0.95);
      padding: 15px 25px;
      border-radius: 15px;
      box-shadow: 0 0 12px rgba(0,0,0,0.25);
      display: flex;
      align-items: center;
      gap: 16px;
      font-size: 16px;
      display: none;
      z-index: 9999;
    }
    
 .music-player button {
      border: none;
      padding: 12px 16px;
      border-radius: 8px;
      cursor: pointer;
      font-size: 18px;
      transition: 0.3s;
      background: #ff4081;
      color: white;
    }
    .music-player button:hover {
      background: #e73370;
    }
    .music-info {
      display: flex;
      align-items: center;
      gap: 12px;
      min-width: 180px;
    }
    .music-info img {
      width: 55px;
      height: 55px;
      border-radius: 8px;
    }
    .music-info span {
      font-weight: bold;
      color: #333;
      font-size: 16px;
    }

    /* 📱 Telefon uyumluluğu */
    @media (max-width: 600px) {
      .music-player {
        bottom: 40px;
        padding: 12px 18px;
        gap: 12px;
        font-size: 14px;
      }
      .music-player button {
        padding: 10px 14px;
        font-size: 16px;
      }
      .music-info img {
        width: 45px;
        height: 45px;
      }
      .music-info span {
        font-size: 14px;
      }
    }
  </style>
</head>
<body>
  <!-- İlk sadece pasta -->
  <div class="cake" onclick="startParty()">🎂</div>

  <!-- Zarf -->
  <div class="envelope" id="envelope" onclick="showNote()">✉️</div>

  <!-- Mesaj -->
  <div class="note" id="note"></div>

  <!-- Müzik -->
  <audio id="bgMusic" loop></audio>

  <!-- Müzik Çalar -->
  <div class="music-player" id="player">
    <div class="music-info">
      <img id="coverArt" src="" alt="Kapak">
      <span id="songName">Şarkı yükleniyor...</span>
    </div>
    <button onclick="prevSong()">⏮️</button>
    <button onclick="togglePlay()">⏯️</button>
    <button onclick="nextSong()">⏭️</button>
    <button id="volumeBtn" onclick="cycleVolume()">🔊 ▁</button>
  </div>

  <script>
    const songs = [
      {name: "yezdacukk ", url: "muzik1.mp3", cover:"cover1.png"},
      {name: "Doğum günü kızı ", url: "muzik2.mp3", cover:"cover2.jpg"},
      {name: "💕", url: "muzik1.mp3", cover:"cover1.png"}
    ];

    const audio = document.getElementById("bgMusic");
    const songName = document.getElementById("songName");
    const coverArt = document.getElementById("coverArt");
    const noteBox = document.getElementById("note");
    const volumeBtn = document.getElementById("volumeBtn");
    let currentSong = 0;
    let volumeLevel = 1;
    let noteShown = false;

    const volumeSteps = [0.2, 0.4, 0.7, 1.0];

    const message = "pişt eşşek nabıyon nasılsın hayatın nasıl gidiyor biliyorum ben biraz kötü biriyim ama bazen de böyle şeyleri düşünülebilcek kadar da zarifimdir tanışalı yaklaşık 2 yıl oldu belkide geçti fakat hem kalbimde hemde yüreğimde çok iyi bir yere sahip oldun be yaparsam yapayım ne sokarsam sokayım kalbime/yüreğime başaramıyorum ulan seni silmeyi yani benim tanıdıgım yezda bana tanıttıgın yezda çok ayrı bir yerlerde bunu bilmeni isterim inşallah artık sende beni düşünür arada aklına gelirim belki hatırlarsan bir değer verrsin umarım yani,uzun lafın kısası bana verdiğin ve kattığın herşey için teşekkür ederim yani doğum günün kutlu olsun nice bizli senelere inşallah  🎉🎂💖 16.06.2008";

    function startParty() {
      document.body.style.background = "linear-gradient(to right, #ffdde1, #ee9ca7)";
      document.querySelector(".cake").style.display = "none";
      document.getElementById("envelope").style.display = "block";
      document.getElementById("player").style.display = "flex";
      playSong();
    }

    function showNote() {
      if (noteShown) return;
      noteShown = true;
      noteBox.style.display = "block";
      typeWriter(message, noteBox);
    }

    function typeWriter(text, element) {
      element.innerHTML = "";
      let i = 0;
      const interval = setInterval(() => {
        element.innerHTML += text.charAt(i);
        i++;
        if (i >= text.length) clearInterval(interval);
      }, 50);
    }

    function playSong() {
      audio.src = songs[currentSong].url;
      songName.textContent = songs[currentSong].name;
      coverArt.src = songs[currentSong].cover;
      audio.volume = volumeSteps[0];
      audio.play().catch((e)=>{console.log("Müzik engellendi:", e)});
    }
    function togglePlay() {
      if (audio.paused) { audio.play(); } else { audio.pause(); }
    }
    function nextSong() {
      currentSong = (currentSong + 1) % songs.length;
      playSong();
    }
    function prevSong() {
      currentSong = (currentSong - 1 + songs.length) % songs.length;
      playSong();
    }

    function cycleVolume() {
      volumeLevel++;
      if (volumeLevel > 4) volumeLevel = 1;
      audio.volume = volumeSteps[volumeLevel - 1];
      if (volumeLevel === 1) {
        volumeBtn.textContent = "🔊 ▁";
      } else if (volumeLevel === 2) {
        volumeBtn.textContent = "🔊 ▁▃";
      } else if (volumeLevel === 3) {
        volumeBtn.textContent = "🔊 ▁▃▆";
      } else if (volumeLevel === 4) {
        volumeBtn.textContent = "🔊 ▁▃▆█";
      }
    }
  </script>
</body>
</html>
