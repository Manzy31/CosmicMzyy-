<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Firman Septian | Cosmic Crasher</title>
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
      animation: bgMove 60s linear infinite;
    }
    @keyframes bgMove {
      0% { background-position: 0 0; }
      100% { background-position: 1000px 1000px; }
    }
    a {
      text-decoration: none;
      color: #6C63FF;
      transition: 0.3s ease;
    }
    a:hover {
      color: #a89eff;
      text-decoration: underline;
    }
    .container {
      width: 90%;
      max-width: 960px;
      margin: auto;
      padding: 20px 0;
    }
    header {
      background-color: #111;
      border-bottom: 1px solid #333;
      padding: 30px 0 20px;
      text-align: center;
    }
    header h1 {
      font-family: 'Orbitron', sans-serif;
      color: #6C63FF;
      font-size: 2.5rem;
      position: relative;
      display: inline-block;
      padding-bottom: 10px;
    }
    header h1::after {
      content: "";
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 60%;
      height: 3px;
      background-color: #6C63FF;
      border-radius: 2px;
    }
    header nav {
      margin-top: 15px;
    }
    header nav a {
      margin: 0 15px;
      font-weight: bold;
      color: #aaa;
      font-size: 1rem;
    }
    header nav a.active,
    header nav a:hover {
      color: #fff;
    }
    .hero {
      text-align: center;
      padding: 100px 20px;
      background: radial-gradient(circle at center, #1c1c1c, #000);
    }
    .hero h2 {
      font-size: 2.7rem;
      color: #6C63FF;
      font-family: 'Orbitron', sans-serif;
    }
    .subtext {
      font-size: 1.2rem;
      color: #f14bf1;
      margin: 10px 0;
    }
    .hero .btn {
      margin-top: 25px;
      display: inline-block;
      background: #6C63FF;
      color: white;
      padding: 12px 28px;
      border-radius: 8px;
      font-weight: bold;
      letter-spacing: 0.5px;
      box-shadow: 0 0 10px rgba(108, 99, 255, 0.3);
    }
    .hero .btn:hover {
      background: #524bdf;
      transform: scale(1.05);
      box-shadow: 0 0 20px rgba(108, 99, 255, 0.6);
    }
    section {
      padding: 60px 0;
    }
    .projects {
      background: #111;
    }
    .project-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 25px;
      margin-top: 30px;
    }
    .project-card {
      background: #1a1a1a;
      border-left: 4px solid #6C63FF;
      padding: 25px;
      border-radius: 12px;
      box-shadow: 0 0 12px rgba(108, 99, 255, 0.15);
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .project-card:hover {
      transform: translateY(-5px);
      box-shadow: 0 0 18px rgba(108, 99, 255, 0.3);
    }
    .project-logo {
      font-size: 2rem;
      margin-bottom: 10px;
      text-align: center;
    }
    .contact {
      background: #1a1a1a;
      text-align: center;
      padding: 60px 20px;
    }
    .contact h2 {
      font-size: 2rem;
      color: #6C63FF;
      margin-bottom: 20px;
    }
    .contact p {
      font-size: 1.1rem;
      margin-bottom: 10px;
    }
    .contact a {
      color: #f14bf1;
    }
    footer {
      background: #111;
      text-align: center;
      padding: 25px;
      font-size: 0.9rem;
      color: #888;
      margin-top: 40px;
    }
    #toTopBtn {
      position: fixed;
      bottom: 25px;
      right: 25px;
      background: #6C63FF;
      color: white;
      border: none;
      border-radius: 50%;
      width: 45px;
      height: 45px;
      font-size: 20px;
      cursor: pointer;
      box-shadow: 0 0 10px rgba(108, 99, 255, 0.5);
      display: none;
      z-index: 1000;
    }
    #toTopBtn:hover {
      background: #524bdf;
    }
  </style>
