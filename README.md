
<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>HANZZTRIS ALLGAME</title>
<style>
*{box-sizing:border-box}
:root{--bg:#090714;--card:#151128;--purple:#8b5cf6;--pink:#d946ef;--text:#f8f5ff;--muted:#b8b0d0}
body{margin:0;background:radial-gradient(ellipse at top,#291044,var(--bg) 55%);color:var(--text);font-family:Arial,sans-serif}
a{text-decoration:none;color:inherit}
header{position:sticky;top:0;background:#0c0919ed;backdrop-filter:blur(12px);border-bottom:1px solid #352451;padding:16px 5%;display:flex;align-items:center;justify-content:space-between;z-index:2}
.logo{font-weight:900;font-size:19px;letter-spacing:1px}
.logo span{color:#bd83ff}
nav{display:flex;gap:20px;color:var(--muted);font-size:14px}
.btn{display:inline-block;background:linear-gradient(120deg,var(--purple),var(--pink));color:white;padding:12px 17px;border-radius:11px;font-weight:bold;border:0;cursor:pointer}
.btn2{background:#211735;border:1px solid #503875}
.wrap{width:min(1100px,90%);margin:auto}
.hero{padding:65px 0;display:grid;grid-template-columns:1fr 1fr;gap:30px;align-items:center}
.tag{color:#d9baff;background:#24153c;border:1px solid #644098;border-radius:30px;padding:8px 12px;font-size:12px}
h1{font-size:clamp(38px,5vw,60px);line-height:1.08;margin:22px 0}
.gradient{background:linear-gradient(90deg,#c4a5ff,#f0abff);color:transparent;background-clip:text}
p{color:var(--muted);line-height:1.7}
.art{min-height:300px;border:1px solid #56358b;border-radius:25px;background:radial-gradient(circle,#6929b577,transparent 55%),linear-gradient(135deg,#24123f,#0e0b1b);display:grid;place-items:center;text-align:center;box-shadow:0 0 55px #6d28d922}
.art strong{display:block;font-size:clamp(30px,4vw,45px);letter-spacing:3px}
.art .symbol{font-size:90px;color:#c4a5ff;text-shadow:0 0 30px #a855f7}
section{padding:30px 0 45px}
h2{font-size:28px;margin-bottom:8px}
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:17px}
.card{background:linear-gradient(145deg,#1b1530,#100d1d);border:1px solid #392854;border-radius:18px;padding:22px}
.icon{font-size:32px;color:#c4a5ff}
.card h3{margin:10px 0}
.price{font-size:18px;color:#f9d68a;font-weight:bold}
.small{font-size:12px;color:#a9a0c5}
.steps{counter-reset:step}
.step{padding:12px 0;border-bottom:1px solid #302341;color:#e4dcf5}
.step:before{counter-increment:step;content:counter(step);display:inline-grid;place-items:center;background:#492779;color:white;border-radius:8px;width:28px;height:28px;margin-right:10px;font-weight:bold}
.notice{padding:17px;border:1px dashed #7553a4;background:#1b1430;border-radius:14px}
footer{border-top:1px solid #352451;padding:25px 5%;text-align:center;color:var(--muted)}
@media(max-width:700px){nav{display:none}.hero{grid-template-columns:1fr;padding:40px 0}.art{min-height:220px}.grid{grid-template-columns:1fr}header{padding:14px 5%}}
</style>
</head>
<body>
<header>
  <a class="logo" href="#">H <span>HANZZTRIS</span></a>
  <nav><a href="#home">Beranda</a><a href="#akun">Akun FF</a><a href="#order">Cara Order</a></nav>
  <a class="btn" href="https://wa.me/628135650762">Chat Admin</a>
</header>

<main class="wrap">
<section class="hero" id="home">
  <div>
    <span class="tag">✦ TOKO AKUN FREE FIRE</span>
    <h1>Main lebih seru.<br><span class="gradient">Pilih akun impianmu.</span></h1>
    <p>Selamat datang di HanzzTris Allgame! Cari akun Free Fire biasa dan tanyakan stok serta harga terbaru langsung kepada admin.</p>
    <p><a class="btn" href="#akun">Lihat Etalase ↗</a></p>
    <p>✓ Konfirmasi manual &nbsp; ✓ Admin WhatsApp</p>
  </div>
  <div class="art">
    <div><div class="symbol">✦</div><strong>FREE FIRE</strong><p>ACCOUNT MARKETPLACE</p></div>
  </div>
</section>

<section>
  <div class="grid">
    <div class="card"><div class="icon">◈</div><h3>Info transparan</h3><p>Konfirmasi harga dan detail akun sebelum membayar.</p></div>
    <div class="card"><div class="icon">⚡</div><h3>Order simpel</h3><p>Semua pertanyaan dan pemesanan melalui WhatsApp.</p></div>
    <div class="card"><div class="icon">✓</div><h3>Cek pembayaran</h3><p>Admin memeriksa saldo masuk secara manual.</p></div>
  </div>
</section>

<section id="akun">
  <h2><span class="gradient">Etalase Akun FF</span></h2>
  <p>Stok dan harga belum dicantumkan. Hubungi admin untuk daftar akun yang benar-benar tersedia.</p>
  <div class="grid">
    <article class="card">
      <div class="icon">✦</div><h3>Akun Free Fire</h3>
      <p>Detail skin, level, bundle, dan item ditanyakan ke admin.</p>
      <div class="price">Tanya harga</div><p class="small">Stok belum dikonfirmasi</p>
      <a class="btn" href="https://wa.me/628135650762?text=Halo%20Admin%2C%20saya%20mau%20tanya%20stok%20akun%20FF.">Tanya Stok ↗</a>
    </article>
    <article class="card">
      <div class="icon">♜</div><h3>Akun Free Fire</h3>
      <p>Minta foto dan rincian akun yang tersedia saat ini.</p>
      <div class="price">Tanya harga</div><p class="small">Stok belum dikonfirmasi</p>
      <a class="btn" href="https://wa.me/628135650762?text=Halo%20Admin%2C%20boleh%20lihat%20detail%20akun%20FF%3F">Lihat Detail ↗</a>
    </article>
    <article class="card">
      <div class="icon">♛</div><h3>Akun Free Fire</h3>
      <p>Pastikan akses dan metode serah terima sebelum transaksi.</p>
      <div class="price">Tanya harga</div><p class="small">Stok belum dikonfirmasi</p>
      <a class="btn" href="https://wa.me/628135650762?text=Halo%20Admin%2C%20saya%20tertarik%20akun%20FF.">Hubungi Admin ↗</a>
    </article>
  </div>
  <p class="small">Kartu di atas adalah tempat produk, bukan akun asli yang tersedia.</p>
</section>

<section id="order">
  <h2>Cara Order</h2>
  <p>Ikuti langkah berikut supaya transaksi lebih jelas.</p>
  <div class="card">
    <div class="step">Pilih akun atau tanyakan stok terbaru.</div>
    <div class="step">Konfirmasi harga dan detail melalui WhatsApp.</div>
    <div class="step">Minta QRIS resmi dari admin setelah kesepakatan.</div>
    <div class="step">Bayar sesuai nominal dan kirim bukti pembayaran.</div>
    <div class="step">Admin cek saldo masuk langsung, bukan hanya screenshot.</div>
    <div class="step">Setelah pembayaran terverifikasi, atur serah terima.</div>
  </div>
  <br>
  <div class="notice">
    <strong>💳 Pembayaran QRIS manual</strong>
    <p>QRIS belum dipasang karena gambar QRIS asli toko belum tersedia. Jangan gunakan QRIS palsu atau QRIS milik orang lain.</p>
    <a class="btn" href="https://wa.me/628135650762?text=Halo%20Admin%2C%20saya%20minta%20QRIS%20resmi%20untuk%20pesanan.">Minta QRIS ke Admin ↗</a>
  </div>
</section>
</main>

<footer>
  <strong>HANZZTRIS ALLGAME</strong>
  <p>Etalase akun Free Fire biasa · © <span id="year"></span></p>
  <a href="https://wa.me/628135650762">WhatsApp Admin ↗</a>
</footer>
<script>document.getElementById("year").textContent=new Date().getFullYear()</script>
</body>
</html>
