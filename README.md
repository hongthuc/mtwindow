<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH MTV MT WINDOW - Cửa Nhôm Xingfa & Nhôm Kính Cao Cấp Đà Nẵng | mtwindow.com</title>
    <meta name="description" content="CÔNG TY TNHH MTV MT WINDOW (mtwindow.com) chuyên thiết kế, sản xuất và thi công Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Kính ốp bếp, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0905.898.755.">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link qua Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://mtwindow.com/">
    <meta property="og:site_name" content="mtwindow.com - CÔNG TY TNHH MTV MT WINDOW">
    <meta property="og:title" content="CÔNG TY TNHH MTV MT WINDOW - Cửa Nhôm Xingfa Đà Nẵng | mtwindow.com">
    <meta property="og:description" content="Chuyên thiết kế, sản xuất & thi công Cửa nhôm Xingfa, Cửa nhựa lõi thép, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính, Kính ốp bếp tại Đà Nẵng. ĐT: 0905.898.755">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP">
    <meta property="og:image:alt" content="Logo CÔNG TY TNHH MTV MT WINDOW">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH MTV MT WINDOW - mtwindow.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP">

    <!-- Tailwind CSS & Google Fonts (Inter) & FontAwesome -->
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        mtblue: {
                            50: '#f0f7ff',
                            100: '#e0effe',
                            500: '#0284c7',
                            600: '#0369a1',
                            700: '#0b4f8a',
                            800: '#083b66',
                            900: '#062847',
                        },
                        mtred: {
                            500: '#e11d48',
                            600: '#be123c',
                        }
                    }
                }
            }
        };

        // Hàm tự động chuyển đổi dự phòng ảnh Google Drive để đảm bảo hiển thị 100%
        function handleDriveImageError(img, fileId, fallbackText) {
            if (!img.dataset.retriedThumbnail) {
                img.dataset.retriedThumbnail = 'true';
                img.src = 'https://drive.google.com/thumbnail?id=' + fileId + '&sz=w1000';
            } else if (!img.dataset.retriedUc) {
                img.dataset.retriedUc = 'true';
                img.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
            } else {
                img.onerror = null;
                img.src = 'https://placehold.co/800x600/0b4f8a/ffffff?text=' + encodeURIComponent(fallbackText || 'MT WINDOW');
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .ux-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Chuẩn hóa tên danh mục trên máy tính: chữ nhỏ gọn, viết liền 1 dòng (không ngắt chữ xuống dòng), nằm trên 1 hàng hoặc xuống hàng 2 */
        .category-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 4px 6px;
            width: 100%;
        }
        .category-nav-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            font-size: 12.5px;
            line-height: 1.3;
            font-weight: 600;
            padding: 6px 10px;
            border-radius: 6px;
            transition: all 0.2s ease;
        }
        @media (min-width: 1280px) {
            .category-nav-list {
                gap: 6px 8px;
            }
            .category-nav-item {
                font-size: 13px;
                padding: 7px 11px;
            }
        }

        /* Tiêu đề Section phong cách Flatsome UX Builder */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 100%;
            margin-bottom: 1.25rem;
        }
        .flatsome-section-title b {
            display: block;
            flex: 1;
            height: 2px;
            background-color: #cbd5e1;
        }
        .flatsome-section-title span {
            padding: 0 14px;
            text-align: center;
            font-weight: 800;
            text-transform: uppercase;
            color: #0b4f8a;
            letter-spacing: 0.02em;
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal !important;
            word-wrap: break-word !important;
            overflow-wrap: break-word !important;
            overflow: visible !important;
            display: block;
            line-height: 1.4;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulse-ring {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(225, 29, 72, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(225, 29, 72, 0); }
        }
        .pulse-hotline {
            animation: pulse-ring 2s infinite;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased">

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome - Không có thanh UX Builder)
    =========================================== -->
    <div class="bg-mtblue-800 text-white text-xs py-2 border-b border-mtblue-700">
        <div class="ux-container flex flex-col sm:flex-row items-center justify-between gap-1.5 text-center sm:text-left">
            <div class="flex flex-wrap items-center justify-center sm:justify-start gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-sky-300"></i>
                    <span>Lô số 13 Khu B2-7 Đường Đinh Liệt, Khu TĐC Phước Lý, P. An Khê, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="flex items-center justify-center sm:justify-end gap-4 whitespace-nowrap">
                <span class="inline-flex items-center gap-1 text-sky-200">
                    <i class="fa-regular fa-clock"></i> Làm việc: T2 - T7 (06:30 - 22:00)
                </span>
                <span class="hidden md:inline-block text-mtblue-500">|</span>
                <a href="https://www.facebook.com/cuanhomxinfadanang" target="_blank" rel="noopener noreferrer" class="hover:text-sky-300 inline-flex items-center gap-1 font-medium">
                    <i class="fa-brands fa-facebook"></i> Fanpage MT Window
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER CHÍNH (Logo gọn nhỏ, Không để nút Gọi ngay để tránh tràn viền)
    =========================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
        <div class="ux-container py-2.5">
            <div class="flex items-center justify-between gap-3">
                <!-- Logo chỉnh gọn nhỏ + Tên công ty -->
                <a href="#trang-chu" class="flex items-center gap-2.5 min-w-0 shrink-0">
                    <img 
                        src="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP" 
                        onerror="handleDriveImageError(this, '1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP', 'LOGO MT')"
                        alt="Logo Công Ty TNHH MTV MT Window" 
                        class="h-9 w-9 sm:h-10 sm:w-10 object-contain rounded border border-slate-200 bg-white p-0.5 shrink-0"
                    >
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm md:text-base font-extrabold text-mtblue-700 tracking-tight leading-tight">
                            CÔNG TY TNHH MTV MT WINDOW
                        </div>
                        <div class="text-[10px] sm:text-xs text-slate-500 font-medium leading-tight">
                            mtwindow.com • Cửa Nhôm Xingfa Đà Nẵng
                        </div>
                    </div>
                </a>

                <!-- Thanh tìm kiếm nhanh trên Máy tính (Giống mẫu ngochanwindow.com) -->
                <div class="hidden md:flex items-center flex-1 max-w-md mx-4">
                    <div class="flex w-full border border-slate-300 rounded-lg overflow-hidden focus-within:border-mtblue-600 focus-within:ring-1 focus-within:ring-mtblue-600 bg-slate-50">
                        <select id="searchCategorySelect" onchange="filterProductsByCategory(this.value)" class="bg-slate-100 text-slate-700 text-xs font-medium px-2.5 py-2 border-r border-slate-300 focus:outline-none">
                            <option value="all">Tất cả danh mục</option>
                            <option value="cua-nhom-xingfa">Cửa Nhôm Xingfa</option>
                            <option value="cua-nhua-loi-thep">Cửa Nhựa Lõi Thép</option>
                            <option value="cua-kinh-tu-dong">Cửa Kính & Tự Động</option>
                            <option value="cau-thang-kinh">Cầu Thang Kính</option>
                            <option value="kinh-op-bep">Kính Ốp Bếp</option>
                            <option value="phong-tam-kinh">Phòng Tắm Kính</option>
                        </select>
                        <input 
                            id="headerSearchInput" 
                            type="text" 
                            oninput="searchProducts(this.value)"
                            placeholder="Tìm cửa nhôm Xingfa, phòng tắm kính, kính ốp bếp..." 
                            class="w-full px-3 py-1.5 text-xs bg-white focus:outline-none text-slate-700"
                        >
                        <button type="button" onclick="scrollToSection('san-pham-thuc-te')" class="bg-mtblue-700 hover:bg-mtblue-800 text-white px-3.5 py-1.5 text-xs font-semibold transition">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Nút mở Menu trên Điện thoại (Không để nút gọi ngay trên Header) -->
                <button 
                    type="button" 
                    onclick="toggleMobileMenu()" 
                    aria-label="Mở danh mục"
                    class="lg:hidden inline-flex items-center gap-1.5 px-3 py-1.5 rounded-lg border border-slate-300 bg-slate-50 text-mtblue-800 text-xs font-bold hover:bg-slate-100"
                >
                    <i class="fa-solid fa-bars text-sm"></i>
                    <span>DANH MỤC</span>
                </button>
            </div>
        </div>

        <!-- Thanh Danh Mục Ngang trên Máy tính (Chữ nhỏ gọn, viết liền 1 dòng, nằm trên 1 hàng hoặc xuống hàng 2) -->
        <nav class="hidden lg:block bg-mtblue-700 text-white border-t border-mtblue-600">
            <div class="ux-container py-1.5">
                <div class="category-nav-list">
                    <a href="#trang-chu" class="category-nav-item bg-mtblue-800 text-white hover:bg-mtblue-900">
                        <i class="fa-solid fa-house mr-1.5 text-[11px]"></i>Trang Chủ
                    </a>
                    <a href="#gioi-thieu" class="category-nav-item text-white hover:bg-mtblue-800">
                        Giới Thiệu
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Cửa Nhôm Xingfa
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Cửa Nhựa Lõi Thép
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Cửa Kính Tự Động
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cau-thang-kinh')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Cầu Thang Kính
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('kinh-op-bep')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Kính Ốp Bếp
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('phong-tam-kinh')" class="category-nav-item text-white hover:bg-mtblue-800">
                        Phòng Tắm Kính
                    </a>
                    <a href="#du-an-da-nang" class="category-nav-item text-white hover:bg-mtblue-800">
                        Dự Án Đà Nẵng
                    </a>
                    <a href="#form-bao-gia" class="category-nav-item text-white hover:bg-mtblue-800">
                        Báo Giá
                    </a>
                    <a href="#tin-tuc" class="category-nav-item text-white hover:bg-mtblue-800">
                        Bài Viết
                    </a>
                    <a href="#ban-do-fanpage" class="category-nav-item text-white hover:bg-mtblue-800">
                        Liên Hệ
                    </a>
                </div>
            </div>
        </nav>

        <!-- Menu Danh mục trên Điện thoại (Thiết kế gọn đẹp, không tràn viền) -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="ux-container py-3 space-y-2.5">
                <div class="flex border border-slate-300 rounded-lg overflow-hidden">
                    <input 
                        type="text" 
                        oninput="searchProducts(this.value)"
                        placeholder="Tìm kiếm sản phẩm..." 
                        class="w-full px-3 py-2 text-xs focus:outline-none"
                    >
                    <button type="button" onclick="toggleMobileMenu(); scrollToSection('san-pham-thuc-te')" class="bg-mtblue-700 text-white px-3 text-xs font-semibold">
                        Tìm
                    </button>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5">
                    <a href="#trang-chu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        <i class="fa-solid fa-house mr-1"></i>Trang Chủ
                    </a>
                    <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 text-xs font-semibold whitespace-nowrap">
                        Giới Thiệu Công Ty
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhom-xingfa'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Cửa Nhôm Xingfa
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhua-loi-thep'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Cửa Nhựa Lõi Thép
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-kinh-tu-dong'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Cửa Kính Tự Động
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cau-thang-kinh'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Cầu Thang Kính
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('kinh-op-bep'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Kính Ốp Bếp
                    </a>
                    <a href="#san-pham-thuc-te" onclick="filterProductsByCategory('phong-tam-kinh'); toggleMobileMenu()" class="px-2.5 py-2 rounded bg-mtblue-50 text-mtblue-800 text-xs font-semibold whitespace-nowrap">
                        Phòng Tắm Kính
                    </a>
                    <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 text-xs font-semibold whitespace-nowrap">
                        Dự Án Đà Nẵng
                    </a>
                    <a href="#form-bao-gia" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 text-xs font-semibold whitespace-nowrap">
                        Yêu Cầu Báo Giá
                    </a>
                    <a href="#tin-tuc" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 text-xs font-semibold whitespace-nowrap">
                        Bài Viết Tư Vấn
                    </a>
                    <a href="#ban-do-fanpage" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 text-xs font-semibold whitespace-nowrap">
                        Bản Đồ & Fanpage
                    </a>
                </div>
            </div>
        </div>
    </header>

    <!-- ==========================================
         SLIDER 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         (Thiết kế Banner Điện Thoại riêng & Banner Máy Tính riêng, chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền)
    =========================================== -->
    <section id="trang-chu" class="py-3 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-slate-200 bg-mtblue-900">
                
                <!-- SLIDE 1 -->
                <div class="banner-slide block transition-opacity duration-500" data-slide="0">
                    <!-- Bản Banner dành riêng cho MÁY TÍNH (Chiều cao cố định 380px bằng nhau giữa 2 slide) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] w-full bg-gradient-to-r from-mtblue-900 via-mtblue-800 to-mtblue-700 px-10 py-6 relative overflow-hidden">
                        <div class="col-span-7 pr-6 z-10 space-y-2.5">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-sky-500/20 border border-sky-300/30 text-sky-200 text-xs font-semibold">
                                <span>CÔNG TY TNHH MTV MT WINDOW • MTWINDOW.COM</span>
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug">
                                CHUYÊN SẢN XUẤT & THI CÔNG CỬA NHÔM XINGFA CHÍNH HÃNG TẠI ĐÀ NẴNG
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Giải pháp đồng bộ Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông, Cửa nhựa lõi thép, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính & Kính ốp bếp bền đẹp cho mọi công trình.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 max-w-lg text-xs text-white/90">
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-sky-300"></i> Phụ kiện Kinlong đồng bộ 100%</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-sky-300"></i> Khảo sát & báo giá tận nơi miễn phí</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-sky-300"></i> Xưởng sản xuất trực tiếp giá gốc</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-circle-check text-sky-300"></i> Bảo hành dài hạn, uy tín tận tâm</div>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#form-bao-gia" class="px-4 py-2 rounded-lg bg-mtred-500 hover:bg-mtred-600 text-white text-xs font-bold shadow transition">
                                    NHẬN BÁO GIÁ NGAY
                                </a>
                                <a href="#san-pham-thuc-te" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white text-xs font-semibold border border-white/30 transition">
                                    XEM SẢN PHẨM THỰC TẾ
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 grid grid-cols-2 gap-2.5 z-10 h-[310px]">
                            <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u" onerror="handleDriveImageError(this, '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u', 'Cửa Nhôm Xingfa')" alt="Thực tế cửa nhôm Xingfa MT Window" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                    <img src="https://lh3.googleusercontent.com/d/1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv" onerror="handleDriveImageError(this, '1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv', 'Thi Công Cửa')" alt="Thi công thực tế MT Window" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                    <img src="https://lh3.googleusercontent.com/d/1erGS-7PZ2rporP7BFywxuzoy6a1dPlMz" onerror="handleDriveImageError(this, '1erGS-7PZ2rporP7BFywxuzoy6a1dPlMz', 'Công Ty MT Window')" alt="Công ty MT Window Đà Nẵng" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Bản Banner thiết kế MỚI dành riêng cho ĐIỆN THOẠI (Chiều cao cố định 310px bằng nhau, chữ nhỏ gọn nằm trọn trong ảnh banner, không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[310px] w-full bg-gradient-to-b from-mtblue-900 via-mtblue-800 to-mtblue-900 p-4 relative overflow-hidden">
                        <div class="flex items-center justify-between gap-2 border-b border-white/15 pb-2">
                            <span class="text-[11px] font-bold text-sky-300 tracking-wide">MTWINDOW.COM • ĐÀ NẴNG</span>
                            <span class="text-[11px] font-semibold text-white bg-mtred-500 px-2 py-0.5 rounded">0905.898.755</span>
                        </div>
                        <div class="my-auto py-1 space-y-1.5">
                            <h2 class="text-sm sm:text-base font-extrabold text-white leading-snug">
                                THI CÔNG CỬA NHÔM XINGFA & NHÔM KÍNH UY TÍN ĐÀ NẴNG
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-normal">
                                Cửa nhôm Xingfa nhập khẩu • Cửa nhựa lõi thép • Cửa kính cường lực • Cầu thang kính • Phòng tắm kính • Kính ốp bếp.
                            </p>
                        </div>
                        <div class="grid grid-cols-3 gap-1.5 h-24">
                            <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u" onerror="handleDriveImageError(this, '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u', 'Ảnh 1')" alt="Ảnh thực tế 1" class="w-full h-24 object-cover rounded border border-white/30">
                            <img src="https://lh3.googleusercontent.com/d/1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv" onerror="handleDriveImageError(this, '1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv', 'Ảnh 2')" alt="Ảnh thực tế 2" class="w-full h-24 object-cover rounded border border-white/30">
                            <img src="https://lh3.googleusercontent.com/d/1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9" onerror="handleDriveImageError(this, '1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9', 'Ảnh 3')" alt="Ảnh thực tế 3" class="w-full h-24 object-cover rounded border border-white/30">
                        </div>
                        <div class="pt-2 flex items-center justify-between text-[11px] text-sky-200">
                            <span class="truncate">Đ/c: Lô 13 Khu B2-7 Đinh Liệt, P. An Khê, Đà Nẵng</span>
                        </div>
                    </div>
                </div>

                <!-- SLIDE 2 (Kích thước bằng nhau tuyệt đối với Slide 1) -->
                <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
                    <!-- Bản Banner dành riêng cho MÁY TÍNH (Chiều cao cố định 380px bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[380px] w-full bg-gradient-to-r from-slate-900 via-mtblue-900 to-mtblue-800 px-10 py-6 relative overflow-hidden">
                        <div class="col-span-7 pr-6 z-10 space-y-2.5">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-amber-500/20 border border-amber-300/30 text-amber-200 text-xs font-semibold">
                                <span>NHÀ XƯỞNG QUY MÔ • THI CÔNG TRỌN GÓI TẠI ĐÀ NẴNG & MIỀN TRUNG</span>
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-3xl font-extrabold text-white leading-snug">
                                GIẢI PHÁP CỬA ĐẸP CHO BIỆT THỰ, NHÀ PHỐ, KHÁCH SẠN & DỰ ÁN
                            </h2>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Công ty TNHH MTV MT Window trực tiếp gia công sản xuất trên dây chuyền máy móc hiện đại tại Khu TĐC Phước Lý, Phường An Khê, TP Đà Nẵng. Cam kết tiến độ, thẩm mỹ và độ bền vượt thời gian.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 max-w-lg text-xs text-white/90">
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-location-dot text-amber-300"></i> Lô 13 Khu B2-7 Đinh Liệt, Đà Nẵng</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-phone-volume text-amber-300"></i> Tư vấn kỹ thuật: 0905.898.755</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-screwdriver-wrench text-amber-300"></i> Lắp đặt chuẩn kỹ thuật, kín khít</div>
                                <div class="flex items-center gap-1.5"><i class="fa-solid fa-shield-halved text-amber-300"></i> Giá tận xưởng không qua trung gian</div>
                            </div>
                            <div class="pt-2 flex items-center gap-3">
                                <a href="#du-an-da-nang" class="px-4 py-2 rounded-lg bg-sky-500 hover:bg-sky-600 text-white text-xs font-bold shadow transition">
                                    DỰ ÁN TẠI ĐÀ NẴNG
                                </a>
                                <a href="#ban-do-fanpage" class="px-4 py-2 rounded-lg bg-white/15 hover:bg-white/25 text-white text-xs font-semibold border border-white/30 transition">
                                    XEM BẢN ĐỒ & FANPAGE
                                </a>
                            </div>
                        </div>
                        <div class="col-span-5 grid grid-cols-2 gap-2.5 z-10 h-[310px]">
                            <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                <img src="https://lh3.googleusercontent.com/d/1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC" onerror="handleDriveImageError(this, '1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC', 'Nhà Xưởng MT Window')" alt="Nhà xưởng MT Window Đà Nẵng" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                    <img src="https://lh3.googleusercontent.com/d/1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t" onerror="handleDriveImageError(this, '1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t', 'Cầu Thang Kính')" alt="Cầu thang kính cường lực" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/30 shadow-lg h-full">
                                    <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc" onerror="handleDriveImageError(this, '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc', 'Phòng Tắm Kính')" alt="Phòng tắm kính cường lực" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- Bản Banner thiết kế MỚI dành riêng cho ĐIỆN THOẠI (Chiều cao cố định 310px bằng nhau, chữ nhỏ gọn nằm hết trong ảnh banner) -->
                    <div class="flex md:hidden flex-col justify-between h-[310px] w-full bg-gradient-to-b from-slate-900 via-mtblue-900 to-mtblue-800 p-4 relative overflow-hidden">
                        <div class="flex items-center justify-between gap-2 border-b border-white/15 pb-2">
                            <span class="text-[11px] font-bold text-amber-300 tracking-wide">XƯỞNG SẢN XUẤT TRỰC TIẾP</span>
                            <span class="text-[11px] font-semibold text-white bg-sky-600 px-2 py-0.5 rounded">GIÁ TẬN GỐC</span>
                        </div>
                        <div class="my-auto py-1 space-y-1.5">
                            <h2 class="text-sm sm:text-base font-extrabold text-white leading-snug">
                                CÔNG TY TNHH MTV MT WINDOW - CỬA ĐẸP CHO MỌI NHÀ
                            </h2>
                            <p class="text-[11px] text-sky-100 leading-normal">
                                Chuyên thi công dự án Khách sạn, Biệt thự, Nhà phố tại Đà Nẵng. Bảo hành uy tín, khảo sát & báo giá miễn phí tận nơi.
                            </p>
                        </div>
                        <div class="grid grid-cols-3 gap-1.5 h-24">
                            <img src="https://lh3.googleusercontent.com/d/1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC" onerror="handleDriveImageError(this, '1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC', 'Xưởng 1')" alt="Ảnh công ty 1" class="w-full h-24 object-cover rounded border border-white/30">
                            <img src="https://lh3.googleusercontent.com/d/1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t" onerror="handleDriveImageError(this, '1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t', 'Cầu Thang')" alt="Ảnh thực tế 4" class="w-full h-24 object-cover rounded border border-white/30">
                            <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc" onerror="handleDriveImageError(this, '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc', 'Phòng Tắm')" alt="Ảnh thực tế 5" class="w-full h-24 object-cover rounded border border-white/30">
                        </div>
                        <div class="pt-2 flex items-center justify-between text-[11px] text-sky-200">
                            <span class="truncate">Hotline/Zalo: 0905.898.755 • mtwindow.com</span>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng & Chấm chuyển Slide Banner -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Banner trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Banner tiếp theo" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-black/65 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-white transition-all" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/50 transition-all" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         KHỐI CAM KẾT CHẤT LƯỢNG & THỐNG KÊ (Giống mẫu ngochanwindow.com)
    =========================================== -->
    <section class="py-4 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3">
                <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-mtblue-700 text-white flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-medal"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm font-bold text-mtblue-800">CHÍNH HÃNG 100%</div>
                        <div class="text-[11px] text-slate-600">Nhôm Xingfa & phụ kiện đồng bộ</div>
                    </div>
                </div>
                <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-mtblue-700 text-white flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-ruler-combined"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm font-bold text-mtblue-800">LẮP ĐẶT TẬN NƠI</div>
                        <div class="text-[11px] text-slate-600">Khảo sát, đo đạc miễn phí Đà Nẵng</div>
                    </div>
                </div>
                <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-mtblue-700 text-white flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-industry"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm font-bold text-mtblue-800">GIÁ GỐC TẬN XƯỞNG</div>
                        <div class="text-[11px] text-slate-600">Sản xuất trực tiếp không qua trung gian</div>
                    </div>
                </div>
                <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                    <div class="w-10 h-10 rounded-lg bg-mtblue-700 text-white flex items-center justify-center shrink-0 text-base">
                        <i class="fa-solid fa-shield-heart"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="text-xs sm:text-sm font-bold text-mtblue-800">BẢO HÀNH DÀI HẠN</div>
                        <div class="text-[11px] text-slate-600">Hỗ trợ kỹ thuật nhanh chóng 24/7</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM NỔI BẬT TRANG CHỦ
         (Lấy đúng 6 danh mục từ ngochanwindow.com, chữ nhỏ gọn, không nhãn dán)
    =========================================== -->
    <section class="py-7 bg-slate-50">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">DANH MỤC SẢN PHẨM NỔI BẬT</span>
                <b></b>
            </div>

            <!-- Thanh danh mục chữ nhỏ gọn, viết liền 1 dòng trên cùng 1 hàng hoặc xuống hàng 2 -->
            <div class="category-nav-list mb-5">
                <button type="button" onclick="filterProductsByCategory('all'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-mtblue-700 text-white hover:bg-mtblue-800">
                    Tất Cả Sản Phẩm
                </button>
                <button type="button" onclick="filterProductsByCategory('cua-nhom-xingfa'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Cửa Nhôm Xingfa
                </button>
                <button type="button" onclick="filterProductsByCategory('cua-nhua-loi-thep'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Cửa Nhựa Lõi Thép
                </button>
                <button type="button" onclick="filterProductsByCategory('cua-kinh-tu-dong'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Cửa Kính Tự Động
                </button>
                <button type="button" onclick="filterProductsByCategory('cau-thang-kinh'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Cầu Thang Kính
                </button>
                <button type="button" onclick="filterProductsByCategory('kinh-op-bep'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Kính Ốp Bếp
                </button>
                <button type="button" onclick="filterProductsByCategory('phong-tam-kinh'); scrollToSection('san-pham-thuc-te')" class="category-nav-item bg-white border border-slate-300 text-mtblue-800 hover:bg-mtblue-50">
                    Phòng Tắm Kính
                </button>
            </div>

            <!-- 6 Ô Danh Mục Sản Phẩm (Chia 2 cột trên điện thoại, 3-6 cột trên máy tính, chữ nhỏ gọn, không nhãn dán) -->
            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div onclick="filterProductsByCategory('cua-nhom-xingfa'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u" onerror="handleDriveImageError(this, '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u', 'Cửa Nhôm Xingfa')" alt="Cửa Nhôm Xingfa" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">CỬA NHÔM XINGFA</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Hệ 55, 63, 93 nhập khẩu</p>
                    </div>
                </div>

                <div onclick="filterProductsByCategory('cua-nhua-loi-thep'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN" onerror="handleDriveImageError(this, '1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN', 'Cửa Nhựa Lõi Thép')" alt="Cửa Nhựa Lõi Thép" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">CỬA NHỰA LÕI THÉP</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cách âm, cách nhiệt tốt</p>
                    </div>
                </div>

                <div onclick="filterProductsByCategory('cua-kinh-tu-dong'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x" onerror="handleDriveImageError(this, '1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x', 'Cửa Kính Tự Động')" alt="Cửa Kính Tự Động" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">CỬA KÍNH TỰ ĐỘNG</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cửa kính cường lực & lùa</p>
                    </div>
                </div>

                <div onclick="filterProductsByCategory('cau-thang-kinh'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t" onerror="handleDriveImageError(this, '1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t', 'Cầu Thang Kính')" alt="Cầu Thang Kính" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">CẦU THANG KÍNH</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Cầu thang & lan can kính</p>
                    </div>
                </div>

                <div onclick="filterProductsByCategory('kinh-op-bep'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE" onerror="handleDriveImageError(this, '19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE', 'Kính Ốp Bếp')" alt="Kính Ốp Bếp" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">KÍNH ỐP BẾP</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Kính màu cường lực bền đẹp</p>
                    </div>
                </div>

                <div onclick="filterProductsByCategory('phong-tam-kinh'); scrollToSection('san-pham-thuc-te')" class="cursor-pointer group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition">
                    <div class="aspect-[4/3] overflow-hidden bg-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc" onerror="handleDriveImageError(this, '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc', 'Phòng Tắm Kính')" alt="Phòng Tắm Kính" class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 text-center">
                        <h3 class="text-xs font-bold text-mtblue-800 whitespace-nowrap">PHÒNG TẮM KÍNH</h3>
                        <p class="text-[11px] text-slate-500 mt-0.5">Vách kính tắm cabin inox 304</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         BÁO GIÁ & SẢN PHẨM THỰC TẾ (13 Ảnh Thực Tế từ Google Drive)
         - Chia 2 cột trên điện thoại (grid-cols-2), 3-4 cột trên máy tính
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
         - Không có nhãn dán ở trang chủ
    =========================================== -->
    <section id="san-pham-thuc-te" class="py-8 bg-white border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">BÁO GIÁ & SẢN PHẨM THI CÔNG THỰC TẾ</span>
                <b></b>
            </div>

            <!-- Thanh lọc danh mục sản phẩm (Chữ nhỏ gọn, viết liền 1 dòng) -->
            <div class="category-nav-list mb-6" id="productFilterButtons">
                <button type="button" data-cat="all" onclick="filterProductsByCategory('all')" class="prod-filter-btn category-nav-item bg-mtblue-700 text-white">
                    Tất Cả (13)
                </button>
                <button type="button" data-cat="cua-nhom-xingfa" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Cửa Nhôm Xingfa
                </button>
                <button type="button" data-cat="cua-nhua-loi-thep" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Cửa Nhựa Lõi Thép
                </button>
                <button type="button" data-cat="cua-kinh-tu-dong" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Cửa Kính Tự Động
                </button>
                <button type="button" data-cat="cau-thang-kinh" onclick="filterProductsByCategory('cau-thang-kinh')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Cầu Thang Kính
                </button>
                <button type="button" data-cat="kinh-op-bep" onclick="filterProductsByCategory('kinh-op-bep')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Kính Ốp Bếp
                </button>
                <button type="button" data-cat="phong-tam-kinh" onclick="filterProductsByCategory('phong-tam-kinh')" class="prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200">
                    Phòng Tắm Kính
                </button>
            </div>

            <!-- Grid Sản Phẩm: 2 cột trên Điện thoại (grid-cols-2), 3 cột trên Tablet, 4 cột trên Máy tính -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 sm:gap-4">
                
                <!-- Sản phẩm 1: 1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa đi mở quay 4 cánh nhôm Xingfa nhập khẩu">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u" onerror="handleDriveImageError(this, '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u', 'Cửa đi 4 cánh Xingfa')" alt="Cửa đi mở quay 4 cánh nhôm Xingfa nhập khẩu" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa đi mở quay 4 cánh nhôm Xingfa nhập khẩu
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa đi mở quay 4 cánh nhôm Xingfa nhập khẩu')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 2: 1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa đi mở quay 2 cánh nhôm Xingfa hệ 55">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv" onerror="handleDriveImageError(this, '1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv', 'Cửa đi 2 cánh Xingfa')" alt="Cửa đi mở quay 2 cánh nhôm Xingfa hệ 55" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa đi mở quay 2 cánh nhôm Xingfa hệ 55
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa đi mở quay 2 cánh nhôm Xingfa hệ 55')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 3: 1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9 -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa nhôm Xingfa cửa đi xếp trượt cao cấp">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9" onerror="handleDriveImageError(this, '1KyVcG2MZw_RD-VuaE5ODgjcVJvBV_jF9', 'Cửa đi xếp trượt Xingfa')" alt="Cửa nhôm Xingfa cửa đi xếp trượt cao cấp" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa nhôm Xingfa cửa đi xếp trượt cao cấp
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa nhôm Xingfa cửa đi xếp trượt cao cấp')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 4: 1HYJsCgo2je2-Ln49KXHOqpcRzZOtxH6W -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa sổ mở hất 2 cánh nhôm Xingfa chính hãng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1HYJsCgo2je2-Ln49KXHOqpcRzZOtxH6W" onerror="handleDriveImageError(this, '1HYJsCgo2je2-Ln49KXHOqpcRzZOtxH6W', 'Cửa sổ mở hất Xingfa')" alt="Cửa sổ mở hất 2 cánh nhôm Xingfa chính hãng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa sổ mở hất 2 cánh nhôm Xingfa chính hãng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa sổ mở hất 2 cánh nhôm Xingfa chính hãng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 5: 1Jtqz7YO9GY3xildzF_3wLK2ADMeImN7- -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa đi mở quay 3 cánh nhôm Xingfa Đà Nẵng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1Jtqz7YO9GY3xildzF_3wLK2ADMeImN7-" onerror="handleDriveImageError(this, '1Jtqz7YO9GY3xildzF_3wLK2ADMeImN7-', 'Cửa đi 3 cánh Xingfa')" alt="Cửa đi mở quay 3 cánh nhôm Xingfa Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa đi mở quay 3 cánh nhôm Xingfa Đà Nẵng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa đi mở quay 3 cánh nhôm Xingfa Đà Nẵng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 6: 1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa đi mở quay 1 cánh nhôm Xingfa phòng ngủ & WC">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe" onerror="handleDriveImageError(this, '1-GyY9h3yJdvY5yZ91mSQvjiqT8EenGLe', 'Cửa đi 1 cánh Xingfa')" alt="Cửa đi mở quay 1 cánh nhôm Xingfa phòng ngủ & WC" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa đi mở quay 1 cánh nhôm Xingfa phòng ngủ & WC
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.100.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa đi mở quay 1 cánh nhôm Xingfa phòng ngủ & WC')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 7: 1RgXZDMcfRLNfFQgdBpTGeUIzPXOC8ucz -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhom-xingfa" data-name="Cửa sổ mở trượt lùa nhôm Xingfa hệ 93 cao cấp">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1RgXZDMcfRLNfFQgdBpTGeUIzPXOC8ucz" onerror="handleDriveImageError(this, '1RgXZDMcfRLNfFQgdBpTGeUIzPXOC8ucz', 'Cửa sổ lùa Xingfa')" alt="Cửa sổ mở trượt lùa nhôm Xingfa hệ 93 cao cấp" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhôm Xingfa</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa sổ mở trượt lùa nhôm Xingfa hệ 93 cao cấp
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">2.050.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa sổ mở trượt lùa nhôm Xingfa hệ 93 cao cấp')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 8: 1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-nhua-loi-thep" data-name="Cửa nhựa lõi thép uPVC cách âm chống ồn Đà Nẵng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN" onerror="handleDriveImageError(this, '1dO_txhpwvwvqTX1ZAVsCvCq_54rCDQZN', 'Cửa nhựa lõi thép')" alt="Cửa nhựa lõi thép uPVC cách âm chống ồn Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Nhựa Lõi Thép</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa nhựa lõi thép uPVC cách âm chống ồn Đà Nẵng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">1.650.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa nhựa lõi thép uPVC cách âm chống ồn Đà Nẵng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 9: 1S_zC1nNmPhYGGpt4aOTVZlb1M3okigkd -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-kinh-tu-dong" data-name="Cửa kính cường lực bản lề sàn mặt tiền Đà Nẵng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1S_zC1nNmPhYGGpt4aOTVZlb1M3okigkd" onerror="handleDriveImageError(this, '1S_zC1nNmPhYGGpt4aOTVZlb1M3okigkd', 'Cửa kính cường lực')" alt="Cửa kính cường lực bản lề sàn mặt tiền Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Kính Tự Động</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa kính cường lực bản lề sàn mặt tiền Đà Nẵng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">950.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Cửa kính cường lực bản lề sàn mặt tiền Đà Nẵng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 10: 1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cua-kinh-tu-dong" data-name="Cửa kính trượt tự động Hàn Quốc 2 cánh, 4 cánh">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x" onerror="handleDriveImageError(this, '1j10IYTaNCPMekLpE-3eqlT-JLXPeDB5x', 'Cửa kính tự động')" alt="Cửa kính trượt tự động Hàn Quốc 2 cánh, 4 cánh" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cửa Kính Tự Động</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa kính trượt tự động Hàn Quốc 2 cánh, 4 cánh
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">Liên hệ báo giá</span>
                        <button type="button" onclick="selectProductForQuote('Cửa kính trượt tự động Hàn Quốc 2 cánh, 4 cánh')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 11: 1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="cau-thang-kinh" data-name="Cầu thang kính cường lực tay vịn gỗ & lan can kính">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t" onerror="handleDriveImageError(this, '1k1M5Xw-H0JGait9c2yjQ37mrsfs_fr_t', 'Cầu thang kính')" alt="Cầu thang kính cường lực tay vịn gỗ & lan can kính" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Cầu Thang Kính</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cầu thang kính cường lực tay vịn gỗ & lan can kính
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">1.250.000 ₫/md</span>
                        <button type="button" onclick="selectProductForQuote('Cầu thang kính cường lực tay vịn gỗ & lan can kính')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 12: 19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="kinh-op-bep" data-name="Kính cường lực ốp bếp sơn màu cao cấp Đà Nẵng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE" onerror="handleDriveImageError(this, '19_hzNMKX6YYmqwl6LsH64J9cscmoCvmE', 'Kính ốp bếp')" alt="Kính cường lực ốp bếp sơn màu cao cấp Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Kính Ốp Bếp</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Kính cường lực ốp bếp sơn màu cao cấp Đà Nẵng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">750.000 ₫/md</span>
                        <button type="button" onclick="selectProductForQuote('Kính cường lực ốp bếp sơn màu cao cấp Đà Nẵng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

                <!-- Sản phẩm 13: 15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc -->
                <div class="product-card bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between" data-category="phong-tam-kinh" data-name="Phòng tắm kính cường lực vách kính cabin Đà Nẵng">
                    <div>
                        <div class="aspect-[4/3] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc" onerror="handleDriveImageError(this, '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc', 'Phòng tắm kính')" alt="Phòng tắm kính cường lực vách kính cabin Đà Nẵng" class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 sm:p-3.5">
                            <div class="text-[11px] text-slate-500 font-medium mb-1">Phòng Tắm Kính</div>
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Phòng tắm kính cường lực vách kính cabin Đà Nẵng
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3.5 sm:pb-3.5 pt-1 border-t border-slate-100 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5">
                        <span class="text-xs sm:text-sm font-extrabold text-mtred-500">1.350.000 ₫/m²</span>
                        <button type="button" onclick="selectProductForQuote('Phòng tắm kính cường lực vách kính cabin Đà Nẵng')" class="px-2.5 py-1.5 rounded bg-mtblue-700 hover:bg-mtblue-800 text-white text-[11px] font-semibold text-center">
                            Nhận báo giá
                        </button>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU CÔNG TY & HÌNH ẢNH NHÀ XƯỞNG HOẠT ĐỘNG
         (Tích hợp đầy đủ 9 Ảnh Công Ty trong file Google Drive)
    =========================================== -->
    <section id="gioi-thieu" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">VỀ CÔNG TY TNHH MTV MT WINDOW</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-start mb-6">
                <div class="lg:col-span-5 bg-white p-5 rounded-xl border border-slate-200 shadow-sm space-y-3">
                    <div class="flex items-center gap-3 pb-3 border-b border-slate-100">
                        <img src="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP" onerror="handleDriveImageError(this, '1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP', 'Logo MT Window')" alt="Logo MT Window" class="h-10 w-10 object-contain rounded border border-slate-200 p-0.5">
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-mtblue-800">CÔNG TY TNHH MTV MT WINDOW</h3>
                            <p class="text-xs text-slate-500">Website: mtwindow.com • MST: 0401956219</p>
                        </div>
                    </div>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                        <strong>CÔNG TY TNHH MTV MT WINDOW</strong> là đơn vị uy tín hàng đầu chuyên tư vấn thiết kế, gia công sản xuất và thi công lắp đặt các hạng mục <strong>Cửa nhôm Xingfa nhập khẩu, Cửa nhựa lõi thép, Cửa kính cường lực, Cửa tự động, Cầu thang kính, Lan can kính, Kính ốp bếp và Phòng tắm kính</strong> tại TP Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
                        Với phương châm <em>“Cửa đẹp cho mọi nhà – Uy tín tạo thương hiệu”</em>, MT Window sở hữu nhà xưởng sản xuất trực tiếp cùng đội ngũ kỹ thuật viên lành nghề, đem lại không gian kiến trúc hiện đại, sang trọng, cách âm cách nhiệt và an toàn bền vững.
                    </p>
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-2 pt-2 text-center">
                        <div class="p-2.5 rounded-lg bg-mtblue-50 border border-mtblue-100">
                            <div class="text-base sm:text-lg font-extrabold text-mtblue-700">150+</div>
                            <div class="text-[11px] text-slate-600">Dự án hoàn thành</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-mtblue-50 border border-mtblue-100">
                            <div class="text-base sm:text-lg font-extrabold text-mtblue-700">50+</div>
                            <div class="text-[11px] text-slate-600">Nhân sự kinh nghiệm</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-mtblue-50 border border-mtblue-100">
                            <div class="text-base sm:text-lg font-extrabold text-mtblue-700">100+</div>
                            <div class="text-[11px] text-slate-600">Mẫu sản phẩm</div>
                        </div>
                        <div class="p-2.5 rounded-lg bg-mtblue-50 border border-mtblue-100">
                            <div class="text-base sm:text-lg font-extrabold text-mtblue-700">100%</div>
                            <div class="text-[11px] text-slate-600">Khách hàng hài lòng</div>
                        </div>
                    </div>
                </div>

                <!-- 9 Ảnh Công Ty thực tế từ Google Drive -->
                <div class="lg:col-span-7">
                    <div class="grid grid-cols-2 sm:grid-cols-3 gap-2.5">
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1erGS-7PZ2rporP7BFywxuzoy6a1dPlMz" onerror="handleDriveImageError(this, '1erGS-7PZ2rporP7BFywxuzoy6a1dPlMz', 'Ảnh Công Ty 1')" alt="Hình ảnh công ty MT Window 1" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Văn phòng & Nhà xưởng MT Window</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC" onerror="handleDriveImageError(this, '1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC', 'Ảnh Công Ty 2')" alt="Hình ảnh công ty MT Window 2" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Xưởng gia công cửa nhôm Xingfa</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1ymsy3X1ALU0F0DAfSApl0Rao9Z-EyyNp" onerror="handleDriveImageError(this, '1ymsy3X1ALU0F0DAfSApl0Rao9Z-EyyNp', 'Ảnh Công Ty 3')" alt="Hình ảnh công ty MT Window 3" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Hệ thống máy sản xuất hiện đại</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/11goNV6LqvK_nBVl6QjhCVtT1Ryc7TcWA" onerror="handleDriveImageError(this, '11goNV6LqvK_nBVl6QjhCVtT1Ryc7TcWA', 'Ảnh Công Ty 4')" alt="Hình ảnh công ty MT Window 4" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Đội ngũ kỹ thuật thi công lắp đặt</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1qBBWyacoMaFNKoXalMZgsMsRzNJuVwiI" onerror="handleDriveImageError(this, '1qBBWyacoMaFNKoXalMZgsMsRzNJuVwiI', 'Ảnh Công Ty 5')" alt="Hình ảnh công ty MT Window 5" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Thi công thực tế tại công trình</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1vMf-VGegi0EldDoVnlNtDjxbrA8Nz7tB" onerror="handleDriveImageError(this, '1vMf-VGegi0EldDoVnlNtDjxbrA8Nz7tB', 'Ảnh Công Ty 6')" alt="Hình ảnh công ty MT Window 6" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Lắp đặt vách kính & cửa mặt tiền</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1su5hiABdfwl5ozT95E6keZK7AQYi-dw6" onerror="handleDriveImageError(this, '1su5hiABdfwl5ozT95E6keZK7AQYi-dw6', 'Ảnh Công Ty 7')" alt="Hình ảnh công ty MT Window 7" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Hoàn thiện cửa nhôm biệt thự</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/16pRxbZBRoZOAmZOr3Dx1jURkZxZ9zjb5" onerror="handleDriveImageError(this, '16pRxbZBRoZOAmZOr3Dx1jURkZxZ9zjb5', 'Ảnh Công Ty 8')" alt="Hình ảnh công ty MT Window 8" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Công trình nhà phố Đà Nẵng</div>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-sm col-span-2 sm:col-span-1">
                            <div class="aspect-[4/3] bg-slate-100">
                                <img src="https://lh3.googleusercontent.com/d/1nowTAPJ_-z53Avov5smG5_fih5ra0dkU" onerror="handleDriveImageError(this, '1nowTAPJ_-z53Avov5smG5_fih5ra0dkU', 'Ảnh Công Ty 9')" alt="Hình ảnh công ty MT Window 9" class="w-full h-full object-cover">
                            </div>
                            <div class="p-2 text-center text-[11px] font-semibold text-slate-700">Kiểm định & bàn giao công trình</div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG
         (Chuẩn danh mục dự án từ web mẫu ngochanwindow.com, chia 2 cột trên điện thoại, không nhãn dán)
    =========================================== -->
    <section id="du-an-da-nang" class="py-8 bg-white border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">DANH MỤC CÁC DỰ ÁN NỔI BẬT TẠI ĐÀ NẴNG</span>
                <b></b>
            </div>

            <!-- Danh mục phân loại Dự án tại Đà Nẵng (Chữ nhỏ gọn, viết liền 1 dòng) -->
            <div class="category-nav-list mb-6">
                <button type="button" onclick="filterProjects('all')" class="proj-filter-btn category-nav-item bg-mtblue-700 text-white" data-pcat="all">
                    Tất Cả Dự Án
                </button>
                <button type="button" onclick="filterProjects('khach-san')" class="proj-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200" data-pcat="khach-san">
                    Dự Án Về Khách Sạn
                </button>
                <button type="button" onclick="filterProjects('can-ho')" class="proj-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200" data-pcat="can-ho">
                    Dự Án Về Căn Hộ & Resort
                </button>
                <button type="button" onclick="filterProjects('nha-pho')" class="proj-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200" data-pcat="nha-pho">
                    Dự Án Về Nhà Phố & Biệt Thự
                </button>
                <button type="button" onclick="filterProjects('co-quan')" class="proj-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200" data-pcat="co-quan">
                    Dự Án Cơ Quan & Showroom
                </button>
            </div>

            <!-- Grid Dự án tại Đà Nẵng: 2 cột trên điện thoại, 3 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5" id="projectGrid">
                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="khach-san">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1qBBWyacoMaFNKoXalMZgsMsRzNJuVwiI" onerror="handleDriveImageError(this, '1qBBWyacoMaFNKoXalMZgsMsRzNJuVwiI', 'Dự Án Raon Beach Đà Nẵng')" alt="Thi công dự án Raon Đà Nẵng Beach Hotel" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            THI CÔNG DỰ ÁN KHÁCH SẠN RAON ĐÀ NẴNG BEACH HOTEL
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Hệ thống cửa đi, cửa sổ nhôm Xingfa & vách kính mặt dựng cách âm ven biển Đà Nẵng.</p>
                    </div>
                </div>

                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="khach-san">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/16pRxbZBRoZOAmZOr3Dx1jURkZxZ9zjb5" onerror="handleDriveImageError(this, '16pRxbZBRoZOAmZOr3Dx1jURkZxZ9zjb5', 'Dự Án Khách Sạn Golden Line')" alt="Thi công dự án Khách sạn Golden Line Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            THI CÔNG DỰ ÁN KHÁCH SẠN GOLDEN LINE ĐÀ NẴNG
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Cửa nhôm kính Xingfa nhập khẩu, phòng tắm kính cường lực & lan can kính.</p>
                    </div>
                </div>

                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="khach-san">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1vMf-VGegi0EldDoVnlNtDjxbrA8Nz7tB" onerror="handleDriveImageError(this, '1vMf-VGegi0EldDoVnlNtDjxbrA8Nz7tB', 'Dự Án Khách Sạn Soho Đà Nẵng')" alt="Thi công dự án Khách sạn Soho Boutique Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            THI CÔNG DỰ ÁN KHÁCH SẠN SOHO BOUTIQUE ĐÀ NẴNG
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Cửa kính cường lực tự động sảnh chính, vách kính mặt tiền & cabin tắm kính.</p>
                    </div>
                </div>

                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="can-ho">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1su5hiABdfwl5ozT95E6keZK7AQYi-dw6" onerror="handleDriveImageError(this, '1su5hiABdfwl5ozT95E6keZK7AQYi-dw6', 'Dự Án Căn Hộ Jolia Đà Nẵng')" alt="Thi công dự án Căn hộ & Khách sạn Jolia Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            THI CÔNG DỰ ÁN KHÁCH SẠN & CĂN HỘ JOLIA ĐÀ NẴNG
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Cửa sổ mở hất, cửa đi lùa nhôm Xingfa hệ 93 và kính ốp bếp cao cấp.</p>
                    </div>
                </div>

                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="nha-pho">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/1nowTAPJ_-z53Avov5smG5_fih5ra0dkU" onerror="handleDriveImageError(this, '1nowTAPJ_-z53Avov5smG5_fih5ra0dkU', 'Dự Án Khu Đô Thị Phước Lý')" alt="Thi công Biệt thự & Nhà phố Khu TĐC Phước Lý Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            DỰ ÁN NHÀ PHỐ & BIỆT THỰ KHU TĐC PHƯỚC LÝ - AN KHÊ ĐÀ NẴNG
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Trọn gói cửa đi 4 cánh nhôm Xingfa, cầu thang kính tay vịn gỗ & phòng tắm kính.</p>
                    </div>
                </div>

                <div class="project-card bg-slate-50 rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition" data-pcat="co-quan">
                    <div class="aspect-[16/10] bg-slate-200 overflow-hidden">
                        <img src="https://lh3.googleusercontent.com/d/11goNV6LqvK_nBVl6QjhCVtT1Ryc7TcWA" onerror="handleDriveImageError(this, '11goNV6LqvK_nBVl6QjhCVtT1Ryc7TcWA', 'Dự Án Khách Sạn Ruby Light')" alt="Thi công dự án Khách sạn Ruby Light & Văn phòng Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3">
                        <h3 class="product-title-full text-xs sm:text-sm font-bold text-mtblue-800">
                            DỰ ÁN KHÁCH SẠN RUBY LIGHT & KHỐI VĂN PHÒNG ĐÀ NẴNG
                        </h3>
                        <p class="text-[11px] text-slate-600 mt-1">Hạng mục: Vách kính cường lực văn phòng, cửa nhựa lõi thép và hệ cửa nhôm Xingfa đồng bộ.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU TƯ VẤN VÀ NHẬN BÁO GIÁ TRANG CHỦ
    =========================================== -->
    <section id="form-bao-gia" class="py-8 bg-gradient-to-r from-mtblue-900 via-mtblue-800 to-mtblue-700 text-white">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                <div class="lg:col-span-5 space-y-3">
                    <div class="inline-block px-3 py-1 rounded bg-white/15 text-sky-200 text-xs font-bold">
                        BÁO GIÁ NHANH TRONG 5 PHÚT
                    </div>
                    <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold leading-snug">
                        ĐĂNG KÝ YÊU CẦU TƯ VẤN & NHẬN BÁO GIÁ THI CÔNG TẠI ĐÀ NẴNG
                    </h2>
                    <p class="text-xs sm:text-sm text-sky-100 leading-relaxed">
                        Quý khách vui lòng để lại thông tin hoặc kích thước sơ bộ. Kỹ sư của <strong>CÔNG TY TNHH MTV MT WINDOW</strong> sẽ liên hệ tư vấn phương án tối ưu và gửi bảng báo giá chi tiết ưu đãi nhất.
                    </p>
                    <div class="space-y-2 pt-1 text-xs sm:text-sm">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-amber-300"></i>
                            <span>Hotline / Zalo: <strong class="text-white">0905.898.755</strong></span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-location-dot text-amber-300"></i>
                            <span>Địa chỉ: Lô số 13 Khu B2-7 Đường Đinh Liệt, Khu TĐC Phước Lý, Phường An Khê, TP Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-amber-300"></i>
                            <span>Website: <strong>mtwindow.com</strong></span>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="bg-white text-slate-800 p-4 sm:p-6 rounded-xl shadow-lg space-y-3.5">
                        <h3 class="text-sm sm:text-base font-extrabold text-mtblue-800 border-b border-slate-200 pb-2">
                            FORM YÊU CẦU & BÁO GIÁ TRực TUYẾN
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs focus:outline-none focus:border-mtblue-600">
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0905898755" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs focus:outline-none focus:border-mtblue-600">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục cần báo giá *</label>
                                <select id="qCategory" class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs focus:outline-none focus:border-mtblue-600 bg-white">
                                    <option value="Cửa Nhôm Xingfa Nhập Khẩu">Cửa Nhôm Xingfa Nhập Khẩu</option>
                                    <option value="Cửa Nhựa Lõi Thép uPVC">Cửa Nhựa Lõi Thép uPVC</option>
                                    <option value="Cửa Kính Cường Lực & Cửa Tự Động">Cửa Kính Cường Lực & Cửa Tự Động</option>
                                    <option value="Cầu Thang Kính & Lan Can Kính">Cầu Thang Kính & Lan Can Kính</option>
                                    <option value="Kính Cường Lực Ốp Bếp">Kính Cường Lực Ốp Bếp</option>
                                    <option value="Phòng Tắm Kính Cabin">Phòng Tắm Kính Cabin</option>
                                    <option value="Thi Công Trọn Gói Công Trình">Thi Công Trọn Gói Công Trình</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-semibold text-slate-700 mb-1">Địa chỉ công trình tại Đà Nẵng</label>
                                <input id="qAddress" type="text" placeholder="Quận/Phường tại Đà Nẵng..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs focus:outline-none focus:border-mtblue-600">
                            </div>
                        </div>
                        <div>
                            <label class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu / Kích thước hoặc mẫu sản phẩm quan tâm</label>
                            <textarea id="qNote" rows="2" placeholder="Nhập yêu cầu tư vấn, số lượng cửa hoặc kích thước..." class="w-full px-3 py-2 rounded-lg border border-slate-300 text-xs focus:outline-none focus:border-mtblue-600"></textarea>
                        </div>
                        <div id="quoteSuccessNotification" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                        <div class="flex flex-col sm:flex-row items-stretch sm:items-center justify-between gap-2 pt-1">
                            <button type="submit" class="px-5 py-2.5 rounded-lg bg-mtred-500 hover:bg-mtred-600 text-white text-xs font-bold transition shadow">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU BÁO GIÁ
                            </button>
                            <a href="https://zalo.me/0905898755" target="_blank" rel="noopener noreferrer" class="px-4 py-2.5 rounded-lg bg-mtblue-50 hover:bg-mtblue-100 text-mtblue-800 text-xs font-bold text-center border border-mtblue-200 transition">
                                Chat Zalo nhận báo giá: 0905.898.755
                            </a>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ
         (Lấy chủ đề bài viết thực tế từ ngochanwindow.com, chia 2 cột trên điện thoại, 4 cột trên máy tính)
    =========================================== -->
    <section id="tin-tuc" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">DANH MỤC BÀI VIẾT & KINH NGHIỆM NHÔM KÍNH</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u" onerror="handleDriveImageError(this, '1do1PKpzoa5GIEjkObMrflqJHqtxRqC5u', 'Tin tức 1')" alt="Cửa nhôm Xingfa có phù hợp với khí hậu Đà Nẵng không" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa nhôm Xingfa có phù hợp với khí hậu miền Trung & Đà Nẵng không?
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 line-clamp-3">
                                Cửa nhôm Xingfa nhập khẩu kết hợp phụ kiện Kinlong đồng bộ có khả năng chống chịu bão gió, chống ăn mòn muối biển và cách âm vượt trội.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-mtblue-700 hover:underline">Xem chi tiết & Báo giá →</a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv" onerror="handleDriveImageError(this, '1_0OPEN23aiahMJJKTvxpzEF4xBkWv4Gv', 'Tin tức 2')" alt="So sánh cửa nhôm Xingfa và cửa nhựa lõi thép" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Cửa nhôm Xingfa có tốt hơn cửa gỗ và cửa nhựa lõi thép không?
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 line-clamp-3">
                                Phân tích ưu nhược điểm chi tiết về độ bền, tính thẩm mỹ, khả năng chống cong vênh mối mọt và chi phí lắp đặt cho nhà phố, biệt thự.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-mtblue-700 hover:underline">Xem chi tiết & Báo giá →</a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc" onerror="handleDriveImageError(this, '15huQBtVZfLCY0SXZegjtXNBQCK5I2ZCc', 'Tin tức 3')" alt="Kinh nghiệm lắp đặt phòng tắm kính và kính ốp bếp" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Tư vấn chọn phòng tắm kính cường lực & kính ốp bếp bền đẹp tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 line-clamp-3">
                                Lựa chọn kính cường lực 8ly - 10ly kết hợp phụ kiện Inox 304 chống gỉ giúp không gian bếp và phòng tắm luôn sáng bóng, hiện đại.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-mtblue-700 hover:underline">Xem chi tiết & Báo giá →</a>
                    </div>
                </article>

                <article class="bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition flex flex-col justify-between">
                    <div>
                        <div class="aspect-[16/10] bg-slate-100 overflow-hidden">
                            <img src="https://lh3.googleusercontent.com/d/1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC" onerror="handleDriveImageError(this, '1ZmPa0Q5lbLuRYvN46gLMvL-OUjXSsIJC', 'Tin tức 4')" alt="Địa chỉ gia công lắp đặt cửa nhôm Xingfa uy tín Đà Nẵng" class="w-full h-full object-cover">
                        </div>
                        <div class="p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-mtblue-700">
                                Bảng báo giá thi công cửa nhôm Xingfa & cửa kính cường lực Đà Nẵng mới nhất
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-1.5 line-clamp-3">
                                Cập nhật đơn giá sản xuất và lắp đặt hoàn thiện tại xưởng Công ty TNHH MTV MT Window - Cam kết chính hãng 100%, bảo hành chu đáo.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-mtblue-700 hover:underline">Xem chi tiết & Báo giá →</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC ĐỐI TÁC CỦA CHÚNG TÔI (Giống mẫu ngochanwindow.com)
    =========================================== -->
    <section class="py-7 bg-white border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">ĐỐI TÁC CỦA CHÚNG TÔI</span>
                <b></b>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-mtred-600 tracking-wider">XINGFA</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Nhôm Xingfa Quảng Đông</div>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-mtblue-800 tracking-wider">KINLONG</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Phụ Kiện Đồng Bộ</div>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-sky-700 tracking-wider">VVP THAILAND</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Bản Lề Sàn & Phụ Kiện Kính</div>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-amber-700 tracking-wider">MITADOOR</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Giải Pháp Cửa Hiện Đại</div>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-emerald-700 tracking-wider">CHU LAI GLASS</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Phôi Kính Cường Lực Cao Cấp</div>
                </div>
                <div class="p-3 rounded-xl border border-slate-200 bg-slate-50 flex flex-col items-center justify-center text-center">
                    <div class="text-xs sm:text-sm font-black text-indigo-800 tracking-wider">DRAHO / CMECH</div>
                    <div class="text-[11px] text-slate-600 font-medium mt-0.5">Phụ Kiện Cửa Nhôm Cao Cấp</div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         ĐƯA GOOGLE MAP VÀ FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ
    =========================================== -->
    <section id="ban-do-fanpage" class="py-8 bg-slate-50 border-t border-slate-200">
        <div class="ux-container">
            <div class="flatsome-section-title">
                <b></b>
                <span class="text-base sm:text-lg md:text-xl">BẢN ĐỒ GOOGLE MAPS & FANPAGE CHÍNH THỨC</span>
                <b></b>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Cột 1: Bản đồ Google Map ngoài trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between">
                    <div class="p-3.5 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2 bg-slate-50">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-mtblue-800">
                                <i class="fa-solid fa-map-location-dot mr-1.5 text-mtred-500"></i>VỊ TRÍ GOOGLE MAPS - CÔNG TY TNHH MTV MT WINDOW
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-0.5">
                                Lô số 13 Khu B2-7 Đường Đinh Liệt, Khu TĐC Phước Lý, Phường An Khê, TP Đà Nẵng
                            </p>
                        </div>
                        <a 
                            href="https://www.google.com/maps/search/?api=1&query=C%C3%94NG+TY+TNHH+MTV+MT+WINDOW+%C4%90inh+Li%E1%BB%87t+Ph%C6%B0%E1%BB%9Bc+L%C3%BD+%C4%90%C3%A0+N%E1%BA%B5ng" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="px-3 py-1.5 rounded-lg bg-mtblue-700 hover:bg-mtblue-800 text-white text-xs font-semibold shrink-0"
                        >
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Google Maps lớn
                        </a>
                    </div>
                    <div class="w-full h-[320px] sm:h-[360px] bg-slate-100 relative">
                        <iframe 
                            title="Bản đồ Google Maps Công Ty TNHH MTV MT Window Đà Nẵng"
                            src="https://maps.google.com/maps?q=Đinh%20Liệt,%20Khu%20TĐC%20Phước%20Lý,%20Đà%20Nẵng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            allowfullscreen="" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột 2: Đưa Fanpage Facebook ra ngoài trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col justify-between">
                    <div class="p-3.5 border-b border-slate-200 flex items-center justify-between gap-2 bg-slate-50">
                        <div>
                            <h3 class="text-xs sm:text-sm font-extrabold text-mtblue-800">
                                <i class="fa-brands fa-facebook mr-1.5 text-blue-600"></i>FANPAGE FACEBOOK CHÍNH THỨC
                            </h3>
                            <p class="text-[11px] text-slate-600 mt-0.5">facebook.com/cuanhomxinfadanang</p>
                        </div>
                        <a 
                            href="https://www.facebook.com/cuanhomxinfadanang" 
                            target="_blank" 
                            rel="noopener noreferrer"
                            class="px-3 py-1.5 rounded-lg bg-blue-600 hover:bg-blue-700 text-white text-xs font-semibold shrink-0"
                        >
                            Theo dõi Fanpage
                        </a>
                    </div>

                    <div class="p-4 flex-1 flex flex-col justify-between space-y-3">
                        <!-- Khung kết nối trực tiếp Fanpage Facebook -->
                        <div class="flex items-center gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200">
                            <img 
                                src="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP" 
                                onerror="handleDriveImageError(this, '1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP', 'Logo')" 
                                alt="Logo Fanpage MT Window" 
                                class="w-12 h-12 object-contain rounded-lg border border-slate-200 bg-white p-1 shrink-0"
                            >
                            <div class="min-w-0">
                                <a href="https://www.facebook.com/cuanhomxinfadanang" target="_blank" rel="noopener noreferrer" class="text-xs sm:text-sm font-extrabold text-blue-700 hover:underline block">
                                    Cửa Nhôm Xingfa Đà Nẵng - MT Window
                                </a>
                                <p class="text-[11px] text-slate-500">CÔNG TY TNHH MTV MT WINDOW • 0905.898.755</p>
                                <div class="flex items-center gap-2 mt-1.5">
                                    <a href="https://www.facebook.com/cuanhomxinfadanang" target="_blank" rel="noopener noreferrer" class="px-2.5 py-1 rounded bg-blue-600 text-white text-[11px] font-semibold">
                                        <i class="fa-solid fa-thumbs-up mr-1"></i>Thích Trang
                                    </a>
                                    <a href="https://www.facebook.com/cuanhomxinfadanang" target="_blank" rel="noopener noreferrer" class="px-2.5 py-1 rounded bg-slate-200 text-slate-800 text-[11px] font-semibold">
                                        <i class="fa-brands fa-facebook-messenger mr-1 text-blue-600"></i>Gửi tin nhắn
                                    </a>
                                </div>
                            </div>
                        </div>

                        <!-- Nhúng Facebook Page Plugin chuẩn + Hình ảnh hoạt động trên Fanpage -->
                        <div class="w-full overflow-hidden rounded-lg border border-slate-200 bg-slate-50">
                            <iframe 
                                title="Fanpage Facebook Cửa Nhôm Xingfa Đà Nẵng"
                                src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fcuanhomxinfadanang&tabs=timeline&width=340&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                class="w-full h-[210px] border-0 overflow-hidden" 
                                scrolling="no" 
                                frameborder="0" 
                                allowfullscreen="true" 
                                allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                            </iframe>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Logo gọn nhỏ, đầy đủ danh mục & thông tin Công ty)
    =========================================== -->
    <footer class="bg-mtblue-900 text-slate-200 pt-10 pb-20 md:pb-8 border-t-4 border-mtblue-600">
        <div class="ux-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6 pb-8 border-b border-white/15">
                <!-- Cột 1: Thông tin liên hệ -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <img 
                            src="https://lh3.googleusercontent.com/d/1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP" 
                            onerror="handleDriveImageError(this, '1DtPAhZjBbrQXxRl0tpTErsLQ2zqKejEP', 'Logo')" 
                            alt="Logo MT Window" 
                            class="h-9 w-9 object-contain rounded bg-white p-0.5 shrink-0"
                        >
                        <div>
                            <div class="text-sm font-extrabold text-white">CÔNG TY TNHH MTV MT WINDOW</div>
                            <div class="text-[11px] text-sky-300">Website: mtwindow.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-sky-400 mt-1"></i>
                            <span><strong>Địa chỉ:</strong> Lô số 13 Khu B2-7 Đường Đinh Liệt, Khu TĐC Phước Lý, Phường An Khê, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-sky-400"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0905898755" class="text-white font-bold hover:underline">0905.898.755</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-id-card text-sky-400"></i>
                            <span><strong>Mã số thuế:</strong> 0401956219</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-brands fa-facebook text-sky-400"></i>
                            <span><strong>Fanpage:</strong> <a href="https://www.facebook.com/cuanhomxinfadanang" target="_blank" rel="noopener noreferrer" class="hover:text-white underline">fb.com/cuanhomxinfadanang</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục dịch vụ -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-white/15 pb-2">DANH MỤC SẢN PHẨM</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">› Cửa Nhôm Xingfa Đà Nẵng</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhom-xingfa')" class="hover:text-white">› Cửa nhôm Xingfa 1 cánh, 2 cánh, 4 cánh</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-nhua-loi-thep')" class="hover:text-white">› Cửa Nhựa Lõi Thép Đà Nẵng</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cua-kinh-tu-dong')" class="hover:text-white">› Cửa Kính Cường Lực & Cửa Tự Động</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('cau-thang-kinh')" class="hover:text-white">› Cầu Thang Kính & Lan Can Kính</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('kinh-op-bep')" class="hover:text-white">› Kính Ốp Bếp Cường Lực Đà Nẵng</a></li>
                        <li><a href="#san-pham-thuc-te" onclick="filterProductsByCategory('phong-tam-kinh')" class="hover:text-white">› Phòng Tắm Kính Cường Lực Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-white/15 pb-2">CHÍNH SÁCH & DỊCH VỤ</h4>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><a href="#form-bao-gia" class="hover:text-white">› Khảo sát & đo đạc tận nhà miễn phí</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-white">› Báo giá cửa nhôm Xingfa chính hãng</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-white">› Hồ sơ năng lực & Dự án tiêu biểu</a></li>
                        <li><a href="#gioi-thieu" class="hover:text-white">› Chính sách bảo hành & bảo trì dài hạn</a></li>
                        <li><a href="#ban-do-fanpage" class="hover:text-white">› Chỉ đường đến Xưởng & Showroom</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Cam kết thương hiệu -->
                <div>
                    <h4 class="text-sm font-extrabold text-white uppercase mb-3 border-b border-white/15 pb-2">CAM KẾT MT WINDOW</h4>
                    <p class="text-xs text-slate-300 leading-relaxed mb-3">
                        CÔNG TY TNHH MTV MT WINDOW cam kết sử dụng thanh nhôm Xingfa chính hãng, kính cường lực phôi chuẩn và phụ kiện đồng bộ 100%, mang đến những bộ cửa bền đẹp, thẩm mỹ cao cho mọi công trình tại Đà Nẵng.
                    </p>
                    <div class="p-3 rounded-lg bg-white/10 border border-white/15 text-xs">
                        <div class="font-bold text-amber-300">TƯ VẤN KỸ THUẬT & BÁO GIÁ 24/7</div>
                        <a href="tel:0905898755" class="text-base font-extrabold text-white block mt-0.5">0905.898.755</a>
                    </div>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400 text-center sm:text-left">
                <div>© Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH MTV MT WINDOW (mtwindow.com)</strong>.</div>
                <div>Địa chỉ: Lô số 13 Khu B2-7 Đường Đinh Liệt, Khu TĐC Phước Lý, P. An Khê, TP Đà Nẵng</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả Máy tính và Điện thoại
    =========================================== -->
    <div class="fixed bottom-4 left-3 z-50 flex flex-col gap-2.5">
        <!-- Nút Zalo nổi bật -->
        <a 
            href="https://zalo.me/0905898755" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-sky-500 hover:bg-sky-600 text-white px-3 py-2 rounded-full shadow-lg border-2 border-white transition transform hover:scale-105"
            title="Chat Zalo 0905.898.755"
        >
            <span class="w-7 h-7 rounded-full bg-white text-sky-600 font-black text-xs flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a 
            href="https://www.facebook.com/cuanhomxinfadanang" 
            target="_blank" 
            rel="noopener noreferrer"
            class="flex items-center gap-2 bg-blue-600 hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg border-2 border-white transition transform hover:scale-105"
            title="Fanpage Cửa Nhôm Xingfa Đà Nẵng"
        >
            <span class="w-7 h-7 rounded-full bg-white text-blue-600 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a 
            href="tel:0905898755" 
            class="pulse-hotline flex items-center gap-2 bg-mtred-500 hover:bg-mtred-600 text-white px-3 py-2 rounded-full shadow-lg border-2 border-white transition transform hover:scale-105"
            title="Gọi ngay 0905.898.755"
        >
            <span class="w-7 h-7 rounded-full bg-white text-mtred-500 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold pr-1">0905.898.755</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ SLIDER TỰ TRƯỢT, LỌC DANH MỤC & FORM BÁO GIÁ
    =========================================== -->
    <script>
        // 1. Tự động trượt 2 Banner chuyên nghiệp
        let currentSlideIndex = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.banner-dot');
        let slideTimer = null;

        function showSlide(index) {
            if (!slides.length) return;
            currentSlideIndex = (index + slides.length) % slides.length;
            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            dots.forEach((dot, idx) => {
                if (idx === currentSlideIndex) {
                    dot.className = 'banner-dot w-6 h-2 rounded-full bg-white transition-all';
                } else {
                    dot.className = 'banner-dot w-2.5 h-2 rounded-full bg-white/50 transition-all';
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlideIndex + step);
            resetSlideTimer();
        }

        function goToSlide(index) {
            showSlide(index);
            resetSlideTimer();
        }

        function resetSlideTimer() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                showSlide(currentSlideIndex + 1);
            }, 5000);
        }

        // 2. Bật/tắt Menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        // 3. Cuộn mượt đến section
        function scrollToSection(id) {
            const el = document.getElementById(id);
            if (el) {
                el.scrollIntoView({ behavior: 'smooth' });
            }
        }

        // 4. Lọc sản phẩm theo danh mục
        function filterProductsByCategory(category) {
            const cards = document.querySelectorAll('.product-card');
            const buttons = document.querySelectorAll('.prod-filter-btn');

            buttons.forEach(btn => {
                if (btn.dataset.cat === category) {
                    btn.className = 'prod-filter-btn category-nav-item bg-mtblue-700 text-white';
                } else {
                    btn.className = 'prod-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200';
                }
            });

            cards.forEach(card => {
                if (category === 'all' || card.dataset.category === category) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 5. Tìm kiếm sản phẩm theo từ khóa
        function searchProducts(keyword) {
            const normalized = (keyword || '').toLowerCase().trim();
            const cards = document.querySelectorAll('.product-card');
            cards.forEach(card => {
                const name = (card.dataset.name || '').toLowerCase();
                if (!normalized || name.includes(normalized)) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 6. Lọc dự án tại Đà Nẵng
        function filterProjects(pcat) {
            const cards = document.querySelectorAll('.project-card');
            const buttons = document.querySelectorAll('.proj-filter-btn');

            buttons.forEach(btn => {
                if (btn.dataset.pcat === pcat) {
                    btn.className = 'proj-filter-btn category-nav-item bg-mtblue-700 text-white';
                } else {
                    btn.className = 'proj-filter-btn category-nav-item bg-slate-100 text-slate-700 hover:bg-slate-200';
                }
            });

            cards.forEach(card => {
                if (pcat === 'all' || card.dataset.pcat === pcat) {
                    card.classList.remove('hidden');
                } else {
                    card.classList.add('hidden');
                }
            });
        }

        // 7. Chọn sản phẩm điền nhanh vào Form báo giá
        function selectProductForQuote(productName) {
            const noteInput = document.getElementById('qNote');
            if (noteInput) {
                noteInput.value = 'Tôi cần tư vấn & báo giá sản phẩm: ' + productName;
            }
            scrollToSection('form-bao-gia');
            const nameInput = document.getElementById('qName');
            if (nameInput) nameInput.focus();
        }

        // 8. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const cat = document.getElementById('qCategory').value;
            const addr = document.getElementById('qAddress').value.trim();
            const notif = document.getElementById('quoteSuccessNotification');

            if (notif) {
                notif.innerHTML = '<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>' + name + '</strong> (' + phone + ')! Yêu cầu báo giá hạng mục <strong>' + cat + '</strong> ' + (addr ? 'tại ' + addr : '') + ' đã được ghi nhận. Bộ phận kỹ thuật CÔNG TY TNHH MTV MT WINDOW (0905.898.755) sẽ liên hệ ngay với quý khách.';
                notif.classList.remove('hidden');
            }
        }

        window.onload = function () {
            resetSlideTimer();
        };
    </script>
</body>
</html>
