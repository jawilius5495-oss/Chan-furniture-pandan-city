# Chan-furniture-pandan-city
<!DOCTYPE html>
<html lang="ms">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Chan Furniture Pandan City JB – Perabot Murah & Elektronik Berkualiti. Sofa Premium, Smart TV, Peti Sejuk, iPhone, Laptop dengan ansuran mudah tanpa deposit.">
  <meta name="keywords" content="Chan Furniture, Pandan City, Johor Bahru, perabot murah, sofa premium, smart TV, peti sejuk, iPhone, laptop, ansuran mudah, TikTok Chan Furniture">
  <meta name="author" content="Chan Furniture">
  <title>Chan Furniture Pandan City JB</title>
  <style>
    body { 
      font-family: Arial, sans-serif; 
      margin: 0; 
      padding: 0; 
      background: #FFFFFF; 
      color: #1C2526; 
      line-height: 1.6; 
    }
    header { 
      background: #1C2526; 
      color: #FFFFFF; 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: 0 2px 10px rgba(0,0,0,0.3); 
    }
    header h1 { margin: 0; font-size: 2rem; }
    nav { 
      background: #1C2526; 
      padding: 0.5rem; 
      border-bottom: 2px solid #C20114; 
    }
    nav a { 
      margin: 0 1rem; 
      color: #FFFFFF; 
      text-decoration: none; 
      font-weight: bold; 
      transition: color 0.3s; 
    }
    nav a:hover { color: #C20114; }
    .section { 
      padding: 2rem 1rem; 
      max-width: 1100px; 
      margin: auto; 
    }
    h2 { 
      text-align: center; 
      margin-bottom: 1.5rem; 
      color: #1C2526; 
      font-size: 1.8rem; 
    }
    /* Produk Grid */
    .produk-grid { 
      display: grid; 
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
      gap: 1.5rem; 
    }
    .produk-card { 
      background: #FFFFFF; 
      border-radius: 12px; 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
      transition: transform 0.3s, box-shadow 0.3s; 
    }
    .produk-card:hover { 
      transform: translateY(-8px); 
      box-shadow: 0 6px 20px rgba(0,0,0,0.15); 
    }
    .produk-card img { 
      width: 100%; 
      height: 200px; 
      object-fit: cover; 
      border-radius: 8px; 
      margin-bottom: 1rem; 
    }
    .produk-card p { font-weight: bold; color: #1C2526; margin: 0; }
    .produk-card small { color: #666; font-size: 0.9rem; }
    /* Testimoni */
    .testimoni-slider { 
      display: flex; 
      overflow: hidden; 
      gap: 1rem; 
      padding: 1rem 0; 
      position: relative; 
      width: 100%; 
      box-sizing: border-box; 
    }
    .testimoni-card { 
      flex: 0 0 300px; 
      background: #FFFFFF; 
      border-radius: 12px; 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
      transition: transform 0.3s; 
    }
    .testimoni-card:hover { transform: scale(1.02); }
    .avatar-img { 
      width: 60px; 
      height: 60px; 
      border-radius: 50%; 
      overflow: hidden; 
      margin: 0 auto 1rem; 
      box-shadow: 0 2px 6px rgba(0,0,0,0.1); 
    }
    .avatar-img img { width: 100%; height: 100%; object-fit: cover; }
    .rating { color: #C20114; font-size: 1.2rem; margin-top: 0.5rem; }
    /* Hubungi */
    .contact-info { display: grid; gap: 1rem; margin-bottom: 1rem; }
    .contact-info p { margin: 0; font-size: 1.1rem; }
    .contact-info a { color: #C20114; font-weight: bold; text-decoration: none; }
    .contact-info a:hover { text-decoration: underline; }
    .maps-container { 
      margin-top: 1rem; 
      border-radius: 10px; 
      overflow: hidden; 
      box-shadow: 0 4px 15px rgba(0,0,0,0.1); 
    }
    .social-icons { 
      display: flex; 
      justify-content: center; 
      gap: 1rem; 
      margin-top: 1rem; 
    }
    .social-icons a { transition: transform 0.3s; }
    .social-icons a:hover { transform: scale(1.1); }
    .social-icons img { 
      width: 40px; 
      height: 40px; 
      border-radius: 50%; 
      box-shadow: 0 2px 6px rgba(0,0,0,0.1); 
    }
    /* WhatsApp Float */
    .whatsapp-float { 
      position: fixed; 
      bottom: 20px; 
      right: 20px; 
      background: #C20114; 
      color: #FFFFFF; 
      width: 60px; 
      height: 60px; 
      border-radius: 50%; 
      display: flex; 
      align-items: center; 
      justify-content: center; 
      text-decoration: none; 
      font-size: 2rem; 
      box-shadow: 0 4px 12px rgba(0,0,0,0.25); 
      z-index: 1000; 
      transition: transform 0.3s, background 0.3s; 
    }
    .whatsapp-float:hover { 
      transform: scale(1.1); 
      background: #F02D3A; 
    }
    /* Footer */
    footer { 
      background: #1C2526; 
      color: #FFFFFF; 
      text-align: center; 
      padding: 1.5rem; 
      margin-top: 2rem; 
    }
    footer a { color: #FFFFFF; margin: 0 0.5rem; text-decoration: none; }
    footer a:hover { color: #C20114; }
    /* Responsif */
    @media (max-width: 768px) {
      header h1 { font-size: 1.5rem; }
      nav { padding: 0.5rem; }
      nav a { display: block; margin: 0.5rem 0; }
      .produk-grid { grid-template-columns: 1fr; }
      .testimoni-card { flex: 0 0 80%; }
      .testimoni-slider { overflow-x: auto; scroll-snap-type: x mandatory; }
      .social-icons { gap: 0.5rem; }
      .social-icons img { width: 35px; height: 35px; }
      .whatsapp-float { width: 50px; height: 50px; font-size: 1.5rem; }
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
        <img src="images/sofa-premium.jpg" alt="Sofa Premium Chan Furniture Pandan City JB" loading="lazy">
        <p>Sofa Premium</p>
        <small>Harga bermula RM999, ansuran mudah!</small>
      </div>
      <div class="produk-card">
        <img src="images/smart-tv-samsung.jpg" alt="Smart TV Samsung Chan Furniture Pandan City JB" loading="lazy">
        <p>Smart TV Samsung</p>
        <small>4K UHD, sesuai untuk hiburan keluarga!</small>
      </div>
      <div class="produk-card">
        <img src="images/peti-sejuk-panasonic.jpg" alt="Peti Sejuk Panasonic Chan Furniture Pandan City JB" loading="lazy">
        <p>Peti Sejuk Panasonic</p>
        <small>Hemat tenaga, kapasiti besar!</small>
      </div>
      <div class="produk-card">
        <img src="images/iphone-13.jpg" alt="iPhone 13 Chan Furniture Pandan City JB" loading="lazy">
        <p>iPhone 13</p>
        <small>Kamera canggih, prestasi pantas!</small>
      </div>
      <div class="produk-card">
        <img src="images/laptop-acer.jpg" alt="Laptop Acer Chan Furniture Pandan City JB" loading="lazy">
        <p>Laptop Acer</p>
        <small>Untuk kerja dan hiburan, ansuran mudah!</small>
      </div>
    </div>
  </section>

  <!-- Testimoni Section -->
  <section class="section" id="testimoni">
    <h2>Apa Kata Pelanggan Kami</h2>
    <div class="testimoni-slider" id="testimoniSlider">
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-aisyah.jpg" alt="Avatar Aisyah" loading="lazy">
        </div>
        <p>“Perabot dan elektronik berkualiti, harga berpatutan. Staf mesra & layanan terbaik!”</p>
        <strong>- Aisyah, JB</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-farid.jpg" alt="Avatar Farid" loading="lazy">
        </div>
        <p>“Beli TV dan iPhone, penghantaran cepat. Senang urusan ansuran bulanan!”</p>
        <strong>- Farid, Skudai</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-lim-wei.jpg" alt="Avatar Lim Wei" loading="lazy">
        </div>
        <p>“Banyak pilihan elektronik moden. Akan datang lagi untuk peti sejuk!”</p>
        <strong>- Lim Wei, Tebrau</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
      <div class="testimoni-card">
        <div class="avatar-img">
          <img src="images/avatar-siti.jpg" alt="Avatar Siti" loading="lazy">
        </div>
        <p>“Ansuran tanpa deposit sungguh memudahkan. Terima kasih Chan Furniture!”</p>
        <strong>- Siti, Pasir Gudang</strong>
        <div class="rating">⭐⭐⭐⭐⭐</div>
      </div>
    </div>
  </section>

  <!-- Hubungi Section -->
  <section class="section" id="hubungi">
    <h2>Hubungi Kami</h2>
    <div class="contact-info">
      <p>📞 Telefon: <a href="tel:0162625886">016-2625886</a></p>
      <p>📍 Alamat: No. 19, Jalan Pandan City Ria 5, Pusat Perdagangan Pandan, 81100 Johor Bahru</p>
      <p>🕒 Waktu Operasi:<br>
         Isnin - Sabtu: 12PM - 9PM<br>
         Ahad / Cuti Umum: 12PM - 8PM</p>
    </div>
    <!-- Google Maps Embed -->
    <div class="maps-container">
      <iframe 
        src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.771567123456!2d103.760123!3d1.318456!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMcKwMTknMDYuNCJOIDEwM8KwNDUnMzYuNCJF!5e0!3m2!1sms!2smy!4v1724069600000!5m2!1sms!2smy" 
        width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy" title="Peta Lokasi Chan Furniture Pandan City JB">
      </iframe>
    </div>
    <!-- Ikon Sosial -->
    <div class="social-icons">
      <a href="https://www.tiktok.com/@chanfurniturepandancityjb" target="_blank" title="TikTok Chan Furniture Pandan City JB">
        <img src="images/tiktok-icon.png" alt="TikTok Chan Furniture Pandan City JB" loading="lazy">
      </a>
      <a href="https://wa.me/60162625886" target="_blank" title="WhatsApp Chan Furniture">
        <img src="images/whatsapp-icon.png" alt="WhatsApp Chan Furniture Pandan City JB" loading="lazy">
      </a>
      <a href="https://www.facebook.com/cfpandancty/" target="_blank" title="Facebook Chan Furniture">
        <img src="images/facebook-icon.png" alt="Facebook Chan Furniture Pandan City JB" loading="lazy">
      </a>
    </div>
  </section>

  <!-- WhatsApp Float Button -->
  <a href="https://wa.me/60162625886?text=Hai!%20Saya%20nak%20tahu%20promosi%20terkini%20Chan%20Furniture%20Pandan%20City%20JB." class="whatsapp-float" target="_blank" aria-label="Hubungi WhatsApp">
    💬
  </a>

  <footer>
    <p>&copy; 2025 Chan Furniture Pandan City JB. Murah & Bergaya, Pilihan Bijak Rakyat Malaysia.</p>
    <p>
      <a href="https://www.chanfurniture.com.my/">Laman Rasmi</a> | 
      <a href="https://www.facebook.com/cfpandancty/">Facebook</a> | 
      <a href="https://www.tiktok.com/@chanfurniturepandancityjb">TikTok</a>
    </p>
  </footer>

  <script>
    // Auto-scroll testimoni
    let currentSlide = 0;
    const slider = document.getElementById('testimoniSlider');
    const cards = slider.children;
    const totalCards = cards.length;
    let slideInterval;

    function startSlider() {
      slideInterval = setInterval(() => {
        currentSlide = (currentSlide + 1) % totalCards;
        slider.style.transform = `translateX(-${currentSlide * (300 + 16)}px)`; // 300px card + 16px gap
      }, 4000);
    }

    // Hentikan scroll semasa hover
    slider.addEventListener('mouseenter', () => clearInterval(slideInterval));
    slider.addEventListener('mouseleave', () => startSlider());
    
    // Mulakan slider
    startSlider();
  </script>
</body>
</html>
