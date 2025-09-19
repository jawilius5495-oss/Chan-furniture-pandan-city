# Chan-furniture-pandan-city
<!DOCTYPE html>
<html lang="ms">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Chan Furniture Pandan City JB – Perabot berkualiti tinggi dengan harga mampu milik. Nikmati Merdeka Sale dan angsuran mudah tanpa deposit untuk TV, peti ais, smartphone, laptop, dll.! Ikuti kami di TikTok untuk tips & promosi!">
    <meta name="keywords" content="Chan Furniture, Pandan City, Johor Bahru, perabot murah, Merdeka Sale, ansuran tanpa deposit, furniture Malaysia, TV, peti ais, smartphone, laptop, mesin basuh, aircond, soundbar, TikTok Chan Furniture">
    <meta name="author" content="Chan Furniture">
    <meta name="robots" content="index, follow">
    <title>Chan Furniture Pandan City JB</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffffff;
            color: #333;
            line-height: 1.6;
        }
        header {
            background-color: #b22222;
            color: #ffffff;
            padding: 1.5rem;
            text-align: center;
            position: relative;
        }
        .lang-toggle {
            position: absolute;
            top: 1rem;
            right: 1rem;
            background: #ff0000;
            color: #ffffff;
            border: none;
            padding: 8px 12px;
            border-radius: 5px;
            cursor: pointer;
            font-weight: bold;
        }
        nav {
            background-color: #ffffff;
            padding: 1rem;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        nav ul {
            list-style: none;
            padding: 0;
            margin: 0;
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        nav li { margin: 0 1.5rem; }
        nav a {
            color: #b22222;
            text-decoration: none;
            font-weight: bold;
            transition: color 0.3s;
        }
        nav a:hover { color: #ff0000; }
        .hero {
            background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)), url('https://scontent.fkul8-1.fna.fbcdn.net/v/t39.30808-6/459241258_122141433024387695_8118241594475338478_n.jpg?_nc_cat=106&ccb=1-7&_nc_sid=833d83&_nc_ohc=kqOa5d5gskMQ7kNvgHibI79&_nc_zt=23&_nc_ht=scontent.fkul8-1.fna&oh=00_AYDK3v9O1G1atVR3g8y1b3y2h6zD1GRq0a3Z1z6z3A&oe=66F6A123') center/cover;
            color: #ffffff;
            text-align: center;
            padding: 6rem 1rem;
        }
        .hero h1 { font-size: 2.8rem; margin-bottom: 1rem; }
        .btn {
            background-color: #ff0000;
            color: #ffffff;
            padding: 1rem 2rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            margin-top: 1rem;
            transition: background-color 0.3s;
        }
        .btn:hover { background-color: #cc0000; }
        .btn-small {
            background-color: #ff0000;
            color: #ffffff;
            padding: 0.8rem 1.5rem;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            display: inline-block;
            margin-top: 0.5rem;
            transition: background-color 0.3s;
            font-size: 0.9rem;
        }
        .btn-small:hover { background-color: #cc0000; }
        .section {
            padding: 3rem 1rem;
            max-width: 1200px;
            margin: 0 auto;
        }
        .promo-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        .promo-item {
            background: #f8f9fa;
            padding: 1.5rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .about, .contact, .slider, .gallery { background-color: #ffffff; }
        .contact {
            background-color: #b22222;
            color: #ffffff;
            text-align: center;
        }
        .social-buttons {
            display: flex;
            justify-content: center;
            gap: 1rem;
            margin-top: 1rem;
        }
        footer {
            background-color: #b22222;
            color: #ffffff;
            text-align: center;
            padding: 1rem;
        }
        .footer-social {
            margin-top: 0.5rem;
        }
        .footer-social a {
            color: #ffffff;
            margin: 0 0.5rem;
            text-decoration: none;
            font-size: 1.2rem;
        }
        .footer-social a:hover {
            color: #ff0000;
        }
        /* WhatsApp Button */
        .whatsapp-float {
            position: fixed;
            width: 60px;
            height: 60px;
            bottom: 20px;
            right: 20px;
            background: linear-gradient(135deg, #ff0000, #cc0000);
            color: #ffffff;
            border-radius: 50%;
            text-align: center;
            font-size: 30px;
            box-shadow: 0 4px 12px rgba(0,0,0,0.25);
            display: flex;
            align-items: center;
            justify-content: center;
            z-index: 1000;
            transition: transform 0.2s ease-in-out, background 0.3s;
            animation: pulse 1.8s infinite;
        }
        .whatsapp-float:hover {
            transform: scale(1.1);
            background: linear-gradient(135deg, #cc0000, #990000);
        }
        .tooltip-text {
            visibility: hidden;
            background-color: #333;
            color: #fff;
            text-align: center;
            padding: 5px 10px;
            border-radius: 6px;
            position: absolute;
            right: 70px;
            bottom: 15px;
            opacity: 0;
            transition: opacity 0.3s;
            font-size: 14px;
            white-space: nowrap;
        }
        .whatsapp-float:hover .tooltip-text {
            visibility: visible;
            opacity: 1;
        }
        @keyframes pulse {
            0% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 0, 0, 0.5); }
            50% { transform: scale(1.08); box-shadow: 0 0 0 10px rgba(255, 0, 0, 0); }
            100% { transform: scale(1); box-shadow: 0 0 0 0 rgba(255, 0, 0, 0); }
        }
        /* Slider Produk */
        .slider {
            position: relative;
            max-width: 1200px;
            margin: 2rem auto;
            overflow: hidden;
        }
        .slider-container {
            display: flex;
            transition: transform 0.5s ease-in-out;
        }
        .slide {
            min-width: 100%;
            box-sizing: border-box;
            padding: 1rem;
            text-align: center;
        }
        .slide img {
            width: 100%;
            max-height: 400px;
            object-fit: cover;
            border-radius: 10px;
        }
        .slide h3 { margin: 1rem 0 0.5rem; color: #b22222; }
        .slider-nav {
            position: absolute;
            top: 50%;
            width: 100%;
            display: flex;
            justify-content: space-between;
            transform: translateY(-50%);
        }
        .slider-nav button {
            background: rgba(255, 0, 0, 0.5);
            color: #ffffff;
            border: none;
            padding: 10px;
            cursor: pointer;
            border-radius: 50%;
        }
        .slider-dots {
            text-align: center;
            margin-top: 1rem;
        }
        .dot {
            height: 10px;
            width: 10px;
            background-color: #bbb;
            border-radius: 50%;
            display: inline-block;
            margin: 0 5px;
            cursor: pointer;
        }
        .dot.active { background-color: #ff0000; }
        /* Galeri Barangan Elektrik */
        .gallery-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 2rem;
            margin-top: 2rem;
        }
        .gallery-item {
            background: #f8f9fa;
            padding: 1rem;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
            text-align: center;
        }
        .gallery-item img {
            width: 100%;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .gallery-item h3 { margin: 1rem 0 0.5rem; color: #b22222; }
        /* Borang WhatsApp */
        .whatsapp-form {
            max-width: 500px;
            margin: 2rem auto;
            padding: 1.5rem;
            background: #ffffff;
            border-radius: 10px;
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);
        }
        .whatsapp-form input, .whatsapp-form textarea {
            width: 100%;
            padding: 0.8rem;
            margin: 0.5rem 0;
            border: 1px solid #ccc;
            border-radius: 5px;
            font-size: 1rem;
        }
        .whatsapp-form button {
            background-color: #ff0000;
            color: #ffffff;
            padding: 1rem;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            width: 100%;
            font-weight: bold;
        }
        .whatsapp-form button:hover { background-color: #cc0000; }
        .success-message {
            color: #ff0000;
            text-align: center;
            margin-top: 1rem;
            display: none;
        }
        @media (max-width: 768px) {
            .hero h1 { font-size: 2rem; }
            nav ul { flex-direction: column; }
            nav li { margin: 0.5rem 0; }
            .slide img, .gallery-item img { max-height: 250px; }
            .hero { padding: 4rem 1rem; }
            .gallery-grid { grid-template-columns: 1fr; }
            .social-buttons { flex-direction: column; gap: 0.5rem; }
        }
    </style>
</head>
<body>
    <header>
        <h2>Chan Furniture Pandan City JB</h2>
        <p class="lang-ms">Perabot Berkualiti untuk Rumah Impian Anda</p>
        <p class="lang-en" style="display:none;">Quality Furniture for Your Dream Home</p>
        <button class="lang-toggle" id="langToggle" aria-label="Tukar bahasa">EN</button>
    </header>

    <nav>
        <ul>
            <li><a href="#utama" class="lang-ms">Utama</a><a href="#utama" class="lang-en" style="display:none;">Home</a></li>
            <li><a href="#promosi" class="lang-ms">Promosi</a><a href="#promosi" class="lang-en" style="display:none;">Promotions</a></li>
            <li><a href="#produk" class="lang-ms">Produk</a><a href="#produk" class="lang-en" style="display:none;">Products</a></li>
            <li><a href="#galeri" class="lang-ms">Galeri Elektrik</a><a href="#galeri" class="lang-en" style="display:none;">Electronics Gallery</a></li>
            <li><a href="#tentang" class="lang-ms">Tentang</a><a href="#tentang" class="lang-en" style="display:none;">About</a></li>
            <li><a href="#hubungi" class="lang-ms">Hubungi</a><a href="#hubungi" class="lang-en" style="display:none;">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section id="utama" class="hero">
            <h1 class="lang-ms">Selamat Datang ke Chan Furniture Pandan City!</h1>
            <h1 class="lang-en" style="display:none;">Welcome to Chan Furniture Pandan City!</h1>
            <p class="lang-ms">Nikmati perabot mewah dengan harga mampu milik. Promosi Merdeka Sale sedang berlangsung – jimat besar! 🥳</p>
            <p class="lang-en" style="display:none;">Discover premium furniture at affordable prices. Merdeka Sale is on now – save big! 🥳</p>
            <a href="#promosi" class="btn lang-ms">Lihat Promosi</a>
            <a href="#promosi" class="btn lang-en" style="display:none;">View Promotions</a>
        </section>

        <section id="promosi" class="section promo">
            <h2 class="lang-ms">Promosi Terkini</h2>
            <h2 class="lang-en" style="display:none;">Latest Promotions</h2>
            <p class="lang-ms">Ansuran mudah tanpa deposit untuk perabot, telefon, laptop, TV, peti ais, mesin basuh, aircond & soundbar pelbagai jenama berkualiti. Bayar bulanan murah tanpa kad kredit!</p>
            <p class="lang-en" style="display:none;">Easy instalments with no deposit for furniture, smartphones, laptops, TV, fridge, washing machine, aircond & soundbar from various quality brands. Affordable monthly payments without credit card!</p>
            <div class="promo-grid">
                <div class="promo-item">
                    <h3 class="lang-ms">0% Faedah</h3>
                    <h3 class="lang-en" style="display:none;">0% Interest</h3>
                    <p class="lang-ms">Bayar bulanan tanpa deposit atau kad kredit untuk smartphone & laptop.</p>
                    <p class="lang-en" style="display:none;">Pay monthly with no deposit or credit card for smartphones & laptops.</p>
                </div>
                <div class="promo-item">
                    <h3 class="lang-ms">Merdeka Sale</h3>
                    <h3 class="lang-en" style="display:none;">Merdeka Sale</h3>
                    <p class="lang-ms">Diskaun sehingga 50% untuk sofa, katil, dan almari.</p>
                    <p class="lang-en" style="display:none;">Up to 50% off on sofas, beds, and wardrobes.</p>
                </div>
                <div class="promo-item">
                    <h3 class="lang-ms">Ansuran Mudah IT</h3>
                    <h3 class="lang-en" style="display:none;">Easy IT Installments</h3>
                    <p class="lang-ms">Smartphone (iPhone, Samsung, Oppo) & laptop (Acer, Lenovo) – tanpa deposit!</p>
                    <p class="lang-en" style="display:none;">Smartphones (iPhone, Samsung, Oppo) & laptops (Acer, Lenovo) – no deposit!</p>
                </div>
            </div>
            <a href="https://wa.me/60162625886?text=Hai!%20Saya%20berminat%20untuk%20membeli%20perabot,%20smartphone,%20laptop%20atau%20barangan%20elektrik%20di%20Chan%20Furniture%20Pandan%20City.%20Boleh%20kongsikan%20katalog%20atau%20promosi%20terkini?" 
               class="btn lang-ms" id="shopNowMs" target="_blank" aria-label="Beli sekarang melalui WhatsApp">Beli Sekarang</a>
            <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20buying%20furniture,%20smartphones,%20laptops%20or%20electronics%20at%20Chan%20Furniture%20Pandan%20City.%20Can%20you%20share%20the%20latest%20catalog%20or%20promotions?" 
               class="btn lang-en" id="shopNowEn" style="display:none;" target="_blank" aria-label="Shop now via WhatsApp">Shop Now</a>
        </section>

        <section id="produk" class="section slider">
            <h2 class="lang-ms">Produk Pilihan</h2>
            <h2 class="lang-en" style="display:none;">Featured Products</h2>
            <div class="slider-container">
                <div class="slide">
                    <img src="https://via.placeholder.com/800x400?text=Sofa+Mewah" alt="Sofa Mewah Chan Furniture">
                    <h3 class="lang-ms">Sofa Mewah</h3>
                    <h3 class="lang-en" style="display:none;">Luxury Sofa</h3>
                    <p class="lang-ms">Selesa dan bergaya untuk ruang tamu anda.</p>
                    <p class="lang-en" style="display:none;">Comfortable and stylish for your living room.</p>
                </div>
                <div class="slide">
                    <img src="https://via.placeholder.com/800x400?text=Katil+Moden" alt="Katil Moden Chan Furniture">
                    <h3 class="lang-ms">Katil Moden</h3>
                    <h3 class="lang-en" style="display:none;">Modern Bed</h3>
                    <p class="lang-ms">Reka bentuk minimalis untuk tidur nyenyak.</p>
                    <p class="lang-en" style="display:none;">Minimalist design for a restful sleep.</p>
                </div>
                <div class="slide">
                    <img src="https://via.placeholder.com/800x400?text=Almari+Elegan" alt="Almari Elegan Chan Furniture">
                    <h3 class="lang-ms">Almari Elegan</h3>
                    <h3 class="lang-en" style="display:none;">Elegant Wardrobe</h3>
                    <p class="lang-ms">Penyimpanan luas dengan gaya moden.</p>
                    <p class="lang-en" style="display:none;">Spacious storage with modern style.</p>
                </div>
                <div class="slide">
                    <img src="https://via.placeholder.com/800x400?text=Soundbar+Berkualiti" alt="Soundbar Berkualiti Chan Furniture">
                    <h3 class="lang-ms">Soundbar Berkualiti</h3>
                    <h3 class="lang-en" style="display:none;">Quality Soundbar</h3>
                    <p class="lang-ms">Bunyi jernih untuk hiburan rumah – pelbagai jenama!</p>
                    <p class="lang-en" style="display:none;">Clear sound for home entertainment – various brands!</p>
                </div>
            </div>
            <div class="slider-nav">
                <button onclick="prevSlide()" aria-label="Slaid sebelumnya">❮</button>
                <button onclick="nextSlide()" aria-label="Slaid berikutnya">❯</button>
            </div>
            <div class="slider-dots">
                <span class="dot active" onclick="currentSlide(0)" aria-label="Slaid 1"></span>
                <span class="dot" onclick="currentSlide(1)" aria-label="Slaid 2"></span>
                <span class="dot" onclick="currentSlide(2)" aria-label="Slaid 3"></span>
                <span class="dot" onclick="currentSlide(3)" aria-label="Slaid 4"></span>
            </div>
        </section>

        <section id="galeri" class="section gallery">
            <h2 class="lang-ms">Galeri Barangan Elektrik</h2>
            <h2 class="lang-en" style="display:none;">Electronics Gallery</h2>
            <p class="lang-ms">Lihat pelbagai barangan elektrik berkualiti seperti TV, peti ais, smartphone, laptop, mesin basuh, aircond dan soundbar dari jenama terkenal. Ansuran mudah tanpa deposit!</p>
            <p class="lang-en" style="display:none;">Explore a variety of quality electronics like TV, fridge, smartphones, laptops, washing machine, aircond and soundbar from top brands. Easy instalments with no deposit!</p>
            <div class="gallery-grid">
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1592735186518-7ed7192b63e5?w=400&h=200&fit=crop" alt="Smart TV Chan Furniture">
                    <h3 class="lang-ms">Smart TV</h3>
                    <h3 class="lang-en" style="display:none;">Smart TV</h3>
                    <p class="lang-ms">Sk rin besar untuk hiburan keluarga – jenama seperti Samsung & LG.</p>
                    <p class="lang-en" style="display:none;">Large screen for family entertainment – brands like Samsung & LG.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Smart%20TV%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Smart%20TV%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1600585154340-be6161a56a0c?w=400&h=200&fit=crop" alt="Peti Ais Chan Furniture">
                    <h3 class="lang-ms">Peti Ais</h3>
                    <h3 class="lang-en" style="display:none;">Fridge</h3>
                    <p class="lang-ms">Model moden dengan ruang penyimpanan luas – jenama Panasonic.</p>
                    <p class="lang-en" style="display:none;">Modern model with spacious storage – Panasonic brands.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Peti%20Ais%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Fridge%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1580894908361-9679e9228d53?w=400&h=200&fit=crop" alt="Mesin Basuh Chan Furniture">
                    <h3 class="lang-ms">Mesin Basuh</h3>
                    <h3 class="lang-en" style="display:none;">Washing Machine</h3>
                    <p class="lang-ms">Automatik dengan ciri canggih – jenama Sharp & Toshiba.</p>
                    <p class="lang-en" style="display:none;">Automatic with advanced features – Sharp & Toshiba brands.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Mesin%20Basuh%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Washing%20Machine%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1602940659805-770b6a68cb0e?w=400&h=200&fit=crop" alt="Aircond Chan Furniture">
                    <h3 class="lang-ms">Aircond</h3>
                    <h3 class="lang-en" style="display:none;">Air Conditioner</h3>
                    <p class="lang-ms">Penyejuk udara cekap tenaga – jenama Daikin & Midea.</p>
                    <p class="lang-en" style="display:none;">Energy-efficient cooling – Daikin & Midea brands.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Aircond%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Air%20Conditioner%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1610945268338-9e2e6f9e3a5e?w=400&h=200&fit=crop" alt="Soundbar Chan Furniture">
                    <h3 class="lang-ms">Soundbar</h3>
                    <h3 class="lang-en" style="display:none;">Soundbar</h3>
                    <p class="lang-ms">Audio surround berkualiti – jenama Sony & Bose.</p>
                    <p class="lang-en" style="display:none;">Quality surround audio – Sony & Bose brands.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Soundbar%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Soundbar%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1587563871167-1ee9c731a8e5?w=400&h=200&fit=crop" alt="Mesin Pengering Chan Furniture">
                    <h3 class="lang-ms">Mesin Pengering</h3>
                    <h3 class="lang-en" style="display:none;">Dryer</h3>
                    <p class="lang-ms">Pengering baju cepat – jenama Electrolux.</p>
                    <p class="lang-en" style="display:none;">Fast clothes dryer – Electrolux brands.</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Mesin%20Pengering%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Dryer%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1511707171634-5f897ff02aa9?w=400&h=200&fit=crop" alt="Smartphone Chan Furniture">
                    <h3 class="lang-ms">Smartphone</h3>
                    <h3 class="lang-en" style="display:none;">Smartphone</h3>
                    <p class="lang-ms">iPhone, Samsung, Oppo – ansuran mudah tanpa deposit!</p>
                    <p class="lang-en" style="display:none;">iPhone, Samsung, Oppo – easy instalments with no deposit!</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Smartphone%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini%20&%20ansuran?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Smartphone%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion%20&%20installment?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
                <div class="gallery-item">
                    <img src="https://images.unsplash.com/photo-1496181133206-80ce9b88a853?w=400&h=200&fit=crop" alt="Laptop Chan Furniture">
                    <h3 class="lang-ms">Laptop</h3>
                    <h3 class="lang-en" style="display:none;">Laptop</h3>
                    <p class="lang-ms">Acer, Lenovo – bayar bulanan murah tanpa kad kredit!</p>
                    <p class="lang-en" style="display:none;">Acer, Lenovo – affordable monthly payments without credit card!</p>
                    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20minat%20Laptop%20di%20Chan%20Furniture%20Pandan%20City.%20Apa%20promosi%20terkini%20&%20ansuran?" class="btn-small lang-ms" target="_blank">Tanya Sekarang</a>
                    <a href="https://wa.me/60162625886?text=Hi!%20I'm%20interested%20in%20Laptop%20at%20Chan%20Furniture%20Pandan%20City.%20What's%20the%20latest%20promotion%20&%20installment?" class="btn-small lang-en" style="display:none;" target="_blank">Inquire Now</a>
                </div>
            </div>
        </section>

        <section id="tentang" class="section about">
            <h2 class="lang-ms">Tentang Kami</h2>
            <h2 class="lang-en" style="display:none;">About Us</h2>
            <p class="lang-ms">Chan Furniture adalah rangkaian kedai perabot terbesar di Malaysia dengan 95 cawangan. Cawangan Pandan City kami menawarkan pelbagai pilihan perabot berkualiti tinggi serta barangan elektrik seperti TV, peti ais, smartphone, laptop, mesin basuh, aircond dan soundbar pelbagai jenama berkualiti pada harga berpatutan. Nikmati ansuran mudah tanpa deposit untuk smartphone & laptop!</p>
            <p class="lang-en" style="display:none;">Chan Furniture is Malaysia’s largest furniture chain with 95 branches. Our Pandan City store offers a wide range of high-quality furniture as well as electronics like TV, fridge, smartphones, laptops, washing machine, aircond and soundbar from various quality brands at competitive prices. Enjoy easy instalments with no deposit for smartphones & laptops!</p>
            <ul>
                <li class="lang-ms">📍 <strong>Alamat:</strong> No. 19, Jalan Pandan City Ria 5, Pusat Perdagangan Pandan, 81100 Johor Bahru</li>
                <li class="lang-en" style="display:none;">📍 <strong>Address:</strong> No. 19, Jalan Pandan City Ria 5, Pusat Perdagangan Pandan, 81100 Johor Bahru</li>
                <li class="lang-ms">⏰ <strong>Jam Buka:</strong> Isnin–Sabtu: 12PM–9PM | Ahad & Cuti Umum: 12PM–8PM</li>
                <li class="lang-en" style="display:none;">⏰ <strong>Opening Hours:</strong> Mon–Sat: 12PM–9PM | Sun & Public Holiday: 12PM–8PM</li>
                <li>📞 <strong>WhatsApp:</strong> <a href="https://wa.me/60162625886" target="_blank" aria-label="Hubungi melalui WhatsApp">016-2625886</a></li>
            </ul>
            <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3988.771567123456!2d103.760123!3d1.318456!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x0%3A0x0!2zMcKwMTknMDYuNCJOIDEwM8KwNDUnMzYuNCJF!5e0!3m2!1sms!2smy!4v1634567890" width="100%" height="300" style="border:0; border-radius:10px;" allowfullscreen="" loading="lazy" title="Peta Chan Furniture Pandan City"></iframe>
        </section>

        <section id="hubungi" class="section contact">
            <h2 class="lang-ms">Hubungi Kami</h2>
            <h2 class="lang-en" style="display:none;">Contact Us</h2>
            <p class="lang-ms">Hantar pertanyaan anda melalui WhatsApp atau lawati kedai kami!</p>
            <p class="lang-en" style="display:none;">Send us your inquiries via WhatsApp or visit our store!</p>
            <form class="whatsapp-form" id="whatsappForm">
                <input type="text" id="name" placeholder="Nama / Name" required aria-label="Nama atau Name">
                <input type="tel" id="phone" placeholder="No. Telefon / Phone Number" required aria-label="Nombor telefon atau Phone number">
                <textarea id="message" placeholder="Mesej anda / Your message" rows="4" required aria-label="Mesej atau Message"></textarea>
                <button type="submit" class="lang-ms">Hantar melalui WhatsApp</button>
                <button type="submit" class="lang-en" style="display:none;">Send via WhatsApp</button>
                <p class="success-message lang-ms">Mesej berjaya dihantar!</p>
                <p class="success-message lang-en" style="display:none;">Message sent successfully!</p>
            </form>
            <div class="social-buttons">
                <a href="https://www.facebook.com/cfpandancty/" class="btn" target="_blank" aria-label="Ikuti kami di Facebook">Facebook</a>
                <a href="https://www.tiktok.com/@chanfurnitureofficial" class="btn" target="_blank" aria-label="Ikuti kami di TikTok">TikTok</a>
            </div>
        </section>
    </main>

    <footer>
        <p>&copy; 2025 Chan Furniture Pandan City JB | <a href="https://www.chanfurniture.com.my/" style="color: #ffffff;">Laman Rasmi / Official Website</a></p>
        <div class="footer-social">
            <a href="https://www.facebook.com/cfpandancty/" target="_blank" aria-label="Facebook">📘</a>
            <a href="https://www.tiktok.com/@chanfurnitureofficial" target="_blank" aria-label="TikTok">🎵</a>
        </div>
    </footer>

    <!-- WhatsApp Floating Button -->
    <a href="https://wa.me/60162625886?text=Hai!%20Saya%20nak%20tahu%20promosi%20terbaru%20Chan%20Furniture%20Pandan%20City." 
       class="whatsapp-float lang-ms" id="waButton" target="_blank" aria-label="Chat dengan kami di WhatsApp">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" width="30" height="30" fill="white">
            <path d="M380.9 97.1C339-35.6 194.8-35.7 152.8 97.1 126.6 174 158.2 262.4 223.4 310.1c65.1 47.7 146.4 51.6 214.3-10.3 66.9-60.8 66.8-169.3-56.8-202.7zm-106.2 297.4c-27.6 0-54.7-7.5-78.2-21.6l-81.4 21.6 21.8-79.1c-14.5-24.2-22.2-52-22.2-80.7 0-87.1 70.9-158 158-158s158 70.9 158 158-70.9 158-158 158z"/>
        </svg>
        <span class="tooltip-text lang-ms">Chat dengan kami di WhatsApp 📲</span>
        <span class="tooltip-text lang-en" style="display:none;">Chat with us on WhatsApp 📲</span>
    </a>
    <a href="https://wa.me/60162625886?text=Hi!%20I%20want%20to%20know%20about%20the%20latest%20promotions%20at%20Chan%20Furniture%20Pandan%20City." 
       class="whatsapp-float lang-en" id="waButtonEn" style="display:none;" target="_blank" aria-label="Chat with us on WhatsApp">
        <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 448 512" width="30" height="30" fill="white">
            <path d="M380.9 97.1C339-35.6 194.8-35.7 152.8 97.1 126.6 174 158.2 262.4 223.4 310.1c65.1 47.7 146.4 51.6 214.3-10.3 66.9-60.8 66.8-169.3-56.8-202.7zm-106.2 297.4c-27.6 0-54.7-7.5-78.2-21.6l-81.4 21.6 21.8-79.1c-14.5-24.2-22.2-52-22.2-80.7 0-87.1 70.9-158 158-158s158 70.9 158 158-70.9 158-158 158z"/>
        </svg>
        <span class="tooltip-text lang-ms">Chat dengan kami di WhatsApp 📲</span>
        <span class="tooltip-text lang-en" style="display:none;">Chat with us on WhatsApp 📲</span>
    </a>

    <audio id="popSound" preload="auto">
        <source src="https://actions.google.com/sounds/v1/cartoon/pop.ogg" type="audio/ogg">
    </audio>

    <script>
        // Smooth scroll untuk anchor link
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Bahasa toggle dengan localStorage
        const langToggle = document.getElementById('langToggle');
        const waButtonMs = document.getElementById('waButton');
        const waButtonEn = document.getElementById('waButtonEn');
        const shopNowMs = document.getElementById('shopNowMs');
        const shopNowEn = document.getElementById('shopNowEn');
        
        function toggleLang() {
            const isEnglish = document.querySelector('.lang-ms').style.display === 'none';
            document.querySelectorAll('.lang-ms').forEach(el => el.style.display = isEnglish ? '' : 'none');
            document.querySelectorAll('.lang-en').forEach(el => el.style.display = isEnglish ? 'none' : '');
            waButtonMs.style.display = isEnglish ? '' : 'none';
            waButtonEn.style.display = isEnglish ? 'none' : '';
            shopNowMs.style.display = isEnglish ? '' : 'none';
            shopNowEn.style.display = isEnglish ? 'none' : '';
            langToggle.textContent = isEnglish ? 'EN' : 'BM';
            localStorage.setItem('language', isEnglish ? 'ms' : 'en');
        }

        // Muat bahasa dari localStorage
        document.addEventListener('DOMContentLoaded', () => {
            const savedLang = localStorage.getItem('language');
            if (savedLang === 'en') toggleLang();
        });

        langToggle.addEventListener('click', toggleLang);

        // Mainkan bunyi pop bila klik WhatsApp atau Shop Now atau butang galeri
        [waButtonMs, waButtonEn, shopNowMs, shopNowEn].forEach(button => {
            button.addEventListener('click', () => {
                document.getElementById('popSound').play();
            });
        });
        document.querySelectorAll('.btn-small').forEach(button => {
            button.addEventListener('click', () => {
                document.getElementById('popSound').play();
            });
        });

        // Slider Produk (Automatik + Manual)
        let slideIndex = 0;
        const slides = document.querySelectorAll('.slide');
        const dots = document.querySelectorAll('.dot');

        function showSlide(index) {
            if (index >= slides.length) slideIndex = 0;
            if (index < 0) slideIndex = slides.length - 1;
            document.querySelector('.slider-container').style.transform = `translateX(-${slideIndex * 100}%)`;
            dots.forEach(dot => dot.classList.remove('active'));
            dots[slideIndex].classList.add('active');
        }

        function nextSlide() {
            slideIndex++;
            showSlide(slideIndex);
        }

        function prevSlide() {
            slideIndex--;
            showSlide(slideIndex);
        }

        function currentSlide(index) {
            slideIndex = index;
            showSlide(slideIndex);
        }

        // Auto slide setiap 5 saat
        let autoSlide = setInterval(nextSlide, 5000);
        document.querySelector('.slider').addEventListener('mouseenter', () => clearInterval(autoSlide));
        document.querySelector('.slider').addEventListener('mouseleave', () => autoSlide = setInterval(nextSlide, 5000));

        showSlide(slideIndex);

        // Borang WhatsApp
        document.getElementById('whatsappForm').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('name').value;
            const phone = document.getElementById('phone').value;
            const message = document.getElementById('message').value;
            const isEnglish = document.querySelector('.lang-ms').style.display === 'none';
            const text = isEnglish 
                ? `Hi! I'm ${name} (Phone: ${phone}). ${message}`
                : `Hai! Saya ${name} (Telefon: ${phone}). ${message}`;
            const url = `https://wa.me/60162625886?text=${encodeURIComponent(text)}`;
            window.open(url, '_blank');
            document.getElementById('popSound').play();
            document.querySelectorAll('.success-message').forEach(msg => msg.style.display = isEnglish ? (msg.classList.contains('lang-en') ? 'block' : 'none') : (msg.classList.contains('lang-ms') ? 'block' : 'none'));
            setTimeout(() => document.querySelectorAll('.success-message').forEach(msg => msg.style.display = 'none'), 3000);
            this.reset();
        });
    </script>
</body>
</html>
kedai-pandan-city-hero.jpg
sofa-mewah-chan-pandan.jpg
