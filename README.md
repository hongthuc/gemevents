<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - gemevwnts.vn</title>
    <meta name="description" content="CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - Chuyên tổ chức sự kiện trọn gói, cho thuê thiết bị sự kiện, âm thanh ánh sáng, nhà bạt, sân khấu, màn hình LED, nhân sự sự kiện và truyền thông tại Đà Nẵng. Địa chỉ: 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng. Hotline: 093.1121.222.">

    <!-- Open Graph / Thumbnail là ảnh Logo khi gửi link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://gemevwnts.vn/">
    <meta property="og:site_name" content="gemevwnts.vn - CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS">
    <meta property="og:title" content="CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS | Tổ Chức Sự Kiện & Thiết Bị Sự Kiện Đà Nẵng">
    <meta property="og:description" content="Đơn vị tổ chức sự kiện trọn gói và cung ứng trang thiết bị sự kiện chuyên nghiệp tại Đà Nẵng. Địa chỉ: 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng. Hotline: 093.1121.222.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - gemevwnts.vn">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb">
    <link rel="icon" href="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Google Fonts: Inter / Montserrat chuẩn Flatsome -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <style>
        /* Chặn tràn viền tuyệt đối và đảm bảo không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden !important;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Bố cục chuẩn Flatsome Container (1200px) dễ dàng dựng lại trên UX Builder */
        .fs-container {
            width: 100%;
            max-width: 1200px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 640px) {
            .fs-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }

        /* Tiêu đề Section phong cách Flatsome (Section Title) */
        .fs-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.5rem;
            text-align: center;
        }
        .fs-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #e2e8f0;
        }
        .fs-section-title span {
            padding: 0 16px;
            font-weight: 800;
            text-transform: uppercase;
            color: #b91c1c;
            letter-spacing: 0.02em;
            max-width: 100%;
            word-wrap: break-word;
        }

        /* Đảm bảo tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal !important;
            overflow: visible !important;
            text-overflow: clip !important;
            word-break: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Desktop Dropdown Menu chuẩn Flatsome */
        .nav-item-dropdown:hover .dropdown-panel {
            display: block;
        }

        /* Hiệu ứng rung nhẹ cho nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(220, 38, 38, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(220, 38, 38, 0); }
        }
        .pulse-btn {
            animation: pulse-ring 2s infinite;
        }
    </style>

    <script>
        // Hàm xử lý tự động dự phòng link ảnh Google Drive để luôn hiển thị ảnh thực tế ổn định
        function handleDriveImgError(img, fileId, fallbackTitle) {
            const step = parseInt(img.getAttribute('data-fallback-step') || '0', 10);
            if (step === 0) {
                img.setAttribute('data-fallback-step', '1');
                img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1200';
            } else if (step === 1) {
                img.setAttribute('data-fallback-step', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/800x600/991b1b/ffffff?text=' + encodeURIComponent(fallbackTitle || 'GEM EVENTS');
            }
        }
    </script>
</head>
<body class="w-full overflow-x-hidden">

    <!-- ==================== TOP BAR (ĐƠN GIẢN, KHÔNG CÓ THANH CÔNG CỤ UX BUILDER) ==================== -->
    <div class="w-full bg-red-800 text-white text-xs sm:text-sm py-2 border-b border-red-900">
        <div class="fs-container flex flex-col sm:flex-row items-center justify-between gap-1 text-center sm:text-left">
            <div class="font-semibold tracking-wide break-words max-w-full">
                CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - <span class="text-yellow-300 font-bold">gemevwnts.vn</span>
            </div>
            <div class="flex flex-wrap items-center justify-center sm:justify-end gap-x-4 gap-y-1 text-red-100">
                <span><i class="fa-solid fa-location-dot text-yellow-300 mr-1"></i>313 Hải Phòng, Phường Thanh Khê, Đà Nẵng</span>
                <span><i class="fa-solid fa-phone text-yellow-300 mr-1"></i>093.1121.222</span>
            </div>
        </div>
    </div>

    <!-- ==================== HEADER (KHÔNG ĐỂ NÚT GỌI NGAY ĐỂ TRÁNH TRÀN VIỀN) ==================== -->
    <header class="w-full bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
        <div class="fs-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo Công ty -->
            <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 flex-shrink">
                <img src="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb=w400"
                     onerror="handleDriveImgError(this, '1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb', 'GEM EVENTS')"
                     alt="Logo CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS"
                     class="h-11 sm:h-14 w-auto object-contain rounded flex-shrink-0 bg-white">
                <div class="min-w-0">
                    <div class="text-sm sm:text-lg font-extrabold text-red-700 leading-tight break-words">
                        GEM EVENTS
                    </div>
                    <div class="text-[11px] sm:text-xs font-medium text-slate-600 leading-tight break-words">
                        Tổ Chức Sự Kiện & Thiết Bị Đà Nẵng
                    </div>
                </div>
            </a>

            <!-- Thanh tìm kiếm trên máy tính (Chuẩn Flatsome Header) -->
            <div class="hidden lg:flex items-center flex-1 max-w-sm mx-4">
                <div class="relative w-full">
                    <input type="text" id="desktopSearchInput" placeholder="Tìm dịch vụ, thiết bị sự kiện..."
                           oninput="filterServicesByKeyword(this.value)"
                           class="w-full pl-3.5 pr-9 py-2 text-sm border border-slate-300 rounded-full focus:outline-none focus:border-red-600">
                    <span class="absolute right-3 top-1/2 -translate-y-1/2 text-slate-400">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </span>
                </div>
            </div>

            <!-- Menu Danh Mục Máy Tính (Tối ưu hiển thị đẹp, rõ ràng, không tràn viền) -->
            <nav class="hidden xl:flex items-center gap-1 text-xs font-bold uppercase text-slate-700">
                <a href="#trang-chu" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition">Trang chủ</a>
                <a href="#gioi-thieu" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition">Giới thiệu</a>

                <!-- Dropdown: Tổ chức sự kiện -->
                <div class="relative nav-item-dropdown">
                    <a href="#to-chuc-su-kien" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition flex items-center gap-1">
                        Tổ chức sự kiện <i class="fa-solid fa-chevron-down text-[10px]"></i>
                    </a>
                    <div class="dropdown-panel hidden absolute left-0 top-full pt-1 w-64 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-200 py-2 text-xs font-semibold normal-case text-slate-700">
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức tiệc cuối năm Gala Dinner</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức khai trương - khánh thành</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức lễ khởi công xây dựng</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức chạy Roadshow</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức tiệc trà Tea Break</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức hội nghị khách hàng</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức hội chợ triển lãm</a>
                            <a href="#to-chuc-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Tổ chức Team Building</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Cho thuê thiết bị -->
                <div class="relative nav-item-dropdown">
                    <a href="#thiet-bi-su-kien" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition flex items-center gap-1">
                        Cho thuê thiết bị <i class="fa-solid fa-chevron-down text-[10px]"></i>
                    </a>
                    <div class="dropdown-panel hidden absolute left-0 top-full pt-1 w-64 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-200 py-2 text-xs font-semibold normal-case text-slate-700">
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê nhà bạt không gian</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê bàn ghế sự kiện</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê gian hàng tiêu chuẩn</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê & lắp đặt sân khấu</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê âm thanh ánh sáng</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê màn hình LED</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê cổng hơi - trụ Barrier</a>
                            <a href="#thiet-bi-su-kien" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê khung Truss hợp kim nhôm</a>
                        </div>
                    </div>
                </div>

                <!-- Dropdown: Truyền thông & Nhân sự -->
                <div class="relative nav-item-dropdown">
                    <a href="#nhan-su-truyen-thong" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition flex items-center gap-1">
                        Nhân sự & Media <i class="fa-solid fa-chevron-down text-[10px]"></i>
                    </a>
                    <div class="dropdown-panel hidden absolute right-0 top-full pt-1 w-64 z-50">
                        <div class="bg-white rounded-lg shadow-xl border border-slate-200 py-2 text-xs font-semibold normal-case text-slate-700">
                            <a href="#nhan-su-truyen-thong" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cho thuê MC tại Đà Nẵng</a>
                            <a href="#nhan-su-truyen-thong" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cung cấp đoàn Lân Sư Rồng</a>
                            <a href="#nhan-su-truyen-thong" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Cung cấp Ca sĩ, Vũ đoàn, PG - PB</a>
                            <a href="#nhan-su-truyen-thong" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Quay phim sự kiện & Sản xuất TVC</a>
                            <a href="#nhan-su-truyen-thong" class="block px-4 py-2 hover:bg-red-50 hover:text-red-700">Dịch vụ treo phướn, băng rôn</a>
                        </div>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition">Dự án Đà Nẵng</a>
                <a href="#tin-tuc" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition">Tin tức</a>
                <a href="#bao-gia" class="px-2.5 py-2 rounded hover:bg-red-50 hover:text-red-700 transition">Báo giá & Liên hệ</a>
            </nav>

            <!-- Nút mở Menu trên Điện thoại / Tablet -->
            <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục"
                    class="xl:hidden p-2.5 rounded-lg border border-slate-200 text-slate-700 hover:bg-red-50 hover:text-red-700 flex-shrink-0">
                <i id="mobileMenuIcon" class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Menu Điện Thoại (Thiết kế gọn gàng, chia danh mục rõ ràng) -->
        <div id="mobileMenuPanel" class="hidden xl:hidden w-full bg-white border-t border-slate-200 shadow-lg">
            <div class="fs-container py-3 flex flex-col gap-1 text-sm font-semibold text-slate-700">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Trang chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Giới thiệu GEM EVENTS</a>
                <a href="#danh-muc-nhanh" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Danh mục dịch vụ & sản phẩm</a>
                <a href="#thiet-bi-su-kien" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Cho thuê thiết bị sự kiện</a>
                <a href="#to-chuc-su-kien" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Tổ chức sự kiện trọn gói</a>
                <a href="#nhan-su-truyen-thong" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Nhân sự sự kiện & Truyền thông</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Dự án tiêu biểu tại Đà Nẵng</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Tin tức & Kinh nghiệm sự kiện</a>
                <a href="#bao-gia" onclick="toggleMobileMenu()" class="py-2 px-3 rounded hover:bg-red-50 hover:text-red-700">Form yêu cầu báo giá & Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- ==================== 2 ẢNH BANNER TỰ TRƯỢT BẰNG KÍCH THƯỚC (TỐI ƯU MOBILE, CHỮ KHÔNG TRÀN VIỀN) ==================== -->
    <section id="trang-chu" class="w-full relative overflow-hidden bg-slate-900">
        <!-- Khung cố định chiều cao đồng nhất cho cả 2 ảnh banner trên từng màn hình -->
        <div class="relative w-full h-[230px] sm:h-[340px] md:h-[440px] lg:h-[520px] overflow-hidden">

            <!-- SLIDE 1 -->
            <div id="bannerSlide0" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
                <img src="https://lh3.googleusercontent.com/d/1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs=w1600"
                     onerror="handleDriveImgError(this, '1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs', 'GEM EVENTS BANNER 1')"
                     alt="CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - Tổ chức sự kiện chuyên nghiệp"
                     class="w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-black/75 via-black/55 to-black/40 flex items-center justify-center">
                    <div class="fs-container text-center text-white px-4 max-w-full overflow-hidden">
                        <p class="text-[11px] sm:text-sm md:text-base font-bold uppercase tracking-wider text-yellow-400 mb-1 sm:mb-2 break-words">
                            WEBSITE CHÍNH THỨC: GEMEVWNTS.VN
                        </p>
                        <h1 class="text-base sm:text-2xl md:text-4xl lg:text-5xl font-extrabold leading-tight mb-2 sm:mb-4 break-words max-w-3xl mx-auto">
                            CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS
                        </h1>
                        <p class="text-xs sm:text-sm md:text-lg text-slate-100 max-w-2xl mx-auto mb-3 sm:mb-6 leading-relaxed break-words">
                            Chuyên tổ chức sự kiện trọn gói, cung ứng trang thiết bị sự kiện, âm thanh ánh sáng, sân khấu, nhà bạt hàng đầu tại Đà Nẵng.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3">
                            <a href="#bao-gia" class="px-4 py-2 sm:px-6 sm:py-3 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold rounded-lg transition shadow">
                                Nhận Báo Giá Ngay
                            </a>
                            <a href="#du-an-da-nang" class="px-4 py-2 sm:px-6 sm:py-3 bg-white/95 hover:bg-white text-slate-900 text-xs sm:text-sm font-bold rounded-lg transition shadow">
                                Xem Dự Án Đà Nẵng
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- SLIDE 2 (Kích thước bằng tuyệt đối với Slide 1) -->
            <div id="bannerSlide1" class="banner-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0">
                <img src="https://lh3.googleusercontent.com/d/19ccZ9kx8gub8qbbQfrfGz8Me-vBTiVDu=w1600"
                     onerror="handleDriveImgError(this, '19ccZ9kx8gub8qbbQfrfGz8Me-vBTiVDu', 'GEM EVENTS BANNER 2')"
                     alt="Cho thuê thiết bị sự kiện chuyên nghiệp tại Đà Nẵng - GEM EVENTS"
                     class="w-full h-full object-cover object-center">
                <div class="absolute inset-0 bg-gradient-to-r from-black/75 via-black/55 to-black/40 flex items-center justify-center">
                    <div class="fs-container text-center text-white px-4 max-w-full overflow-hidden">
                        <p class="text-[11px] sm:text-sm md:text-base font-bold uppercase tracking-wider text-yellow-400 mb-1 sm:mb-2 break-words">
                            HỆ THỐNG TRANG THIẾT BỊ HIỆN ĐẠI - ĐỒNG BỘ
                        </p>
                        <h2 class="text-base sm:text-2xl md:text-4xl lg:text-5xl font-extrabold leading-tight mb-2 sm:mb-4 break-words max-w-3xl mx-auto">
                            CUNG ỨNG THIẾT BỊ SỰ KIỆN TRỌN GÓI ĐÀ NẴNG
                        </h2>
                        <p class="text-xs sm:text-sm md:text-lg text-slate-100 max-w-2xl mx-auto mb-3 sm:mb-6 leading-relaxed break-words">
                            Cho thuê nhà bạt không gian, sân khấu, màn hình LED, bàn ghế sự kiện, gian hàng tiêu chuẩn tại 313 Hải Phòng, Thanh Khê, Đà Nẵng.
                        </p>
                        <div class="flex flex-wrap items-center justify-center gap-2 sm:gap-3">
                            <a href="#thiet-bi-su-kien" class="px-4 py-2 sm:px-6 sm:py-3 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold rounded-lg transition shadow">
                                Danh Mục Thiết Bị
                            </a>
                            <a href="#bao-gia" class="px-4 py-2 sm:px-6 sm:py-3 bg-white/95 hover:bg-white text-slate-900 text-xs sm:text-sm font-bold rounded-lg transition shadow">
                                Liên Hệ: 093.1121.222
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng 2 Banner -->
            <button type="button" onclick="changeBannerSlide(-1)" aria-label="Banner trước"
                    class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/45 hover:bg-red-600 text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
            </button>
            <button type="button" onclick="changeBannerSlide(1)" aria-label="Banner tiếp"
                    class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/45 hover:bg-red-600 text-white flex items-center justify-center transition">
                <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
            </button>

            <!-- Chấm chỉ báo Slide -->
            <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                <button type="button" onclick="goToBannerSlide(0)" id="bannerDot0" aria-label="Slide 1"
                        class="w-6 h-2 rounded-full bg-yellow-400 transition-all"></button>
                <button type="button" onclick="goToBannerSlide(1)" id="bannerDot1" aria-label="Slide 2"
                        class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC TỔNG QUAN (TỐI ƯU TRÊN MÁY TÍNH & ĐIỆN THOẠI CHO ĐẸP) ==================== -->
    <section id="danh-muc-nhanh" class="w-full py-8 sm:py-10 bg-white border-b border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">DANH MỤC DỊCH VỤ & TRANG THIẾT BỊ SỰ KIỆN</span>
                <b></b>
            </div>

            <!-- Lưới Danh Mục: 2 cột trên điện thoại, 4 cột trên máy tính cân đối đẹp mắt -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Danh mục 1: Tổ chức sự kiện -->
                <a href="#to-chuc-su-kien" class="group bg-slate-50 hover:bg-red-50 rounded-xl border border-slate-200 hover:border-red-300 p-3 sm:p-5 transition flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg bg-red-600 text-white flex items-center justify-center text-base sm:text-xl mb-3">
                            <i class="fa-solid fa-calendar-check"></i>
                        </div>
                        <h3 class="product-title-full text-sm sm:text-base font-extrabold text-slate-900 group-hover:text-red-700 mb-2">
                            1. TỔ CHỨC SỰ KIỆN TRỌN GÓI
                        </h3>
                        <ul class="text-xs text-slate-600 space-y-1">
                            <li>• Tiệc cuối năm Gala Dinner</li>
                            <li>• Lễ khai trương - Khánh thành</li>
                            <li>• Lễ khởi công - Động thổ</li>
                            <li>• Hội nghị - Triển lãm - Roadshow</li>
                        </ul>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/80 text-xs font-bold text-red-700 flex items-center justify-between">
                        <span>Xem chi tiết</span>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                </a>

                <!-- Danh mục 2: Cho thuê thiết bị sự kiện -->
                <a href="#thiet-bi-su-kien" class="group bg-slate-50 hover:bg-red-50 rounded-xl border border-slate-200 hover:border-red-300 p-3 sm:p-5 transition flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg bg-red-600 text-white flex items-center justify-center text-base sm:text-xl mb-3">
                            <i class="fa-solid fa-tent"></i>
                        </div>
                        <h3 class="product-title-full text-sm sm:text-base font-extrabold text-slate-900 group-hover:text-red-700 mb-2">
                            2. CHO THUÊ THIẾT BỊ SỰ KIỆN
                        </h3>
                        <ul class="text-xs text-slate-600 space-y-1">
                            <li>• Nhà bạt không gian - Gian hàng</li>
                            <li>• Âm thanh ánh sáng - Màn hình LED</li>
                            <li>• Bàn ghế - Sân khấu - Khung Truss</li>
                            <li>• Cổng hơi - Trụ Barrier - Thảm đỏ</li>
                        </ul>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/80 text-xs font-bold text-red-700 flex items-center justify-between">
                        <span>Xem chi tiết</span>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                </a>

                <!-- Danh mục 3: Nhân sự sự kiện -->
                <a href="#nhan-su-truyen-thong" class="group bg-slate-50 hover:bg-red-50 rounded-xl border border-slate-200 hover:border-red-300 p-3 sm:p-5 transition flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg bg-red-600 text-white flex items-center justify-center text-base sm:text-xl mb-3">
                            <i class="fa-solid fa-users-line"></i>
                        </div>
                        <h3 class="product-title-full text-sm sm:text-base font-extrabold text-slate-900 group-hover:text-red-700 mb-2">
                            3. CUNG CẤP NHÂN SỰ SỰ KIỆN
                        </h3>
                        <ul class="text-xs text-slate-600 space-y-1">
                            <li>• Cho thuê MC chuyên nghiệp Đà Nẵng</li>
                            <li>• Cung cấp Đội Lân Sư Rồng</li>
                            <li>• Ca sĩ biểu diễn - Vũ đoàn</li>
                            <li>• Cung cấp lễ tân PG – PB</li>
                        </ul>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/80 text-xs font-bold text-red-700 flex items-center justify-between">
                        <span>Xem chi tiết</span>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                </a>

                <!-- Danh mục 4: Dịch vụ truyền thông -->
                <a href="#nhan-su-truyen-thong" class="group bg-slate-50 hover:bg-red-50 rounded-xl border border-slate-200 hover:border-red-300 p-3 sm:p-5 transition flex flex-col justify-between">
                    <div>
                        <div class="w-10 h-10 sm:w-12 sm:h-12 rounded-lg bg-red-600 text-white flex items-center justify-center text-base sm:text-xl mb-3">
                            <i class="fa-solid fa-video"></i>
                        </div>
                        <h3 class="product-title-full text-sm sm:text-base font-extrabold text-slate-900 group-hover:text-red-700 mb-2">
                            4. DỊCH VỤ TRUYỀN THÔNG MEDIA
                        </h3>
                        <ul class="text-xs text-slate-600 space-y-1">
                            <li>• Quay phim sự kiện - Highlight</li>
                            <li>• Sản xuất TVC - Phim doanh nghiệp</li>
                            <li>• Phim phóng sự truyền hình</li>
                            <li>• Treo phướn, băng rôn quảng cáo</li>
                        </ul>
                    </div>
                    <div class="mt-3 pt-2 border-t border-slate-200/80 text-xs font-bold text-red-700 flex items-center justify-between">
                        <span>Xem chi tiết</span>
                        <i class="fa-solid fa-arrow-right"></i>
                    </div>
                </a>
            </div>
        </div>
    </section>

    <!-- ==================== DỊCH VỤ CUNG ỨNG THIẾT BỊ SỰ KIỆN (2 CỘT TRÊN MOBILE, KHÔNG NHÃN DÁN, KHÔNG TRÀN CHỮ) ==================== -->
    <section id="thiet-bi-su-kien" class="w-full py-10 sm:py-12 bg-slate-50">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">DỊCH VỤ CHO THUÊ TRANG THIẾT BỊ SỰ KIỆN - GEM EVENTS</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-6 sm:mb-8">
                Dịch vụ chính của <strong>CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS</strong> là cho thuê trang thiết bị sự kiện trọn gói tại Đà Nẵng và miền Trung, đáp ứng mọi quy mô sự kiện từ nhỏ đến lớn với thiết bị hiện đại và chi phí tối ưu.
            </p>

            <!-- Grid: 2 cột trên điện thoại (grid-cols-2), 3 cột tablet, 4 cột máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5 service-card-grid">

                <!-- Sản phẩm 1 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/16tylaGPyHZVUXS4lDbg_tIqCe7c5AUlK=w800"
                             onerror="handleDriveImgError(this, '16tylaGPyHZVUXS4lDbg_tIqCe7c5AUlK', 'Nhà bạt không gian')"
                             alt="Cho thuê nhà bạt không gian sự kiện Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ NHÀ BẠT KHÔNG GIAN SỰ KIỆN
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Nhà bạt khẩu độ lớn, khung hợp kim nhôm kiên cố cho lễ khởi công, khánh thành, lễ hội ngoài trời.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê nhà bạt không gian sự kiện')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 2 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1FMC8r2p8PegWl1j-U45goosfcks7nC7n=w800"
                             onerror="handleDriveImgError(this, '1FMC8r2p8PegWl1j-U45goosfcks7nC7n', 'Cho thuê bàn ghế')"
                             alt="Cho thuê bàn ghế sự kiện Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ BÀN GHẾ SỰ KIỆN HỘI NGHỊ
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Ghế Banquet, ghế Tiffany, bàn đại biểu IBM, bàn tròn tiệc áo nơ sang trọng đồng bộ.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê bàn ghế sự kiện hội nghị')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 3 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1phElISnIy3aAr1ea1ocH6ryIjzHl12a9=w800"
                             onerror="handleDriveImgError(this, '1phElISnIy3aAr1ea1ocH6ryIjzHl12a9', 'Gian hàng tiêu chuẩn')"
                             alt="Cho thuê gian hàng tiêu chuẩn hội chợ Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ GIAN HÀNG TIÊU CHUẨN HỘI CHỢ
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Gian hàng triển lãm kích thước chuẩn 3x3m, đầy đủ vách, па-nô, bàn ghế, đèn điện.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê gian hàng tiêu chuẩn hội chợ')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 4 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1XLNYbzehB0SxEihjAreLz4r7l94eud8x=w800"
                             onerror="handleDriveImgError(this, '1XLNYbzehB0SxEihjAreLz4r7l94eud8x', 'Lắp đặt sân khấu')"
                             alt="Cho thuê và lắp đặt sân khấu sự kiện"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ VÀ LẮP ĐẶT SÂN KHẤU SỰ KIỆN
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Sân khấu lắp ghép đa kích thước, bọc thảm đỏ mới 100%, bậc tam cấp chắc chắn an toàn.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê và lắp đặt sân khấu sự kiện')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 5 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1uS8t_robnqNBj90Fuu3I9bTN5Pp7EyPf=w800"
                             onerror="handleDriveImgError(this, '1uS8t_robnqNBj90Fuu3I9bTN5Pp7EyPf', 'Âm thanh ánh sáng')"
                             alt="Cho thuê âm thanh ánh sáng sự kiện Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ ÂM THANH ÁNH SÁNG CHUYÊN NGHIỆP
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Hệ thống loa Line Array, đèn Beam Moving Head, Par LED, bàn Mixer kỹ thuật số hiện đại.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê âm thanh ánh sáng chuyên nghiệp')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 6 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1VotJEh_lHg9ZHUzhf3UdFzNeDAcCEGzi=w800"
                             onerror="handleDriveImgError(this, '1VotJEh_lHg9ZHUzhf3UdFzNeDAcCEGzi', 'Màn hình LED')"
                             alt="Cho thuê màn hình LED sự kiện"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ MÀN HÌNH LED INDOOR & OUTDOOR
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Màn hình LED P3, P4 sắc nét độ sáng cao cho hội nghị, tiệc Gala Dinner, sân khấu ngoài trời.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê màn hình LED Indoor & Outdoor')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 7 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1pBV8jxgnMfGLhqNruUGwyqWTKenUXFg0=w800"
                             onerror="handleDriveImgError(this, '1pBV8jxgnMfGLhqNruUGwyqWTKenUXFg0', 'Khung Truss Nhôm')"
                             alt="Cho thuê khung Truss hợp kim nhôm và trụ Barrier"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ KHUNG TRUSS NHÔM & TRỤ BARRIER
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Cung cấp khung Truss treo âm thanh ánh sáng, cột chắn inox dây nhung đỏ đón khách VIP.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê khung Truss nhôm & Trụ Barrier')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

                <!-- Sản phẩm 8 -->
                <div class="service-item bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1p1to6bjzlewudpMhZpcnzEDSiPLb-IDR=w800"
                             onerror="handleDriveImgError(this, '1p1to6bjzlewudpMhZpcnzEDSiPLb-IDR', 'Cổng hơi khai trương')"
                             alt="Cho thuê cổng hơi, bộ cắt băng khai trương khánh thành"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                CHO THUÊ CỔNG HƠI & BỘ CẮT BĂNG KHAI TRƯƠNG
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Cổng hơi rồng phụng, rối hơi vẫy tay, khinh khí cầu, bộ dụng cụ cắt băng khánh thành.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Cho thuê cổng hơi & Bộ cắt băng khai trương')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-50 hover:bg-red-600 text-red-700 hover:text-white text-xs font-bold rounded-lg transition">
                            Nhận báo giá
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DỊCH VỤ TỔ CHỨC SỰ KIỆN TRỌN GÓI (GIỐNG WEB MẪU TSK MEDIA) ==================== -->
    <section id="to-chuc-su-kien" class="w-full py-10 sm:py-12 bg-white border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">DỊCH VỤ TỔ CHỨC SỰ KIỆN CHUYÊN NGHIỆP TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-6 sm:mb-8">
                Lên kịch bản sáng tạo, thiết kế 3D sân khấu, thi công trọn gói và điều phối chương trình chuyên nghiệp cho doanh nghiệp tại Đà Nẵng.
            </p>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">

                <!-- Sự kiện 1 -->
                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1H7MWPsGARnyKm3HL1XfPGT12Ka8GDrso=w800"
                             onerror="handleDriveImgError(this, '1H7MWPsGARnyKm3HL1XfPGT12Ka8GDrso', 'Tiệc cuối năm Gala Dinner')"
                             alt="Tổ chức tiệc cuối năm Gala Dinner Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1.5">
                                TỔ CHỨC TIỆC CUỐI NĂM GALA DINNER
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Thiết kế chủ đề Year End Party ấn tượng, kịch bản vinh danh và nghệ thuật đặc sắc.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Tổ chức tiệc cuối năm Gala Dinner')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-600 hover:bg-red-700 text-white text-xs font-bold rounded-lg transition">
                            Tư vấn kịch bản
                        </a>
                    </div>
                </div>

                <!-- Sự kiện 2 -->
                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1HnWVfzifHbyzNEys9ejEaChPxyoE4B0t=w800"
                             onerror="handleDriveImgError(this, '1HnWVfzifHbyzNEys9ejEaChPxyoE4B0t', 'Khai trương khánh thành')"
                             alt="Tổ chức lễ khai trương khánh thành Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1.5">
                                TỔ CHỨC LỄ KHAI TRƯƠNG - KHÁNH THÀNH
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Tổ chức khai trương trọn gói từ backdrop, thảm đỏ, múa lân khai hồng vận đến tiệc Tea Break.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Tổ chức lễ khai trương - khánh thành')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-600 hover:bg-red-700 text-white text-xs font-bold rounded-lg transition">
                            Tư vấn kịch bản
                        </a>
                    </div>
                </div>

                <!-- Sự kiện 3 -->
                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1REP0EhGE2lpjSpTBHUUoTf53NxCGvZf-=w800"
                             onerror="handleDriveImgError(this, '1REP0EhGE2lpjSpTBHUUoTf53NxCGvZf-', 'Lễ khởi công động thổ')"
                             alt="Tổ chức lễ khởi công động thổ xây dựng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1.5">
                                TỔ CHỨC LỄ KHỞI CÔNG - ĐỘNG THỔ XÂY DỰNG
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Chuẩn bị đầy đủ nhà bạt không gian, bộ xúc cát động thổ, nghi thức trang trọng, chuẩn chỉnh.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Tổ chức lễ khởi công - động thổ xây dựng')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-600 hover:bg-red-700 text-white text-xs font-bold rounded-lg transition">
                            Tư vấn kịch bản
                        </a>
                    </div>
                </div>

                <!-- Sự kiện 4 -->
                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[4/3] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1TUH7NeQm3nDi42i6KNrNAx91nHeTtHvN=w800"
                             onerror="handleDriveImgError(this, '1TUH7NeQm3nDi42i6KNrNAx91nHeTtHvN', 'Hội nghị khách hàng')"
                             alt="Tổ chức hội nghị khách hàng, hội thảo, triển lãm"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1.5">
                                TỔ CHỨC HỘI NGHỊ KHÁCH HÀNG & TEAM BUILDING
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Tổ chức hội thảo, lễ kỷ niệm thành lập, giải chạy Marathon, chạy Roadshow và Team Building.
                            </p>
                        </div>
                        <a href="#bao-gia" onclick="prefillService('Tổ chức hội nghị khách hàng & Team Building')" class="mt-3 inline-block text-center w-full py-2 px-2 bg-red-600 hover:bg-red-700 text-white text-xs font-bold rounded-lg transition">
                            Tư vấn kịch bản
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG TRÊN TRANG CHỦ ==================== -->
    <section id="du-an-da-nang" class="w-full py-10 sm:py-12 bg-slate-100 border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">DỰ ÁN TỔ CHỨC SỰ KIỆN TIÊU BIỂU TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>
            <p class="text-center text-xs sm:text-sm text-slate-600 max-w-3xl mx-auto mb-6">
                Hình ảnh thực tế các dự án sự kiện, lễ khởi công, hội nghị, khai trương và lắp đặt trang thiết bị do <strong>GEM EVENTS</strong> trực tiếp triển khai tại TP. Đà Nẵng.
            </p>

            <!-- Bộ lọc danh mục dự án tại Đà Nẵng -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8">
                <button type="button" onclick="filterProjects('all', this)" class="project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-red-600 text-white transition">
                    Tất cả dự án Đà Nẵng
                </button>
                <button type="button" onclick="filterProjects('khoi-cong', this)" class="project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 border border-slate-300 hover:border-red-600 transition">
                    Lễ Khởi Công - Khánh Thành
                </button>
                <button type="button" onclick="filterProjects('hoi-nghi', this)" class="project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 border border-slate-300 hover:border-red-600 transition">
                    Hội Nghị - Gala Dinner
                </button>
                <button type="button" onclick="filterProjects('ngoai-troi', this)" class="project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 border border-slate-300 hover:border-red-600 transition">
                    Lễ Hội & Sự Kiện Ngoài Trời
                </button>
            </div>

            <!-- Lưới Dự Án Đà Nẵng: 2 cột trên điện thoại, 3 cột trên máy tính, không nhãn dán -->
            <div id="daNangProjectsGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">

                <!-- Dự án Đà Nẵng 1 -->
                <div data-cat="khoi-cong" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1xl4NKQDMt-D-_aa-ALY3sS_eCV-7_hqM=w900"
                             onerror="handleDriveImgError(this, '1xl4NKQDMt-D-_aa-ALY3sS_eCV-7_hqM', 'Dự án Đà Nẵng 1')"
                             alt="Dự án Lễ Khởi Công & Khánh Thành tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Lễ Khởi Công & Động Thổ Tổ Hợp Dự Án Tại Quận Liên Chiểu, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Thi công trọn gói hệ thống nhà bạt không gian, sân khấu, âm thanh ánh sáng và nghi thức khởi công.
                        </p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 2 -->
                <div data-cat="hoi-nghi" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1ySX6cD4vU_fzI2CMzQSc60t5JRl011I8=w900"
                             onerror="handleDriveImgError(this, '1ySX6cD4vU_fzI2CMzQSc60t5JRl011I8', 'Dự án Đà Nẵng 2')"
                             alt="Sự kiện Hội Nghị Khách Hàng & Gala Dinner tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Đêm Tiệc Gala Dinner & Hội Nghị Tri Ân Khách Hàng Tại Hải Châu, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Cung cấp hệ thống màn hình LED P3, âm thanh Line Array, ánh sáng sân khấu và đạo diễn chương trình.
                        </p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 3 -->
                <div data-cat="ngoai-troi" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1fLNuB_REX1R5byKyqkBoBvuScgKqEUs2=w900"
                             onerror="handleDriveImgError(this, '1fLNuB_REX1R5byKyqkBoBvuScgKqEUs2', 'Dự án Đà Nẵng 3')"
                             alt="Sự kiện Giải Chạy & Lễ Hội Biển Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Cung Ứng Thiết Bị Sự Kiện Lễ Hội Biển & Giải Chạy Marathon Sơn Trà, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Lắp đặt cổng chào, gian hàng tiêu chuẩn, rào chắn Barrier và sân khấu chính ven biển Đà Nẵng.
                        </p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 4 -->
                <div data-cat="khoi-cong" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs=w900"
                             onerror="handleDriveImgError(this, '1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs', 'Dự án Đà Nẵng 4')"
                             alt="Lễ Khai Trương Showroom tại Thanh Khê, Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Tổ Chức Lễ Khai Trương Hệ Thống Showroom Tại Quận Thanh Khê, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Tổ chức trọn gói từ trang trí backdrop, thảm đỏ, đội Lân Sư Rồng, MC, PG đến tiệc trà Tea Break.
                        </p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 5 -->
                <div data-cat="ngoai-troi" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/19ccZ9kx8gub8qbbQfrfGz8Me-vBTiVDu=w900"
                             onerror="handleDriveImgError(this, '19ccZ9kx8gub8qbbQfrfGz8Me-vBTiVDu', 'Dự án Đà Nẵng 5')"
                             alt="Sự kiện Triển Lãm Thương Mại & Hội Chợ tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Thi Công Gian Hàng Triển Lãm & Hội Chợ Thương Mại Tại Cẩm Lệ, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Dàn dựng hệ thống nhà bạt không gian, gian hàng hội chợ tiêu chuẩn và hệ thống chiếu sáng sự kiện.
                        </p>
                    </div>
                </div>

                <!-- Dự án Đà Nẵng 6 -->
                <div data-cat="hoi-nghi" class="project-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/16tylaGPyHZVUXS4lDbg_tIqCe7c5AUlK=w900"
                             onerror="handleDriveImgError(this, '16tylaGPyHZVUXS4lDbg_tIqCe7c5AUlK', 'Dự án Đà Nẵng 6')"
                             alt="Sự kiện Kỷ Niệm Thành Lập Doanh Nghiệp tại Ngũ Hành Sơn, Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            Lễ Kỷ Niệm Thành Lập & Team Building Resort Ngũ Hành Sơn, Đà Nẵng
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Thực hiện trọn gói chương trình Team Building bãi biển và đêm nhạc Gala Dinner ngoài trời.
                        </p>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==================== NHÂN SỰ SỰ KIỆN & DỊCH VỤ TRUYỀN THÔNG ==================== -->
    <section id="nhan-su-truyen-thong" class="w-full py-10 sm:py-12 bg-white border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">NHÂN SỰ SỰ KIỆN & SẢN XUẤT TRUYỀN THÔNG</span>
                <b></b>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-3 sm:p-4 flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1FMC8r2p8PegWl1j-U45goosfcks7nC7n=w600"
                             onerror="handleDriveImgError(this, '1FMC8r2p8PegWl1j-U45goosfcks7nC7n', 'MC Sự kiện')"
                             alt="Cho thuê MC chuyên nghiệp tại Đà Nẵng"
                             class="w-full aspect-[4/3] object-cover rounded-lg mb-3">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            CUNG CẤP MC SỰ KIỆN SONG NGỮ & HOẠT NÁO
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Đội ngũ MC chuyên nghiệp dẫn lễ khai trương, hội nghị, Gala Dinner và Team Building tại Đà Nẵng.
                        </p>
                    </div>
                    <a href="#bao-gia" onclick="prefillService('Cung cấp MC sự kiện tại Đà Nẵng')" class="mt-3 text-xs font-bold text-red-700 hover:underline">Liên hệ đặt lịch →</a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-3 sm:p-4 flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1phElISnIy3aAr1ea1ocH6ryIjzHl12a9=w600"
                             onerror="handleDriveImgError(this, '1phElISnIy3aAr1ea1ocH6ryIjzHl12a9', 'Đoàn Lân Sư Rồng')"
                             alt="Cung cấp đội Lân Sư Rồng khai trương Đà Nẵng"
                             class="w-full aspect-[4/3] object-cover rounded-lg mb-3">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            CUNG CẤP ĐỘI LÂN SƯ RỒNG & TRỐNG HỘI
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Biểu diễn múa Lân Sư Rồng mai hoa thung, trống hội khai mạc mang tài lộc cho lễ khai trương, khánh thành.
                        </p>
                    </div>
                    <a href="#bao-gia" onclick="prefillService('Cung cấp Đội Lân Sư Rồng & Trống hội')" class="mt-3 text-xs font-bold text-red-700 hover:underline">Liên hệ đặt lịch →</a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-3 sm:p-4 flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1XLNYbzehB0SxEihjAreLz4r7l94eud8x=w600"
                             onerror="handleDriveImgError(this, '1XLNYbzehB0SxEihjAreLz4r7l94eud8x', 'Ca sĩ PG PB')"
                             alt="Cung cấp Ca sĩ, Vũ đoàn, PG PB sự kiện"
                             class="w-full aspect-[4/3] object-cover rounded-lg mb-3">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            CUNG CẤP CA SĨ, VŨ ĐOÀN & LỄ TÂN PG – PB
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Nhân sự lễ tân đón khách, cắt băng khánh thành, ca sĩ, nhóm nhảy, ban nhạc Acoustic chuyên nghiệp.
                        </p>
                    </div>
                    <a href="#bao-gia" onclick="prefillService('Cung cấp Ca sĩ, Vũ đoàn & PG - PB')" class="mt-3 text-xs font-bold text-red-700 hover:underline">Liên hệ đặt lịch →</a>
                </div>

                <div class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden p-3 sm:p-4 flex flex-col justify-between">
                    <div>
                        <img src="https://lh3.googleusercontent.com/d/1uS8t_robnqNBj90Fuu3I9bTN5Pp7EyPf=w600"
                             onerror="handleDriveImgError(this, '1uS8t_robnqNBj90Fuu3I9bTN5Pp7EyPf', 'Quay phim sự kiện')"
                             alt="Quay phim chụp ảnh sự kiện, Flycam, TVC doanh nghiệp"
                             class="w-full aspect-[4/3] object-cover rounded-lg mb-3">
                        <h3 class="product-title-full text-xs sm:text-base font-bold text-slate-900 mb-1">
                            QUAY PHIM SỰ KIỆN, FLYCAM & TREO PHƯỚN
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-600">
                            Quay phim Highlight sự kiện, chụp hình phóng sự, sản xuất TVC quảng cáo và thi công treo băng rôn.
                        </p>
                    </div>
                    <a href="#bao-gia" onclick="prefillService('Dịch vụ Quay phim sự kiện & Truyền thông')" class="mt-3 text-xs font-bold text-red-700 hover:underline">Liên hệ đặt lịch →</a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== CƠ SỞ VẬT CHẤT & TẠI SAO CHỌN GEM EVENTS (THEO MẪU TSK MEDIA) ==================== -->
    <section id="gioi-thieu" class="w-full py-10 sm:py-12 bg-slate-50 border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">TẠI SAO LỰA CHỌN CÔNG TY TỔ CHỨC SỰ KIỆN GEM EVENTS?</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-2 gap-6 sm:gap-8 items-start">
                <!-- Cột thông tin lý do chọn GEM EVENTS -->
                <div class="bg-white p-4 sm:p-6 rounded-xl border border-slate-200 shadow-sm space-y-3 text-xs sm:text-sm text-slate-700 leading-relaxed">
                    <h3 class="text-base sm:text-lg font-extrabold text-red-700">
                        CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS - ĐỐI TÁC TIN CẬY TẠI ĐÀ NẴNG
                    </h3>
                    <p>
                        Tọa lạc tại <strong>313 Hải Phòng, Phường Thanh Khê, TP. Đà Nẵng</strong>, <strong>GEM EVENTS (gemevwnts.vn)</strong> tự hào là đơn vị tổ chức sự kiện và cung ứng thiết bị sự kiện uy tín, sở hữu kho trang thiết bị chủ động cùng đội ngũ kỹ thuật viên giàu kinh nghiệm.
                    </p>
                    <ul class="space-y-2.5 pt-1">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-red-600 mt-1 flex-shrink-0"></i>
                            <span><strong>1. Kinh nghiệm thực chiến đa dạng:</strong> Đảm nhận thành công hàng trăm sự kiện khởi công, khánh thành, hội nghị khách hàng, Gala Dinner, lễ hội tại Đà Nẵng và miền Trung.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-red-600 mt-1 flex-shrink-0"></i>
                            <span><strong>2. Kịch bản sáng tạo & chỉn chu:</strong> Lên ý tưởng chi tiết từ thiết kế 2D/3D, kịch bản MC, âm thanh ánh sáng đến từng điểm nhấn Key Moment.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-red-600 mt-1 flex-shrink-0"></i>
                            <span><strong>3. Hệ thống thiết bị trực tiếp, không qua trung gian:</strong> Chủ động kho nhà bạt, sân khấu, màn hình LED, bàn ghế, âm thanh ánh sáng giúp tối ưu chi phí tốt nhất.</span>
                        </li>
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-circle-check text-red-600 mt-1 flex-shrink-0"></i>
                            <span><strong>4. Đội ngũ nhân sự tận tâm, hỗ trợ 24/7:</strong> Khảo sát mặt bằng tận nơi miễn phí tại Đà Nẵng, thi công đúng tiến độ, an toàn tuyệt đối.</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột hình ảnh thực tế cơ sở vật chất & sự kiện (Từ danh sách 17 ảnh Google Drive) -->
                <div>
                    <h3 class="text-sm sm:text-base font-extrabold text-slate-800 uppercase mb-3">
                        HÌNH ẢNH THỰC TẾ THIẾT BỊ & ĐỘI NGŨ GEM EVENTS
                    </h3>
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/1VotJEh_lHg9ZHUzhf3UdFzNeDAcCEGzi=w500"
                             onerror="handleDriveImgError(this, '1VotJEh_lHg9ZHUzhf3UdFzNeDAcCEGzi', 'Ảnh thực tế 1')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 1" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1pBV8jxgnMfGLhqNruUGwyqWTKenUXFg0=w500"
                             onerror="handleDriveImgError(this, '1pBV8jxgnMfGLhqNruUGwyqWTKenUXFg0', 'Ảnh thực tế 2')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 2" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1p1to6bjzlewudpMhZpcnzEDSiPLb-IDR=w500"
                             onerror="handleDriveImgError(this, '1p1to6bjzlewudpMhZpcnzEDSiPLb-IDR', 'Ảnh thực tế 3')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 3" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1H7MWPsGARnyKm3HL1XfPGT12Ka8GDrso=w500"
                             onerror="handleDriveImgError(this, '1H7MWPsGARnyKm3HL1XfPGT12Ka8GDrso', 'Ảnh thực tế 4')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 4" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1HnWVfzifHbyzNEys9ejEaChPxyoE4B0t=w500"
                             onerror="handleDriveImgError(this, '1HnWVfzifHbyzNEys9ejEaChPxyoE4B0t', 'Ảnh thực tế 5')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 5" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1REP0EhGE2lpjSpTBHUUoTf53NxCGvZf-=w500"
                             onerror="handleDriveImgError(this, '1REP0EhGE2lpjSpTBHUUoTf53NxCGvZf-', 'Ảnh thực tế 6')"
                             alt="Hình ảnh thực tế sự kiện GEM EVENTS 6" class="w-full aspect-[4/3] object-cover rounded-lg border border-slate-200">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==================== DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (CHIA SẺ KINH NGHIỆM) ==================== -->
    <section id="tin-tuc" class="w-full py-10 sm:py-12 bg-white border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl">TIN TỨC SỰ KIỆN & CHIA SẺ KINH NGHIỆM</span>
                <b></b>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">

                <!-- Bài viết 1 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1TUH7NeQm3nDi42i6KNrNAx91nHeTtHvN=w600"
                             onerror="handleDriveImgError(this, '1TUH7NeQm3nDi42i6KNrNAx91nHeTtHvN', 'Tin tức 1')"
                             alt="Kinh nghiệm chọn đơn vị cho thuê nhà bạt sự kiện tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                Tiêu chí chọn đơn vị cho thuê nhà bạt không gian chuẩn tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Kinh nghiệm lựa chọn khẩu độ nhà bạt, kết cấu khung giàn an toàn cho sự kiện ngoài trời quy mô lớn.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-3 text-xs font-bold text-red-700 hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1xl4NKQDMt-D-_aa-ALY3sS_eCV-7_hqM=w600"
                             onerror="handleDriveImgError(this, '1xl4NKQDMt-D-_aa-ALY3sS_eCV-7_hqM', 'Tin tức 2')"
                             alt="Kế hoạch tổ chức lễ khai trương khánh thành trọn gói"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                Quy trình 7 bước tổ chức lễ khai trương hồng phát cho doanh nghiệp
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Từ khâu thiết kế bộ nhận diện, lắp đặt sân khấu, thảm đỏ đến kịch bản cắt băng khai trương.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-3 text-xs font-bold text-red-700 hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1ySX6cD4vU_fzI2CMzQSc60t5JRl011I8=w600"
                             onerror="handleDriveImgError(this, '1ySX6cD4vU_fzI2CMzQSc60t5JRl011I8', 'Tin tức 3')"
                             alt="Lưu ý khi tổ chức lễ khởi công động thổ công trình"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                Cần lưu ý những gì trước khi tổ chức lễ khởi công động thổ xây dựng?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Danh mục trang thiết bị cần thiết và cách bố trí sơ đồ khu vực lễ khởi công trang trọng, thuận lợi.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-3 text-xs font-bold text-red-700 hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col">
                    <div class="w-full aspect-[16/10] overflow-hidden bg-slate-200">
                        <img src="https://lh3.googleusercontent.com/d/1fLNuB_REX1R5byKyqkBoBvuScgKqEUs2=w600"
                             onerror="handleDriveImgError(this, '1fLNuB_REX1R5byKyqkBoBvuScgKqEUs2', 'Tin tức 4')"
                             alt="Báo giá thuê âm thanh ánh sáng màn hình LED Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-900 hover:text-red-700 mb-1.5">
                                Kinh nghiệm chọn cấu hình âm thanh ánh sáng và màn hình LED sự kiện
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600">
                                Tư vấn chọn công suất âm thanh ánh sáng phù hợp với không gian hội trường và ngoài trời.
                            </p>
                        </div>
                        <a href="#bao-gia" class="mt-3 text-xs font-bold text-red-700 hover:underline">Xem chi tiết →</a>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- ==================== FORM YÊU CẦU BÁO GIÁ + FANPAGE + BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ ==================== -->
    <section id="bao-gia" class="w-full py-10 sm:py-12 bg-slate-100 border-t border-slate-200">
        <div class="fs-container">
            <div class="fs-section-title">
                <b></b>
                <span class="text-base sm:text-xl md:text-2xl"> ĐĂNG KÝ TƯ VẤN BÁO GIÁ & KẾT NỐI VỚI GEM EVENTS</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start">

                <!-- CỘT 1 (5/12): FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm p-4 sm:p-6">
                    <h3 class="text-base sm:text-lg font-extrabold text-red-700 uppercase mb-1">
                        FORM YÊU CẦU TƯ VẤN & BÁO GIÁ
                    </h3>
                    <p class="text-xs text-slate-600 mb-4">
                        Quý khách vui lòng để lại thông tin, bộ phận điều hành <strong>GEM EVENTS</strong> sẽ liên hệ gửi báo giá chi tiết ngay trong 15 phút.
                    </p>

                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
                            <input type="text" id="qName" required placeholder="Nhập họ tên hoặc tên công ty..."
                                   class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-red-600">
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo liên hệ *</label>
                            <input type="tel" id="qPhone" required placeholder="Ví dụ: 0931121222"
                                   class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-red-600">
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                            <select id="qService" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-red-600 bg-white">
                                <option value="Tổ chức sự kiện trọn gói tại Đà Nẵng">Tổ chức sự kiện trọn gói tại Đà Nẵng</option>
                                <option value="Cho thuê nhà bạt không gian sự kiện">Cho thuê nhà bạt không gian sự kiện</option>
                                <option value="Cho thuê bàn ghế sự kiện hội nghị">Cho thuê bàn ghế sự kiện hội nghị</option>
                                <option value="Cho thuê gian hàng tiêu chuẩn hội chợ">Cho thuê gian hàng tiêu chuẩn hội chợ</option>
                                <option value="Cho thuê và lắp đặt sân khấu sự kiện">Cho thuê và lắp đặt sân khấu sự kiện</option>
                                <option value="Cho thuê âm thanh ánh sáng chuyên nghiệp">Cho thuê âm thanh ánh sáng chuyên nghiệp</option>
                                <option value="Cho thuê màn hình LED Indoor & Outdoor">Cho thuê màn hình LED Indoor & Outdoor</option>
                                <option value="Cho thuê khung Truss nhôm & Trụ Barrier">Cho thuê khung Truss nhôm & Trụ Barrier</option>
                                <option value="Cho thuê cổng hơi & Bộ cắt băng khai trương">Cho thuê cổng hơi & Bộ cắt băng khai trương</option>
                                <option value="Tổ chức tiệc cuối năm Gala Dinner">Tổ chức tiệc cuối năm Gala Dinner</option>
                                <option value="Tổ chức lễ khai trương - khánh thành">Tổ chức lễ khai trương - khánh thành</option>
                                <option value="Tổ chức lễ khởi công - động thổ xây dựng">Tổ chức lễ khởi công - động thổ xây dựng</option>
                                <option value="Cung cấp Nhân sự (MC, Lân Sư Rồng, PG) & Media">Cung cấp Nhân sự (MC, Lân Sư Rồng, PG) & Media</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Thời gian dự kiến & Nội dung yêu cầu</label>
                            <textarea id="qNote" rows="3" placeholder="Nhập thời gian tổ chức, địa điểm tại Đà Nẵng, số lượng khách hoặc thiết bị cần thuê..."
                                      class="w-full px-3.5 py-2 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-red-600"></textarea>
                        </div>

                        <button type="submit" class="w-full py-3 px-4 bg-red-600 hover:bg-red-700 text-white font-extrabold text-sm uppercase rounded-lg shadow transition">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i> GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>

                    <!-- Hộp thông báo gửi thành công -->
                    <div id="quoteSuccessBox" class="hidden mt-4 p-3.5 rounded-lg bg-green-50 border border-green-300 text-green-800 text-xs sm:text-sm">
                        <div class="font-bold mb-1"><i class="fa-solid fa-circle-check mr-1"></i> Đã tiếp nhận yêu cầu báo giá!</div>
                        <p id="quoteSuccessText" class="mb-2"></p>
                        <div class="flex flex-wrap gap-2">
                            <a href="tel:0931121222" class="px-3 py-1.5 bg-red-600 text-white rounded font-bold text-xs">Gọi Hotline: 093.1121.222</a>
                            <a href="https://zalo.me/0931121222" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 bg-blue-600 text-white rounded font-bold text-xs">Chat Zalo ngay</a>
                        </div>
                    </div>
                </div>

                <!-- CỘT 2 (7/12): ĐƯA FANPAGE & ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ -->
                <div class="lg:col-span-7 grid grid-cols-1 md:grid-cols-2 gap-5">

                    <!-- KHỐI FANPAGE TRÊN TRANG CHỦ -->
                    <div class="bg-white rounded-xl border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-slate-900 uppercase mb-3 flex items-center gap-2">
                                <i class="fa-brands fa-facebook text-blue-600 text-lg"></i> FANPAGE GEM EVENTS
                            </h3>

                            <!-- Thẻ nhận diện Fanpage trực quan + Nhúng Facebook Page Plugin -->
                            <div class="rounded-lg border border-slate-200 overflow-hidden mb-3 bg-slate-50">
                                <div class="relative h-28 w-full overflow-hidden">
                                    <img src="https://lh3.googleusercontent.com/d/1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs=w600"
                                         onerror="handleDriveImgError(this, '1yRFxML5U7QZFzvOHAUfrAVbwfzE6EBRs', 'Fanpage Cover')"
                                         alt="Ảnh bìa Fanpage GEM EVENTS" class="w-full h-full object-cover">
                                    <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                                    <div class="absolute bottom-2.5 left-3 right-3 flex items-center gap-2.5">
                                        <img src="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb=w200"
                                             onerror="handleDriveImgError(this, '1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb', 'Logo')"
                                             alt="Logo Fanpage" class="w-11 h-11 rounded-full border-2 border-white bg-white object-contain flex-shrink-0">
                                        <div class="text-white min-w-0">
                                            <div class="font-bold text-xs sm:text-sm truncate">CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS</div>
                                            <div class="text-[11px] text-slate-200">Tổ chức sự kiện & Thiết bị Đà Nẵng</div>
                                        </div>
                                    </div>
                                </div>
                                <div class="p-3 text-xs text-slate-600 space-y-1.5">
                                    <p><i class="fa-solid fa-location-dot text-red-600 mr-1.5"></i>313 Hải Phòng, Phường Thanh Khê, Đà Nẵng</p>
                                    <p><i class="fa-solid fa-phone text-red-600 mr-1.5"></i>Hotline: <strong>093.1121.222</strong></p>
                                    <p><i class="fa-solid fa-globe text-red-600 mr-1.5"></i>Website: <strong>gemevwnts.vn</strong></p>
                                </div>
                            </div>

                            <!-- Khung iframe Facebook Plugin chính thức -->
                            <div class="w-full overflow-hidden rounded border border-slate-200 bg-white flex justify-center">
                                <iframe src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fprofile.php%3Fid%3D100063772651280&tabs=timeline&width=320&height=180&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true"
                                        width="320" height="180" style="border:none;overflow:hidden;max-width:100%;" scrolling="no" frameborder="0"
                                        allowfullscreen="true" allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share"></iframe>
                            </div>
                        </div>

                        <a href="https://www.facebook.com/profile.php?id=100063772651280&locale=vi_VN"
                           target="_blank" rel="noopener noreferrer"
                           class="mt-3 w-full py-2.5 px-3 bg-blue-600 hover:bg-blue-700 text-white text-xs sm:text-sm font-bold rounded-lg text-center transition block">
                            <i class="fa-brands fa-facebook-messenger mr-1.5"></i> Truy Cập Fanpage & Nhắn Tin
                        </a>
                    </div>

                    <!-- KHỐI ẢNH & BẢN ĐỒ GOOGLE MAP NGOÀI TRANG CHỦ -->
                    <div class="bg-white rounded-xl border border-slate-200 shadow-sm p-4 flex flex-col justify-between">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-slate-900 uppercase mb-3 flex items-center gap-2">
                                <i class="fa-solid fa-map-location-dot text-red-600 text-lg"></i> BẢN ĐỒ GOOGLE MAP TRANG CHỦ
                            </h3>

                            <!-- Bản đồ trực quan tới 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng -->
                            <div class="w-full h-56 sm:h-64 rounded-lg overflow-hidden border border-slate-200 mb-3 relative bg-slate-100">
                                <iframe
                                    title="Bản đồ 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng"
                                    src="https://maps.google.com/maps?q=313%20H%E1%BA%A3i%20Ph%C3%B2ng,%20Thanh%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                                    class="w-full h-full border-0"
                                    allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade">
                                </iframe>
                            </div>

                            <div class="p-3 rounded-lg bg-red-50 border border-red-100 text-xs text-slate-700 space-y-1">
                                <div class="font-bold text-red-800">TRỤ SỞ CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS</div>
                                <div><i class="fa-solid fa-location-dot text-red-600 mr-1.5"></i>Địa chỉ: <strong>313 Hải Phòng, Phường Thanh Khê, Đà Nẵng</strong></div>
                                <div><i class="fa-solid fa-phone-volume text-red-600 mr-1.5"></i>Điện thoại: <strong>093.1121.222</strong></div>
                            </div>
                        </div>

                        <a href="https://maps.app.goo.gl/Gg4sZYSQA7wZ6yCe9"
                           target="_blank" rel="noopener noreferrer"
                           class="mt-3 w-full py-2.5 px-3 bg-red-600 hover:bg-red-700 text-white text-xs sm:text-sm font-bold rounded-lg text-center transition block">
                            <i class="fa-solid fa-diamond-turn-right mr-1.5"></i> Mở Chỉ Đường Trên Google Maps
                        </a>
                    </div>

                </div>

            </div>
        </div>
    </section>

    <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
    <footer class="w-full bg-slate-900 text-slate-200 pt-10 pb-20 sm:pb-10 border-t-4 border-red-600">
        <div class="fs-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 sm:gap-8 pb-8 border-b border-slate-800">

                <!-- Cột 1: Thông tin công ty -->
                <div>
                    <div class="flex items-center gap-3 mb-3">
                        <img src="https://lh3.googleusercontent.com/d/1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb=w200"
                             onerror="handleDriveImgError(this, '1TWxqUm39OAKz8oge_V8C7fFVxAMS1ksb', 'GEM EVENTS')"
                             alt="Logo GEM EVENTS" class="h-12 w-auto bg-white p-1 rounded">
                        <span class="font-extrabold text-base text-white">GEM EVENTS</span>
                    </div>
                    <h4 class="text-xs sm:text-sm font-bold text-yellow-400 mb-2">
                        CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS
                    </h4>
                    <ul class="text-xs sm:text-sm space-y-2 text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-red-500 mr-2"></i>Địa chỉ: 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-red-500 mr-2"></i>Hotline: <a href="tel:0931121222" class="text-white font-bold hover:text-yellow-400">093.1121.222</a></li>
                        <li><i class="fa-solid fa-globe text-red-500 mr-2"></i>Website: <a href="https://gemevwnts.vn" class="text-white font-bold hover:text-yellow-400">gemevwnts.vn</a></li>
                        <li><i class="fa-solid fa-map-pin text-red-500 mr-2"></i><a href="https://maps.app.goo.gl/Gg4sZYSQA7wZ6yCe9" target="_blank" rel="noopener noreferrer" class="underline hover:text-yellow-400">Xem vị trí trên Google Maps</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Dịch vụ tổ chức sự kiện -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-slate-700 pb-2">
                        DỊCH VỤ TỔ CHỨC SỰ KIỆN
                    </h4>
                    <ul class="text-xs sm:text-sm space-y-2 text-slate-300">
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức tiệc cuối năm Gala Dinner</a></li>
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức lễ khai trương - khánh thành</a></li>
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức lễ khởi công - động thổ</a></li>
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức hội nghị - hội thảo khách hàng</a></li>
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức chạy Roadshow & Triển lãm</a></li>
                        <li><a href="#to-chuc-su-kien" class="hover:text-yellow-400">• Tổ chức Team Building & Ngày hội 1/6</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Cho thuê thiết bị sự kiện -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-slate-700 pb-2">
                        CHO THUÊ THIẾT BỊ SỰ KIỆN
                    </h4>
                    <ul class="text-xs sm:text-sm space-y-2 text-slate-300">
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê nhà bạt không gian</a></li>
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê âm thanh ánh sáng</a></li>
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê màn hình LED sự kiện</a></li>
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê bàn ghế & Gian hàng hội chợ</a></li>
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê sân khấu & Khung Truss nhôm</a></li>
                        <li><a href="#thiet-bi-su-kien" class="hover:text-yellow-400">• Cho thuê cổng hơi & Trụ Barrier</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Kết nối mạng xã hội -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-slate-700 pb-2">
                        KẾT NỐI VỚI CHÚNG TÔI
                    </h4>
                    <p class="text-xs text-slate-300 mb-3 leading-relaxed">
                        Theo dõi Fanpage chính thức của <strong>CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS</strong> để cập nhật hình ảnh các dự án sự kiện mới nhất tại Đà Nẵng.
                    </p>
                    <div class="flex flex-col gap-2">
                        <a href="https://www.facebook.com/profile.php?id=100063772651280&locale=vi_VN" target="_blank" rel="noopener noreferrer"
                           class="py-2 px-3 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-bold flex items-center gap-2 transition">
                            <i class="fa-brands fa-facebook-f w-4 text-center"></i> Fanpage GEM EVENTS
                        </a>
                        <a href="https://zalo.me/0931121222" target="_blank" rel="noopener noreferrer"
                           class="py-2 px-3 rounded-lg bg-sky-500 hover:bg-sky-600 text-white text-xs font-bold flex items-center gap-2 transition">
                            <i class="fa-solid fa-comment-dots w-4 text-center"></i> Chat Zalo: 093.1121.222
                        </a>
                        <a href="https://maps.app.goo.gl/Gg4sZYSQA7wZ6yCe9" target="_blank" rel="noopener noreferrer"
                           class="py-2 px-3 rounded-lg bg-red-600 hover:bg-red-700 text-white text-xs font-bold flex items-center gap-2 transition">
                            <i class="fa-solid fa-location-dot w-4 text-center"></i> Bản Đồ: 313 Hải Phòng, Đà Nẵng
                        </a>
                    </div>
                </div>

            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                © Bản quyền thuộc về <strong>CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS</strong> | Website: <strong>gemevwnts.vn</strong> | Địa chỉ: 313 Hải Phòng, Phường Thanh Khê, Đà Nẵng.
            </div>
        </div>
    </footer>

    <!-- ==================== NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (GỌN GÀNG, KHÔNG TRÀN VIỀN) ==================== -->
    <div class="fixed left-3 bottom-3 z-50 flex flex-col gap-2.5 max-w-[calc(100vw-24px)]">
        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/profile.php?id=100063772651280&locale=vi_VN"
           target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition w-fit">
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center flex-shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook Chat</span>
        </a>

        <!-- Nút Zalo Chat -->
        <a href="https://zalo.me/0931121222"
           target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg transition w-fit">
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 flex items-center justify-center font-extrabold text-[11px] flex-shrink-0">
                Zalo
            </span>
            <span class="text-xs font-bold pr-1">Zalo: 093.1121.222</span>
        </a>

        <!-- Nút Hotline Nổi Bật -->
        <a href="tel:0931121222"
           class="pulse-btn flex items-center gap-2 bg-red-600 hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition w-fit">
            <span class="w-7 h-7 rounded-full bg-white text-red-600 flex items-center justify-center flex-shrink-0">
                <i class="fa-solid fa-phone-volume text-sm"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">093.1121.222</span>
        </a>
    </div>

    <!-- ==================== JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, MENU, LỌC DỰ ÁN & FORM BÁO GIÁ ==================== -->
    <script>
        // 1. Điều khiển 2 ảnh Banner tự trượt bằng kích thước
        let currentBannerIndex = 0;
        const totalBannerSlides = 2;
        let bannerInterval = null;

        function showBannerSlide(index) {
            currentBannerIndex = (index + totalBannerSlides) % totalBannerSlides;
            for (let i = 0; i < totalBannerSlides; i++) {
                const slide = document.getElementById('bannerSlide' + i);
                const dot = document.getElementById('bannerDot' + i);
                if (!slide || !dot) continue;
                if (i === currentBannerIndex) {
                    slide.classList.remove('opacity-0', 'z-0');
                    slide.classList.add('opacity-100', 'z-10');
                    dot.className = 'w-6 h-2 rounded-full bg-yellow-400 transition-all';
                } else {
                    slide.classList.remove('opacity-100', 'z-10');
                    slide.classList.add('opacity-0', 'z-0');
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                }
            }
        }

        function changeBannerSlide(step) {
            showBannerSlide(currentBannerIndex + step);
            restartBannerAutoSlide();
        }

        function goToBannerSlide(index) {
            showBannerSlide(index);
            restartBannerAutoSlide();
        }

        function restartBannerAutoSlide() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(function () {
                showBannerSlide(currentBannerIndex + 1);
            }, 4500);
        }

        // 2. Đóng / Mở menu trên điện thoại
        function toggleMobileMenu() {
            const panel = document.getElementById('mobileMenuPanel');
            const icon = document.getElementById('mobileMenuIcon');
            if (!panel) return;
            panel.classList.toggle('hidden');
            if (panel.classList.contains('hidden')) {
                icon.className = 'fa-solid fa-bars text-lg';
            } else {
                icon.className = 'fa-solid fa-xmark text-lg';
            }
        }

        // 3. Lọc danh mục các dự án tại Đà Nẵng
        function filterProjects(category, btnElement) {
            const cards = document.querySelectorAll('#daNangProjectsGrid .project-card');
            cards.forEach(function (card) {
                const cardCat = card.getAttribute('data-cat');
                if (category === 'all' || cardCat === category) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });

            const buttons = document.querySelectorAll('.project-tab-btn');
            buttons.forEach(function (btn) {
                btn.className = 'project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-white text-slate-700 border border-slate-300 hover:border-red-600 transition';
            });
            if (btnElement) {
                btnElement.className = 'project-tab-btn px-3.5 py-1.5 rounded-full text-xs sm:text-sm font-bold bg-red-600 text-white transition';
            }
        }

        // 4. Chọn nhanh dịch vụ đưa xuống Form báo giá
        function prefillService(serviceName) {
            const select = document.getElementById('qService');
            if (!select) return;
            for (let i = 0; i < select.options.length; i++) {
                if (select.options[i].value === serviceName) {
                    select.selectedIndex = i;
                    break;
                }
            }
        }

        // 5. Tìm kiếm nhanh dịch vụ trên thanh tìm kiếm
        function filterServicesByKeyword(keyword) {
            const normalized = (keyword || '').toLowerCase().trim();
            const cards = document.querySelectorAll('.service-card-grid .service-item');
            cards.forEach(function (card) {
                const text = card.innerText.toLowerCase();
                if (!normalized || text.includes(normalized)) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 6. Xử lý gửi Form yêu cầu báo giá trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const service = document.getElementById('qService').value;
            const successBox = document.getElementById('quoteSuccessBox');
            const successText = document.getElementById('quoteSuccessText');

            successText.textContent = 'Cảm ơn ' + name + ' (' + phone + '). Yêu cầu báo giá hạng mục "' + service + '" đã được gửi tới CÔNG TY TNHH TỔ CHỨC SỰ KIỆN GEM EVENTS.';
            successBox.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        window.onload = function () {
            restartBannerAutoSlide();
        };
    </script>
</body>
</html>
