 <!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>ALRDWAN - أفضل أدوات المطبخ</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    :root {
      --primary: #e60023;
      --secondary: #ff4757;
      --dark: #333;
      --light: #f8f8f8;
      --success: #2ecc71;
      --info: #3498db;
      --warning: #f39c12;
      --danger: #e74c3c;
      --shadow: 0 4px 12px rgba(0, 0, 0, 0.1);
      --transition: all 0.3s ease;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f7fa;
      color: #333;
      line-height: 1.6;
    }

    #navbar-iframe {
      display: none !important;
    }

    /* Header Styles */
    header {
      background: linear-gradient(135deg, #000 0%, #333 100%);
      color: white;
      padding: 0.8rem 1rem;
      box-shadow: var(--shadow);
      position: sticky;
      top: 0;
      z-index: 1000;
    }

    .header-container {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: 1200px;
      margin: 0 auto;
    }

    .logo {
      font-size: 1.8rem;
      font-weight: 800;
      color: white;
      text-decoration: none;
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .logo i {
      color: var(--primary);
    }

    /* Navigation */
    nav {
      display: flex;
      background-color: #222;
      justify-content: center;
      flex-wrap: wrap;
      padding: 0.5rem;
    }

    nav a {
      color: white;
      padding: 0.8rem 1.2rem;
      text-decoration: none;
      transition: var(--transition);
      position: relative;
      font-weight: 500;
    }

    nav a:hover {
      background-color: #444;
    }

    nav a.active {
      background-color: var(--primary);
    }

    nav a.active::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 50%;
      transform: translateX(-50%);
      width: 80%;
      height: 3px;
      background-color: white;
      border-radius: 2px;
    }

    /* Hero Section */
    .hero {
      background: linear-gradient(rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.7)), 
                  url('https://images.unsplash.com/photo-1556911220-ef412ae179a9?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=1200&q=80');
      background-size: cover;
      background-position: center;
      color: white;
      padding: 4rem 1rem;
      text-align: center;
      position: relative;
      margin-bottom: 2rem;
    }

    .hero-content {
      max-width: 800px;
      margin: 0 auto;
      animation: fadeInUp 1s ease;
    }

    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
      text-shadow: 0 2px 4px rgba(0,0,0,0.3);
    }

    .hero p {
      font-size: 1.2rem;
      margin-bottom: 2rem;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
    }

    .btn {
      display: inline-block;
      padding: 0.8rem 2rem;
      background-color: var(--primary);
      color: white;
      text-decoration: none;
      border-radius: 30px;
      font-weight: 600;
      transition: var(--transition);
      border: none;
      cursor: pointer;
      font-size: 1rem;
      box-shadow: 0 4px 10px rgba(230, 0, 35, 0.3);
    }

    .btn:hover {
      background-color: #ff0019;
      transform: translateY(-3px);
      box-shadow: 0 6px 15px rgba(230, 0, 35, 0.4);
    }

    /* Main Content */
    .container {
      max-width: 1200px;
      margin: 0 auto;
      padding: 0 1rem;
    }

    .section-title {
      text-align: center;
      margin: 2rem 0;
      font-size: 2rem;
      color: var(--dark);
      position: relative;
    }

    .section-title::after {
      content: '';
      position: absolute;
      bottom: -10px;
      left: 50%;
      transform: translateX(-50%);
      width: 80px;
      height: 4px;
      background-color: var(--primary);
      border-radius: 2px;
    }

    /* Filter and Search */
    .filter-bar {
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 1rem;
      margin-bottom: 2rem;
      background: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: var(--shadow);
    }

    .search-box {
      flex: 1;
      min-width: 250px;
      position: relative;
    }

    .search-box input {
      width: 100%;
      padding: 0.8rem 1rem 0.8rem 2.5rem;
      border: 1px solid #ddd;
      border-radius: 30px;
      font-size: 1rem;
      transition: var(--transition);
    }

    .search-box input:focus {
      border-color: var(--primary);
      outline: none;
      box-shadow: 0 0 0 3px rgba(230, 0, 35, 0.1);
    }

    .search-box i {
      position: absolute;
      left: 1rem;
      top: 50%;
      transform: translateY(-50%);
      color: #777;
    }

    .filter-options {
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
    }

    .filter-select {
      padding: 0.6rem 1rem;
      border: 1px solid #ddd;
      border-radius: 30px;
      background: white;
      font-size: 0.9rem;
      cursor: pointer;
      transition: var(--transition);
    }

    .filter-select:focus {
      border-color: var(--primary);
      outline: none;
    }

    /* Categories */
    .categories {
      display: flex;
      justify-content: center;
      gap: 1rem;
      flex-wrap: wrap;
      margin-bottom: 2rem;
    }

    .category {
      background: white;
      border-radius: 8px;
      padding: 1rem 1.5rem;
      text-align: center;
      box-shadow: var(--shadow);
      cursor: pointer;
      transition: var(--transition);
      border: 2px solid transparent;
      min-width: 120px;
    }

    .category:hover, .category.active {
      border-color: var(--primary);
      transform: translateY(-5px);
    }

    .category i {
      font-size: 2rem;
      color: var(--primary);
      margin-bottom: 0.5rem;
    }

    /* Products Grid */
    .products {
      display: grid;
      grid-template-columns: repeat(auto-fill, minmax(250px, 1fr));
      gap: 1.5rem;
      margin-bottom: 3rem;
    }

    .product {
      background-color: white;
      border-radius: 12px;
      overflow: hidden;
      text-align: center;
      box-shadow: var(--shadow);
      transition: var(--transition);
      position: relative;
    }

    .product:hover {
      transform: translateY(-10px);
      box-shadow: 0 12px 20px rgba(0,0,0,0.15);
    }

    .product-badge {
      position: absolute;
      top: 10px;
      left: 10px;
      background-color: var(--primary);
      color: white;
      padding: 0.3rem 0.8rem;
      border-radius: 20px;
      font-size: 0.8rem;
      font-weight: bold;
      z-index: 10;
    }

    .product-image {
      height: 200px;
      overflow: hidden;
      position: relative;
    }

    .product-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.5s ease;
    }

    .product:hover .product-image img {
      transform: scale(1.1);
    }

    .quick-view {
      position: absolute;
      bottom: -50px;
      left: 0;
      width: 100%;
      background-color: rgba(0,0,0,0.7);
      color: white;
      padding: 0.8rem;
      transition: var(--transition);
      cursor: pointer;
    }

    .product:hover .quick-view {
      bottom: 0;
    }

    .product-content {
      padding: 1.2rem;
    }

    .product h3 {
      font-size: 1.2rem;
      margin-bottom: 0.5rem;
      color: #333;
    }

    .product-price {
      color: var(--primary);
      font-size: 1.3rem;
      font-weight: bold;
      margin-bottom: 0.8rem;
    }

    .product-price .old-price {
      color: #999;
      text-decoration: line-through;
      font-size: 0.9rem;
      margin-left: 0.5rem;
    }

    .product-rating {
      color: var(--warning);
      margin-bottom: 1rem;
      font-size: 0.9rem;
    }

    .product-actions {
      display: flex;
      gap: 0.5rem;
    }

    .add-cart, .buy-now {
      flex: 1;
      padding: 0.6rem;
      border-radius: 4px;
      color: white;
      text-decoration: none;
      font-weight: 500;
      cursor: pointer;
      transition: var(--transition);
      border: none;
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 0.5rem;
    }

    .add-cart {
      background-color: var(--info);
    }

    .add-cart:hover {
      background-color: #2980b9;
    }

    .buy-now {
      background-color: var(--success);
    }

    .buy-now:hover {
      background-color: #27ae60;
    }

    /* Cart Sidebar */
    .cart-toggle {
      position: fixed;
      top: 100px;
      right: 20px;
      background: var(--primary);
      color: white;
      width: 60px;
      height: 60px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      box-shadow: 0 4px 12px rgba(230, 0, 35, 0.3);
      z-index: 999;
      font-size: 1.5rem;
      transition: var(--transition);
    }

    .cart-toggle:hover {
      transform: scale(1.1);
    }

    .cart-badge {
      position: absolute;
      top: -5px;
      right: -5px;
      background: var(--success);
      color: white;
      width: 25px;
      height: 25px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 0.8rem;
      font-weight: bold;
    }

    .cart-sidebar {
      position: fixed;
      top: 0;
      right: -400px;
      width: 380px;
      height: 100vh;
      background: white;
      box-shadow: -5px 0 15px rgba(0,0,0,0.1);
      z-index: 1000;
      transition: var(--transition);
      padding: 1.5rem;
      display: flex;
      flex-direction: column;
    }

    .cart-sidebar.active {
      right: 0;
    }

    .cart-header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding-bottom: 1rem;
      border-bottom: 1px solid #eee;
      margin-bottom: 1rem;
    }

    .cart-title {
      font-size: 1.5rem;
      font-weight: 600;
    }

    .close-cart {
      background: none;
      border: none;
      font-size: 1.5rem;
      cursor: pointer;
      color: #777;
    }

    .cart-items {
      flex: 1;
      overflow-y: auto;
      margin-bottom: 1rem;
    }

    .cart-item {
      display: flex;
      gap: 1rem;
      padding: 1rem 0;
      border-bottom: 1px solid #eee;
    }

    .cart-item-image {
      width: 80px;
      height: 80px;
      border-radius: 8px;
      overflow: hidden;
    }

    .cart-item-image img {
      width: 100%;
      height: 100%;
      object-fit: cover;
    }

    .cart-item-details {
      flex: 1;
    }

    .cart-item-name {
      font-weight: 600;
      margin-bottom: 0.5rem;
    }

    .cart-item-price {
      color: var(--primary);
      font-weight: bold;
      margin-bottom: 0.5rem;
    }

    .cart-item-quantity {
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .quantity-btn {
      width: 30px;
      height: 30px;
      border-radius: 50%;
      background: #f1f1f1;
      border: none;
      display: flex;
      align-items: center;
      justify-content: center;
      cursor: pointer;
      font-size: 1.2rem;
    }

    .quantity-input {
      width: 40px;
      text-align: center;
      border: 1px solid #ddd;
      border-radius: 4px;
      padding: 0.3rem;
    }

    .remove-item {
      color: var(--danger);
      background: none;
      border: none;
      cursor: pointer;
      font-size: 1.2rem;
      align-self: flex-start;
    }

    .cart-footer {
      padding-top: 1rem;
      border-top: 1px solid #eee;
    }

    .cart-total {
      display: flex;
      justify-content: space-between;
      font-size: 1.2rem;
      font-weight: bold;
      margin-bottom: 1.5rem;
    }

    .checkout-btn {
      width: 100%;
      padding: 1rem;
      background: var(--primary);
      color: white;
      border: none;
      border-radius: 8px;
      font-size: 1.1rem;
      font-weight: 600;
      cursor: pointer;
      transition: var(--transition);
    }

    .checkout-btn:hover {
      background: #ff0019;
    }

    /* Notification */
    #notification {
      position: fixed;
      top: 20px;
      right: 20px;
      background: var(--success);
      color: white;
      padding: 15px 25px;
      border-radius: 8px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.15);
      z-index: 2000;
      font-size: 1rem;
      display: flex;
      align-items: center;
      gap: 10px;
      transform: translateX(150%);
      transition: transform 0.5s ease;
    }

    #notification.show {
      transform: translateX(0);
    }

    /* Footer */
    footer {
      background: linear-gradient(135deg, #000 0%, #222 100%);
      color: white;
      padding: 3rem 1rem 1.5rem;
      margin-top: 3rem;
    }

    .footer-container {
      max-width: 1200px;
      margin: 0 auto;
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }

    .footer-section h3 {
      font-size: 1.3rem;
      margin-bottom: 1.5rem;
      position: relative;
      padding-bottom: 0.5rem;
    }

    .footer-section h3::after {
      content: '';
      position: absolute;
      bottom: 0;
      left: 0;
      width: 50px;
      height: 3px;
      background: var(--primary);
    }

    .footer-links {
      list-style: none;
    }

    .footer-links li {
      margin-bottom: 0.8rem;
    }

    .footer-links a {
      color: #ddd;
      text-decoration: none;
      transition: var(--transition);
      display: flex;
      align-items: center;
      gap: 0.5rem;
    }

    .footer-links a:hover {
      color: white;
      transform: translateX(5px);
    }

    .footer-contact p {
      display: flex;
      align-items: center;
      gap: 0.8rem;
      margin-bottom: 1rem;
    }

    .social-links {
      display: flex;
      gap: 1rem;
      margin-top: 1rem;
    }

    .social-links a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 40px;
      height: 40px;
      background: rgba(255,255,255,0.1);
      border-radius: 50%;
      color: white;
      transition: var(--transition);
    }

    .social-links a:hover {
      background: var(--primary);
      transform: translateY(-5px);
    }

    .footer-bottom {
      text-align: center;
      padding-top: 2rem;
      margin-top: 2rem;
      border-top: 1px solid rgba(255,255,255,0.1);
    }

    /* Responsive Design */
    @media (max-width: 992px) {
      .cart-sidebar {
        width: 320px;
      }
    }

    @media (max-width: 768px) {
      .header-container {
        flex-direction: column;
        gap: 1rem;
      }
      
      .hero h2 {
        font-size: 2rem;
      }
      
      .filter-bar {
        flex-direction: column;
        align-items: stretch;
      }
      
      .cart-sidebar {
        width: 100%;
        right: -100%;
      }
    }

    @media (max-width: 480px) {
      .product-actions {
        flex-direction: column;
      }
      
      .category {
        min-width: 100px;
        padding: 0.8rem 1rem;
      }
      
      .hero {
        padding: 2rem 1rem;
      }
      
      .hero h2 {
        font-size: 1.8rem;
      }
    }

    /* Animations */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    @keyframes pulse {
      0% { transform: scale(1); }
      50% { transform: scale(1.1); }
      100% { transform: scale(1); }
    }
  </style>
