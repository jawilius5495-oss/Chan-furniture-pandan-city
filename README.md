# Chan-furniture-pandan-city
<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Chan Furniture Pandan City JB – Murah & Bergaya, Pilihan Bijak Rakyat Malaysia.">
  <meta name="keywords" content="Chan Furniture, Pandan City, Johor Bahru, perabot murah, sofa, katil, meja makan, rak TV, ansuran mudah">
  <meta name="author" content="Chan Furniture">
  <title>Chan Furniture Pandan City JB</title>
  <style>
    body { font-family: Arial, sans-serif; margin: 0; padding: 0; background: #fafafa; color: #333; }
    header { background: #004aad; color: #fff; padding: 1rem; text-align: center; }
    nav a { margin: 0 1rem; color: #fff; text-decoration: none; font-weight: bold; }
    nav a:hover { color: #ffcc00; }
    .section { padding: 2rem 1rem; max-width: 1100px; margin: auto; }
    h2 { text-align: center; margin-bottom: 1rem; }
    /* Produk Grid */
    .produk-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); gap: 1rem; }
    .produk-card { 
      background: #fff; 
      border-radius: 10px; 
      padding: 1rem; 
      text-align: center; 
      box-shadow: 0 3px 10px rgba(0,0,0,0.08); 
      transition: transform 0.3s; 
    }
    .produk-card:hover { transform: translateY(-5px); }
    .produk-card img { 
      width: 100%; 
      height: 200px; 
      object-fit: cover; 
      border-radius: 10px; 
      margin-bottom: 0.5rem; 
    }
    /* Testimoni */
    .testimoni-slider { 
      display: flex; 
      overflow-x: auto; 
      gap: 1rem; 
      scroll-snap-type: x mandatory; 
      padding: 1rem 0; 
      scrollbar-width: thin; 
    }
    .testimoni-card { 
      flex: 0 0 300px; 
      background: #fff; 
      border-radius: 10px; 
      padding: 1rem; 
      text-align: center; 
      scroll-snap-align: center; 
      box-shadow: 0 3px 10px rgba(0,0,0,0.08); 
    }
    .avatar-img { 
      width: 60px; 
      height: 60px; 
      border-radius: 50%; 
      overflow: hidden; 
      margin: 0 auto 1rem; 
      box-shadow: 0 2px 6px rgba(0,0,0,0.1); 
    }
    .avatar-img img { width: 100%; height: 100%; object-fit: cover; }
    .rating { color: #ffcc00; font-size: 1.2rem; margin-top: 0.5rem; }
    /* Footer */
    footer { background: #004aad; color: #fff; text-align: center; padding: 1rem; }
    footer a { color: #fff; margin: 0 0.5rem; }
    footer a:hover { color: #ffcc00; }
    /* Responsif */
    @media (max-width: 768px) {
      nav a { display: block; margin: 0.5rem 0; }
      .produk-grid { grid-template-columns: 1fr; }
      .testimoni-card { flex: 0 0 80%; }
    }
  </style>
</head>
<body>
  <header>
    <h1>Chan Furniture Pandan City JB</h1>
    <nav>
      <a href="#produk">Produk</a>
      <a href="#testimoni">Testimoni</a>
      <a href="#hubungi">Hubungi</a>
    </nav>
  </header>

  <!-- Produk Section -->
  <section class="section" id="produk">
    <h2>Produk Popular</h2>
    <div class="produk-grid">
      <div class="produk-card">
        <img src="images/sofa-jati-chan-pandan.jpg" alt="Sofa Jati Chan Furniture Pandan City JB" loading="lazy">
        <p>🛋️ Sofa Jati</p>
      </div>
      <div class="produk-card">
        <img src="images/katil-tilam-chan-pandan.jpg" alt="Katil & Tilam Chan Furniture Pandan City JB" loading="lazy">
        <p>🛏️ Katil & Tilam</p>
      </div>
      <div class="produk-card">
        <img src="images/meja-makan-chan-pandan.jpg" alt="Meja Makan Chan Furniture Pandan City JB" loading="lazy">
        <p>🪑 Meja Makan</p>
      </div>
      <div class="produk-card">
        <img src="images/rak-tv-chan-pandan.jpg" alt="Rak TV Chan Furniture Pandan City JB" loading="lazy">
        <p>📺 Rak TV</p>
      </div>
    </div>
  </section>

  <!-- Testimoni Section -->
  <section class="section" id="testimoni">
    <h2>Apa Kata Pelanggan Kami</h2>
    <div class="testimoni-slider">
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-aisyah.jpg" alt="Avatar Aisyah" loading="lazy">
        </div>
        <p>“Perabot sangat berkualiti, harga berpatutan. Staf mesra & layanan terbaik!”</p>
        <strong>- Aisyah, JB</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-farid.jpg" alt="Avatar Farid" loading="lazy">
        </div>
        <p>“Beli sofa & TV, penghantaran cepat. Senang urusan ansuran bulanan!”</p>
        <strong>- Farid, Skudai</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-lim-wei.jpg" alt="Avatar Lim Wei" loading="lazy">
        </div>
        <p>“Banyak pilihan perabot moden. Akan datang lagi untuk beli almari dapur.”</p>
        <strong>- Lim Wei, Tebrau</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
    </div>
  </section>

  <!-- Hubungi Section -->
  <section class="section" id="hubungi">
    <h2>Hubungi Kami</h2>
    <p>📞 Telefon: <a href="tel:0162625886">016-2625886</a></p>
    <p>📍 Alamat: Chan Furniture, Pandan City, Johor Bahru</p>
    <p>🕒 Waktu Operasi:<br>
       Isnin - Sabtu: 12PM - 9PM<br>
       Ahad / Cuti Umum: 12PM - 8PM</p>
    <!-- Google Maps Embed -->
    <div style="margin-top:1rem; border-radius:10px; overflow:hidden;">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d15930.648390728287!2d103.7401611!3d1.4947536!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da6d1426a8d4f3%3A0x92a503c3e223b1d5!2sChan%20Furniture%20Pandan%20City!5e0!3m2!1sen!2smy!4v1724069600000!5m2!1sen!2smy" 
        width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" title="Peta Chan Furniture Pandan City">
      </iframe>
    </div>
    <!-- Ikon Sosial -->
    <div style="margin-top: 1rem; display:flex; justify-content:center; gap:10px;">
      <a href="https://www.tiktok.com/@chanfurniture" target="_blank" title="TikTok Chan Furniture">
        <img src="images/tiktok-icon.png" alt="TikTok Chan Furniture" width="35" loading="lazy">
      </a>
      <a href="https://wa.me/60162625886" target="_blank" title="WhatsApp">
        <img src="images/whatsapp-icon.png" alt="WhatsApp Chan Furniture" width="35" loading="lazy">
      </a>
      <a href="https://www.facebook.com/chanfurniture" target="_blank" title="Facebook Chan Furniture">
        <img src="images/facebook-icon.png" alt="Facebook Chan Furniture" width="35" loading="lazy">
      </a>
    </div>
  </section>

  <footer>
    <p>&copy; 2025 Chan Furniture Pandan City JB. Murah & Bergaya, Pilihan Bijak Rakyat Malaysia.</p>
  </footer>
</body>
</html>
kedai-pandan-city-hero.jpg
sofa-mewah-chan-pandan.jpg
