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
    /* Variables for consistent theming */
    :root {
      --primary-color: #1C2526;
      --accent-color: #C20114;
      --light-accent: #F02D3A;
      --background: #FFFFFF;
      --text-color: #1C2526;
      --light-text: #666;
      --card-shadow: 0 4px 15px rgba(0,0,0,0.1);
      --card-shadow-hover: 0 6px 20px rgba(0,0,0,0.15);
    }
    
    body { 
      font-family: Arial, sans-serif; 
      margin: 0; 
      padding: 0; 
      background: var(--background); 
      color: var(--text-color); 
      line-height: 1.6; 
    }
    
    /* Header Styles */
    header { 
      background: var(--primary-color); 
      color: var(--background); 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: 0 2px 10px rgba(0,0,0,0.3); 
    }
    
    header h1 { 
      margin: 0; 
      font-size: 2rem; 
    }
    
    nav { 
      background: var(--primary-color); 
      padding: 0.5rem; 
      border-bottom: 2px solid var(--accent-color); 
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    
    nav a { 
      margin: 0 1rem; 
      color: var(--background); 
      text-decoration: none; 
      font-weight: bold; 
      transition: color 0.3s; 
    }
    
    nav a:hover { 
      color: var(--accent-color); 
    }
    
    /* Main content sections */
    .section { 
      padding: 2rem 1rem; 
      max-width: 1100px; 
      margin: auto; 
    }
    
    h2 { 
      text-align: center; 
      margin-bottom: 1.5rem; 
      color: var(--text-color); 
      font-size: 1.8rem; 
    }
    
    /* Produk Grid */
    .produk-grid { 
      display: grid; 
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); 
      gap: 1.5rem; 
    }
    
    .produk-card { 
      background: var(--background); 
      border-radius: 12px; 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: var(--card-shadow); 
      transition: transform 0.3s, box-shadow 0.3s; 
    }
    
    .produk-card:hover { 
      transform: translateY(-8px); 
      box-shadow: var(--card-shadow-hover); 
    }
    
    .produk-card img { 
      width: 100%; 
      height: 200px; 
      object-fit: cover; 
      border-radius: 8px; 
      margin-bottom: 1rem; 
    }
    
    .produk-card p { 
      font-weight: bold; 
      color: var(--text-color); 
      margin: 0; 
    }
    
    .produk-card small { 
      color: var(--light-text); 
      font-size: 0.9rem; 
    }
    
    /* Testimoni Slider */
    .testimoni-container {
      position: relative;
      overflow: hidden;
      padding: 1rem 0;
    }
    
    .testimoni-slider { 
      display: flex; 
      transition: transform 0.5s ease-in-out;
      gap: 1rem; 
      padding: 1rem 0; 
    }
    
    .testimoni-card { 
      flex: 0 0 calc(100% - 2rem);
      background: var(--background); 
      border-radius: 12px; 
      padding: 1.5rem; 
      text-align: center; 
      box-shadow: var(--card-shadow); 
    }
    
    @media (min-width: 768px) {
      .testimoni-card {
        flex: 0 0 calc(50% - 1rem);
      }
    }
    
    @media (min-width: 1024px) {
      .testimoni-card {
        flex: 0 0 calc(33.333% - 1.5rem);
      }
    }
    
    .avatar-img { 
      width: 60px; 
      height: 60px; 
      border-radius: 50%; 
      overflow: hidden; 
      margin: 0 auto 1rem; 
      box-shadow: 0 2px 6px rgba(0,0,0,0.1); 
      background-color: #f0f0f0;
      display: flex;
      align-items: center;
      justify-content: center;
    }
    
    .avatar-img img { 
      width: 100%; 
      height: 100%; 
      object-fit: cover; 
    }
    
    .rating { 
      color: var(--accent-color); 
      font-size: 1.2rem; 
      margin-top: 0.5rem; 
    }
    
    /* Slider controls */
    .slider-controls {
      display: flex;
      justify-content: center;
      gap: 1rem;
      margin-top: 1rem;
    }
    
    .slider-btn {
      background: var(--primary-color);
      color: white;
      border: none;
      border-radius: 50%;
      width: 40px;
      height: 40px;
      cursor: pointer;
      display: flex;
      align-items: center;
      justify-content: center;
      transition: background 0.3s;
    }
    
    .slider-btn:hover {
      background: var(--accent-color);
    }
    
    /* Hubungi Section */
    .contact-info { 
      display: grid; 
      gap: 1rem; 
      margin-bottom: 1rem; 
    }
    
    .contact-info p { 
      margin: 0; 
      font-size: 1.1rem; 
    }
    
    .contact-info a { 
      color: var(--accent-color); 
      font-weight: bold; 
      text-decoration: none; 
    }
    
    .contact-info a:hover { 
      text-decoration: underline; 
    }
    
    .maps-container { 
      margin-top: 1rem; 
      border-radius: 10px; 
      overflow: hidden; 
      box-shadow: var(--card-shadow); 
    }
    
    .social-icons { 
      display: flex; 
      justify-content: center; 
      gap: 1rem; 
      margin-top: 1rem; 
    }
    
    .social-icons a { 
      transition: transform 0.3s; 
      display: flex;
      align-items: center;
      justify-content: center;
      width: 40px;
      height: 40px;
      border-radius: 50%;
      background: var(--primary-color);
    }
    
    .social-icons a:hover { 
      transform: scale(1.1); 
      background: var(--accent-color);
    }
    
    .social-icons img { 
      width: 24px; 
      height: 24px; 
    }
    
    /* WhatsApp Float */
    .whatsapp-float { 
      position: fixed; 
      bottom: 20px; 
      right: 20px; 
      background: var(--accent-color); 
      color: var(--background); 
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
      background: var(--light-accent); 
    }
    
    /* Footer */
    footer { 
      background: var(--primary-color); 
      color: var(--background); 
      text-align: center; 
      padding: 1.5rem; 
      margin-top: 2rem; 
    }
    
    footer a { 
      color: var(--background); 
      margin: 0 0.5rem; 
      text-decoration: none; 
    }
    
    footer a:hover { 
      color: var(--accent-color); 
    }
    
    /* Responsif */
    @media (max-width: 768px) {
      header h1 { 
        font-size: 1.5rem; 
      }
      
      nav { 
        flex-direction: column;
        align-items: center;
        gap: 0.5rem;
      }
      
      nav a { 
        margin: 0.25rem 0; 
      }
      
      .produk-grid { 
        grid-template-columns: 1fr; 
      }
      
      .social-icons { 
        gap: 0.5rem; 
      }
      
      .social-icons a {
        width: 35px;
        height: 35px;
      }
      
      .social-icons img { 
        width: 20px; 
        height: 20px; 
      }
      
      .whatsapp-float { 
        width: 50px; 
        height: 50px; 
        font-size: 1.5rem; 
      }
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

  <main>
    <!-- Produk Section -->
    <section class="section" id="produk">
      <h2>Produk Popular</h2>
      <div class="produk-grid">
        <article class="produk-card">
          <img src="images/sofa-premium.jpg" alt="Sofa Premium Chan Furniture Pandan City JB" loading="lazy" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZTVlNWU1Ii8+PHRleHQgeD0iNTAlIiB5PSI1MCUiIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxNCIgZmlsbD0iIzY2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZHk9Ii4zZW0iPlNvZmEgUHJlbWl1bTwvdGV4dD48L3N2Zz4='">
          <p>Sofa Premium</p>
          <small>Harga bermula RM999, ansuran mudah!</small>
        </article>
        <article class="produk-card">
          <img src="images/smart-tv-samsung.jpg" alt="Smart TV Samsung Chan Furniture Pandan City JB" loading="lazy" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZTVlNWU1Ii8+PHRleHQgeD0iNTAlIiB5PSI1MCUiIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxNCIgZmlsbD0iIzY2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZHk9Ii4zZW0iPlNtYXJ0IFRWIFNhbXN1bmc8L3RleHQ+PC9zdmc+'">
          <p>Smart TV Samsung</p>
          <small>4K UHD, sesuai untuk hiburan keluarga!</small>
        </article>
        <article class="produk-card">
          <img src="images/peti-sejuk-panasonic.jpg" alt="Peti Sejuk Panasonic Chan Furniture Pandan City JB" loading="lazy" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZTVlNWU1Ii8+PHRleHQgeD0iNTAlIiB5PSI1MCUiIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxNCIgZmlsbD0iIzY2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZHk9Ii4zZW0iPlBldGkgU2VqdWsgUGFuYXNvbmljPC90ZXh0Pjwvc3ZnPg=='">
          <p>Peti Sejuk Panasonic</p>
          <small>Hemat tenaga, kapasiti besar!</small>
        </article>
        <article class="produk-card">
          <img src="images/iphone-13.jpg" alt="iPhone 13 Chan Furniture Pandan City JB" loading="lazy" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZTVlNWU1Ii8+PHRleHQgeD0iNTAlIiB5PSI1MCUiIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxNCIgZmlsbD0iIzY2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZHk9Ii4zZW0iPmlQaG9uZSAxMzwvdGV4dD48L3N2Zz4='">
          <p>iPhone 13</p>
          <small>Kamera canggih, prestasi pantas!</small>
        </article>
        <article class="produk-card">
          <img src="images/laptop-acer.jpg" alt="Laptop Acer Chan Furniture Pandan City JB" loading="lazy" onerror="this.src='data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAwIiBoZWlnaHQ9IjIwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48cmVjdCB3aWR0aD0iMTAwJSIgaGVpZ2h0PSIxMDAlIiBmaWxsPSIjZTVlNWU1Ii8+PHRleHQgeD0iNTAlIiB5PSI1MCUiIGZvbnQtZmFtaWx5PSJBcmlhbCwgc2Fucy1zZXJpZiIgZm9udC1zaXplPSIxNCIgZmlsbD0iIzY2NiIgdGV4dC1hbmNob3I9Im1pZGRsZSIgZHk9Ii4zZW0iPkxhcHRvcCBBY2VyPC90ZXh0Pjwvc3ZnPg=='">
          <p>Laptop Acer</p>
          <small>Untuk kerja dan hiburan, ansuran mudah!</small>
        </article>
      </div>
    </section>

    <!-- Testimoni Section -->
    <section class="section" id="testimoni">
      <h2>Apa Kata Pelanggan Kami</h2>
      <div class="testimoni-container">
        <div class="testimoni-slider" id="testimoniSlider">
          <article class="testimoni-card">
            <div class="avatar-img">
              <img src="images/avatar-aisyah.jpg" alt="Avatar Aisyah" loading="lazy" onerror="this.style.display='none'">
            </div>
            <p>“Perabot dan elektronik berkualiti, harga berpatutan. Staf mesra & layanan terbaik!”</p>
            <strong>- Aisyah, JB</strong>
            <div class="rating">⭐⭐⭐⭐⭐</div>
          </article>
          <article class="testimoni-card">
            <div class="avatar-img">
              <img src="images/avatar-farid.jpg" alt="Avatar Farid" loading="lazy" onerror="this.style.display='none'">
            </div>
            <p>“Beli TV dan iPhone, penghantaran cepat. Senang urusan ansuran bulanan!”</p>
            <strong>- Farid, Skudai</strong>
            <div class="rating">⭐⭐⭐⭐⭐</div>
          </article>
          <article class="testimoni-card">
            <div class="avatar-img">
              <img src="images/avatar-lim-wei.jpg" alt="Avatar Lim Wei" loading="lazy" onerror="this.style.display='none'">
            </div>
            <p>“Banyak pilihan elektronik moden. Akan datang lagi untuk peti sejuk!”</p>
            <strong>- Lim Wei, Tebrau</strong>
            <div class="rating">⭐⭐⭐⭐⭐</div>
          </article>
          <article class="testimoni-card">
            <div class="avatar-img">
              <img src="images/avatar-siti.jpg" alt="Avatar Siti" loading="lazy" onerror="this.style.display='none'">
            </div>
            <p>“Ansuran tanpa deposit sungguh memudahkan. Terima kasih Chan Furniture!”</p>
            <strong>- Siti, Pasir Gudang</strong>
            <div class="rating">⭐⭐⭐⭐⭐</div>
          </article>
        </div>
      </div>
      <div class="slider-controls">
        <button class="slider-btn prev" aria-label="Testimoni sebelumnya">←</button>
        <button class="slider-btn next" aria-label="Testimoni seterusnya">→</button>
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
        <a href="https://www.tiktok.com/@chanfurniturepandancityjb" target="_blank" title="TikTok Chan Furniture Pandan City JB" aria-label="TikTok">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
            <path d="M12.525.02c1.31-.02 2.61-.01 3.91-.02.08 1.53.63 3.09 1.75 4.17 1.12 1.11 2.7 1.62 4.24 1.79v4.03c-1.44-.05-2.89-.35-4.2-.97-.57-.26-1.1-.59-1.62-.93-.01 2.92.01 5.84-.02 8.75-.08 1.4-.54 2.79-1.35 3.94-1.31 1.92-3.58 3.17-5.91 3.21-1.43.08-2.86-.31-4.08-1.03-2.02-1.19-3.44-3.37-3.65-5.71-.02-.5-.03-1-.01-1.49.18-1.9 1.12-3.72 2.58-4.96 1.66-1.44 3.98-2.13 6.15-1.72.02 1.48-.04 2.96-.04 4.44-.99-.32-2.15-.23-3.02.37-.63.41-1.11 1.04-1.36 1.75-.21.51-.15 1.07-.14 1.61.24 1.64 1.82 3.02 3.5 2.87 1.12-.01 2.19-.66 2.77-1.61.19-.33.4-.67.41-1.06.1-1.79.06-3.57.07-5.36.01-4.03-.01-8.05.02-12.07z"/>
          </svg>
        </a>
        <a href="https://wa.me/60162625886" target="_blank" title="WhatsApp Chan Furniture" aria-label="WhatsApp">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
            <path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347m-5.421 7.403h-.004a9.87 9.87 0 01-5.031-1.378l-.361-.214-3.741.982.998-3.648-.235-.374a9.86 9.86 0 01-1.51-5.26c.001-5.45 4.436-9.884 9.888-9.884 2.64 0 5.122 1.03 6.988 2.898a9.825 9.825 0 012.893 6.994c-.003 5.45-4.437 9.884-9.885 9.884m8.413-18.297A11.815 11.815 0 0012.05 0C5.495 0 .16 5.335.157 11.892c0 2.096.547 4.142 1.588 5.945L.057 24l6.305-1.654a11.882 11.882 0 005.683 1.448h.005c6.554 0 11.89-5.335 11.893-11.893A11.821 11.821 0 0020.864 3.488"/>
          </svg>
        </a>
        <a href="https://www.facebook.com/cfpandancty/" target="_blank" title="Facebook Chan Furniture" aria-label="Facebook">
          <svg width="24" height="24" viewBox="0 0 24 24" fill="white">
            <path d="M24 12.073c0-6.627-5.373-12-12-12s-12 5.373-12 12c0 5.99 4.388 10.954 10.125 11.854v-8.385H7.078v-3.47h3.047V9.43c0-3.007 1.792-4.669 4.533-4.669 1.312 0 2.686.235 2.686.235v2.953H15.83c-1.491 0-1.956.925-1.956 1.874v2.25h3.328l-.532 3.47h-2.796v8.385C19.612 23.027 24 18.062 24 12.073z"/>
          </svg>
        </a>
      </div>
    </section>
  </main>

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
    // Testimonial slider functionality
    document.addEventListener('DOMContentLoaded', function() {
      const slider = document.getElementById('testimoniSlider');
      const slides = document.querySelectorAll('.testimoni-card');
      const prevBtn = document.querySelector('.slider-btn.prev');
      const nextBtn = document.querySelector('.slider-btn.next');
      let currentIndex = 0;
      let slideInterval;
      
      // Function to update slider position
      function updateSlider() {
        const slideWidth = slides[0].offsetWidth + 16; // card width + gap
        slider.style.transform = `translateX(-${currentIndex * slideWidth}px)`;
      }
      
      // Function to go to next slide
      function nextSlide() {
        currentIndex = (currentIndex + 1) % slides.length;
        updateSlider();
      }
      
      // Function to go to previous slide
      function prevSlide() {
        currentIndex = (currentIndex - 1 + slides.length) % slides.length;
        updateSlider();
      }
      
      // Start auto sliding
      function startSlider() {
        slideInterval = setInterval(nextSlide, 4000);
      }
      
      // Stop auto sliding
      function stopSlider() {
        clearInterval(slideInterval);
      }
      
      // Event listeners for buttons
      nextBtn.addEventListener('click', function() {
        stopSlider();
        nextSlide();
        startSlider();
      });
      
      prevBtn.addEventListener('click', function() {
        stopSlider();
        prevSlide();
        startSlider();
      });
      
      // Pause slider on hover
      slider.addEventListener('mouseenter', stopSlider);
      slider.addEventListener('mouseleave', startSlider);
      
      // Initialize slider and start auto sliding
      updateSlider();
      startSlider();
      
      // Update slider on window resize
      window.addEventListener('resize', updateSlider);
    });
  </script>
</body>
</html>