</head>

<body>
  <header>
    <div class="header-container">
      <a href="#" class="logo">
        <i class="fas fa-utensils"></i>
        ALRDWAN
      </a>
      <div class="search-box">
        <i class="fas fa-search"></i>
        <input type="text" id="search-input" placeholder="ابحث عن منتج...">
      </div>
      <div class="user-actions">
        <button class="btn">
          <i class="fas fa-user"></i> تسجيل الدخول
        </button>
      </div>
    </div>
  </header>

  <nav>
    <a href="#" class="active">الرئيسية</a>
    <a href="#">أدوات المطبخ</a>
    <a href="#">أدوات التقطيع</a>
    <a href="#">أدوات الخبز</a>
    <a href="#">العروض الخاصة</a>
    <a href="#">اتصل بنا</a>
  </nav>

  <section class="hero">
    <div class="hero-content">
      <h2>اكتشف أفضل أدوات المطبخ</h2>
      <p>نقدم لك أحدث وأجود أدوات المطبخ بأسعار منافسة وجودة عالية. تصفح مجموعتنا المميزة واجعل طهيك تجربة ممتعة.</p>
      <button class="btn">تصفح المنتجات الآن</button>
    </div>
  </section>

  <div class="container">
    <h2 class="section-title">تصنيفات المنتجات</h2>
    <div class="categories">
      <div class="category active">
        <i class="fas fa-blender"></i>
        <h3>الجميع</h3>
      </div>
      <div class="category">
        <i class="fas fa-cookie-bite"></i>
        <h3>أدوات الخبز</h3>
      </div>
      <div class="category">
        <i class="fas fa-utensils"></i>
        <h3>أدوات المائدة</h3>
      </div>
      <div class="category">
        <i class="fas fa-knife-kitchen"></i>
        <h3>أدوات التقطيع</h3>
      </div>
      <div class="category">
        <i class="fas fa-coffee"></i>
        <h3>أدوات المشروبات</h3>
      </div>
    </div>

    <div class="filter-bar">
      <div class="filter-options">
        <select class="filter-select" id="sort-select">
          <option value="">ترتيب حسب</option>
          <option value="price-asc">السعر: من الأقل للأعلى</option>
          <option value="price-desc">السعر: من الأعلى للأقل</option>
          <option value="rating">الأعلى تقييماً</option>
        </select>
        <select class="filter-select" id="price-select">
          <option value="">فلترة السعر</option>
          <option value="0-50">حتى 50 ج</option>
          <option value="50-100">50 - 100 ج</option>
          <option value="100+">أكثر من 100 ج</option>
        </select>
      </div>
      <div class="results-count">عرض 12 منتج من 24</div>
    </div>

    <h2 class="section-title">منتجاتنا المميزة</h2>
    <div class="products" id="products-grid">
      <!-- Products will be dynamically inserted here -->
    </div>
  </div>

  <!-- Cart Toggle Button -->
  <div class="cart-toggle" id="cart-toggle">
    <i class="fas fa-shopping-cart"></i>
    <div class="cart-badge" id="cart-badge">0</div>
  </div>

  <!-- Cart Sidebar -->
  <div class="cart-sidebar" id="cart-sidebar">
    <div class="cart-header">
      <h3 class="cart-title">سلة التسوق</h3>
      <button class="close-cart" id="close-cart">
        <i class="fas fa-times"></i>
      </button>
    </div>
    <div class="cart-items" id="cart-items">
      <!-- Cart items will be dynamically inserted here -->
    </div>
    <div class="cart-footer">
      <div class="cart-total">
        <span>المجموع:</span>
        <span id="cart-total">0 ج</span>
      </div>
      <button class="checkout-btn" id="checkout-btn">إتمام الشراء</button>
    </div>
  </div>

  <!-- Notification -->
  <div id="notification">
    <i class="fas fa-check-circle"></i>
    <span id="notification-text">تمت إضافة المنتج إلى العربة!</span>
  </div>

  <footer>
    <div class="footer-container">
      <div class="footer-section">
        <h3>عن ALRDWAN</h3>
        <p>متجر متخصص في بيع أفضل أدوات المطبخ بجودة عالية وأسعار مناسبة. نسعى لتوفير كل ما يحتاجه مطبخك من أدوات حديثة وعملية.</p>
        <div class="social-links">
          <a href="#"><i class="fab fa-facebook-f"></i></a>
          <a href="#"><i class="fab fa-instagram"></i></a>
          <a href="#"><i class="fab fa-twitter"></i></a>
          <a href="#"><i class="fab fa-youtube"></i></a>
        </div>
      </div>
      <div class="footer-section">
        <h3>روابط سريعة</h3>
        <ul class="footer-links">
          <li><a href="#"><i class="fas fa-chevron-left"></i> الرئيسية</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> المنتجات</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> العروض</a></li>
            <li><a href="about.html"><i class="fas fa-chevron-left"></i>من نحن</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> اتصل بنا</a></li>
        </ul>
      </div>
      <div class="footer-section">
        <h3>التصنيفات</h3>
        <ul class="footer-links">
          <li><a href="#"><i class="fas fa-chevron-left"></i> أدوات الخبز</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> أدوات المائدة</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> أدوات التقطيع</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> أدوات المشروبات</a></li>
          <li><a href="#"><i class="fas fa-chevron-left"></i> أدوات الطهي</a></li>
        </ul>
      </div>
      <div class="footer-section footer-contact">
        <h3>اتصل بنا</h3>
        <p><i class="fas fa-map-marker-alt"></i> 123 شارع التسوق، القاهرة، مصر</p>
        <p><i class="fas fa-phone"></i> +20 123 456 7890</p>
        <p><i class="fas fa-envelope"></i> info@alrdwan.com</p>
        <p><i class="fab fa-whatsapp"></i> +20 123 456 7890</p>
      </div>
    </div>
    <div class="footer-bottom">
      <p>&copy; 2023 ALRDWAN. جميع الحقوق محفوظة.</p>
    </div>
  </footer>

  <script>
    // Sample product data
    const products = [
      {
        id: 1,
        name: "قشارة بطاطس",
        price: 20,
        oldPrice: 25,
        image: "https://m.media-amazon.com/images/I/41FW9hbRtpL._AC_SY879_.jpg",
        category: "أدوات التقطيع",
        rating: 4.5,
        badge: "جديد"
      },
      {
        id: 2,
        name: "مقص الشيف",
        price: 45,
        image: "https://elghazawy.com/storage/205222/2.webp",
        category: "أدوات التقطيع",
        rating: 4.8,
        badge: "الأكثر مبيعاً"
      },
      {
        id: 3,
        name: "ماسك لحمة",
        price: 65,
        image: "https://scontent.fcai19-8.fna.fbcdn.net/v/t1.6435-9/125885752_206396541050367_6629127788817650201_n.jpg?_nc_cat=111&ccb=1-7&_nc_sid=833d8c&_nc_ohc=ss3uOs_Hf30Q7kNvwGjraZT&_nc_ht=scontent.fcai19-8.fna&oh=00_AfMqEL2I_P_2bVSuDCCU9lInMTA02Z8iL2DGdPWH9eNEHA&oe=686CBC6D",
        category: "أدوات المائدة",
        rating: 4.2
      },
      {
        id: 4,
        name: "مضرب نسكافية",
        price: 55,
        oldPrice: 70,
        image: "https://m.media-amazon.com/images/I/51qqXzx5rJL.__AC_SX300_SY300_QL70_ML2_.jpg",
        category: "أدوات المشروبات",
        rating: 4.7,
        badge: "خصم 20%"
      },
      {
        id: 5,
        name: "مفرمة لحم كهربائية",
        price: 350,
        image: "https://images.unsplash.com/photo-1626082927389-6cd097cee6a6?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80",
        category: "أدوات التقطيع",
        rating: 4.9,
        badge: "الأفضل"
      },
      {
        id: 6,
        name: "طقم سكاكين",
        price: 220,
        oldPrice: 280,
        image: "https://images.unsplash.com/photo-1583947215259-38e31be8751f?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80",
        category: "أدوات التقطيع",
        rating: 4.6
      },
      {
        id: 7,
        name: "طقم حلل ستانلس",
        price: 650,
        image: "https://images.unsplash.com/photo-1600880292203-757bb62b4baf?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80",
        category: "أدوات الطهي",
        rating: 4.8,
        badge: "جديد"
      },
      {
        id: 8,
        name: "خلاط يدوي",
        price: 180,
        oldPrice: 220,
        image: "https://images.unsplash.com/photo-1603739903239-8b6e64c3b185?ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D&auto=format&fit=crop&w=500&q=80",
        category: "أدوات الخبز",
        rating: 4.4,
        badge: "خصم"
      }
    ];

    // Cart functionality
    let cart = [];
    const phoneNumber = "201234567890";

    // DOM Elements
    const productsGrid = document.getElementById('products-grid');
    const cartToggle = document.getElementById('cart-toggle');
    const cartSidebar = document.getElementById('cart-sidebar');
    const closeCart = document.getElementById('close-cart');
    const cartItems = document.getElementById('cart-items');
    const cartTotal = document.getElementById('cart-total');
    const cartBadge = document.getElementById('cart-badge');
    const checkoutBtn = document.getElementById('checkout-btn');
    const notification = document.getElementById('notification');
    const notificationText = document.getElementById('notification-text');

    // Render products
    function renderProducts(productsArray) {
      productsGrid.innerHTML = '';
      
      productsArray.forEach(product => {
        const productEl = document.createElement('div');
        productEl.className = 'product';
        productEl.innerHTML = `
          ${product.badge ? `<div class="product-badge">${product.badge}</div>` : ''}
          <div class="product-image">
            <img src="${product.image}" alt="${product.name}">
            <div class="quick-view">عرض سريع</div>
          </div>
          <div class="product-content">
            <h3>${product.name}</h3>
            <div class="product-price">
              ${product.price} ج
              ${product.oldPrice ? `<span class="old-price">${product.oldPrice} ج</span>` : ''}
            </div>
            <div class="product-rating">
              ${renderRating(product.rating)}
              <span>(${product.rating})</span>
            </div>
            <div class="product-actions">
              <button class="add-cart" onclick="addToCart(${product.id})">
                <i class="fas fa-cart-plus"></i> أضف إلى العربة
              </button>
              <button class="buy-now" onclick="buyNow(${product.id})">
                <i class="fas fa-bolt"></i> شراء الآن
              </button>
            </div>
          </div>
        `;
        productsGrid.appendChild(productEl);
      });
    }

    // Render star rating
    function renderRating(rating) {
      let stars = '';
      const fullStars = Math.floor(rating);
      const halfStar = rating % 1 >= 0.5;
      
      for (let i = 1; i <= 5; i++) {
        if (i <= fullStars) {
          stars += '<i class="fas fa-star"></i>';
        } else if (i === fullStars + 1 && halfStar) {
          stars += '<i class="fas fa-star-half-alt"></i>';
        } else {
          stars += '<i class="far fa-star"></i>';
        }
      }
      
      return stars;
    }

    // Add to cart function
    function addToCart(productId) {
      const product = products.find(p => p.id === productId);
      
      // Check if product is already in cart
      const existingItem = cart.find(item => item.id === productId);
      
      if (existingItem) {
        existingItem.quantity++;
      } else {
        cart.push({
          id: product.id,
          name: product.name,
          price: product.price,
          image: product.image,
          quantity: 1
        });
      }
      
      updateCart();
      showNotification(`تمت إضافة "${product.name}" إلى العربة`);
    }

    // Buy now function
    function buyNow(productId) {
      const product = products.find(p => p.id === productId);
      const message = encodeURIComponent(`مرحبًا، أرغب في شراء هذا المنتج: ${product.name}`);
      const url = `https://wa.me/${phoneNumber}?text=${message}`;
      window.open(url, '_blank');
    }

    // Update cart UI
    function updateCart() {
      // Update cart badge
      const totalItems = cart.reduce((total, item) => total + item.quantity, 0);
      cartBadge.textContent = totalItems;
      
      // Update cart items
      cartItems.innerHTML = '';
      
      if (cart.length === 0) {
        cartItems.innerHTML = '<div style="text-align: center; padding: 2rem; color: #777;">سلة التسوق فارغة</div>';
        cartTotal.textContent = '0 ج';
        return;
      }
      
      let total = 0;
      
      cart.forEach(item => {
        const itemTotal = item.price * item.quantity;
        total += itemTotal;
        
        const cartItemEl = document.createElement('div');
        cartItemEl.className = 'cart-item';
        cartItemEl.innerHTML = `
          <div class="cart-item-image">
            <img src="${item.image}" alt="${item.name}">
          </div>
          <div class="cart-item-details">
            <div class="cart-item-name">${item.name}</div>
            <div class="cart-item-price">${item.price} ج × ${item.quantity}</div>
            <div class="cart-item-total">${itemTotal} ج</div>
            <div class="cart-item-quantity">
              <button class="quantity-btn" onclick="updateQuantity(${item.id}, -1)">-</button>
              <input type="number" class="quantity-input" value="${item.quantity}" min="1" onchange="updateQuantityInput(${item.id}, this.value)">
              <button class="quantity-btn" onclick="updateQuantity(${item.id}, 1)">+</button>
            </div>
          </div>
          <button class="remove-item" onclick="removeFromCart(${item.id})">
            <i class="fas fa-trash"></i>
          </button>
        `;
        cartItems.appendChild(cartItemEl);
      });
      
      cartTotal.textContent = `${total} ج`;
    }

    // Update quantity
    function updateQuantity(productId, change) {
      const item = cart.find(item => item.id === productId);
      if (item) {
        item.quantity += change;
        if (item.quantity < 1) item.quantity = 1;
        updateCart();
      }
    }

    // Update quantity via input
    function updateQuantityInput(productId, value) {
      const quantity = parseInt(value);
      if (isNaN(quantity) || quantity < 1) return;
      
      const item = cart.find(item => item.id === productId);
      if (item) {
        item.quantity = quantity;
        updateCart();
      }
    }

    // Remove from cart
    function removeFromCart(productId) {
      cart = cart.filter(item => item.id !== productId);
      updateCart();
      showNotification("تمت إزالة المنتج من العربة");
    }

    // Show notification
    function showNotification(text = "تمت إضافة المنتج إلى العربة!") {
      notificationText.textContent = text;
      notification.classList.add('show');
      
      setTimeout(() => {
        notification.classList.remove('show');
      }, 3000);
    }

    // Checkout cart
    function checkoutCart() {
      if (cart.length === 0) {
        showNotification("العربة فارغة!");
        return;
      }
      
      const productList = cart.map((item, i) => 
        `${i + 1}- ${item.name} (${item.quantity} × ${item.price} ج) = ${item.quantity * item.price} ج`
      ).join("\n");
      
      const total = cart.reduce((sum, item) => sum + (item.price * item.quantity), 0);
      
      const message = encodeURIComponent(
        `مرحبًا، أرغب في شراء المنتجات التالية:\n\n${productList}\n\nالمجموع الكلي: ${total} ج`
      );
      
      const url = `https://wa.me/${phoneNumber}?text=${message}`;
      window.open(url, '_blank');
    }

    // Event listeners
    cartToggle.addEventListener('click', () => {
      cartSidebar.classList.add('active');
    });

    closeCart.addEventListener('click', () => {
      cartSidebar.classList.remove('active');
    });

    checkoutBtn.addEventListener('click', checkoutCart);

    // Initialize
    document.addEventListener('DOMContentLoaded', () => {
      renderProducts(products);
      updateCart();
    });
  </script>
</body>
</html>
