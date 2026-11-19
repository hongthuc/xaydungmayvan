<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN | xaydungmayvan.com</title>
  <meta name="description" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ & XÂY DỰNG MAY VĂN - Chuyên tư vấn thiết kế kiến trúc, nội thất, thi công phần thô, hoàn thiện và xây nhà trọn gói uy tín tại Đà Nẵng. Hotline: 0916.143.477.">
  <meta name="keywords" content="xaydungmayvan.com, xây dựng May Văn, thiết kế xây dựng Đà Nẵng, thi công trọn gói Đà Nẵng, xây nhà Hòa Xuân">

  <!-- Meta Open Graph & Thumbnail Logo khi chia sẻ đường link website -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://xaydungmayvan.com/">
  <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ & XÂY DỰNG MAY VĂN">
  <meta property="og:description" content="Tư vấn thiết kế kiến trúc, nội thất & thi công xây dựng trọn gói chuyên nghiệp tại Đà Nẵng. Địa chỉ: 74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0916.143.477.">
  <meta property="og:image" content="https://xaydungmayvan.com/wp-content/uploads/logo-may-van-thumbnail.png">
  <meta property="og:image:width" content="1200">
  <meta property="og:image:height" content="630">
  <meta property="og:site_name" content="Xây Dựng May Văn">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:title" content="CÔNG TY TNHH TƯ VẤN THIẾT KẾ & XÂY DỰNG MAY VĂN">
  <meta name="twitter:description" content="Thiết kế kiến trúc - Thi công xây dựng trọn gói uy tín tại Đà Nẵng.">
  <meta name="twitter:image" content="https://xaydungmayvan.com/wp-content/uploads/logo-may-van-thumbnail.png">

  <!-- Favicon SVG đồng bộ màu logo May Văn -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='10' fill='%230F2A44'/%3E%3Cpath d='M12 46V24L32 10L52 24V46H44V28L32 19L20 28V46H12Z' fill='%23D4A745'/%3E%3Cpath d='M25 46V31L32 39L39 31V46H34V39L32 42L30 39V46H25Z' fill='%23FFFFFF'/%3E%3C/svg%3E">

  <!-- Font chữ Inter chuẩn hiện đại & dễ đọc tiếng Việt -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>

  <!-- Font Awesome cho icon chuyên nghiệp -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <script>
    /* Cấu hình bảng màu đồng bộ theo Logo Công Ty May Văn (Xanh Navy Kiến Trúc & Vàng Kim Đồng) */
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            brandNavy: '#0F2A44',
            brandNavyLight: '#1A3E63',
            brandGold: '#C89B3C',
            brandGoldLight: '#DFB65B',
            brandBg: '#F6F7F9',
            brandText: '#1F2937'
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif']
          }
        }
      }
    };
  </script>

  <style>
    /* ==========================================================================
       CẤU HÌNH CHUNG & CHỐNG TRÀN VIỀN TUYỆT ĐỐI (CHUẨN FLATSOME / UX BUILDER)
       ========================================================================== */
    *, *::before, *::after {
      box-sizing: border-box;
    }

    html, body {
      width: 100%;
      max-width: 100%;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1F2937;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện: Mobile gọn sát lề an toàn, Máy tính rộng đúng 95% màn hình */
    .ux-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }

    @media (min-width: 768px) {
      .ux-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Đảm bảo ảnh, iframe không bao giờ vượt quá khung chứa */
    img, iframe, svg {
      max-width: 100%;
    }

    /* ==========================================================================
       HEADER & MENU ĐIỀU HƯỚNG (MÁY TÍNH 1 HÀNG GỌN ĐẸP, KHÔNG XUỐNG DÒNG TÊN MỤC)
       ========================================================================== */
    .flatsome-header {
      position: sticky;
      top: 0;
      z-index: 50;
      width: 100%;
      background: #FFFFFF;
      border-bottom: 1px solid #E5E7EB;
      box-shadow: 0 2px 10px rgba(15, 42, 68, 0.06);
    }

    .nav-desktop-list {
      display: flex;
      align-items: center;
      justify-content: flex-end;
      flex-wrap: nowrap;
      gap: 14px;
      margin: 0;
      padding: 0;
      list-style: none;
    }

    @media (min-width: 1280px) {
      .nav-desktop-list {
        gap: 20px;
      }
    }

    .nav-desktop-link {
      display: inline-flex;
      align-items: center;
      gap: 4px;
      white-space: nowrap;
      font-size: 12.5px;
      font-weight: 600;
      color: #0F2A44;
      text-transform: uppercase;
      letter-spacing: 0.01em;
      padding: 10px 2px;
      position: relative;
      transition: color 0.2s ease;
    }

    @media (min-width: 1280px) {
      .nav-desktop-link {
        font-size: 13px;
      }
    }

    .nav-desktop-link:hover,
    .nav-desktop-link.active {
      color: #C89B3C;
    }

    .nav-desktop-link::after {
      content: '';
      position: absolute;
      left: 0;
      bottom: 4px;
      width: 0;
      height: 2px;
      background-color: #C89B3C;
      transition: width 0.25s ease;
    }

    .nav-desktop-link:hover::after,
    .nav-desktop-link.active::after {
      width: 100%;
    }

    /* Dropdown chuẩn Flatsome */
    .nav-item-has-sub {
      position: relative;
    }

    .nav-dropdown {
      position: absolute;
      top: 100%;
      left: 0;
      min-width: 235px;
      background: #FFFFFF;
      border: 1px solid #E5E7EB;
      border-top: 2px solid #C89B3C;
      border-radius: 0 0 8px 8px;
      box-shadow: 0 10px 25px rgba(15, 42, 68, 0.12);
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
      z-index: 60;
      padding: 6px 0;
    }

    .nav-item-has-sub:hover .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    .nav-dropdown a {
      display: block;
      padding: 9px 16px;
      font-size: 13px;
      font-weight: 500;
      color: #1F2937;
      white-space: nowrap;
      transition: background 0.15s ease, color 0.15s ease;
    }

    .nav-dropdown a:hover {
      background: #F6F7F9;
      color: #C89B3C;
    }

    /* ==========================================================================
       2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU & CHỮ AN TOÀN CÁCH XA VIỀN
       ========================================================================== */
    .hero-slider-wrap {
      position: relative;
      width: 100%;
      overflow: hidden;
      background-color: #0F2A44;
    }

    .hero-slides-track {
      display: flex;
      width: 200%;
      transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
    }

    .hero-slide {
      width: 50%;
      flex-shrink: 0;
      position: relative;
      /* Chiều cao đồng đều tuyệt đối giữa 2 banner trên mọi thiết bị */
      height: 330px;
      display: flex;
      align-items: center;
      justify-content: center;
      overflow: hidden;
    }

    @media (min-width: 640px) {
      .hero-slide {
        height: 400px;
      }
    }

    @media (min-width: 1024px) {
      .hero-slide {
        height: 500px;
      }
    }

    @media (min-width: 1440px) {
      .hero-slide {
        height: 540px;
      }
    }

    .hero-slide-bg {
      position: absolute;
      inset: 0;
      width: 100%;
      height: 100%;
      object-fit: cover;
      object-position: center;
    }

    .hero-slide-overlay {
      position: absolute;
      inset: 0;
      background: linear-gradient(95deg, rgba(15, 42, 68, 0.92) 0%, rgba(15, 42, 68, 0.78) 55%, rgba(15, 42, 68, 0.48) 100%);
    }

    /* Khung nội dung bên trong banner cách xa viền rõ ràng trên cả điện thoại & máy tính */
    .hero-safe-box {
      position: relative;
      z-index: 2;
      width: 100%;
      max-width: 100%;
      padding: 28px 46px;
    }

    @media (min-width: 768px) {
      .hero-safe-box {
        width: 95%;
        max-width: 95%;
        padding: 40px 68px;
      }
    }

    @media (min-width: 1280px) {
      .hero-safe-box {
        padding: 52px 84px;
      }
    }

    /* ==========================================================================
       THANH DANH MỤC TRANG CHỦ (CHỮ NHỎ GỌN, KHÔNG XUỐNG DÒNG TÊN DANH MỤC)
       ========================================================================== */
    .cat-filter-bar {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 8px;
    }

    .cat-filter-btn {
      white-space: nowrap;
      font-size: 12px;
      font-weight: 600;
      padding: 7px 14px;
      border-radius: 6px;
      border: 1px solid #D1D5DB;
      background: #FFFFFF;
      color: #0F2A44;
      cursor: pointer;
      transition: all 0.2s ease;
      line-height: 1.25;
    }

    @media (min-width: 1024px) {
      .cat-filter-btn {
        font-size: 12.5px;
        padding: 8px 16px;
      }
    }

    .cat-filter-btn:hover {
      border-color: #C89B3C;
      color: #C89B3C;
    }

    .cat-filter-btn.active {
      background: #0F2A44;
      border-color: #0F2A44;
      color: #FFFFFF;
    }

    /* ==========================================================================
       TIÊU ĐỀ SECTION CHUẨN FLATSOME
       ========================================================================== */
    .ux-section-title {
      text-align: center;
      margin-bottom: 24px;
    }

    .ux-section-title h2 {
      font-size: clamp(18px, 2.2vw, 26px);
      font-weight: 800;
      color: #0F2A44;
      text-transform: uppercase;
      letter-spacing: 0.02em;
      margin: 0 0 8px 0;
    }

    .ux-divider {
      width: 56px;
      height: 3px;
      background: #C89B3C;
      margin: 0 auto;
      border-radius: 99px;
    }

    /* ==========================================================================
       CARD SẢN PHẨM / DỰ ÁN (2 CỘT TRÊN MOBILE, TÊN HIỂN THỊ ĐỦ KHÔNG CẮT CHỮ)
       ========================================================================== */
    .ux-card {
      background: #FFFFFF;
      border: 1px solid #E5E7EB;
      border-radius: 10px;
      overflow: hidden;
      display: flex;
      flex-direction: column;
      height: 100%;
      transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
    }

    .ux-card:hover {
      transform: translateY(-3px);
      box-shadow: 0 10px 24px rgba(15, 42, 68, 0.1);
      border-color: #C89B3C;
    }

    .ux-card-thumb {
      width: 100%;
      aspect-ratio: 4 / 3;
      overflow: hidden;
      background: #EEF2F6;
      position: relative;
    }

    .ux-card-thumb img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      display: block;
      transition: transform 0.45s ease;
    }

    .ux-card:hover .ux-card-thumb img {
      transform: scale(1.05);
    }

    .ux-card-body {
      padding: 10px;
      display: flex;
      flex-direction: column;
      flex-grow: 1;
      justify-content: space-between;
    }

    @media (min-width: 768px) {
      .ux-card-body {
        padding: 14px;
      }
    }

    /* Đảm bảo tên sản phẩm/công trình không bao giờ tràn viền hoặc bị thiếu chữ */
    .ux-card-title {
      font-size: 13px;
      font-weight: 700;
      color: #0F2A44;
      line-height: 1.4;
      margin: 0 0 6px 0;
      word-break: break-word;
      overflow-wrap: anywhere;
      white-space: normal;
    }

    @media (min-width: 768px) {
      .ux-card-title {
        font-size: 14.5px;
      }
    }

    .ux-card-sub {
      font-size: 11.5px;
      color: #6B7280;
      line-height: 1.4;
      margin: 0;
      word-break: break-word;
    }

    /* ==========================================================================
       NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH MOBILE & DESKTOP
       ========================================================================== */
    .floating-contact-desktop {
      position: fixed;
      right: 16px;
      bottom: 24px;
      z-index: 70;
      display: none;
      flex-direction: column;
      gap: 10px;
    }

    @media (min-width: 768px) {
      .floating-contact-desktop {
        display: flex;
      }
    }

    .float-btn {
      display: inline-flex;
      align-items: center;
      gap: 9px;
      padding: 9px 15px;
      border-radius: 999px;
      color: #FFFFFF;
      font-size: 13px;
      font-weight: 700;
      text-decoration: none;
      box-shadow: 0 6px 18px rgba(0, 0, 0, 0.2);
      transition: transform 0.2s ease, box-shadow 0.2s ease;
      white-space: nowrap;
    }

    .float-btn:hover {
      transform: translateY(-2px) scale(1.03);
      box-shadow: 0 10px 22px rgba(0, 0, 0, 0.26);
    }

    .float-btn-zalo {
      background: linear-gradient(135deg, #0068FF, #0088FF);
    }

    .float-btn-fb {
      background: linear-gradient(135deg, #1877F2, #0C5DC7);
    }

    .float-btn-phone {
      background: linear-gradient(135deg, #0F2A44, #C89B3C);
      animation: softPulse 2.4s infinite;
    }

    @keyframes softPulse {
      0%, 100% { box-shadow: 0 0 0 0 rgba(200, 155, 60, 0.55); }
      50% { box-shadow: 0 0 0 10px rgba(200, 155, 60, 0); }
    }

    /* Thanh liên hệ cố định đáy màn hình trên điện thoại (gọn đẹp, không tràn viền) */
    .mobile-bottom-bar {
      position: fixed;
      left: 0;
      right: 0;
      bottom: 0;
      width: 100%;
      z-index: 70;
      background: #FFFFFF;
      border-top: 1px solid #E5E7EB;
      box-shadow: 0 -4px 14px rgba(15, 42, 68, 0.12);
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 6px;
      padding: 8px 10px;
    }

    @media (min-width: 768px) {
      .mobile-bottom-bar {
        display: none;
      }
    }

    .mobile-bar-btn {
      display: flex;
      align-items: center;
      justify-content: center;
      gap: 6px;
      padding: 10px 6px;
      border-radius: 8px;
      font-size: 12.5px;
      font-weight: 700;
      color: #FFFFFF;
      text-decoration: none;
      white-space: nowrap;
    }

    /* Đệm dưới chân trang trên mobile để không bị thanh liên hệ che nội dung */
    @media (max-width: 767px) {
      body {
        padding-bottom: 62px;
      }
    }
  </style>
</head>
<body>

  <!-- ========================================================================
       1. TOP BAR THÔNG TIN GỌN NHẸ (KHÔNG HIỂN THỊ TÙY CHỌN UXBUILDER)
       ======================================================================== -->
  <div class="w-full bg-brandNavy text-white text-xs py-2">
    <div class="ux-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <a href="tel:0916143477" class="inline-flex items-center gap-1.5 hover:text-brandGoldLight transition">
          <i class="fa-solid fa-phone text-brandGoldLight"></i>
          <span>0916.143.477</span>
        </a>
        <span class="hidden sm:inline text-white/30">|</span>
        <span class="hidden sm:inline-flex items-center gap-1.5 text-white/90">
          <i class="fa-solid fa-location-dot text-brandGoldLight"></i>
          <span>74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng</span>
        </span>
      </div>
      <div class="flex items-center gap-3">
        <span class="hidden md:inline text-white/80">xaydungmayvan.com</span>
        <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" aria-label="Facebook May Văn" class="hover:text-brandGoldLight transition">
          <i class="fa-brands fa-facebook-f"></i>
        </a>
        <a href="https://zalo.me/0916143477" target="_blank" rel="noopener noreferrer" aria-label="Zalo May Văn" class="hover:text-brandGoldLight transition font-bold">
          Zalo
        </a>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       2. HEADER CHÍNH CHUẨN FLATSOME (LOGO GỌN NHỎ, KHÔNG CÓ NÚT GỌI NGAY)
       ======================================================================== -->
  <header class="flatsome-header">
    <div class="ux-container flex items-center justify-between h-16 md:h-[72px] gap-4">

      <!-- Logo Công Ty TNHH Tư Vấn Thiết Kế & Xây Dựng May Văn (Chỉnh gọn nhỏ, sắc nét) -->
      <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 no-underline group" aria-label="Trang chủ Xây Dựng May Văn">
        <svg width="38" height="38" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" class="shrink-0">
          <rect width="64" height="64" rx="10" fill="#0F2A44"/>
          <!-- Khung mái kiến trúc vững chãi -->
          <path d="M11 48V24.5L32 9.5L53 24.5V48H45.5V28.2L32 18.5L18.5 28.2V48H11Z" fill="#D4A745"/>
          <!-- Biểu tượng chữ M-V kết cấu công trình -->
          <path d="M23.5 48V30.5L32 40.5L40.5 30.5V48H35.2V39.2L32 43L28.8 39.2V48H23.5Z" fill="#FFFFFF"/>
          <!-- Đường chân móng đồng bộ -->
          <rect x="11" y="51" width="42" height="3.5" rx="1.75" fill="#D4A745"/>
        </svg>
        <div class="leading-tight">
          <div class="text-[15px] md:text-[17px] font-extrabold tracking-tight text-brandNavy group-hover:text-brandGold transition">
            MAY VĂN
          </div>
          <div class="text-[9.5px] md:text-[10px] font-semibold tracking-wider text-brandGold uppercase">
            DESIGN &amp; BUILD
          </div>
        </div>
      </a>

      <!-- Menu Máy Tính: Nằm gọn 1 hàng ngang, chữ nhỏ gọn, không xuống dòng tên danh mục -->
      <nav class="hidden lg:block flex-1" aria-label="Menu chính">
        <ul class="nav-desktop-list">
          <li><a href="#trang-chu" class="nav-desktop-link active">Trang chủ</a></li>
          <li><a href="#gioi-thieu" class="nav-desktop-link">Giới thiệu</a></li>
          <li class="nav-item-has-sub">
            <a href="#cong-trinh-thuc-te" class="nav-desktop-link">
              <span>Công trình thực tế</span>
              <i class="fa-solid fa-chevron-down text-[9px]"></i>
            </a>
            <div class="nav-dropdown">
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')">Khách sạn – Căn hộ – Phòng trọ</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')">Biệt thự</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')">Nhà phố</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')">Văn phòng</a>
            </div>
          </li>
          <li class="nav-item-has-sub">
            <a href="#linh-vuc" class="nav-desktop-link">
              <span>Lĩnh vực hoạt động</span>
              <i class="fa-solid fa-chevron-down text-[9px]"></i>
            </a>
            <div class="nav-dropdown">
              <a href="#linh-vuc">Thiết kế Kiến trúc – Nội thất</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('phan-tho')">Thi công phần thô</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')">Thi công hoàn thiện</a>
              <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('noi-that')">Thi công nội thất</a>
            </div>
          </li>
          <li><a href="#du-an-da-nang" class="nav-desktop-link">Dự án Đà Nẵng</a></li>
          <li><a href="#bao-gia" class="nav-desktop-link">Báo giá</a></li>
          <li><a href="#tin-tuc" class="nav-desktop-link">Tin tức</a></li>
          <li><a href="#lien-he" class="nav-desktop-link">Liên hệ</a></li>
        </ul>
      </nav>

      <!-- Nút mở Menu trên Điện thoại / Tablet -->
      <button type="button" id="mobileMenuOpenBtn" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-gray-200 text-brandNavy hover:border-brandGold hover:text-brandGold transition" aria-label="Mở menu điều hướng">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>
  </header>

  <!-- Menu Trượt Mobile chuẩn Flatsome Off-Canvas -->
  <div id="mobileDrawerBackdrop" class="fixed inset-0 bg-black/50 z-[80] hidden transition-opacity"></div>
  <aside id="mobileDrawer" class="fixed top-0 right-0 h-full w-[285px] max-w-[85vw] bg-white z-[90] transform translate-x-full transition-transform duration-300 shadow-2xl flex flex-col">
    <div class="flex items-center justify-between px-4 py-3.5 border-b border-gray-200 bg-brandNavy text-white">
      <span class="font-bold text-sm tracking-wide">DANH MỤC MAY VĂN</span>
      <button type="button" id="mobileMenuCloseBtn" class="w-8 h-8 rounded-md flex items-center justify-center bg-white/10 hover:bg-white/20 text-white" aria-label="Đóng menu">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <div class="flex-1 overflow-y-auto py-3 px-4">
      <ul class="space-y-1 text-sm font-semibold text-brandNavy">
        <li><a href="#trang-chu" class="mobile-nav-link block py-2.5 border-b border-gray-100">Trang chủ</a></li>
        <li><a href="#gioi-thieu" class="mobile-nav-link block py-2.5 border-b border-gray-100">Giới thiệu công ty</a></li>
        <li><a href="#linh-vuc" class="mobile-nav-link block py-2.5 border-b border-gray-100">Lĩnh vực hoạt động</a></li>
        <li><a href="#cong-trinh-thuc-te" class="mobile-nav-link block py-2.5 border-b border-gray-100">Công trình thực tế</a></li>
        <li class="pl-3 space-y-1 pb-2 border-b border-gray-100 text-xs font-medium text-gray-600">
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')" class="mobile-nav-link block py-1.5">• Khách sạn – Căn hộ – Phòng trọ</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')" class="mobile-nav-link block py-1.5">• Biệt thự</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="mobile-nav-link block py-1.5">• Nhà phố</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')" class="mobile-nav-link block py-1.5">• Văn phòng</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('phan-tho')" class="mobile-nav-link block py-1.5">• Thi công phần thô</a>
          <a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('noi-that')" class="mobile-nav-link block py-1.5">• Thi công nội thất</a>
        </li>
        <li><a href="#du-an-da-nang" class="mobile-nav-link block py-2.5 border-b border-gray-100">Dự án tại Đà Nẵng</a></li>
        <li><a href="#doi-tac" class="mobile-nav-link block py-2.5 border-b border-gray-100">Đối tác chiến lược</a></li>
        <li><a href="#bao-gia" class="mobile-nav-link block py-2.5 border-b border-gray-100">Yêu cầu báo giá</a></li>
        <li><a href="#tin-tuc" class="mobile-nav-link block py-2.5 border-b border-gray-100">Tin tức &amp; Cẩm nang</a></li>
        <li><a href="#lien-he" class="mobile-nav-link block py-2.5">Liên hệ &amp; Bản đồ</a></li>
      </ul>
      <div class="mt-5 p-3.5 rounded-lg bg-brandBg border border-gray-200 text-xs text-gray-700 space-y-1.5">
        <div class="font-bold text-brandNavy">CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN</div>
        <div><i class="fa-solid fa-location-dot text-brandGold mr-1.5"></i>74 Hồ Phi Tích, Hòa Xuân, TP Đà Nẵng</div>
        <div><i class="fa-solid fa-phone text-brandGold mr-1.5"></i>0916.143.477</div>
      </div>
    </div>
  </aside>

  <!-- ========================================================================
       3. HERO SLIDER - 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU, CHỮ NẰM GỌN BÊN TRONG
       ======================================================================== -->
  <section id="trang-chu" class="hero-slider-wrap">
    <div id="heroSlidesTrack" class="hero-slides-track">

      <!-- Banner 1 -->
      <div class="hero-slide">
        <img
          src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1400"
          alt="Thiết kế và thi công xây dựng trọn gói May Văn"
          class="hero-slide-bg"
          onerror="handleImgFallback(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 'MAY VAN DESIGN & BUILD')"
        >
        <div class="hero-slide-overlay"></div>
        <div class="hero-safe-box">
          <div class="max-w-2xl text-white">
            <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-widest uppercase text-brandGoldLight mb-2">
              CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN
            </p>
            <h1 class="text-[20px] sm:text-[28px] md:text-[36px] lg:text-[42px] font-extrabold leading-[1.22] mb-3">
              KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG &amp; ĐẲNG CẤP TẠI ĐÀ NẴNG
            </h1>
            <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed mb-5 max-w-xl">
              Chuyên tư vấn thiết kế kiến trúc, thi công phần thô, hoàn thiện nội thất và xây nhà trọn gói theo tiêu chuẩn kỹ thuật nghiêm ngặt.
            </p>
            <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
              <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brandGold hover:bg-brandGoldLight text-brandNavy font-bold text-xs sm:text-sm transition">
                Nhận Báo Giá Miễn Phí
              </a>
              <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg border border-white/60 hover:border-brandGoldLight hover:text-brandGoldLight text-white font-semibold text-xs sm:text-sm transition">
                Xem Dự Án Đà Nẵng
              </a>
            </div>
          </div>
        </div>
      </div>

      <!-- Banner 2 -->
      <div class="hero-slide">
        <img
          src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
          alt="Thi công công trình thực tế nhà phố biệt thự Đà Nẵng"
          class="hero-slide-bg"
          onerror="handleImgFallback(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 'CONG TRINH DA NANG')"
        >
        <div class="hero-slide-overlay"></div>
        <div class="hero-safe-box">
          <div class="max-w-2xl text-white">
            <p class="text-[11px] sm:text-xs md:text-sm font-semibold tracking-widest uppercase text-brandGoldLight mb-2">
              AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ – MINH BẠCH CHI PHÍ
            </p>
            <h2 class="text-[20px] sm:text-[28px] md:text-[36px] lg:text-[42px] font-extrabold leading-[1.22] mb-3">
              GIẢI PHÁP THIẾT KẾ &amp; XÂY NHÀ TRỌN GÓI CHÌA KHÓA TRAO TAY
            </h2>
            <p class="text-xs sm:text-sm md:text-base text-white/90 leading-relaxed mb-5 max-w-xl">
              Đồng hành cùng chủ đầu tư từ bản vẽ ý tưởng, xin phép xây dựng đến hoàn thiện Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng.
            </p>
            <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
              <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg bg-brandGold hover:bg-brandGoldLight text-brandNavy font-bold text-xs sm:text-sm transition">
                Công Trình Thực Tế
              </a>
              <a href="tel:0916143477" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 rounded-lg border border-white/60 hover:border-brandGoldLight hover:text-brandGoldLight text-white font-semibold text-xs sm:text-sm transition">
                Tư Vấn: 0916.143.477
              </a>
            </div>
          </div>
        </div>
      </div>

    </div>

    <!-- Nút chuyển Banner Trái / Phải đặt sát mép gọn gàng -->
    <button type="button" id="prevBannerBtn" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brandGold text-white hover:text-brandNavy flex items-center justify-center transition">
      <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
    </button>
    <button type="button" id="nextBannerBtn" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-10 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brandGold text-white hover:text-brandNavy flex items-center justify-center transition">
      <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
    </button>

    <!-- Dấu chấm chỉ thị vị trí 2 Banner -->
    <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-10 flex items-center gap-2">
      <button type="button" data-slide="0" class="banner-dot w-7 h-2 rounded-full bg-brandGold transition-all" aria-label="Chuyển tới banner 1"></button>
      <button type="button" data-slide="1" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all" aria-label="Chuyển tới banner 2"></button>
    </div>
  </section>

  <!-- ========================================================================
       4. DỊCH VỤ TIÊU BIỂU (3 KHỐI GIỐNG BỐ CỤC MẪU TINTRUONGTHINH.COM)
       ======================================================================== -->
  <section id="linh-vuc" class="py-10 md:py-14 bg-white">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Dịch Vụ Tiêu Biểu</h2>
        <div class="ux-divider"></div>
      </div>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-4 md:gap-6">
        <!-- Dịch vụ 1 -->
        <div class="rounded-xl border border-gray-200 bg-brandBg p-6 text-center hover:border-brandGold hover:shadow-lg transition">
          <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brandNavy text-brandGoldLight flex items-center justify-center text-2xl">
            <i class="fa-solid fa-compass-drafting"></i>
          </div>
          <h3 class="text-base md:text-lg font-extrabold text-brandNavy uppercase mb-2">Thiết Kế Kiến Trúc</h3>
          <p class="text-sm text-gray-600 leading-relaxed mb-4">
            Thiết kế nhà phố, biệt thự, khách sạn, căn hộ, văn phòng chuẩn công năng, tối ưu ánh sáng, thông gió tự nhiên và thẩm mỹ hiện đại.
          </p>
          <a href="#bao-gia" class="inline-flex items-center gap-1.5 text-xs font-bold uppercase text-brandGold hover:text-brandNavy transition">
            <span>Nhận tư vấn thiết kế</span>
            <i class="fa-solid fa-arrow-right text-[11px]"></i>
          </a>
        </div>

        <!-- Dịch vụ 2 -->
        <div class="rounded-xl border border-gray-200 bg-brandBg p-6 text-center hover:border-brandGold hover:shadow-lg transition">
          <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brandNavy text-brandGoldLight flex items-center justify-center text-2xl">
            <i class="fa-solid fa-helmet-safety"></i>
          </div>
          <h3 class="text-base md:text-lg font-extrabold text-brandNavy uppercase mb-2">Thi Công Xây Dựng</h3>
          <p class="text-sm text-gray-600 leading-relaxed mb-4">
            Thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay. Giám sát kỹ sư trực tiếp tại công trình, vật tư chính hãng.
          </p>
          <a href="#cong-trinh-thuc-te" class="inline-flex items-center gap-1.5 text-xs font-bold uppercase text-brandGold hover:text-brandNavy transition">
            <span>Xem công trình thực tế</span>
            <i class="fa-solid fa-arrow-right text-[11px]"></i>
          </a>
        </div>

        <!-- Dịch vụ 3 -->
        <div class="rounded-xl border border-gray-200 bg-brandBg p-6 text-center hover:border-brandGold hover:shadow-lg transition">
          <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brandNavy text-brandGoldLight flex items-center justify-center text-2xl">
            <i class="fa-solid fa-couch"></i>
          </div>
          <h3 class="text-base md:text-lg font-extrabold text-brandNavy uppercase mb-2">Thiết Kế &amp; Thi Công Nội Thất</h3>
          <p class="text-sm text-gray-600 leading-relaxed mb-4">
            Hoàn thiện nội thất đồng bộ từ phòng khách, bếp, phòng ngủ đến không gian thương mại, đảm bảo sắc nét từng đường nét và bền đẹp dài lâu.
          </p>
          <a href="#bao-gia" class="inline-flex items-center gap-1.5 text-xs font-bold uppercase text-brandGold hover:text-brandNavy transition">
            <span>Nhận báo giá nội thất</span>
            <i class="fa-solid fa-arrow-right text-[11px]"></i>
          </a>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       5. GIỚI THIỆU CÔNG TY & THẾ MẠNH CỦA MAY VĂN (CHUẨN BỐ CỤC FLATSOME)
       ======================================================================== -->
  <section id="gioi-thieu" class="py-10 md:py-14 bg-brandBg border-y border-gray-200">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 md:gap-8 items-center mb-10">
        <div class="lg:col-span-6">
          <div class="rounded-xl overflow-hidden shadow-md border border-gray-200 aspect-[16/10] bg-gray-200">
            <img
              src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1200"
              alt="Đội ngũ thi công Công ty TNHH Tư Vấn Thiết Kế & Xây Dựng May Văn"
              class="w-full h-full object-cover"
              onerror="handleImgFallback(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 'MAY VAN CONSTRUCTION')"
            >
          </div>
        </div>
        <div class="lg:col-span-6">
          <p class="text-xs font-bold uppercase tracking-wider text-brandGold mb-2">Về Chúng Tôi</p>
          <h2 class="text-xl md:text-2xl font-extrabold text-brandNavy leading-snug mb-3">
            CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN
          </h2>
          <p class="text-sm text-gray-700 leading-relaxed mb-3">
            <strong>MAY VĂN</strong> là đơn vị chuyên sâu trong lĩnh vực <strong>Tư vấn Thiết kế Kiến trúc – Nội thất và Thi công Xây dựng</strong> các công trình Nhà phố, Biệt thự, Căn hộ cho thuê, Khách sạn và Văn phòng tại khu vực <strong>Đà Nẵng – Quảng Nam</strong> và miền Trung.
          </p>
          <p class="text-sm text-gray-700 leading-relaxed mb-4">
            Với phương châm đặt chữ <strong>“TÂM”</strong> và tiêu chuẩn kỹ thuật lên hàng đầu, mỗi công trình do May Văn thực hiện đều đảm bảo 4 giá trị cốt lõi: <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – CHI PHÍ HỢP LÝ</strong>. Chúng tôi cung cấp giải pháp trọn gói từ tư vấn phương án, hồ sơ bản vẽ thi công đến bàn giao chìa khóa trao tay.
          </p>
          <div class="grid grid-cols-3 gap-3 pt-2">
            <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
              <div class="text-lg md:text-2xl font-extrabold text-brandNavy">100%</div>
              <div class="text-[11px] text-gray-600 font-medium mt-0.5">Kỹ sư giám sát</div>
            </div>
            <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
              <div class="text-lg md:text-2xl font-extrabold text-brandGold">5+ Năm</div>
              <div class="text-[11px] text-gray-600 font-medium mt-0.5">Phát triển bền vững</div>
            </div>
            <div class="bg-white rounded-lg p-3 border border-gray-200 text-center">
              <div class="text-lg md:text-2xl font-extrabold text-brandNavy">24/7</div>
              <div class="text-[11px] text-gray-600 font-medium mt-0.5">Tư vấn &amp; Bảo hành</div>
            </div>
          </div>
        </div>
      </div>

      <!-- 6 Thế mạnh nổi bật giống web mẫu -->
      <div class="ux-section-title">
        <h2>Thế Mạnh Của Chúng Tôi</h2>
        <div class="ux-divider"></div>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4">
        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-users-gear"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Đội ngũ KTS &amp; Kỹ sư chuyên nghiệp</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Kiến trúc sư sáng tạo kết hợp đội ngũ kỹ sư kết cấu giàu kinh nghiệm và thợ thi công lành nghề.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-layer-group"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Cập nhật xu hướng kiến trúc mới</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Ứng dụng vật liệu bền vững, giải pháp chống nóng và bố trí không gian tối ưu khí hậu miền Trung.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-clipboard-check"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Giám sát tiến độ chuẩn xác</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Báo cáo hình ảnh thi công hằng ngày giúp chủ đầu tư dễ dàng theo dõi chất lượng từ xa.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Bảo hành công trình lâu dài</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Cam kết bảo hành kết cấu dài hạn và bảo trì nhanh chóng, hỗ trợ tận tâm sau bàn giao.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-file-invoice-dollar"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Dự toán minh bạch – Không phát sinh</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Bóc tách khối lượng rõ ràng từng hạng mục, chủng loại vật tư cụ thể ngay từ khi ký hợp đồng.</p>
          </div>
        </div>

        <div class="bg-white rounded-xl p-5 border border-gray-200 flex items-start gap-3.5">
          <div class="w-10 h-10 rounded-lg bg-brandNavy/10 text-brandNavy flex items-center justify-center shrink-0 text-lg">
            <i class="fa-solid fa-headset"></i>
          </div>
          <div>
            <h3 class="text-sm font-bold text-brandNavy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h3>
            <p class="text-xs text-gray-600 leading-relaxed">Tư vấn pháp lý xây dựng, quy hoạch, phong thủy và sơ bộ chi phí hoàn toàn miễn phí.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       6. CÔNG TRÌNH THỰC TẾ & SẢN PHẨM THI CÔNG (9 ẢNH THỰC TẾ GOOGLE DRIVE)
          - Danh mục lấy theo web mẫu tintruongthinh.com
          - Chữ danh mục nhỏ gọn, viết liền không xuống dòng tên danh mục
          - Mobile chia đúng 2 cột, tên sản phẩm không tràn/thiếu chữ, không nhãn dán
       ======================================================================== -->
  <section id="cong-trinh-thuc-te" class="py-10 md:py-14 bg-white">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Công Trình Thực Tế &amp; Hạng Mục Thi Công</h2>
        <div class="ux-divider"></div>
      </div>

      <!-- Thanh lọc danh mục trang chủ (nhỏ gọn, đẹp trên máy tính & điện thoại) -->
      <div id="categoryFilterBar" class="cat-filter-bar mb-6">
        <button type="button" class="cat-filter-btn active" data-cat="all">Tất cả</button>
        <button type="button" class="cat-filter-btn" data-cat="khach-san-can-ho">Khách sạn – Căn hộ</button>
        <button type="button" class="cat-filter-btn" data-cat="biet-thu">Biệt thự</button>
        <button type="button" class="cat-filter-btn" data-cat="nha-pho">Nhà phố</button>
        <button type="button" class="cat-filter-btn" data-cat="van-phong">Văn phòng</button>
        <button type="button" class="cat-filter-btn" data-cat="phan-tho">Thi công phần thô</button>
        <button type="button" class="cat-filter-btn" data-cat="noi-that">Thi công nội thất</button>
      </div>

      <!-- Lưới sản phẩm/công trình: 2 cột trên điện thoại, 3 cột trên máy tính -->
      <div id="constructionGrid" class="grid grid-cols-2 lg:grid-cols-3 gap-2.5 sm:gap-4 md:gap-5">
        <!-- Dữ liệu được render tự động từ JS bên dưới để hỗ trợ lọc danh mục mượt mà -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       7. DANH MỤC CÁC DỰ ÁN TIÊU BIỂU Ở ĐÀ NẴNG (10 ẢNH DỰ ÁN GOOGLE DRIVE)
          - Mobile chia 2 cột đều đẹp, Máy tính chia 5 cột (2 hàng cân đối)
       ======================================================================== -->
  <section id="du-an-da-nang" class="py-10 md:py-14 bg-brandBg border-y border-gray-200">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Các Dự Án Tiêu Biểu Tại Đà Nẵng</h2>
        <div class="ux-divider"></div>
        <p class="text-xs sm:text-sm text-gray-600 mt-2.5 max-w-2xl mx-auto">
          Tổng hợp các công trình thiết kế và thi công xây dựng do Công ty May Văn triển khai thực tế tại Hòa Xuân, Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn và các khu đô thị Đà Nẵng.
        </p>
      </div>

      <div id="danangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-2.5 sm:gap-4">
        <!-- Render 10 dự án Đà Nẵng từ JS -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       8. DANH MỤC CÁC ĐỐI TÁC & NHÀ CUNG CẤP VẬT TƯ CHIẾN LƯỢC
       ======================================================================== -->
  <section id="doi-tac" class="py-10 md:py-12 bg-white">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Đối Tác &amp; Nhà Cung Cấp Vật Tư</h2>
        <div class="ux-divider"></div>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-8 gap-3">
        <!-- 8 đối tác uy tín trong ngành xây dựng Việt Nam -->
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">HÒA PHÁT</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Thép xây dựng</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">SÔNG GIANH</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Xi măng PCB40</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">DULUX</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Sơn nội ngoại thất</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">TOTO</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Thiết bị vệ sinh</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">XINGFA</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Nhôm kính cao cấp</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">CADIVI</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Hệ thống dây điện</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">AN CƯỜNG</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Vật liệu gỗ nội thất</div>
        </div>
        <div class="rounded-lg border border-gray-200 bg-brandBg px-3 py-4 flex flex-col items-center justify-center text-center hover:border-brandGold transition">
          <div class="font-extrabold text-sm text-brandNavy tracking-tight">BÌNH MINH</div>
          <div class="text-[10px] text-gray-500 mt-0.5">Ống cấp thoát nước</div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY TRANG CHỦ (CHUẨN WEB MẪU)
       ======================================================================== -->
  <section id="bao-gia" class="py-10 md:py-14 bg-brandNavy text-white">
    <div class="ux-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 md:gap-8 items-center">
        <!-- Cột thông tin cam kết báo giá -->
        <div class="lg:col-span-5 space-y-4">
          <p class="text-xs font-bold uppercase tracking-widest text-brandGoldLight">Miễn Phí Tư Vấn &amp; Khảo Sát</p>
          <h2 class="text-2xl md:text-3xl font-extrabold leading-tight">
            ĐĂNG KÝ NHẬN BÁO GIÁ THIẾT KẾ &amp; XÂY DỰNG
          </h2>
          <p class="text-sm text-white/85 leading-relaxed">
            Gửi thông tin nhu cầu công trình của quý khách, đội ngũ kỹ sư <strong>May Văn</strong> sẽ liên hệ khảo sát thực tế, tư vấn phương án tối ưu và gửi bảng dự toán chi tiết trong vòng 24 giờ.
          </p>
          <div class="space-y-2.5 pt-2 text-sm text-white/90">
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-brandGoldLight"></i>
              <span>Báo giá thiết kế kiến trúc – nội thất chuẩn công năng</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-brandGoldLight"></i>
              <span>Báo giá thi công phần thô &amp; nhân công hoàn thiện</span>
            </div>
            <div class="flex items-center gap-2.5">
              <i class="fa-solid fa-check-circle text-brandGoldLight"></i>
              <span>Báo giá xây nhà trọn gói chìa khóa trao tay tại Đà Nẵng</span>
            </div>
          </div>
          <div class="pt-2">
            <a href="tel:0916143477" class="inline-flex items-center gap-2 text-brandGoldLight font-bold text-base hover:underline">
              <i class="fa-solid fa-phone-volume"></i>
              <span>Hotline tư vấn trực tiếp: 0916.143.477</span>
            </a>
          </div>
        </div>

        <!-- Cột Form điền yêu cầu -->
        <div class="lg:col-span-7">
          <form id="quoteForm" class="bg-white text-brandText rounded-xl p-5 sm:p-7 shadow-xl space-y-4">
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qName" class="block text-xs font-bold text-brandNavy mb-1.5">Họ và tên *</label>
                <input type="text" id="qName" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brandGold">
              </div>
              <div>
                <label for="qPhone" class="block text-xs font-bold text-brandNavy mb-1.5">Số điện thoại / Zalo *</label>
                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0916 143 477" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brandGold">
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qType" class="block text-xs font-bold text-brandNavy mb-1.5">Loại công trình</label>
                <select id="qType" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg bg-white focus:outline-none focus:border-brandGold">
                  <option value="Nhà phố">Nhà phố</option>
                  <option value="Biệt thự">Biệt thự</option>
                  <option value="Khách sạn - Căn hộ - Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                  <option value="Văn phòng - Showroom">Văn phòng – Showroom</option>
                  <option value="Thi công nội thất">Thi công nội thất</option>
                  <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                </select>
              </div>
              <div>
                <label for="qBudget" class="block text-xs font-bold text-brandNavy mb-1.5">Mức đầu tư dự kiến</label>
                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg bg-white focus:outline-none focus:border-brandGold">
                  <option value="Chưa xác định">Chưa xác định</option>
                  <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                  <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                  <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                  <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                  <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                </select>
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="qEmail" class="block text-xs font-bold text-brandNavy mb-1.5">Email (nếu có)</label>
                <input type="email" id="qEmail" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brandGold">
              </div>
              <div>
                <label for="qArea" class="block text-xs font-bold text-brandNavy mb-1.5">Diện tích &amp; Địa điểm xây dựng</label>
                <input type="text" id="qArea" placeholder="VD: 5x20m, 3 tầng, Hòa Xuân" class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brandGold">
              </div>
            </div>

            <div>
              <label for="qNote" class="block text-xs font-bold text-brandNavy mb-1.5">Nội dung yêu cầu chi tiết</label>
              <textarea id="qNote" rows="3" placeholder="Mô tả sơ bộ nhu cầu thiết kế, thi công phần thô hoặc xây nhà trọn gói..." class="w-full px-3.5 py-2.5 text-sm border border-gray-300 rounded-lg focus:outline-none focus:border-brandGold"></textarea>
            </div>

            <!-- Hộp thông báo phản hồi ngay trên form (không dùng alert) -->
            <div id="quoteFeedback" class="hidden rounded-lg p-3.5 text-sm font-medium"></div>

            <button type="submit" class="w-full py-3 rounded-lg bg-brandGold hover:bg-brandNavy text-brandNavy hover:text-white font-extrabold text-sm uppercase tracking-wide transition cursor-pointer">
              Gửi Yêu Cầu Tư Vấn &amp; Báo Giá
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       10. DANH MỤC CÁC BÀI VIẾT / TIN TỨC XÂY DỰNG TRANG CHỦ
       ======================================================================== -->
  <section id="tin-tuc" class="py-10 md:py-14 bg-white">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Tin Tức &amp; Cẩm Nang Xây Dựng</h2>
        <div class="ux-divider"></div>
      </div>

      <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-2.5 sm:gap-4 md:gap-5">
        <!-- Render 4 bài viết cẩm nang từ JS -->
      </div>
    </div>
  </section>

  <!-- ========================================================================
       11. FANPAGE FACEBOOK & GOOGLE MAP NGAY TRANG CHỦ
       ======================================================================== -->
  <section id="lien-he" class="py-10 md:py-14 bg-brandBg border-t border-gray-200">
    <div class="ux-container">
      <div class="ux-section-title">
        <h2>Kết Nối Fanpage &amp; Chỉ Đường Văn Phòng</h2>
        <div class="ux-divider"></div>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
        <!-- Cột Facebook: https://www.facebook.com/thinhvaneng/ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <div class="flex items-center justify-between gap-2 pb-3 mb-3 border-b border-gray-100">
              <div class="flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-lg bg-[#1877F2] text-white flex items-center justify-center text-lg shrink-0">
                  <i class="fa-brands fa-facebook-f"></i>
                </div>
                <div>
                  <h3 class="text-sm font-extrabold text-brandNavy">Fanpage Facebook Chính Thức</h3>
                  <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="text-xs text-[#1877F2] hover:underline break-all">
                    facebook.com/thinhvaneng
                  </a>
                </div>
              </div>
              <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-md bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold shrink-0 transition">
                Theo dõi
              </a>
            </div>

            <!-- Nhúng trực tiếp Facebook Page Plugin -->
            <div class="w-full overflow-hidden rounded-lg border border-gray-200 bg-gray-50">
              <iframe
                title="Fanpage Facebook Xây Dựng May Văn - thinhvaneng"
                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fthinhvaneng%2F&tabs=timeline&width=500&height=340&small_header=false&adapt_container_width=true&hide_cover=false&show_facepile=true"
                width="100%"
                height="340"
                style="border:none; overflow:hidden; display:block;"
                scrolling="no"
                frameborder="0"
                allowfullscreen="true"
                loading="lazy"
                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"
              ></iframe>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
            <span>Cập nhật nhật ký thi công thực tế hằng ngày</span>
            <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="font-bold text-brandNavy hover:text-brandGold transition">
              Mở trang Facebook <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
            </a>
          </div>
        </div>

        <!-- Cột Google Map: 74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-gray-200 p-4 sm:p-5 flex flex-col justify-between">
          <div>
            <div class="flex flex-wrap items-center justify-between gap-2 pb-3 mb-3 border-b border-gray-100">
              <div class="flex items-center gap-2.5">
                <div class="w-9 h-9 rounded-lg bg-brandNavy text-brandGoldLight flex items-center justify-center text-lg shrink-0">
                  <i class="fa-solid fa-map-location-dot"></i>
                </div>
                <div>
                  <h3 class="text-sm font-extrabold text-brandNavy">Bản Đồ Văn Phòng Công Ty May Văn</h3>
                  <p class="text-xs text-gray-600">74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng</p>
                </div>
              </div>
              <a href="https://www.google.com/maps/search/?api=1&query=74+H%E1%BB%93+Phi+T%C3%ADch,+Ph%C6%B0%E1%BB%9Dng+H%C3%B2a+Xu%C3%A2n,+TP+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded-md bg-brandNavy hover:bg-brandGold text-white hover:text-brandNavy text-xs font-bold shrink-0 transition">
                Chỉ đường Google Maps
              </a>
            </div>

            <!-- Nhúng bản đồ Google Maps trực quan -->
            <div class="w-full overflow-hidden rounded-lg border border-gray-200">
              <iframe
                title="Bản đồ 74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng"
                src="https://maps.google.com/maps?q=74+H%E1%BB%93+Phi+T%C3%ADch,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                width="100%"
                height="340"
                style="border:0; display:block;"
                allowfullscreen=""
                loading="lazy"
                referrerpolicy="no-referrer-when-downgrade"
              ></iframe>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2 text-xs text-gray-600">
            <span><i class="fa-solid fa-clock text-brandGold mr-1"></i>Giờ làm việc: Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
            <span><i class="fa-solid fa-phone text-brandGold mr-1"></i>Hotline: <strong class="text-brandNavy">0916.143.477</strong></span>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ========================================================================
       12. FOOTER CHUẨN FLATSOME ĐỒNG BỘ MÀU LOGO
       ======================================================================== -->
  <footer class="bg-brandNavy text-white/85 pt-12 pb-6">
    <div class="ux-container">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/15">
        <!-- Cột 1: Thông tin công ty -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-2.5">
            <svg width="36" height="36" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" class="shrink-0">
              <rect width="64" height="64" rx="10" fill="#1A3E63"/>
              <path d="M11 48V24.5L32 9.5L53 24.5V48H45.5V28.2L32 18.5L18.5 28.2V48H11Z" fill="#D4A745"/>
              <path d="M23.5 48V30.5L32 40.5L40.5 30.5V48H35.2V39.2L32 43L28.8 39.2V48H23.5Z" fill="#FFFFFF"/>
              <rect x="11" y="51" width="42" height="3.5" rx="1.75" fill="#D4A745"/>
            </svg>
            <div>
              <div class="font-extrabold text-white text-sm sm:text-base leading-tight">
                CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN
              </div>
              <div class="text-[11px] text-brandGoldLight font-semibold">xaydungmayvan.com</div>
            </div>
          </div>

          <ul class="space-y-2 text-xs sm:text-sm text-white/80 pt-1">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-location-dot text-brandGoldLight mt-1 shrink-0"></i>
              <span><strong>Trụ sở:</strong> 74 Hồ Phi Tích, Phường Hòa Xuân, TP Đà Nẵng</span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-phone text-brandGoldLight shrink-0"></i>
              <span><strong>Hotline / Zalo:</strong> <a href="tel:0916143477" class="hover:text-brandGoldLight">0916.143.477</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-globe text-brandGoldLight shrink-0"></i>
              <span><strong>Website:</strong> <a href="https://xaydungmayvan.com" class="hover:text-brandGoldLight">xaydungmayvan.com</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-brands fa-facebook text-brandGoldLight shrink-0"></i>
              <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="hover:text-brandGoldLight">facebook.com/thinhvaneng</a></span>
            </li>
            <li class="flex items-center gap-2">
              <i class="fa-solid fa-building-shield text-brandGoldLight shrink-0"></i>
              <span><strong>Mã số thuế:</strong> 0402094230</span>
            </li>
          </ul>
        </div>

        <!-- Cột 2: Lĩnh vực hoạt động -->
        <div class="lg:col-span-3">
          <h4 class="text-sm font-extrabold uppercase text-brandGoldLight mb-3.5 tracking-wide">Lĩnh Vực Hoạt Động</h4>
          <ul class="space-y-2 text-xs sm:text-sm">
            <li><a href="#linh-vuc" class="hover:text-brandGoldLight transition">Thiết kế kiến trúc – nội thất</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('phan-tho')" class="hover:text-brandGoldLight transition">Thi công phần thô chuẩn kỹ thuật</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="hover:text-brandGoldLight transition">Thi công hoàn thiện trọn gói</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('noi-that')" class="hover:text-brandGoldLight transition">Thiết kế &amp; thi công nội thất</a></li>
            <li><a href="#bao-gia" class="hover:text-brandGoldLight transition">Tư vấn cải tạo &amp; sửa chữa nhà</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục công trình -->
        <div class="lg:col-span-4">
          <h4 class="text-sm font-extrabold uppercase text-brandGoldLight mb-3.5 tracking-wide">Danh Mục Công Trình</h4>
          <ul class="grid grid-cols-2 gap-x-4 gap-y-2 text-xs sm:text-sm">
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('nha-pho')" class="hover:text-brandGoldLight transition">Nhà phố hiện đại</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('biet-thu')" class="hover:text-brandGoldLight transition">Biệt thự cao cấp</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('khach-san-can-ho')" class="hover:text-brandGoldLight transition">Khách sạn – Căn hộ</a></li>
            <li><a href="#cong-trinh-thuc-te" onclick="selectCategoryFromNav('van-phong')" class="hover:text-brandGoldLight transition">Văn phòng làm việc</a></li>
            <li><a href="#du-an-da-nang" class="hover:text-brandGoldLight transition">Dự án tại Đà Nẵng</a></li>
            <li><a href="#tin-tuc" class="hover:text-brandGoldLight transition">Cẩm nang xây dựng</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-white/60">
        <div>Copyright 2026 &copy; CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN.</div>
        <div>Thiết kế chuẩn UX Builder – xaydungmayvan.com</div>
      </div>
    </div>
  </footer>

  <!-- ========================================================================
       13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
           - Máy tính: Cụm nút nổi gọn đẹp góc phải dưới
           - Điện thoại: Thanh cố định đáy màn hình 3 nút dễ chạm
       ======================================================================== -->
  <div class="floating-contact-desktop" aria-label="Liên hệ nhanh máy tính">
    <a href="https://zalo.me/0916143477" target="_blank" rel="noopener noreferrer" class="float-btn float-btn-zalo">
      <i class="fa-solid fa-comment-dots text-base"></i>
      <span>Chat Zalo</span>
    </a>
    <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="float-btn float-btn-fb">
      <i class="fa-brands fa-facebook-messenger text-base"></i>
      <span>Facebook</span>
    </a>
    <a href="tel:0916143477" class="float-btn float-btn-phone">
      <i class="fa-solid fa-phone-volume text-base"></i>
      <span>0916.143.477</span>
    </a>
  </div>

  <div class="mobile-bottom-bar" aria-label="Liên hệ nhanh điện thoại">
    <a href="https://zalo.me/0916143477" target="_blank" rel="noopener noreferrer" class="mobile-bar-btn" style="background:#0068FF;">
      <i class="fa-solid fa-comment-dots"></i>
      <span>Zalo</span>
    </a>
    <a href="https://www.facebook.com/thinhvaneng/" target="_blank" rel="noopener noreferrer" class="mobile-bar-btn" style="background:#1877F2;">
      <i class="fa-brands fa-facebook-f"></i>
      <span>Facebook</span>
    </a>
    <a href="tel:0916143477" class="mobile-bar-btn" style="background:#0F2A44;">
      <i class="fa-solid fa-phone"></i>
      <span>Hotline</span>
    </a>
  </div>

  <!-- ========================================================================
       14. MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH & ĐỌC BÀI VIẾT
       ======================================================================== -->
  <div id="detailModal" class="fixed inset-0 z-[100] hidden items-center justify-center bg-black/70 p-3 sm:p-5">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-gray-200">
      <div class="flex items-center justify-between px-4 py-3 border-b border-gray-200 sticky top-0 bg-white z-10">
        <h3 id="modalTitle" class="text-sm sm:text-base font-extrabold text-brandNavy pr-3">Chi tiết công trình</h3>
        <button type="button" id="closeModalBtn" class="w-8 h-8 rounded-lg bg-gray-100 hover:bg-brandNavy hover:text-white text-gray-700 flex items-center justify-center shrink-0 transition" aria-label="Đóng hộp thoại">
          <i class="fa-solid fa-xmark"></i>
        </button>
      </div>
      <div class="p-4 sm:p-5 space-y-4">
        <div class="w-full rounded-lg overflow-hidden bg-gray-100 border border-gray-200">
          <img id="modalImage" src="" alt="" class="w-full max-h-[420px] object-cover block">
        </div>
        <div id="modalMeta" class="text-xs font-semibold text-brandGold"></div>
        <div id="modalBody" class="text-sm text-gray-700 leading-relaxed space-y-2"></div>
        <div class="pt-3 border-t border-gray-100 flex flex-wrap items-center justify-between gap-2">
          <a href="#bao-gia" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg bg-brandGold hover:bg-brandNavy text-brandNavy hover:text-white text-xs font-bold uppercase transition">
            Nhận báo giá hạng mục này
          </a>
          <a href="tel:0916143477" class="px-4 py-2 rounded-lg border border-brandNavy text-brandNavy hover:bg-brandNavy hover:text-white text-xs font-bold transition">
            Gọi tư vấn: 0916.143.477
          </a>
        </div>
      </div>
    </div>
  </div>

  <!-- ========================================================================
       15. JAVASCRIPT XỬ LÝ TƯƠNG TÁC, DỮ LIỆU ẢNH DRIVE, SLIDER & FORM
       ======================================================================== -->
  <script>
    /* Hàm xử lý fallback ảnh Google Drive thông minh (ưu tiên ảnh gốc từ Drive) */
    function getDriveImgUrl(fileId) {
      return 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
    }

    function handleImgFallback(imgEl, fileId, fallbackText) {
      try {
        const step = parseInt(imgEl.getAttribute('data-fb-step') || '0', 10);
        if (step === 0) {
          imgEl.setAttribute('data-fb-step', '1');
          imgEl.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
        } else if (step === 1) {
          imgEl.setAttribute('data-fb-step', '2');
          imgEl.src = 'https://placehold.co/800x600/0F2A44/D4A745?text=' + encodeURIComponent(fallbackText || 'MAY VAN CONSTRUCTION');
        }
      } catch (err) {
        console.error('Lỗi tải ảnh dự phòng:', err);
      }
    }

    /* Dữ liệu 9 ảnh thực tế thi công xây dựng từ Google Drive đưa vào đúng danh mục mẫu */
    const constructionItems = [
      {
        id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        title: 'Thi công phần thô kết cấu khung bê tông cốt thép nhà phố',
        category: 'phan-tho',
        categoryLabel: 'Thi công phần thô',
        location: 'Hòa Xuân, Đà Nẵng',
        desc: 'Công tác thi công phần thô, lắp dựng cốt thép dầm sàn và đổ bê tông thương phẩm đúng mác thiết kế, đảm bảo độ bền vững lâu dài cho công trình.'
      },
      {
        id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        title: 'Thiết kế & thi công hoàn thiện nhà phố hiện đại 3 tầng',
        category: 'nha-pho',
        categoryLabel: 'Nhà phố',
        location: 'Quận Cẩm Lệ, Đà Nẵng',
        desc: 'Công trình nhà phố hiện đại hoàn thiện trọn gói mặt tiền thông thoáng, tối ưu công năng sử dụng và hệ thống chống thấm, chống nóng chuyên biệt.'
      },
      {
        id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
        title: 'Thi công xây dựng biệt thự phố sang trọng trọn gói',
        category: 'biet-thu',
        categoryLabel: 'Biệt thự',
        location: 'Nam Hòa Xuân, Đà Nẵng',
        desc: 'Biệt thự thiết kế theo phong cách hiện đại với hình khối vững chắc, vật tư hoàn thiện cao cấp và không gian sân vườn hài hòa.'
      },
      {
        id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
        title: 'Thi công trọn gói tòa nhà căn hộ cho thuê cao cấp',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ',
        location: 'Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Giải pháp thiết kế và thi công tòa nhà căn hộ tối ưu số lượng phòng khai thác, hệ thống cơ điện MEP an toàn và hoàn thiện đúng tiến độ.'
      },
      {
        id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        title: 'Thiết kế & thi công hoàn thiện nội thất phòng khách',
        category: 'noi-that',
        categoryLabel: 'Thi công nội thất',
        location: 'Hải Châu, Đà Nẵng',
        desc: 'Hoàn thiện không gian nội thất đồng bộ sử dụng vật liệu gỗ công nghiệp chống ẩm cao cấp, ánh sáng tinh tế và đường nét thi công sắc sảo.'
      },
      {
        id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
        title: 'Thi công hoàn thiện không gian văn phòng làm việc',
        category: 'van-phong',
        categoryLabel: 'Văn phòng',
        location: 'Trung tâm TP Đà Nẵng',
        desc: 'Thiết kế và thi công văn phòng chuyên nghiệp, tối ưu diện tích làm việc, hệ thống vách kính cách âm và điều hòa không khí hiện đại.'
      },
      {
        id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
        title: 'Nghiệm thu cốt thép & thi công phần thô móng băng',
        category: 'phan-tho',
        categoryLabel: 'Thi công phần thô',
        location: 'KĐT Hòa Xuân, Đà Nẵng',
        desc: 'Quy trình kiểm tra thép móng, khoảng cách đai thép và bảo dưỡng bê tông chặt chẽ dưới sự giám sát trực tiếp của kỹ sư May Văn.'
      },
      {
        id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
        title: 'Thi công nội thất phòng bếp & không gian sinh hoạt',
        category: 'noi-that',
        categoryLabel: 'Thi công nội thất',
        location: 'Quận Sơn Trà, Đà Nẵng',
        desc: 'Thi công lắp đặt hệ tủ bếp hiện đại, đá ốp chống bám bẩn và phụ kiện thông minh giúp không gian bếp luôn tiện nghi, gọn gàng.'
      },
      {
        id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
        title: 'Thi công khách sạn mini & lưu trú đạt chuẩn hiện đại',
        category: 'khach-san-can-ho',
        categoryLabel: 'Khách sạn – Căn hộ',
        location: 'Khu biển Mỹ Khê, Đà Nẵng',
        desc: 'Công trình khách sạn lưu trú được May Văn thiết kế tối ưu diện tích phòng, mặt tiền nổi bật và thi công trọn gói chìa khóa trao tay.'
      }
    ];

    /* Dữ liệu 10 ảnh dự án ở Đà Nẵng từ Google Drive */
    const danangProjects = [
      {
        id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        title: 'Nhà Phố Hiện Đại – KĐT Hòa Xuân, Đà Nẵng',
        area: 'Phường Hòa Xuân, TP Đà Nẵng',
        desc: 'Thiết kế và thi công trọn gói nhà phố hiện đại tại khu đô thị Hòa Xuân, tối ưu thông gió tự nhiên và ánh sáng giếng trời.'
      },
      {
        id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
        title: 'Biệt Thự Phố 3 Tầng – Nam Hòa Xuân, Đà Nẵng',
        area: 'Nam Hòa Xuân, Đà Nẵng',
        desc: 'Công trình biệt thự phố thiết kế tinh tế, kết cấu kiên cố và hoàn thiện vật liệu cao cấp theo yêu cầu chủ đầu tư.'
      },
      {
        id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
        title: 'Căn Hộ Dịch Vụ Cao Cấp – Ngũ Hành Sơn, Đà Nẵng',
        area: 'Quận Ngũ Hành Sơn, Đà Nẵng',
        desc: 'Thi công hoàn thiện tòa nhà căn hộ dịch vụ phục vụ khách du lịch và chuyên gia lưu trú dài ngày tại Đà Nẵng.'
      },
      {
        id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
        title: 'Nhà Phố 2 Mặt Tiền – Quận Cẩm Lệ, Đà Nẵng',
        area: 'Quận Cẩm Lệ, Đà Nẵng',
        desc: 'Giải pháp kiến trúc nhà phố 2 mặt tiền hiện đại kết hợp không gian ở tiện nghi và mặt bằng kinh doanh rộng rãi.'
      },
      {
        id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
        title: 'Khách Sạn Boutique – Quận Sơn Trà, Đà Nẵng',
        area: 'Quận Sơn Trà, Đà Nẵng',
        desc: 'Thiết kế kiến trúc và thi công trọn gói khách sạn boutique gần biển với phong cách trẻ trung, thu hút du khách.'
      },
      {
        id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
        title: 'Văn Phòng & Showroom – Quận Hải Châu, Đà Nẵng',
        area: 'Quận Hải Châu, Đà Nẵng',
        desc: 'Hoàn thiện công trình văn phòng kết hợp showroom trưng bày tại trung tâm TP Đà Nẵng với tiến độ thi công nhanh chóng.'
      },
      {
        id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
        title: 'Nhà Phố Kết Hợp Kinh Doanh – Hồ Phi Tích, Đà Nẵng',
        area: 'Hồ Phi Tích, Hòa Xuân, Đà Nẵng',
        desc: 'Công trình nhà phố kết hợp không gian dịch vụ hiện đại ngay khu vực trung tâm phường Hòa Xuân.'
      },
      {
        id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
        title: 'Hoàn Thiện Nội Thất Biệt Thự – KĐT Ven Sông Đà Nẵng',
        area: 'Ven Sông Hàn, Đà Nẵng',
        desc: 'Thi công hoàn thiện nội thất cao cấp đồng bộ phòng khách, bếp, phòng ngủ đảm bảo độ thẩm mỹ và bền bỉ vượt thời gian.'
      },
      {
        id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
        title: 'Nhà Ở Gia Đình Hiện Đại – Quận Thanh Khê, Đà Nẵng',
        area: 'Quận Thanh Khê, Đà Nẵng',
        desc: 'Thiết kế tối ưu diện tích đất phố, bố trí công năng khoa học cho gia đình đa thế hệ tại quận Thanh Khê.'
      },
      {
        id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
        title: 'Tòa Nhà Căn Hộ Cho Thuê – Khu Nam Việt Á, Đà Nẵng',
        area: 'Khu Nam Việt Á, Đà Nẵng',
        desc: 'Thi công phần thô và hoàn thiện trọn gói công trình căn hộ cho thuê với hệ thống kỹ thuật điện nước đồng bộ.'
      }
    ];

    /* Dữ liệu 4 bài viết cẩm nang trang chủ */
    const articlesData = [
      {
        imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
        date: '15/11/2026',
        title: 'Hướng dẫn bảo dưỡng bê tông móng và sàn đúng tiêu chuẩn kỹ thuật',
        excerpt: 'Bảo dưỡng bê tông đúng thời điểm giúp kết cấu đạt cường độ tối đa, hạn chế rạn nứt bề mặt và tăng tuổi thọ công trình.',
        content: 'Sau khi đổ bê tông móng, cột và sàn, công tác giữ ẩm liên tục trong 7 ngày đầu đóng vai trò quyết định đến chất lượng kết cấu. Đội ngũ kỹ sư May Văn luôn áp dụng quy trình tưới nước bảo dưỡng định kỳ, che phủ bề mặt tránh nắng gắt miền Trung và kiểm tra cường độ trước khi tháo cốp pha.'
      },
      {
        imgId: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
        date: '08/11/2026',
        title: 'Kinh nghiệm dự toán chi phí xây nhà trọn gói tại Đà Nẵng không phát sinh',
        excerpt: 'Cách lập kế hoạch tài chính, lựa chọn gói vật tư phù hợp và kiểm soát khối lượng minh bạch trước khi khởi công.',
        content: 'Để xây nhà trọn gói không phát sinh chi phí ngoài dự kiến, gia chủ cần hoàn thiện hồ sơ thiết kế chi tiết 3D và bản vẽ kỹ thuật trước khi thi công. May Văn luôn bóc tách rõ ràng chủng loại vật tư phần thô đến hoàn thiện, ký hợp đồng cam kết tiến độ và đơn giá cố định.'
      },
      {
        imgId: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
        date: '29/10/2026',
        title: 'Giải pháp thiết kế nội thất tối ưu ánh sáng và thông gió cho nhà phố',
        excerpt: 'Bố trí giếng trời, thông tầng và vật liệu phản xạ ánh sáng giúp ngôi nhà luôn mát mẻ, tiết kiệm năng lượng.',
        content: 'Nhà phố thường có đặc trưng hẹp ngang và sâu dài. Việc kết hợp giếng trời giữa nhà, sân sau thông thoáng và hệ cửa nhôm kính cao cấp giúp đối lưu không khí tự nhiên, giảm nhiệt độ mùa hè tại Đà Nẵng và mang lại không gian sống tràn đầy sinh khí.'
      },
      {
        imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
        date: '18/10/2026',
        title: 'Những lưu ý quan trọng về hồ sơ xin giấy phép xây dựng tại Đà Nẵng',
        excerpt: 'Chuẩn bị đầy đủ giấy tờ pháp lý, mật độ xây dựng và chỉ giới đường đỏ giúp quá trình khởi công diễn ra thuận lợi.',
        content: 'Trước khi khởi công xây dựng tại các khu vực như Hòa Xuân, Cẩm Lệ, Hải Châu hay Sơn Trà, chủ đầu tư cần nắm rõ quy định về mật độ xây dựng, độ vươn ban công và chiều cao tầng. Khi hợp tác xây nhà trọn gói cùng May Văn, chúng tôi hỗ trợ trọn gói thủ tục xin phép xây dựng nhanh gọn.'
      }
    ];

    /* Render danh sách Công trình thực tế theo danh mục (không dùng nhãn dán đè lên ảnh) */
    function renderConstructionItems(filterCat) {
      const grid = document.getElementById('constructionGrid');
      if (!grid) return;

      const filtered = filterCat === 'all'
        ? constructionItems
        : constructionItems.filter(item => item.category === filterCat);

      grid.innerHTML = filtered.map((item, idx) => `
        <article class="ux-card cursor-pointer" onclick="openProjectModal('construction', '${item.id}')">
          <div class="ux-card-thumb">
            <img
              src="${getDriveImgUrl(item.id)}"
              alt="${item.title}"
              loading="lazy"
              onerror="handleImgFallback(this, '${item.id}', 'CONG TRINH MAY VAN')"
            >
          </div>
          <div class="ux-card-body">
            <div>
              <h3 class="ux-card-title">${item.title}</h3>
              <p class="ux-card-sub">${item.categoryLabel} • ${item.location}</p>
            </div>
          </div>
        </article>
      `).join('');
    }

    /* Render 10 dự án tại Đà Nẵng */
    function renderDanangProjects() {
      const grid = document.getElementById('danangProjectsGrid');
      if (!grid) return;

      grid.innerHTML = danangProjects.map(proj => `
        <article class="ux-card cursor-pointer" onclick="openProjectModal('danang', '${proj.id}')">
          <div class="ux-card-thumb">
            <img
              src="${getDriveImgUrl(proj.id)}"
              alt="${proj.title}"
              loading="lazy"
              onerror="handleImgFallback(this, '${proj.id}', 'DU AN DA NANG')"
            >
          </div>
          <div class="ux-card-body">
            <div>
              <h3 class="ux-card-title">${proj.title}</h3>
              <p class="ux-card-sub"><i class="fa-solid fa-location-dot text-brandGold mr-1"></i>${proj.area}</p>
            </div>
          </div>
        </article>
      `).join('');
    }

    /* Render 4 bài viết tin tức trang chủ */
    function renderArticles() {
      const grid = document.getElementById('articlesGrid');
      if (!grid) return;

      grid.innerHTML = articlesData.map((art, index) => `
        <article class="ux-card cursor-pointer" onclick="openArticleModal(${index})">
          <div class="ux-card-thumb">
            <img
              src="${getDriveImgUrl(art.imgId)}"
              alt="${art.title}"
              loading="lazy"
              onerror="handleImgFallback(this, '${art.imgId}', 'TIN TUC MAY VAN')"
            >
          </div>
          <div class="ux-card-body">
            <div>
              <div class="text-[11px] font-semibold text-brandGold mb-1">${art.date}</div>
              <h3 class="ux-card-title">${art.title}</h3>
              <p class="ux-card-sub mt-1">${art.excerpt}</p>
            </div>
          </div>
        </article>
      `).join('');
    }

    /* Chọn danh mục từ menu trên Header */
    function selectCategoryFromNav(catKey) {
      const btns = document.querySelectorAll('.cat-filter-btn');
      btns.forEach(btn => {
        btn.classList.toggle('active', btn.getAttribute('data-cat') === catKey);
      });
      renderConstructionItems(catKey);
    }

    /* Hộp thoại xem chi tiết công trình / bài viết */
    function openProjectModal(type, fileId) {
      const list = type === 'danang' ? danangProjects : constructionItems;
      const item = list.find(x => x.id === fileId);
      if (!item) return;

      const modal = document.getElementById('detailModal');
      const img = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = item.title;
      document.getElementById('modalMeta').textContent = type === 'danang'
        ? ('Khu vực: ' + item.area)
        : (item.categoryLabel + ' — ' + item.location);
      document.getElementById('modalBody').innerHTML = '<p>' + item.desc + '</p><p>Quý khách có nhu cầu tư vấn phương án thiết kế và nhận báo giá thi công tương tự, vui lòng liên hệ trực tiếp <strong>CÔNG TY TNHH TƯ VẤN THIẾT KẾ &amp; XÂY DỰNG MAY VĂN</strong> qua Hotline/Zalo <strong>0916.143.477</strong>.</p>';

      img.removeAttribute('data-fb-step');
      img.src = getDriveImgUrl(item.id);
      img.alt = item.title;
      img.onerror = function() { handleImgFallback(img, item.id, 'MAY VAN'); };

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function openArticleModal(index) {
      const art = articlesData[index];
      if (!art) return;

      const modal = document.getElementById('detailModal');
      const img = document.getElementById('modalImage');
      document.getElementById('modalTitle').textContent = art.title;
      document.getElementById('modalMeta').textContent = 'Cẩm nang xây dựng • Ngày đăng: ' + art.date;
      document.getElementById('modalBody').innerHTML = '<p>' + art.excerpt + '</p><p>' + art.content + '</p>';

      img.removeAttribute('data-fb-step');
      img.src = getDriveImgUrl(art.imgId);
      img.alt = art.title;
      img.onerror = function() { handleImgFallback(img, art.imgId, 'TIN TUC MAY VAN'); };

      modal.classList.remove('hidden');
      modal.classList.add('flex');
      document.body.style.overflow = 'hidden';
    }

    function closeDetailModal() {
      const modal = document.getElementById('detailModal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
      document.body.style.overflow = '';
    }

    /* Khởi tạo toàn bộ sự kiện khi trang tải xong */
    document.addEventListener('DOMContentLoaded', function() {
      // 1. Render các khu vực dữ liệu
      renderConstructionItems('all');
      renderDanangProjects();
      renderArticles();

      // 2. Xử lý lọc danh mục trang chủ
      document.querySelectorAll('.cat-filter-btn').forEach(btn => {
        btn.addEventListener('click', function() {
          const cat = this.getAttribute('data-cat');
          document.querySelectorAll('.cat-filter-btn').forEach(b => b.classList.remove('active'));
          this.classList.add('active');
          renderConstructionItems(cat);
        });
      });

      // 3. Slider 2 Banner tự trượt chuyên nghiệp (kích thước bằng nhau)
      let currentSlide = 0;
      const totalSlides = 2;
      const track = document.getElementById('heroSlidesTrack');
      const dots = document.querySelectorAll('.banner-dot');
      let sliderTimer = null;

      function goToSlide(idx) {
        currentSlide = (idx + totalSlides) % totalSlides;
        if (track) {
          track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
        }
        dots.forEach((dot, i) => {
          if (i === currentSlide) {
            dot.classList.remove('w-2.5', 'bg-white/50');
            dot.classList.add('w-7', 'bg-brandGold');
          } else {
            dot.classList.remove('w-7', 'bg-brandGold');
            dot.classList.add('w-2.5', 'bg-white/50');
          }
        });
      }

      function startAutoSlide() {
        clearInterval(sliderTimer);
        sliderTimer = setInterval(function() {
          goToSlide(currentSlide + 1);
        }, 5000);
      }

      document.getElementById('prevBannerBtn')?.addEventListener('click', function() {
        goToSlide(currentSlide - 1);
        startAutoSlide();
      });

      document.getElementById('nextBannerBtn')?.addEventListener('click', function() {
        goToSlide(currentSlide + 1);
        startAutoSlide();
      });

      dots.forEach(dot => {
        dot.addEventListener('click', function() {
          goToSlide(parseInt(this.getAttribute('data-slide'), 10));
          startAutoSlide();
        });
      });

      // Hỗ trợ vuốt cảm ứng trên điện thoại cho 2 banner
      let touchStartX = 0;
      const sliderWrap = document.querySelector('.hero-slider-wrap');
      if (sliderWrap) {
        sliderWrap.addEventListener('touchstart', function(e) {
          touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        sliderWrap.addEventListener('touchend', function(e) {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 40) {
            goToSlide(diff < 0 ? currentSlide + 1 : currentSlide - 1);
            startAutoSlide();
          }
        }, { passive: true });
      }

      startAutoSlide();

      // 4. Menu trượt Mobile
      const openBtn = document.getElementById('mobileMenuOpenBtn');
      const closeBtn = document.getElementById('mobileMenuCloseBtn');
      const drawer = document.getElementById('mobileDrawer');
      const backdrop = document.getElementById('mobileDrawerBackdrop');

      function openMobileMenu() {
        drawer.classList.remove('translate-x-full');
        backdrop.classList.remove('hidden');
        document.body.style.overflow = 'hidden';
      }

      function closeMobileMenu() {
        drawer.classList.add('translate-x-full');
        backdrop.classList.add('hidden');
        document.body.style.overflow = '';
      }

      openBtn?.addEventListener('click', openMobileMenu);
      closeBtn?.addEventListener('click', closeMobileMenu);
      backdrop?.addEventListener('click', closeMobileMenu);
      document.querySelectorAll('.mobile-nav-link').forEach(link => {
        link.addEventListener('click', closeMobileMenu);
      });

      // 5. Đóng Modal khi nhấn nút đóng hoặc click nền ngoài
      document.getElementById('closeModalBtn')?.addEventListener('click', closeDetailModal);
      document.getElementById('detailModal')?.addEventListener('click', function(e) {
        if (e.target === this) closeDetailModal();
      });

      // 6. Xử lý gửi Form yêu cầu báo giá trang chủ (không dùng alert)
      const quoteForm = document.getElementById('quoteForm');
      const quoteFeedback = document.getElementById('quoteFeedback');

      quoteForm?.addEventListener('submit', function(e) {
        e.preventDefault();
        const name = document.getElementById('qName').value.trim();
        const phone = document.getElementById('qPhone').value.trim();
        const type = document.getElementById('qType').value;

        if (!name || !phone) {
          quoteFeedback.className = 'rounded-lg p-3.5 text-sm font-medium bg-red-50 text-red-700 border border-red-200';
          quoteFeedback.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để May Văn liên hệ tư vấn.';
          quoteFeedback.classList.remove('hidden');
          return;
        }

        quoteFeedback.className = 'rounded-lg p-3.5 text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
        quoteFeedback.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá hạng mục <strong>' + type + '</strong> của bạn đã được ghi nhận. Kỹ sư May Văn sẽ liên hệ qua số <strong>' + phone + '</strong> trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0916.143.477).';
        quoteFeedback.classList.remove('hidden');
        quoteForm.reset();
      });
    });
  </script>
</body>
</html>