</head>
<body>
  <header>
    <h1>Firman Septian</h1>
    <nav>
      <a href="#home" class="active">Beranda</a>
      <a href="#project-page-1">Project</a>
      <a href="#contact">Kontak</a>
    </nav>
  </header>

  <section class="hero" id="home">
    <h2>SCRIPT BUG WHATSAPP🦠</h2>
    <p class="subtext">🚀COSMIC CRASHER</p>
    <a href="#project-page-1" class="btn">Lihat Project</a>
  </section>

  <section id="project-page-1" class="projects">
    <div class="container">
      <h2>🧪 Project Script Bug WhatsApp</h2>
      <div class="project-list">
        <!-- Semua deskripsi di bawah ini tentang Script Bug WhatsApp -->
        <div class="project-card"><div class="project-logo">🚀</div><h3>Crash View Once</h3><p>Script untuk menyebabkan crash saat korban membuka media "lihat sekali".</p></div>
        <div class="project-card"><div class="project-logo">🛠️</div><h3>Forward Flooder</h3><p>Mengirim spam beruntun yang memicu stuck saat forward pesan di WhatsApp.</p></div>
        <div class="project-card"><div class="project-logo">💡</div><h3>Invisible Text</h3><p>Bug teks kosong yang memaksa korban reload aplikasi saat dibuka.</p></div>
        <div class="project-card"><div class="project-logo">🎯</div><h3>Tag Glitch</h3><p>Mention grup masif yang menyebabkan WhatsApp freeze saat loading notifikasi.</p></div>
        <div class="project-card"><div class="project-logo">🌌</div><h3>Emoji Overload</h3><p>Script spam emoji tak terbaca hingga membuat aplikasi menjadi lag parah.</p></div>
        <div class="project-card"><div class="project-logo">🧬</div><h3>Bio Bug</h3><p>Bug dengan bio profil panjang dan simbol rusak yang bisa crash saat profil dilihat.</p></div>
        <div class="project-card"><div class="project-logo">🤖</div><h3>Status Loop</h3><p>Status WhatsApp tak henti yang memaksa user stuck saat mencoba skip.</p></div>
        <div class="project-card"><div class="project-logo">🔐</div><h3>Anti Delete</h3><p>Script yang mencegah pesan dihapus dari pengirim, tetap terlihat meski dihapus.</p></div>
        <div class="project-card"><div class="project-logo">📡</div><h3>Auto Join Group</h3><p>Eksploitasi bug undangan grup agar korban masuk otomatis tanpa konfirmasi.</p></div>
        <div class="project-card"><div class="project-logo">🧠</div><h3>Freeze Chat</h3><p>Script khusus yang membuat seluruh isi chat tak bisa digulir.</p></div>
        <div class="project-card"><div class="project-logo">🌠</div><h3>Hyperlink Spam</h3><p>Bug yang membuat link tak terbuka dan menumpuk jadi freeze browser WhatsApp.</p></div>
        <div class="project-card"><div class="project-logo">📱</div><h3>Contact Bomb</h3><p>Menambahkan ratusan kontak palsu sekaligus hingga aplikasi error sinkronisasi.</p></div>
        <div class="project-card"><div class="project-logo">💻</div><h3>Web Stuck</h3><p>Script untuk membuat WhatsApp Web stuck di layar QR tanpa bisa login ulang.</p></div>
        <div class="project-card"><div class="project-logo">🔧</div><h3>Message Injector</h3><p>Script yang menambahkan pesan palsu dalam riwayat chat tanpa notifikasi.</p></div>
        <div class="project-card"><div class="project-logo">🌀</div><h3>GIF Bomb</h3><p>Spam GIF rusak yang menyebabkan aplikasi crash saat dibuka.</p></div>
        <div class="project-card"><div class="project-logo">🎮</div><h3>Emoji Stack</h3><p>Stack emoji besar dalam satu pesan yang memperlambat perangkat low-end.</p></div>
        <div class="project-card"><div class="project-logo">🛰️</div><h3>Ping Lagger</h3><p>Bug pengiriman ping massal untuk membuat delay notifikasi ekstrem.</p></div>
        <div class="project-card"><div class="project-logo">📊</div><h3>Storage Killer</h3><p>Script file besar disguised untuk menguras storage saat diunduh otomatis.</p></div>
        <div class="project-card"><div class="project-logo">🕹️</div><h3>Voice Loop</h3><p>Pesan suara yang terus berulang dan membuat pengguna stuck play/stop.</p></div>
        <div class="project-card"><div class="project-logo">💾</div><h3>Backup Crash</h3><p>Script memicu crash saat WhatsApp melakukan backup otomatis.</p></div>
        <div class="project-card"><div class="project-logo">🧠</div><h3>Link Preview Bug</h3><p>Link dengan metadata rusak yang membuat preview crash saat dibuka.</p></div>
        <div class="project-card"><div class="project-logo">🔍</div><h3>Search Glitch</h3><p>Bug pencarian pesan yang menyebabkan freeze saat kata tertentu diketik.</p></div>
        <div class="project-card"><div class="project-logo">📦</div><h3>File Bomb</h3><p>Spam kirim file corrupt untuk menumpuk proses unduhan background.</p></div>
        <div class="project-card"><div class="project-logo">⚙️</div><h3>Settings Freeze</h3><p>Script yang membuat pengaturan akun crash saat dibuka.</p></div>
        <div class="project-card"><div class="project-logo">🌐</div><h3>Theme Loop</h3><p>Bug tema gelap terang berubah terus menerus tanpa kontrol user.</p></div>
        <div class="project-card"><div class="project-logo">🛡️</div><h3>Group Kick Loop</h3><p>Bot script yang membuat korban terus di-kick dan diundang ulang otomatis.</p></div>
        <div class="project-card"><div class="project-logo">🎨</div><h3>Sticker Flood</h3><p>Flood sticker transparan yang membuat UI WhatsApp tak responsif.</p></div>
        <div class="project-card"><div class="project-logo">⏳</div><h3>Timer Loop</h3><p>Pesan terjadwal terus menerus yang memperlambat proses sinkronisasi.</p></div>
      </div>
    </div>
  </section>

  <section class="contact" id="contact">
    <div class="container">
      <h2>Kontak Bisnis</h2>
      <p>Jika Anda Ingin Bergabung Dengan Group Bug Whatsapp Atau Buy Script Gacor Bisa Contact Di Bawah ini!!</p>
      <p>Email: <a href="mailto:birum5159@gmail.com">birum5159@gmail.com</a></p>
      <p>WhatsApp: <a href="https://wa.me/6285711380151" target="_blank">+62 857-1138-0151</a></p>
      <p>Instagram: <a href="https://instagram.com/firmann.sptn" target="_blank">@firmann.sptn</a></p>
    </div>
  </section>

  <footer>
    &copy; 2025 Firman Septian — DEV SC BUG COSMIC CRASHER🦠
  </footer>

  <button id="toTopBtn" onclick="scrollToTop()">↑</button>

  <script>
    const btn = document.getElementById("toTopBtn");
    window.onscroll = function () {
      if (document.body.scrollTop > 400 || document.documentElement.scrollTop > 400) {
        btn.style.display = "block";
      } else {
        btn.style.display = "none";
      }
    };
    function scrollToTop() {
      window.scrollTo({ top: 0, behavior: 'smooth' });
    }
  </script>
</body>
</html>
