# zzzz
zzzz
<!doctype html>
<html lang="id" class="h-full scroll-smooth">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Undangan Pernikahan Islami</title>
<script src="https://cdn.tailwindcss.com"></script>
<link href="https://fonts.googleapis.com/css2?family=Marcellus&family=Manrope:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
body {
  font-family: 'Manrope', sans-serif;
  background-color: #f9faf9;
  color: #2f3e35;
}
.font-arabic {
  font-family: 'Marcellus', serif;
  letter-spacing: 1px;
}
.bg-pattern {
  background-image: radial-gradient(circle at 20% 20%, rgba(46, 125, 90, 0.08) 0%, transparent 25%), radial-gradient(circle at 80% 80%, rgba(46, 125, 90, 0.08) 0%, transparent 25%);
  background-color: #fdfdfb;
}
.gold {
  color: #c9a646;
}
.btn-primary {
  background-color: #2e7d5a;
  color: #fff;
  border-radius: 9999px;
  padding: 12px 28px;
  font-weight: 600;
  transition: all .3s ease;
}
.btn-primary:hover {
  background-color: #256b4d;
}
.fade-in {
  opacity: 0;
  transform: translateY(20px);
  animation: fadeIn 1s ease forwards;
}
@keyframes fadeIn {
  to { opacity: 1; transform: translateY(0); }
}
.section {
  padding: 80px 20px;
}
.card {
  background: rgba(255,255,255,0.85);
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(0,0,0,0.05);
  padding: 32px;
}
</style>
</head>
<body class="bg-pattern">

<!-- Cover -->
<section id="cover" class="h-screen flex flex-col justify-center items-center text-center relative">
  <div class="absolute inset-0 bg-gradient-to-b from-emerald-900/40 to-emerald-700/20"></div>
  <div class="relative z-10 fade-in">
    <h2 class="text-2xl text-white mb-2">بِسْمِ اللّٰهِ الرَّحْمٰنِ الرَّحِيْمِ</h2>
    <h1 class="text-4xl md:text-5xl font-arabic text-white mb-4">Assalamu’alaikum Warahmatullahi Wabarakatuh</h1>
    <p class="text-white text-lg mb-6">Undangan Pernikahan</p>
    <h2 class="text-3xl md:text-4xl text-gold font-semibold mb-2">Aisyah & Ahmad</h2>
    <button onclick="openInvitation()" class="btn-primary mt-6">Buka Undangan</button>
  </div>
</section>

<!-- Musik -->
<audio id="bg-music" loop>
  <source src="nasyid.mp3" type="audio/mpeg">
</audio>
<button id="music-toggle" class="fixed top-4 right-4 bg-emerald-700 text-white p-3 rounded-full shadow-lg z-50">
  🔊
</button>

<!-- Ayat -->
<section id="ayat" class="section text-center fade-in">
  <div class="max-w-2xl mx-auto">
    <p class="text-xl italic mb-4">“Dan di antara tanda-tanda (kebesaran)-Nya ialah Dia menciptakan pasangan-pasangan untukmu dari jenismu sendiri, agar kamu cenderung dan merasa tenteram kepadanya...”</p>
    <p class="font-semibold gold">— QS. Ar-Rum: 21 —</p>
  </div>
</section>

<!-- Profil -->
<section id="profil" class="section bg-white fade-in">
  <div class="max-w-5xl mx-auto grid md:grid-cols-2 gap-10 items-center">
    <div class="text-center">
      <img src="aisyah.jpg" alt="Aisyah" class="w-48 h-48 object-cover rounded-full mx-auto mb-4 border-4 border-emerald-600">
      <h3 class="text-2xl font-semibold">Aisyah binti Abdullah</h3>
      <p class="text-sm text-gray-600">Putri dari Bapak Abdullah & Ibu Fatimah</p>
    </div>
    <div class="text-center">
      <img src="ahmad.jpg" alt="Ahmad" class="w-48 h-48 object-cover rounded-full mx-auto mb-4 border-4 border-emerald-600">
      <h3 class="text-2xl font-semibold">Ahmad bin Yusuf</h3>
      <p class="text-sm text-gray-600">Putra dari Bapak Yusuf & Ibu Amina</p>
    </div>
  </div>
</section>

