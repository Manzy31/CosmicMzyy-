<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Firman Septian | Cosmic Crasher</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Orbitron:wght@400;700&family=Outfit:wght@300;400;700&display=swap" rel="stylesheet" />

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      font-family: 'Outfit', sans-serif;
      background: #0a0a0a url('https://www.transparenttextures.com/patterns/stardust.png');
      color: #f0f0f0;
      line-height: 1.6;
    }

    header {
      background: #111;
      padding: 20px 0;
      text-align: center;
      border-bottom: 2px solid #222;
    }

    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 2em;
    }

    nav a {
      color: #0ff;
      margin: 0 10px;
      text-decoration: none;
    }

    nav a.active {
      font-weight: bold;
      color: #fff;
    }

    .container {
      max-width: 1000px;
      margin: 20px auto;
      padding: 0 20px;
    }

    .project-list {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(240px, 1fr));
      gap: 20px;
    }

    .project-card {
      background: #1a1a1a;
      padding: 15px;
      border-radius: 10px;
      box-shadow: 0 0 8px rgba(0,255,255,0.2);
    }

    .project-card h4 {
      margin-bottom: 10px;
    }

    section {
      padding: 40px 0;
      border-bottom: 1px solid #333;
    }

    h3 {
      margin-bottom: 20px;
      text-align: center;
      color: #0ff;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #888;
    }

    .contact {
      text-align: center;
      padding: 40px 20px;
      background: #111;
      border-top: 2px solid #222;
    }

    .contact h3 {
      color: #0ff;
      margin-bottom: 15px;
    }

    .contact p {
      margin-bottom: 10px;
    }

    .contact a {
      color: #0ff;
      text-decoration: none;
    }

    .contact a:hover {
      text-decoration: underline;
    }

    #toTopBtn {
      position: fixed;
      bottom: 30px;
      right: 30px;
      background-color: #0ff;
      color: #000;
      padding: 12px 16px;
      border: none;
      border-radius: 8px;
      cursor: pointer;
      font-weight: bold;
      display: none;
      box-shadow: 0 0 12px rgba(0,255,255,0.6);
      z-index: 1000;
    }

    #toTopBtn:hover {
      background-color: #00cccc;
    }
  </style>
</head>
<body>

  <header>
    <div class="container">
      <h1>Firman Septian | DEV SC BUG COSMIC CRASHER🦠</h1>
      <nav>
        <a class="active" href="#">Beranda</a>
        <a href="#project1">Project 1</a>
        <a href="#project2">Project 2</a>
        <a href="#contact">Kontak</a>
      </nav>
    </div>
  </header>

  <section class="container">
    <h3>🛸 Selamat datang di Web Sc Cosmic Crasher</h3>
    <p>Ini adalah website resmi dari Developer SC Bug: <strong>Firman Septian</strong>.</p>
    <p>Jelajahi berbagai proyek keren yang dibuat untuk menjelajahi celah, menciptakan tool, dan menembus batas-batas sistem!</p>
  </section>

  <section id="project1" class="container">
    <h3>🚀 Project 1</h3>
    <div class="project-list">
      <div class="project-card"><h4>💥 WA Auto-Bug</h4><p>Script crash otomatis WhatsApp via payload khusus.</p></div>
      <div class="project-card"><h4>🔐 Xploit Grabber</h4><p>Ambil informasi device lewat link trap khusus.</p></div>
      <div class="project-card"><h4>⚙️ Bot Group Kicker</h4><p>Auto-kick semua member grup dengan delay minim.</p></div>
      <div class="project-card"><h4>🌐 DNS Flooder</h4><p>Melumpuhkan server DNS target dalam hitungan detik.</p></div>
      <div class="project-card"><h4>🌀 Device Freezer</h4><p>Crash script yang membuat perangkat freeze saat membuka file.</p></div>
      <div class="project-card"><h4>💡 Spam Notifier</h4><p>Spam notif dengan suara alarm hingga crash device.</p></div>
      <div class="project-card"><h4>📲 Injector Spammer</h4><p>Inject pesan masif ke sistem aplikasi tertentu.</p></div>
      <div class="project-card"><h4>🧬 SC Anti-Trace</h4><p>Menghapus jejak payload secara otomatis.</p></div>
    </div>
  </section>

  <section id="project2" class="container">
    <h3>🛰️ Project 2</h3>
    <div class="project-list">
      <div class="project-card"><h4>📊 Log Analyzer</h4><p>Analisa log crash secara real-time dari target.</p></div>
      <div class="project-card"><h4>🧠 AI Auto-Bomber</h4><p>Menggunakan AI untuk mengatur interval spam dengan randomisasi.</p></div>
      <div class="project-card"><h4>💣 Payload Custom Builder</h4><p>Generate payload crash dengan UI builder visual.</p></div>
      <div class="project-card"><h4>🛰️ Remote Control Bot</h4><p>Kontrol perangkat target dari dashboard pusat.</p></div>
      <div class="project-card"><h4>🔊 Audio Distorter</h4><p>Memutar suara aneh berulang yang tidak bisa dihentikan.</p></div>
      <div class="project-card"><h4>📦 Zip Bomb Creator</h4><p>Membuat file zip kecil tapi isinya ratusan GB.</p></div>
      <div class="project-card"><h4>🧾 Chat Bomber</h4><p>Mengirim ribuan pesan ke grup hingga crash.</p></div>
      <div class="project-card"><h4>🎭 Fake Update Prompt</h4><p>Meniru sistem update untuk menjebak korban.</p></div>
    </div>
  </section>

  <section id="contact" class="contact">
    <h3>📞 Kontak Bisnis</h3>
    <p>Email: <a href="mailto:birum5159@gmail.com">birum5159@gmail.com</a></p>
    <p>Telegram: <a href="https://t.me/themanzzy" target="_blank">@themanzzy</a></p>
    <p>Instagram: <a href="https://instagram.com/firmann.stpn" target="_blank">@firmann.sptn</a></p>
  </section>

  <footer>
    &copy; 2025 Firman Septian | Cosmic Crasher Developer
  </footer>

  <button id="toTopBtn" onclick="scrollToTop()">⬆ Ke Atas</button>

  <script>
    const toTopBtn = document.getElementById("toTopBtn");

    window.onscroll = function() {
      if (document.body.scrollTop > 300 || document.documentElement.scrollTop > 300) {
        toTopBtn.style.display = "block";
      } else {
        toTopBtn.style.display = "none";
      }
    };

    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  </script>
</body>
</html>
