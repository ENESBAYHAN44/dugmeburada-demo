# dugmeburada-demo
├── index.html
└── styles.css
<!DOCTYPE html>
<html lang="tr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>DüğmeBurada.com | Düğmenin Adresi</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <header><h1>DüğmeBurada.com</h1><p>Seçkin Düğme — Yüzlerce çeşit, şimdi sipariş ver!</p></header>
  <nav><a href="#urunler">Ürünler</a> | <a href="#iletisim">İletişim</a></nav>
  <section class="hero"><h2>Kaliteli ve Şık Düğmeler</h2><p>Plastik, metal, ahşap ve özel tasarım düğmeler burada!</p></section>
  <section id="urunler" class="urunler">
    <h2>Ürünlerimiz</h2>
    <div class="urun-listesi">
      <div class="urun">
        <img src="https://via.placeholder.com/200" alt="Metal Düğme">
        <h3>Metal Düğme</h3><p>Paslanmaz, klasik model</p>
        <a href="https://wa.me/905334942454?text=Metal%20Düğme%20siparişi%20veriyorum" target="_blank">WhatsApp Sipariş</a>
      </div>
      <div class="urun">
        <img src="https://via.placeholder.com/200" alt="Ahşap Düğme">
        <h3>Ahşap Düğme</h3><p>Doğal görünümlü, el yapımı</p>
        <a href="https://wa.me/905334942454?text=Ahşap%20Düğme%20siparişi%20veriyorum" target="_blank">WhatsApp Sipariş</a>
      </div>
      <div class="urun">
        <img src="https://via.placeholder.com/200" alt="Plastik Düğme">
        <h3>Plastik Düğme</h3><p>Renkli, ekonomik seçenek</p>
        <a href="https://wa.me/905334942454?text=Plastik%20Düğme%20siparişi%20veriyorum" target="_blank">WhatsApp Sipariş</a>
      </div>
    </div>
  </section>
  <section id="iletisim" class="iletisim">
    <h2>İletişim</h2>
    <p><strong>Adres:</strong> İstanbul, Fatih – Havuzlu Mescit Sokak</p>
    <p><strong>Telefon:</strong> <a href="tel:+905334942454">0533 494 2454</a></p>
    <p><strong>WhatsApp:</strong> <a href="https://wa.me/905334942454" target="_blank">Mesaj Gönder</a></p>
  </section>
  <footer><p>&copy; 2025 DüğmeBurada.com</p></footer>
</body>
</html>
body { margin:0; font-family:Arial,sans-serif; line-height:1.6; }
header, nav, .hero, section, footer { padding:20px; text-align:center; }
header { background:#222; color:#fff; }
nav a { margin:0 10px; color:#444; text-decoration:none; font-weight:bold; }
.hero { background:#eee; }
.urun-listesi { display:flex; flex-wrap:wrap; justify-content:center; gap:20px; }
.urun { background:#f9f9f9; padding:15px; border-radius:8px; width:200px; }
.urun img { width:100%; border-radius:4px; }
.urun a { display:inline-block; margin-top:10px; background:#25D366;color:#fff;padding:8px 12px;border-radius:4px;text-decoration:none;}
.iletisim p, footer { margin:10px 0; }
footer { background:#222; color:#fff; }
@media(max-width:600px) {.urun-listesi { flex-direction:column; align-items:center; }}