<!-- Detail Acara -->
<section id="acara" class="section fade-in">
  <div class="max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Detail Acara</h2>
    <div class="card mb-6">
      <h3 class="text-2xl font-semibold mb-2">Akad Nikah</h3>
      <p>Sabtu, 10 Mei 2026 | 09.00 WIB</p>
      <p>Masjid Al-Falah, Jakarta</p>
    </div>
    <div class="card">
      <h3 class="text-2xl font-semibold mb-2">Resepsi</h3>
      <p>Sabtu, 10 Mei 2026 | 11.00 WIB - Selesai</p>
      <p>Gedung Serbaguna Al-Falah, Jakarta</p>
    </div>
  </div>
</section>

<!-- Countdown -->
<section id="countdown" class="section text-center fade-in">
  <h2 class="text-3xl font-arabic mb-4 gold">Menuju Hari Bahagia</h2>
  <div id="timer" class="text-2xl font-semibold"></div>
</section>

<!-- Lokasi -->
<section id="lokasi" class="section bg-white fade-in">
  <div class="max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Lokasi Acara</h2>
    <iframe class="w-full h-80 rounded-lg shadow" src="https://www.google.com/maps/embed?pb=!1m18..." allowfullscreen></iframe>
  </div>
</section>

<!-- Love Story -->
<section id="story" class="section fade-in">
  <div class="max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Kisah Ta’aruf</h2>
    <p class="text-lg leading-relaxed">Berawal dari pertemuan dalam majelis ilmu, Allah mempertemukan dua insan yang sama-sama berusaha menjaga diri. Dengan izin-Nya, langkah kecil menuju pernikahan ini menjadi awal perjalanan ibadah bersama.</p>
  </div>
</section>

<!-- Galeri -->
<section id="galeri" class="section bg-white fade-in">
  <div class="max-w-5xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Galeri</h2>
    <div class="grid grid-cols-2 md:grid-cols-3 gap-4">
      <img src="foto1.jpg" class="rounded-lg shadow">
      <img src="foto2.jpg" class="rounded-lg shadow">
      <img src="foto3.jpg" class="rounded-lg shadow">
    </div>
  </div>
</section>

<!-- RSVP -->
<section id="rsvp" class="section fade-in">
  <div class="max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Konfirmasi Kehadiran</h2>
    <form class="space-y-4">
      <input type="text" placeholder="Nama Lengkap" class="w-full border rounded-lg p-3">
      <select class="w-full border rounded-lg p-3">
        <option>Hadir</option>
        <option>Tidak Hadir</option>
      </select>
      <textarea placeholder="Ucapan atau Doa" class="w-full border rounded-lg p-3"></textarea>
      <button type="submit" class="btn-primary">Kirim</button>
    </form>
  </div>
</section>

<!-- Hadiah -->
<section id="hadiah" class="section bg-white fade-in">
  <div class="max-w-3xl mx-auto text-center">
    <h2 class="text-3xl font-arabic mb-6 gold">Hadiah Pernikahan</h2>
    <p class="mb-4">Bagi yang ingin berbagi kebahagiaan, dapat mengirimkan hadiah melalui:</p>
    <div class="card">
      <p><strong>Bank Syariah Indonesia</strong></p>
      <p>No. Rekening: 1234567890</p>
      <p>a.n. Ahmad Yusuf</p>
    </div>
  </div>
</section>

<!-- Penutup -->
<section id="penutup" class="section text-center fade-in">
  <p class="text-lg mb-4">Terima kasih atas doa dan kehadiran yang diberikan.</p>
  <p class="font-semibold gold">Wassalamu’alaikum Warahmatullahi Wabarakatuh</p>
</section>

<script>
function openInvitation() {
  document.getElementById('cover').style.display = 'none';
  document.getElementById('bg-music').play();
}
const music = document.getElementById('bg-music');
const toggle = document.getElementById('music-toggle');
toggle.addEventListener('click', () => {
  if (music.paused) { music.play(); toggle.textContent = '🔊'; }
  else { music.pause(); toggle.textContent = '🔇'; }
});
const weddingDate = new Date("May 10, 2026 09:00:00").getTime();
const timer = document.getElementById("timer");
setInterval(() => {
  const now = new Date().getTime();
  const distance = weddingDate - now;
  const days = Math.floor(distance / (1000 * 60 * 60 * 24));
  const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
  const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
  const seconds = Math.floor((distance % (1000 * 60)) / 1000);
  timer.innerHTML = `${days} Hari ${hours} Jam ${minutes} Menit ${seconds} Detik`;
}, 1000);
</script>

</body>
</html>
