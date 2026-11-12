<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN - Sắt Thép Xây Dựng & Công Nghiệp Đà Nẵng | satthepxuantin.com</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN (satthepxuantin.com) chuyên cung cấp Thép Xây Dựng, Thép Hình U I V H, Thép Hộp, Thép Ống, Thép Tấm, Xà Gồ, Tôn Lợp, Lưới B40, Inox uy tín hàng đầu tại Đà Nẵng và Miền Trung.">
    
    <!-- Open Graph / Thumbnail là ảnh Logo trang web khi gửi link -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://satthepxuantin.com/">
    <meta property="og:site_name" content="satthepxuantin.com">
    <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN - Sắt Thép Đà Nẵng">
    <meta property="og:description" content="Hệ thống kho hàng Sắt Thép Xây Dựng, Thép Hình, Thép Tấm, Thép Hộp, Thép Ống, Xà Gồ, Tôn Lợp chính hãng giá tốt tại Đà Nẵng. Hotline: 02363.767.779 - 0908.767.778">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w1200">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w1200">
    <link rel="icon" href="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w200">

    <!-- Google Fonts: Inter & Roboto (Chuẩn Flatsome) -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0c2d57',
                            blue: '#15437e',
                            red: '#c81e1e',
                            redDark: '#a31515',
                            light: '#f4f6f9',
                            border: '#e2e8f0'
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền và lệch phải tuyệt đối trên mọi thiết bị */
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
            background-color: #f5f7fa;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Chiều ngang giao diện trên máy tính bằng 95% kích thước màn hình máy tính */
        .ux-container {
            width: 100%;
            padding-left: 10px;
            padding-right: 10px;
            margin-left: auto;
            margin-right: auto;
        }
        @media (min-width: 1024px) {
            .ux-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tối ưu thanh menu danh mục trên máy tính: chữ nhỏ gọn, viết liền trên 1 hàng không bị xuống dòng tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-start;
            gap: 2px;
        }
        .desktop-nav-item {
            position: relative;
            white-space: nowrap !important;
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            padding: 9px 8px;
            font-size: 11.5px;
            font-weight: 700;
            color: #ffffff;
            text-transform: uppercase;
            white-space: nowrap !important;
            transition: background-color 0.2s ease;
            border-radius: 4px;
            letter-spacing: -0.01em;
        }
        @media (min-width: 1366px) {
            .desktop-nav-link {
                padding: 10px 10px;
                font-size: 12.2px;
            }
        }
        .desktop-nav-link:hover, .desktop-nav-item:hover > .desktop-nav-link {
            background-color: #c81e1e;
            color: #ffffff;
        }

        /* Dropdown menu chuẩn Flatsome */
        .ux-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 230px;
            background: #ffffff;
            box-shadow: 0 10px 25px rgba(0,0,0,0.15);
            border-top: 3px solid #c81e1e;
            border-radius: 0 0 6px 6px;
            z-index: 100;
            padding: 6px 0;
        }
        .desktop-nav-item:hover .ux-dropdown {
            display: block;
        }
        .ux-dropdown a {
            display: block;
            padding: 7px 14px;
            font-size: 12.5px;
            font-weight: 500;
            color: #1e293b;
            white-space: nowrap;
            border-bottom: 1px solid #f1f5f9;
            transition: all 0.15s ease;
        }
        .ux-dropdown a:last-child {
            border-bottom: none;
        }
        .ux-dropdown a:hover {
            background-color: #f8fafc;
            color: #c81e1e;
            padding-left: 18px;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder */
        .ux-section-title {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0c2d57;
            margin-bottom: 14px;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
        }
        .ux-section-heading {
            background: #0c2d57;
            color: #ffffff;
            font-weight: 700;
            font-size: 13.5px;
            padding: 9px 16px;
            text-transform: uppercase;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            border-radius: 6px 6px 0 0;
            position: relative;
        }
        @media (min-width: 768px) {
            .ux-section-heading {
                font-size: 15px;
                padding: 10px 20px;
            }
        }

        /* Card sản phẩm chuẩn Flatsome - Tên sản phẩm hiển thị đầy đủ không bị cắt hay tràn ra ngoài */
        .ux-product-box {
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 6px;
            overflow: hidden;
            display: flex;
            flex-direction: column;
            height: 100%;
            transition: transform 0.2s ease, box-shadow 0.2s ease, border-color 0.2s ease;
        }
        .ux-product-box:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 20px rgba(12, 45, 87, 0.1);
            border-color: #0c2d57;
        }
        .ux-product-title {
            font-size: 13px;
            line-height: 1.4;
            font-weight: 600;
            color: #0f172a;
            word-wrap: break-word;
            overflow-wrap: break-word;
            white-space: normal;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .ux-product-title {
                font-size: 13.8px;
            }
        }

        /* Danh mục nhỏ gọn trên trang chủ */
        .ux-cat-chip {
            white-space: nowrap !important;
            font-size: 11.5px;
            line-height: 1.25;
        }
        @media (min-width: 768px) {
            .ux-cat-chip {
                font-size: 12.5px;
            }
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { box-shadow: 0 0 0 0 rgba(200, 30, 30, 0.6); }
            70% { box-shadow: 0 0 0 10px rgba(200, 30, 30, 0); }
            100% { box-shadow: 0 0 0 0 rgba(200, 30, 30, 0); }
        }
        .float-pulse {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

    <!-- ==========================================
         TOP BAR (Chuẩn Flatsome Topbar)
    =========================================== -->
    <div class="bg-brand-navy text-white text-[11.5px] md:text-xs py-1.5 border-b border-white/10">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 truncate max-w-full">
                <i class="fa-solid fa-building-shield text-amber-400 shrink-0"></i>
                <span class="font-medium truncate">CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN — Đại Lý Sắt Thép Uy Tín Tại Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-4 shrink-0">
                <span><i class="fa-solid fa-envelope text-amber-400 mr-1"></i>xuantinsteel79@gmail.com</span>
                <span><i class="fa-solid fa-clock text-amber-400 mr-1"></i>Thứ 2 - Thứ 7: 07:00 - 17:30</span>
                <a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="hover:text-amber-300 transition">
                    <i class="fa-brands fa-facebook mr-1"></i>fb.com/satthepxuantin
                </a>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HEADER MAIN (Logo gọn nhỏ, Không để nút Gọi ngay tránh tràn viền)
    =========================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40">
        <div class="ux-container py-2.5 md:py-3">
            <div class="flex items-center justify-between gap-2 md:gap-4">
                
                <!-- Nút mở Menu Danh Mục trên Điện Thoại -->
                <button type="button" onclick="toggleMobileMenu()" class="lg:hidden inline-flex items-center justify-center w-9 h-9 rounded bg-brand-navy text-white shrink-0" aria-label="Mở danh mục">
                    <i class="fa-solid fa-bars text-base"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại + Tên công ty -->
                <a href="#top" class="flex items-center gap-2.5 min-w-0 shrink">
                    <img 
                        src="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w400" 
                        onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP=w400';"
                        alt="Logo Sắt Thép Xuân Tín" 
                        class="h-9 sm:h-10 md:h-11 w-auto object-contain rounded border border-slate-200 p-0.5 bg-white shrink-0"
                    >
                    <div class="min-w-0">
                        <div class="text-[12px] sm:text-[14px] md:text-[16px] font-extrabold text-brand-navy leading-tight truncate">
                            SẮT THÉP XUÂN TÍN
                        </div>
                        <div class="text-[10px] sm:text-[11px] text-brand-red font-bold leading-tight truncate">
                            satthepxuantin.com
                        </div>
                    </div>
                </a>

                <!-- Ô tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-md mx-2">
                    <form onsubmit="handleSearch(event)" class="flex w-full border-2 border-brand-navy rounded overflow-hidden bg-white">
                        <input 
                            id="desktopSearchInput"
                            type="text" 
                            placeholder="Tìm thép hình, thép hộp, thép tấm, thép xây dựng..." 
                            class="w-full px-3 py-1.5 text-xs md:text-sm focus:outline-none text-slate-700"
                        >
                        <button type="submit" class="bg-brand-navy hover:bg-brand-red text-white px-3.5 py-1.5 text-xs font-semibold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </form>
                </div>

                <!-- Thông tin địa chỉ & số điện thoại dạng text gọn gàng (Không để nút Gọi ngay) -->
                <div class="hidden xl:flex items-center gap-5 shrink-0 text-xs">
                    <div class="border-l-2 border-brand-red pl-2.5">
                        <div class="text-slate-500 text-[11px]">Hotline Phòng Kinh Doanh:</div>
                        <div class="font-bold text-brand-navy text-[13px]">02363.767.779 - 02363.769.769</div>
                    </div>
                    <div class="border-l-2 border-brand-navy pl-2.5">
                        <div class="text-slate-500 text-[11px]">Di động / Zalo Báo Giá:</div>
                        <div class="font-bold text-brand-red text-[13px]">0908.767.778</div>
                    </div>
                </div>

                <!-- Nút bật ô tìm kiếm nhanh trên Mobile -->
                <button type="button" onclick="toggleMobileSearch()" class="md:hidden inline-flex items-center justify-center w-9 h-9 rounded border border-slate-200 text-brand-navy shrink-0" aria-label="Tìm kiếm">
                    <i class="fa-solid fa-magnifying-glass text-sm"></i>
                </button>
            </div>

            <!-- Thanh tìm kiếm ẩn/hiện trên Mobile -->
            <div id="mobileSearchBar" class="hidden md:hidden mt-2 pt-2 border-t border-slate-100">
                <form onsubmit="handleMobileSearch(event)" class="flex w-full border border-brand-navy rounded overflow-hidden">
                    <input 
                        id="mobileSearchInput"
                        type="text" 
                        placeholder="Nhập tên sắt thép cần tìm..." 
                        class="w-full px-3 py-1.5 text-xs focus:outline-none"
                    >
                    <button type="submit" class="bg-brand-navy text-white px-3 py-1.5 text-xs font-semibold shrink-0">
                        Tìm
                    </button>
                </form>
            </div>
        </div>

        <!-- ==========================================
             NAVIGATION BAR (Tên danh mục viết liền trên 1 hàng chữ nhỏ gọn, không xuống dòng chữ bên trong tên danh mục)
        =========================================== -->
        <nav class="hidden lg:block bg-brand-navy border-t border-brand-blue">
            <div class="ux-container">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#top" class="desktop-nav-link bg-brand-red">
                            <i class="fa-solid fa-house text-[11px]"></i>Trang chủ
                        </a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thep-xay-dung" class="desktop-nav-link">
                            Thép xây dựng <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#thep-xay-dung">Thép Hòa Phát</a>
                            <a href="#thep-xay-dung">Thép Việt Nhật Vina Kyoei</a>
                            <a href="#thep-xay-dung">Thép Pomina</a>
                            <a href="#thep-xay-dung">Thép Miền Nam VNSTEEL</a>
                            <a href="#thep-xay-dung">Thép Việt Mỹ VAS</a>
                            <a href="#thep-xay-dung">Thép Việt Úc</a>
                            <a href="#thep-xay-dung">Thép cuộn phi 6, phi 8</a>
                            <a href="#thep-xay-dung">Thép thanh vằn D10 - D32</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thep-hinh" class="desktop-nav-link">
                            Thép hình <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#thep-hinh">Thép hình H (H100 - H400)</a>
                            <a href="#thep-hinh">Thép hình I (I100 - I600)</a>
                            <a href="#thep-hinh">Thép hình U (U50 - U300)</a>
                            <a href="#thep-hinh">Thép hình V (V30 - V200)</a>
                            <a href="#thep-hinh">Thép hình C</a>
                            <a href="#thep-hinh">Thép hình L</a>
                            <a href="#thep-hinh">Thép ray P11 - P50, QU70</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thep-hop" class="desktop-nav-link">
                            Thép hộp <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#thep-hop">Thép hộp vuông đen</a>
                            <a href="#thep-hop">Thép hộp chữ nhật đen</a>
                            <a href="#thep-hop">Thép hộp vuông mạ kẽm</a>
                            <a href="#thep-hop">Thép hộp chữ nhật mạ kẽm</a>
                            <a href="#thep-hop">Thép hộp vuông nhúng kẽm</a>
                            <a href="#thep-hop">Thép hộp chữ nhật nhúng kẽm</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thep-ong" class="desktop-nav-link">
                            Thép ống <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#thep-ong">Thép ống đen Hòa Phát</a>
                            <a href="#thep-ong">Thép ống mạ kẽm</a>
                            <a href="#thep-ong">Thép ống nhúng kẽm nóng</a>
                            <a href="#thep-ong">Thép ống đúc chịu áp lực</a>
                            <a href="#thep-ong">Thép ống hàn cỡ lớn</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#thep-tam" class="desktop-nav-link">
                            Thép tấm <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#thep-tam">Thép tấm trơn SS400 / A36</a>
                            <a href="#thep-tam">Thép tấm gân chống trượt</a>
                            <a href="#thep-tam">Thép tấm cường độ cao Q345B</a>
                            <a href="#thep-tam">Thép tròn đặc S45C / CT3</a>
                            <a href="#thep-tam">Bản mã & Cắt CNC theo yêu cầu</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#xa-go-ton" class="desktop-nav-link">
                            Xà gồ <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#xa-go-ton">Xà gồ C đen</a>
                            <a href="#xa-go-ton">Xà gồ C mạ kẽm</a>
                            <a href="#xa-go-ton">Xà gồ Z đen</a>
                            <a href="#xa-go-ton">Xà gồ Z mạ kẽm</a>
                            <a href="#xa-go-ton">Xà gồ nhúng kẽm nóng</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#xa-go-ton" class="desktop-nav-link">
                            Tôn <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#xa-go-ton">Tôn lạnh / Tôn mạ kẽm</a>
                            <a href="#xa-go-ton">Tôn màu cán sóng (5, 9, 11 sóng)</a>
                            <a href="#xa-go-ton">Tôn Kliplock / Seamlock</a>
                            <a href="#xa-go-ton">Tôn sóng ngói / Tôn La phông</a>
                            <a href="#xa-go-ton">Tôn đổ sàn Decking</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#luoi-inox" class="desktop-nav-link">
                            Lưới – kẽm gai <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#luoi-inox">Lưới B40 / Lưới B30 / Lưới B20</a>
                            <a href="#luoi-inox">Kẽm gai / Kẽm lam</a>
                            <a href="#luoi-inox">Dây thép mạ kẽm nhúng nóng</a>
                            <a href="#luoi-inox">Lưới thép hàn đổ bê tông</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#luoi-inox" class="desktop-nav-link">
                            Inox – Máng xối <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="ux-dropdown">
                            <a href="#luoi-inox">Hộp Inox / Ống Inox 201, 304</a>
                            <a href="#luoi-inox">Tấm Inox / V Inox / U Inox</a>
                            <a href="#luoi-inox">Máng xối Inox 201 / 304 / 316</a>
                            <a href="#luoi-inox">Máng xối tôn & Phụ kiện</a>
                        </div>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#barem-thep" class="desktop-nav-link">Bảng tra barem thép</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#du-an-da-nang" class="desktop-nav-link">Dự án Đà Nẵng</a>
                    </li>
                    <li class="desktop-nav-item">
                        <a href="#bao-gia-lien-he" class="desktop-nav-link">Liên hệ</a>
                    </li>
                </ul>
            </div>
        </nav>

        <!-- Thanh Danh Mục Ngang Gọn Đẹp Trên Điện Thoại (Không tràn viền) -->
        <div class="lg:hidden bg-brand-navy border-t border-white/15 px-2 py-1.5">
            <div class="flex items-center gap-1.5 overflow-x-auto no-scrollbar pb-0.5">
                <a href="#thep-xay-dung" class="ux-cat-chip px-2.5 py-1 rounded bg-brand-red text-white font-semibold shrink-0">Thép xây dựng</a>
                <a href="#thep-hinh" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Thép hình</a>
                <a href="#thep-hop" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Thép hộp</a>
                <a href="#thep-ong" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Thép ống</a>
                <a href="#thep-tam" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Thép tấm</a>
                <a href="#xa-go-ton" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Xà gồ - Tôn</a>
                <a href="#luoi-inox" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Lưới B40 - Inox</a>
                <a href="#du-an-da-nang" class="ux-cat-chip px-2.5 py-1 rounded bg-white/10 text-white font-medium shrink-0">Dự án Đà Nẵng</a>
                <a href="#bao-gia-lien-he" class="ux-cat-chip px-2.5 py-1 rounded bg-amber-500 text-slate-950 font-bold shrink-0">Báo giá</a>
            </div>
        </div>
    </header>

    <!-- ==========================================
         MENU DRAWER TRÊN ĐIỆN THOẠI (Chuẩn Flatsome Off-Canvas)
    =========================================== -->
    <div id="mobileMenuDrawer" class="fixed inset-0 z-50 hidden">
        <div class="absolute inset-0 bg-black/60" onclick="toggleMobileMenu()"></div>
        <div class="relative w-[82%] max-w-[310px] h-full bg-white shadow-2xl flex flex-col overflow-y-auto">
            <div class="p-3.5 bg-brand-navy text-white flex items-center justify-between">
                <span class="font-bold text-xs uppercase tracking-wide">DANH MỤC SẢN PHẨM</span>
                <button type="button" onclick="toggleMobileMenu()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="divide-y divide-slate-100 text-xs font-semibold text-slate-800">
                <a href="#top" onclick="toggleMobileMenu()" class="block px-4 py-3 text-brand-red"><i class="fa-solid fa-house mr-2"></i>Trang chủ</a>
                <a href="#thep-xay-dung" onclick="toggleMobileMenu()" class="block px-4 py-3">1. Thép xây dựng (Hòa Phát, Việt Nhật, Pomina...)</a>
                <a href="#thep-hinh" onclick="toggleMobileMenu()" class="block px-4 py-3">2. Thép hình (U, I, V, H, C, L, Thép ray)</a>
                <a href="#thep-hop" onclick="toggleMobileMenu()" class="block px-4 py-3">3. Thép hộp (Vuông, Chữ nhật, Đen, Mạ kẽm)</a>
                <a href="#thep-ong" onclick="toggleMobileMenu()" class="block px-4 py-3">4. Thép ống (Ống đen, Mạ kẽm, Ống đúc)</a>
                <a href="#thep-tam" onclick="toggleMobileMenu()" class="block px-4 py-3">5. Thép tấm (Tấm trơn, Tấm gân, Bản mã)</a>
                <a href="#xa-go-ton" onclick="toggleMobileMenu()" class="block px-4 py-3">6. Xà gồ C, Z & Tôn lợp công trình</a>
                <a href="#luoi-inox" onclick="toggleMobileMenu()" class="block px-4 py-3">7. Lưới B40, Kẽm gai, Inox & Máng xối</a>
                <a href="#barem-thep" onclick="toggleMobileMenu()" class="block px-4 py-3">8. Bảng tra barem thép chuẩn</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="block px-4 py-3">9. Dự án tiêu biểu tại Đà Nẵng</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="block px-4 py-3">10. Đối tác thương hiệu</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="block px-4 py-3">11. Bài viết & Bảng giá mới nhất</a>
                <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="block px-4 py-3 text-brand-navy font-bold">12. Gửi yêu cầu báo giá & Bản đồ</a>
            </div>
            <div class="mt-auto p-3.5 bg-slate-50 border-t border-slate-200 text-[11.5px] space-y-1.5">
                <div class="font-bold text-brand-navy">CÔNG TY TNHH TM & DV XUÂN TÍN</div>
                <div><i class="fa-solid fa-phone text-brand-red mr-1.5"></i>02363.767.779 - 02363.769.769</div>
                <div><i class="fa-solid fa-mobile-screen text-brand-red mr-1.5"></i>0908.767.778</div>
                <div><i class="fa-solid fa-envelope text-brand-navy mr-1.5"></i>xuantinsteel79@gmail.com</div>
            </div>
        </div>
    </div>

    <!-- ==========================================
         HERO BANNER SLIDER (2 Ảnh Banner Tự Trượt Chuyên Nghiệp Kích Thước Bằng Nhau)
         Thiết kế riêng ảnh Banner Máy Tính (md:block) và ảnh Banner Điện Thoại (md:hidden)
         để chữ nhỏ gọn nằm trọn bên trong ảnh, không bao giờ tràn viền
    =========================================== -->
    <section id="top" class="py-3">
        <div class="ux-container">
            <div class="relative rounded-lg overflow-hidden shadow-md border border-slate-200 bg-brand-navy">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide block transition-opacity duration-500" data-slide="0">
                    
                    <!-- ẢNH BANNER 1 TRÊN MÁY TÍNH (Kích thước chuẩn cố định 360px, chữ gọn bên trong) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[350px] lg:h-[370px] w-full relative overflow-hidden bg-gradient-to-r from-[#091f3e] via-[#0f315f] to-[#17427b]">
                        <!-- Ảnh nền kho công ty kết hợp lớp phủ -->
                        <img 
                            src="https://drive.google.com/thumbnail?id=1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2&sz=w1200" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2=w1200';"
                            alt="Kho Sắt Thép Xuân Tín Đà Nẵng" 
                            class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-luminosity"
                        >
                        <!-- Nội dung chữ bên trái (Đã thu nhỏ vừa vặn tuyệt đối trong khung) -->
                        <div class="col-span-7 z-10 pl-8 lg:pl-12 pr-4 py-5 text-white">
                            <div class="inline-flex items-center gap-2 bg-brand-red text-white text-[11px] font-bold px-3 py-1 rounded uppercase tracking-wider mb-2.5">
                                <i class="fa-solid fa-award"></i> NHÀ PHÂN PHỐI SẮT THÉP HÀNG ĐẦU ĐÀ NẴNG & MIỀN TRUNG
                            </div>
                            <h1 class="text-lg lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white uppercase mb-2">
                                CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN
                            </h1>
                            <p class="text-xs lg:text-[13.5px] text-amber-300 font-semibold mb-3">
                                Chuyên cung cấp: Thép Xây Dựng • Thép Hình U-I-V-H • Thép Hộp • Thép Ống • Thép Tấm • Xà Gồ • Tôn Lợp • Lưới B40 • Inox
                            </p>
                            <div class="grid grid-cols-1 gap-1 text-[11.5px] lg:text-xs text-slate-100 bg-black/30 p-3 rounded border-l-4 border-amber-400 mb-3">
                                <div><strong class="text-amber-300">Cơ sở 1:</strong> 178 Tôn Đức Thắng, P. Hòa Khánh, Tp. Đà Nẵng - 04 Nam Trân, P. Hòa Khánh, Tp. Đà Nẵng</div>
                                <div><strong class="text-amber-300">Cơ sở 2:</strong> Đường số 6, KCN Hòa Khánh, Phường Liên Chiểu, Tp. Đà Nẵng</div>
                            </div>
                            <div class="flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-white text-brand-navy font-extrabold px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-phone-volume text-brand-red mr-1"></i>Hotline: 02363.767.779 - 02363.769.769
                                </span>
                                <span class="bg-amber-400 text-slate-950 font-extrabold px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-mobile-screen mr-1"></i>Mobile: 0908.767.778
                                </span>
                            </div>
                        </div>
                        <!-- Khung ảnh thực tế bên phải -->
                        <div class="col-span-5 z-10 pr-8 lg:pr-12 pl-2 py-5 h-full flex items-center">
                            <div class="grid grid-cols-2 gap-2.5 w-full h-[270px]">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2&sz=w600" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2=w600';"
                                    alt="Cơ sở Sắt Thép Xuân Tín" 
                                    class="w-full h-full object-cover rounded border-2 border-white/80 shadow"
                                >
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1mj_S9VX40NT_AhQ9d4BR2x-IdBSLvqFI&sz=w600" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1mj_S9VX40NT_AhQ9d4BR2x-IdBSLvqFI=w600';"
                                    alt="Sản phẩm Sắt Thép Xuân Tín" 
                                    class="w-full h-full object-cover rounded border-2 border-amber-400 shadow"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- ẢNH BANNER 1 THIẾT KẾ RIÊNG CHO ĐIỆN THOẠI (Kích thước bằng nhau 235px, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[235px] w-full p-3.5 relative overflow-hidden bg-gradient-to-br from-[#091f3e] via-[#0f315f] to-[#17427b] text-white">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2=w600';"
                            alt="Kho Sắt Thép Xuân Tín" 
                            class="absolute inset-0 w-full h-full object-cover opacity-20"
                        >
                        <div class="relative z-10">
                            <span class="inline-block bg-brand-red text-white text-[9.5px] font-bold px-2 py-0.5 rounded uppercase mb-1">
                                satthepxuantin.com • Đà Nẵng
                            </span>
                            <h2 class="text-[13px] font-extrabold uppercase leading-snug text-white">
                                CÔNG TY TNHH TM & DV XUÂN TÍN
                            </h2>
                            <p class="text-[10.5px] text-amber-300 font-medium leading-tight mt-0.5">
                                Thép Xây Dựng • Thép Hình U-I-V-H • Thép Hộp • Thép Ống • Thép Tấm • Xà Gồ • Tôn
                            </p>
                        </div>
                        <div class="relative z-10 bg-black/35 rounded p-2 border-l-2 border-amber-400 text-[10px] leading-tight space-y-0.5">
                            <div><strong class="text-amber-300">CS1:</strong> 178 Tôn Đức Thắng & 04 Nam Trân, P. Hòa Khánh, Đà Nẵng</div>
                            <div><strong class="text-amber-300">CS2:</strong> Đường số 6, KCN Hòa Khánh, P. Liên Chiểu, Đà Nẵng</div>
                        </div>
                        <div class="relative z-10 flex items-center justify-between gap-1.5 text-[10px] font-bold">
                            <span class="bg-white text-brand-navy px-2 py-1 rounded truncate">ĐT: 02363.767.779</span>
                            <span class="bg-amber-400 text-slate-950 px-2 py-1 rounded shrink-0">DĐ: 0908.767.778</span>
                        </div>
                    </div>

                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide hidden transition-opacity duration-500" data-slide="1">
                    
                    <!-- ẢNH BANNER 2 TRÊN MÁY TÍNH (Kích thước chuẩn cố định 360px bằng Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[350px] lg:h-[370px] w-full relative overflow-hidden bg-gradient-to-r from-[#132a4a] via-[#1c3f6e] to-[#0c2d57]">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO&sz=w1200" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO=w1200';"
                            alt="Hệ thống kho bãi Xuân Tín" 
                            class="absolute inset-0 w-full h-full object-cover opacity-20 mix-blend-luminosity"
                        >
                        <div class="col-span-7 z-10 pl-8 lg:pl-12 pr-4 py-5 text-white">
                            <div class="inline-flex items-center gap-2 bg-amber-400 text-slate-950 text-[11px] font-extrabold px-3 py-1 rounded uppercase tracking-wider mb-2.5">
                                <i class="fa-solid fa-truck-fast"></i> HỆ THỐNG KHO BÃI LỚN TẠI KCN HÒA KHÁNH - GIAO HÀNG TẬN CÔNG TRÌNH
                            </div>
                            <h2 class="text-lg lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white uppercase mb-2">
                                CUNG ỨNG SẮT THÉP DỰ ÁN & GIA CÔNG BẢN MÃ THEO YÊU CẦU
                            </h2>
                            <p class="text-xs lg:text-[13.5px] text-slate-200 font-medium mb-3">
                                Đầy đủ chứng chỉ CO/CQ nhà máy Hòa Phát, Việt Nhật, Pomina, Miền Nam, Hoa Sen, Posco. Cắt chấn, đột lỗ, gia công thép tấm & vận chuyển cẩu hàng tận nơi.
                            </p>
                            <div class="grid grid-cols-3 gap-2 text-[11.5px] mb-3.5">
                                <div class="bg-white/10 p-2 rounded border border-white/15">
                                    <div class="font-bold text-amber-300">100% Chính Hãng</div>
                                    <div class="text-[11px] text-slate-200">Đúng quy cách, barem</div>
                                </div>
                                <div class="bg-white/10 p-2 rounded border border-white/15">
                                    <div class="font-bold text-amber-300">Giá Gốc Đại Lý</div>
                                    <div class="text-[11px] text-slate-200">Chiết khấu cao dự án</div>
                                </div>
                                <div class="bg-white/10 p-2 rounded border border-white/15">
                                    <div class="font-bold text-amber-300">Vận Chuyển Nhanh</div>
                                    <div class="text-[11px] text-slate-200">Xe cẩu giao tận nơi</div>
                                </div>
                            </div>
                            <div class="flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-brand-red text-white font-extrabold px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-envelope mr-1"></i>Email: xuantinsteel79@gmail.com
                                </span>
                                <span class="bg-white text-brand-navy font-extrabold px-3 py-1.5 rounded">
                                    <i class="fa-solid fa-globe mr-1"></i>Website: satthepxuantin.com
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 pr-8 lg:pr-12 pl-2 py-5 h-full flex items-center">
                            <div class="grid grid-cols-2 gap-2.5 w-full h-[270px]">
                                <img 
                                    src="https://drive.google.com/thumbnail?id=1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx&sz=w600" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx=w600';"
                                    alt="Kho hàng Xuân Tín" 
                                    class="w-full h-full object-cover rounded border-2 border-white/80 shadow"
                                >
                                <img 
                                    src="https://drive.google.com/thumbnail?id=16UE9wAGYPoyb4WpGZY3i62fptIMmWeAR&sz=w600" 
                                    onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/16UE9wAGYPoyb4WpGZY3i62fptIMmWeAR=w600';"
                                    alt="Thép hình thép tấm Xuân Tín" 
                                    class="w-full h-full object-cover rounded border-2 border-amber-400 shadow"
                                >
                            </div>
                        </div>
                    </div>

                    <!-- ẢNH BANNER 2 THIẾT KẾ RIÊNG CHO ĐIỆN THOẠI (Kích thước bằng nhau 235px, chữ nhỏ gọn không tràn viền) -->
                    <div class="flex md:hidden flex-col justify-between h-[235px] w-full p-3.5 relative overflow-hidden bg-gradient-to-br from-[#132a4a] via-[#1c3f6e] to-[#0c2d57] text-white">
                        <img 
                            src="https://drive.google.com/thumbnail?id=1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO&sz=w600" 
                            onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO=w600';"
                            alt="Kho Sắt Thép Xuân Tín 2" 
                            class="absolute inset-0 w-full h-full object-cover opacity-20"
                        >
                        <div class="relative z-10">
                            <span class="inline-block bg-amber-400 text-slate-950 text-[9.5px] font-extrabold px-2 py-0.5 rounded uppercase mb-1">
                                Báo Giá Nhanh 24/7 • Giao Tận Công Trình
                            </span>
                            <h2 class="text-[13px] font-extrabold uppercase leading-snug text-white">
                                TỔNG KHO SẮT THÉP XÂY DỰNG & CÔNG NGHIỆP
                            </h2>
                            <p class="text-[10.5px] text-slate-200 font-medium leading-tight mt-0.5">
                                Đầy đủ CO/CQ • Giá gốc đại lý cấp 1 • Có xe cẩu vận chuyển tận nơi tại Đà Nẵng
                            </p>
                        </div>
                        <div class="relative z-10 grid grid-cols-2 gap-1.5 text-[10px]">
                            <div class="bg-black/35 p-1.5 rounded border border-white/15">
                                <span class="text-amber-300 font-bold block">Cam kết chất lượng</span>
                                Đúng quy cách nhà máy
                            </div>
                            <div class="bg-black/35 p-1.5 rounded border border-white/15">
                                <span class="text-amber-300 font-bold block">Hỗ trợ gia công</span>
                                Cắt quy cách & bản mã
                            </div>
                        </div>
                        <div class="relative z-10 flex items-center justify-between gap-1.5 text-[10px] font-bold">
                            <span class="bg-brand-red text-white px-2 py-1 rounded truncate">02363.769.769</span>
                            <span class="bg-white text-brand-navy px-2 py-1 rounded shrink-0">Zalo: 0908.767.778</span>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng Banner -->
                <button type="button" onclick="changeSlide(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-brand-red text-white flex items-center justify-center z-20 transition" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/40 hover:bg-brand-red text-white flex items-center justify-center z-20 transition" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" class="slide-dot w-2.5 h-2.5 rounded-full bg-amber-400 transition" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="slide-dot w-2.5 h-2.5 rounded-full bg-white/50 transition" aria-label="Slide 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         3 Ô CAM KẾT DỊCH VỤ (Giống mẫu manhtienphat.vn - Flatsome Icon Box)
    =========================================== -->
    <section class="py-2">
        <div class="ux-container">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-3">
                <div class="bg-white border border-slate-200 rounded-md p-3.5 flex items-center gap-3.5 shadow-sm">
                    <div class="w-11 h-11 rounded-full bg-brand-navy text-amber-400 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-truck-moving"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-bold text-brand-navy text-xs md:text-sm uppercase">VẬN CHUYỂN TẬN CÔNG TRÌNH</div>
                        <div class="text-slate-600 text-[11.5px] md:text-xs">Hệ thống xe tải & xe cẩu giao hàng nhanh tại Đà Nẵng & Miền Trung</div>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-md p-3.5 flex items-center gap-3.5 shadow-sm">
                    <div class="w-11 h-11 rounded-full bg-brand-red text-white flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-bold text-brand-navy text-xs md:text-sm uppercase">UY TÍN - CHÍNH HÃNG 100%</div>
                        <div class="text-slate-600 text-[11.5px] md:text-xs">Đầy đủ chứng chỉ CO/CQ, đúng quy cách barem trọng lượng nhà máy</div>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-md p-3.5 flex items-center gap-3.5 shadow-sm">
                    <div class="w-11 h-11 rounded-full bg-brand-navy text-amber-400 flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <div class="min-w-0">
                        <div class="font-bold text-brand-navy text-xs md:text-sm uppercase">BÁO GIÁ SẮT THÉP 24/7</div>
                        <div class="text-slate-600 text-[11.5px] md:text-xs">Hotline: 02363.767.779 - 02363.769.769 | Mobile: 0908.767.778</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu xem trên máy tính & điện thoại gọn đẹp, chữ nhỏ gọn nằm trên 1 hàng)
    =========================================== -->
    <section class="py-3">
        <div class="ux-container">
            <div class="bg-white border border-slate-200 rounded-md p-3 md:p-4 shadow-sm">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                    <h2 class="text-xs md:text-sm font-extrabold text-brand-navy uppercase flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-brand-red"></i> DANH MỤC SẢN PHẨM SẮT THÉP XUÂN TÍN
                    </h2>
                    <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn nhanh danh mục sản phẩm</span>
                </div>
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 lg:grid-cols-10 gap-2">
                    <a href="#thep-xay-dung" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-bars-staggered text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Thép xây dựng</span>
                    </a>
                    <a href="#thep-hinh" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-shapes text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Thép hình</span>
                    </a>
                    <a href="#thep-hop" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-regular fa-square text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Thép hộp</span>
                    </a>
                    <a href="#thep-ong" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-regular fa-circle text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Thép ống</span>
                    </a>
                    <a href="#thep-tam" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-vector-square text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Thép tấm</span>
                    </a>
                    <a href="#xa-go-ton" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-grip-lines text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Xà gồ C - Z</span>
                    </a>
                    <a href="#xa-go-ton" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-warehouse text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Tôn lợp</span>
                    </a>
                    <a href="#luoi-inox" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-border-all text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Lưới - Kẽm gai</span>
                    </a>
                    <a href="#luoi-inox" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-coins text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Inox - Máng xối</span>
                    </a>
                    <a href="#barem-thep" class="group border border-slate-200 hover:border-brand-red rounded p-2 text-center bg-slate-50 hover:bg-white transition flex flex-col items-center justify-center">
                        <i class="fa-solid fa-table-list text-brand-navy group-hover:text-brand-red text-base mb-1"></i>
                        <span class="ux-cat-chip font-bold text-slate-800 group-hover:text-brand-red">Barem thép</span>
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         GIỚI THIỆU CÔNG TY & HÌNH ẢNH THỰC TẾ CÔNG TY (11 Ảnh Công Ty Từ Google Drive)
    =========================================== -->
    <section id="gioi-thieu" class="py-3">
        <div class="ux-container">
            <div class="bg-white border border-slate-200 rounded-md p-4 md:p-5 shadow-sm">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-start">
                    <!-- Cột giới thiệu -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="inline-block bg-brand-navy text-white text-xs font-bold px-3 py-1 rounded uppercase">
                            Về Đại Lý Sắt Thép Xuân Tín
                        </div>
                        <h2 class="text-base md:text-lg font-extrabold text-brand-navy leading-snug">
                            CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN
                        </h2>
                        <p class="text-xs md:text-[13.5px] text-slate-600 leading-relaxed">
                            <strong>Công ty TNHH Thương Mại & Dịch Vụ Xuân Tín</strong> (<span class="text-brand-red font-semibold">satthepxuantin.com</span>) là đơn vị uy tín lâu năm tại TP. Đà Nẵng chuyên cung cấp sỉ và lẻ các loại <strong>thép xây dựng, thép hình (U, I, V, H, C), thép hộp, thép ống, thép tấm, bản mã, xà gồ C-Z, tôn lợp, lưới B40, dây thép và inox</strong> phục vụ các công trình dân dụng, nhà xưởng tiền chế, khu công nghiệp và dự án cầu đường tại Đà Nẵng & khu vực Miền Trung.
                        </p>
                        <div class="bg-slate-50 border border-slate-200 rounded p-3 text-xs space-y-1.5 text-slate-700">
                            <div><i class="fa-solid fa-location-dot text-brand-red mr-1.5"></i><strong>Cơ sở 1:</strong> 178 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng - 04 Nam Trân, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                            <div><i class="fa-solid fa-warehouse text-brand-red mr-1.5"></i><strong>Cơ sở 2:</strong> Đường số 6, KCN Hòa Khánh, Phường Liên Chiểu, Tp. Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone text-brand-red mr-1.5"></i><strong>Hotline:</strong> 02363.767.779 - 02363.769.769</div>
                            <div><i class="fa-solid fa-mobile-screen text-brand-red mr-1.5"></i><strong>Mobile / Zalo:</strong> 0908.767.778</div>
                            <div><i class="fa-solid fa-envelope text-brand-red mr-1.5"></i><strong>Email:</strong> xuantinsteel79@gmail.com</div>
                        </div>
                    </div>

                    <!-- Cột 11 Ảnh Thực Tế Công Ty & Kho Bãi Xuân Tín -->
                    <div class="lg:col-span-7">
                        <div class="flex items-center justify-between mb-2">
                            <span class="text-xs font-bold text-brand-navy uppercase">
                                <i class="fa-solid fa-camera text-brand-red mr-1"></i> Hình ảnh thực tế văn phòng, kho bãi & phương tiện vận chuyển (11 ảnh)
                            </span>
                        </div>
                        <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 gap-2">
                            <!-- Ảnh công ty 1 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2=w600';" alt="Văn phòng và kho Sắt Thép Xuân Tín 1" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Cơ sở giao dịch Xuân Tín</div>
                            </div>
                            <!-- Ảnh công ty 2 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO=w600';" alt="Kho hàng Sắt Thép Xuân Tín 2" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Kho thép KCN Hòa Khánh</div>
                            </div>
                            <!-- Ảnh công ty 3 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx=w600';" alt="Kho thép hình Xuân Tín 3" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Bãi tập kết sắt thép</div>
                            </div>
                            <!-- Ảnh công ty 4 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=14GsWqWRJeaxCcFw0allxCFHKUlKOnD68&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14GsWqWRJeaxCcFw0allxCFHKUlKOnD68=w600';" alt="Cẩu hàng Sắt Thép Xuân Tín 4" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Hệ thống cầu trục kho</div>
                            </div>
                            <!-- Ảnh công ty 5 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1RBZ53twfh7RfMHmGSsxXBuQrmJ7U2_N1&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1RBZ53twfh7RfMHmGSsxXBuQrmJ7U2_N1=w600';" alt="Vận chuyển Sắt Thép Xuân Tín 5" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Xe cẩu giao hàng tận nơi</div>
                            </div>
                            <!-- Ảnh công ty 6 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1oJCfxI0WqkTau9f7RAB1uVA1PRNm1_tD&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1oJCfxI0WqkTau9f7RAB1uVA1PRNm1_tD=w600';" alt="Kho thép hộp ống Xuân Tín 6" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Khu vực thép ống & hộp</div>
                            </div>
                            <!-- Ảnh công ty 7 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1Nr4dnRsA7IXA8mCxdaDUEMPGbsGD_EsE&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Nr4dnRsA7IXA8mCxdaDUEMPGbsGD_EsE=w600';" alt="Gia công sắt thép Xuân Tín 7" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Xuất hàng cho dự án</div>
                            </div>
                            <!-- Ảnh công ty 8 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1yKfFWFSHMNUm9BgIE_asB4cypmeJGaLn&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yKfFWFSHMNUm9BgIE_asB4cypmeJGaLn=w600';" alt="Kho bãi Xuân Tín 8" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Kho thép tấm & hình</div>
                            </div>
                            <!-- Ảnh công ty 9 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1GjJyXB_WK4lEsoln3SanWRN8OIyIJMWb&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GjJyXB_WK4lEsoln3SanWRN8OIyIJMWb=w600';" alt="Đội xe Xuân Tín 9" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Bốc xếp thép chuyên nghiệp</div>
                            </div>
                            <!-- Ảnh công ty 10 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100">
                                <img src="https://drive.google.com/thumbnail?id=1wO7o_TSuQ-7qRMboW6IQfZFdk0SeajwQ&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wO7o_TSuQ-7qRMboW6IQfZFdk0SeajwQ=w600';" alt="Kho thép xây dựng Xuân Tín 10" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Kho dự trữ hàng lớn</div>
                            </div>
                            <!-- Ảnh công ty 11 -->
                            <div class="border border-slate-200 rounded overflow-hidden bg-slate-100 col-span-2 sm:col-span-1">
                                <img src="https://drive.google.com/thumbnail?id=1upDLEeXug763LVa9OBD11F9yQwBayIjr&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1upDLEeXug763LVa9OBD11F9yQwBayIjr=w600';" alt="Tổng kho Xuân Tín 11" class="w-full h-28 object-cover">
                                <div class="p-1.5 text-[11px] font-medium text-center text-slate-700 bg-white">Hoạt động giao nhận</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 1: THÉP XÂY DỰNG (Sản phẩm chia 2 cột trên điện thoại, không để nhãn dán, tên đầy đủ không tràn)
    =========================================== -->
    <section id="thep-xay-dung" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-bars-staggered"></i> THÉP XÂY DỰNG
                </h2>
                <div class="hidden md:flex items-center gap-3 px-3 text-xs font-semibold text-slate-600">
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép Hòa Phát</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép Việt Nhật</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép Pomina</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép Miền Nam</a>
                </div>
            </div>

            <!-- Grid 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                
                <!-- SP 1 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1mj_S9VX40NT_AhQ9d4BR2x-IdBSLvqFI&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1mj_S9VX40NT_AhQ9d4BR2x-IdBSLvqFI=w600';" alt="Thép thanh vằn Hòa Phát D10 - D32" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép xây dựng</div>
                            <h3 class="ux-product-title">Thép thanh vằn Hòa Phát phi 10, 12, 14, 16, 18, 20, 22, 25, 28, 32</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Mác thép: CB300-V, CB400-V, CB500-V | Chiều dài: 11.7m/cây</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép thanh vằn Hòa Phát D10 - D32')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 2 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=16UE9wAGYPoyb4WpGZY3i62fptIMmWeAR&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/16UE9wAGYPoyb4WpGZY3i62fptIMmWeAR=w600';" alt="Thép cuộn xây dựng phi 6, phi 8" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép xây dựng</div>
                            <h3 class="ux-product-title">Thép cuộn xây dựng Hòa Phát - Việt Nhật phi 6, phi 8, phi 10</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Tiêu chuẩn: TCVN 1651-1:2018 | Bề mặt trơn / gân chính hãng</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép cuộn xây dựng phi 6, phi 8')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 3 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1LR120HCcpwQOHnNj_Yf1lm3FsZT9CrkE&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LR120HCcpwQOHnNj_Yf1lm3FsZT9CrkE=w600';" alt="Thép Việt Nhật Vina Kyoei" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép xây dựng</div>
                            <h3 class="ux-product-title">Thép xây dựng Việt Nhật Vina Kyoei chính hãng đầy đủ quy cách</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Tiêu chuẩn JIS G3112 Nhật Bản | Đầy đủ CO/CQ nhà máy</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép xây dựng Việt Nhật Vina Kyoei')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 4 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1NXXbR6RY8xPWXF3ULaa5FgMl5GvCh0nE&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1NXXbR6RY8xPWXF3ULaa5FgMl5GvCh0nE=w600';" alt="Thép Pomina và Thép Việt Mỹ VAS" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép xây dựng</div>
                            <h3 class="ux-product-title">Thép xây dựng Việt Mỹ VAS, Pomina và Thép Miền Nam VNSTEEL</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Cung ứng số lượng lớn cho công trình dân dụng & dự án Đà Nẵng</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép Việt Mỹ VAS - Pomina - Miền Nam')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 2: THÉP HÌNH U - I - V - H - C (Chia 2 cột trên điện thoại, không nhãn dán)
    =========================================== -->
    <section id="thep-hinh" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-shapes"></i> THÉP HÌNH H - I - U - V - C - L
                </h2>
                <div class="hidden md:flex items-center gap-3 px-3 text-xs font-semibold text-slate-600">
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hình H</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hình I</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hình U</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hình V</a>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                
                <!-- SP 5 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1M3DTZCbeDKiBrnkvcavfeYu0zbrYEs1P&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M3DTZCbeDKiBrnkvcavfeYu0zbrYEs1P=w600';" alt="Thép hình I100 đến I600" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hình</div>
                            <h3 class="ux-product-title">Thép hình chữ I (I100, I120, I150, I200, I250, I300, I400, I500)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Mác thép: SS400, A36 | Dài 6m - 12m | Kết cấu dầm nhà xưởng</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hình chữ I các quy cách')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 6 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1BppLHnkrnMB96QXXOEHS5KBCAmNWsAUa&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1BppLHnkrnMB96QXXOEHS5KBCAmNWsAUa=w600';" alt="Thép hình H100 đến H400" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hình</div>
                            <h3 class="ux-product-title">Thép hình chữ H (H100x100, H125, H150, H200, H250, H300, H350, H400)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Thương hiệu: Posco, Hàn Quốc, Nhật Bản, Trung Quốc</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hình chữ H các quy cách')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 7 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1ZmI7UM3AC8C0JjlB_zH7NlV6VxO1XQOq&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ZmI7UM3AC8C0JjlB_zH7NlV6VxO1XQOq=w600';" alt="Thép hình U50 đến U300" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hình</div>
                            <h3 class="ux-product-title">Thép hình chữ U (U50, U65, U80, U100, U120, U140, U160, U200, U250, U300)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Có hàng đen, mạ kẽm và nhúng kẽm nóng theo yêu cầu</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hình chữ U các quy cách')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 8 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1LDePMyssZEMcUOM-l080d380SHROhGvS&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1LDePMyssZEMcUOM-l080d380SHROhGvS=w600';" alt="Thép hình V30 đến V200" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hình</div>
                            <h3 class="ux-product-title">Thép hình chữ V - L (V30, V40, V50, V63, V70, V75, V80, V100, V120, V150)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Thép V đen, V mạ kẽm, V nhúng kẽm nóng chịu lực cao</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hình chữ V - L các quy cách')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 3: THÉP HỘP & THÉP ỐNG (Chia 2 cột trên điện thoại, không nhãn dán)
    =========================================== -->
    <section id="thep-hop" class="py-3">
        <div class="ux-container">
            <div id="thep-ong" class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-regular fa-square"></i> THÉP HỘP & THÉP ỐNG CÁC LOẠI
                </h2>
                <div class="hidden md:flex items-center gap-3 px-3 text-xs font-semibold text-slate-600">
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hộp vuông</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép hộp chữ nhật</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép ống mạ kẽm</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép ống đúc</a>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                
                <!-- SP 9 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1dajYAAtRZOdL_yNPxOVHW4vvnScR4JB-&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1dajYAAtRZOdL_yNPxOVHW4vvnScR4JB-=w600';" alt="Thép hộp vuông mạ kẽm và đen" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hộp</div>
                            <h3 class="ux-product-title">Thép hộp vuông đen & mạ kẽm (14x14, 20x20, 30x30, 40x40, 50x50, 100x100)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Hãng sản xuất: Hòa Phát, Hoa Sen, Đông Á, Nam Kim, TVP</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hộp vuông đen & mạ kẽm')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 10 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1-xaBz6CRtHzutP0vUWTX4DfbtR87IpQh&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-xaBz6CRtHzutP0vUWTX4DfbtR87IpQh=w600';" alt="Thép hộp chữ nhật mạ kẽm và đen" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép hộp</div>
                            <h3 class="ux-product-title">Thép hộp chữ nhật mạ kẽm & đen (13x26, 20x40, 25x50, 30x60, 40x80, 50x100, 60x120)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Độ dày: 0.7ly - 6.0ly | Cây dài 6m tiêu chuẩn</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép hộp chữ nhật mạ kẽm & đen')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 11 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1oJCfxI0WqkTau9f7RAB1uVA1PRNm1_tD&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1oJCfxI0WqkTau9f7RAB1uVA1PRNm1_tD=w600';" alt="Thép ống mạ kẽm và ống đen Hòa Phát" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép ống</div>
                            <h3 class="ux-product-title">Thép ống mạ kẽm, thép ống đen & ống nhúng nóng Hòa Phát (Phi 21 - Phi 219)</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Ứng dụng cấp thoát nước, PCCC, giàn giáo, cơ khí</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép ống mạ kẽm & ống đen Hòa Phát')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 12 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1yKfFWFSHMNUm9BgIE_asB4cypmeJGaLn&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1yKfFWFSHMNUm9BgIE_asB4cypmeJGaLn=w600';" alt="Thép ống đúc chịu áp lực" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép ống</div>
                            <h3 class="ux-product-title">Thép ống đúc tiêu chuẩn ASTM A106 / API 5L & Ống thép cỡ lớn</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Độ dày SCH20, SCH40, SCH80 | Chịu áp lực cao công nghiệp</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép ống đúc & ống thép cỡ lớn')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC 4: THÉP TẤM, XÀ GỒ, TÔN LỢP, LƯỚI B40 & INOX (Chia 2 cột trên điện thoại)
    =========================================== -->
    <section id="thep-tam" class="py-3">
        <div class="ux-container">
            <div id="xa-go-ton" class="ux-section-title">
                <h2 id="luoi-inox" class="ux-section-heading">
                    <i class="fa-solid fa-vector-square"></i> THÉP TẤM • XÀ GỒ • TÔN LỢP • LƯỚI B40 • INOX
                </h2>
                <div class="hidden md:flex items-center gap-3 px-3 text-xs font-semibold text-slate-600">
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Thép tấm SS400</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Xà gồ C - Z</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Tôn lợp</a>
                    <span>•</span>
                    <a href="#bao-gia-lien-he" class="hover:text-brand-red">Lưới B40 & Inox</a>
                </div>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                
                <!-- SP 13 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=14GsWqWRJeaxCcFw0allxCFHKUlKOnD68&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14GsWqWRJeaxCcFw0allxCFHKUlKOnD68=w600';" alt="Thép tấm trơn SS400 và thép tấm gân" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Thép tấm</div>
                            <h3 class="ux-product-title">Thép tấm trơn SS400 / A36, Thép tấm gân chống trượt & Gia công bản mã</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Độ dày: 2ly, 3ly, 4ly, 5ly, 6ly, 8ly, 10ly, 12ly đến 50ly | Cắt theo yêu cầu</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Thép tấm trơn / tấm gân / bản mã')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 14 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Nr4dnRsA7IXA8mCxdaDUEMPGbsGD_EsE&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Nr4dnRsA7IXA8mCxdaDUEMPGbsGD_EsE=w600';" alt="Xà gồ C và Xà gồ Z mạ kẽm" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Xà gồ</div>
                            <h3 class="ux-product-title">Xà gồ C & Xà gồ Z đen, mạ kẽm, nhúng kẽm nóng đột lỗ theo bản vẽ</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Quy cách: C80, C100, C120, C150, C180, C200, Z150, Z200, Z250</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Xà gồ C & Xà gồ Z')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 15 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1wO7o_TSuQ-7qRMboW6IQfZFdk0SeajwQ&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1wO7o_TSuQ-7qRMboW6IQfZFdk0SeajwQ=w600';" alt="Tôn lạnh tôn màu tôn sàn decking" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Tôn lợp</div>
                            <h3 class="ux-product-title">Tôn lạnh, Tôn màu cán sóng, Tôn Kliplock, Tôn cách nhiệt PU & Tôn sàn Decking</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Thương hiệu: Hoa Sen, Đông Á, Việt Nhật, Nam Kim, Hòa Phát</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Tôn lợp công trình & Tôn sàn Deck')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

                <!-- SP 16 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1GjJyXB_WK4lEsoln3SanWRN8OIyIJMWb&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1GjJyXB_WK4lEsoln3SanWRN8OIyIJMWb=w600';" alt="Lưới B40 kẽm gai Inox máng xối" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-slate-500 mb-1">Lưới B40 - Inox</div>
                            <h3 class="ux-product-title">Lưới B40 mạ kẽm, Kẽm gai, Dây thép buộc, Hộp ống Inox 201/304 & Máng xối</h3>
                            <p class="text-[11.5px] text-slate-600 mb-2">Khổ lưới B40: 1m, 1.2m, 1.5m, 1.8m, 2m, 2.4m | Đầy đủ phụ kiện</p>
                        </div>
                        <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
                            <span class="text-xs md:text-sm font-bold text-brand-red">Liên hệ báo giá</span>
                            <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Lưới B40 - Kẽm gai - Inox - Máng xối')" class="text-[11px] font-semibold text-brand-navy hover:text-brand-red">Báo giá &rarr;</a>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         BẢNG TRA QUY CÁCH & BAREM TRỌNG LƯỢNG THÉP CHUẨN NHÀ MÁY
    =========================================== -->
    <section id="barem-thep" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-table-list"></i> BẢNG TRA QUY CÁCH & BAREM TRỌNG LƯỢNG THÉP THAM KHẢO
                </h2>
                <span class="hidden md:inline text-xs text-slate-500 px-3">Cam kết giao hàng đúng barem nhà máy công bố</span>
            </div>

            <div class="bg-white border border-slate-200 rounded-md overflow-hidden shadow-sm">
                <div class="overflow-x-auto">
                    <table class="w-full text-left border-collapse text-xs">
                        <thead>
                            <tr class="bg-brand-navy text-white uppercase text-[11px]">
                                <th class="py-2.5 px-3 border-r border-white/15">Chủng loại thép</th>
                                <th class="py-2.5 px-3 border-r border-white/15">Quy cách phổ biến</th>
                                <th class="py-2.5 px-3 border-r border-white/15">Chiều dài tiêu chuẩn</th>
                                <th class="py-2.5 px-3 border-r border-white/15">Tiêu chuẩn / Mác thép</th>
                                <th class="py-2.5 px-3 text-center">Nhận báo giá</th>
                            </tr>
                        </thead>
                        <tbody class="divide-y divide-slate-200 text-slate-700">
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-bold text-brand-navy">Thép cuộn xây dựng</td>
                                <td class="py-2.5 px-3">Phi 6 (D6), Phi 8 (D8), Phi 10</td>
                                <td class="py-2.5 px-3">Cuộn ~ 1.000kg - 2.100kg</td>
                                <td class="py-2.5 px-3">CB240-T / TCVN 1651-1:2018</td>
                                <td class="py-2.5 px-3 text-center"><a href="#bao-gia-lien-he" onclick="selectProductForQuote('Báo giá Thép cuộn Phi 6, Phi 8')" class="text-brand-red font-bold hover:underline">Báo giá</a></td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-bold text-brand-navy">Thép thanh vằn</td>
                                <td class="py-2.5 px-3">D10, D12, D14, D16, D18, D20, D22, D25, D28, D32</td>
                                <td class="py-2.5 px-3">11.7m / cây</td>
                                <td class="py-2.5 px-3">CB300-V, CB400-V, CB500-V</td>
                                <td class="py-2.5 px-3 text-center"><a href="#bao-gia-lien-he" onclick="selectProductForQuote('Báo giá Thép thanh vằn D10 - D32')" class="text-brand-red font-bold hover:underline">Báo giá</a></td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-bold text-brand-navy">Thép hình U, I, V, H</td>
                                <td class="py-2.5 px-3">U50-U300, I100-I600, V30-V200, H100-H400</td>
                                <td class="py-2.5 px-3">6.0m hoặc 12.0m / cây</td>
                                <td class="py-2.5 px-3">JIS G3101 SS400 / ASTM A36</td>
                                <td class="py-2.5 px-3 text-center"><a href="#bao-gia-lien-he" onclick="selectProductForQuote('Báo giá Thép hình U, I, V, H')" class="text-brand-red font-bold hover:underline">Báo giá</a></td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-bold text-brand-navy">Thép hộp vuông & chữ nhật</td>
                                <td class="py-2.5 px-3">14x14 đến 100x100 | 13x26 đến 60x120 (Dày 0.7ly - 6ly)</td>
                                <td class="py-2.5 px-3">6.0m / cây</td>
                                <td class="py-2.5 px-3">ASTM A500 / JIS G3466</td>
                                <td class="py-2.5 px-3 text-center"><a href="#bao-gia-lien-he" onclick="selectProductForQuote('Báo giá Thép hộp vuông & chữ nhật')" class="text-brand-red font-bold hover:underline">Báo giá</a></td>
                            </tr>
                            <tr class="hover:bg-slate-50">
                                <td class="py-2.5 px-3 font-bold text-brand-navy">Thép tấm & Bản mã</td>
                                <td class="py-2.5 px-3">Khổ 1.5x6m, 2x6m, 2x12m (Độ dày 2ly - 50ly)</td>
                                <td class="py-2.5 px-3">6.0m - 12.0m hoặc cắt theo yêu cầu</td>
                                <td class="py-2.5 px-3">SS400, Q235B, Q345B, A36, C45</td>
                                <td class="py-2.5 px-3 text-center"><a href="#bao-gia-lien-he" onclick="selectProductForQuote('Báo giá Thép tấm & Gia công bản mã')" class="text-brand-red font-bold hover:underline">Báo giá</a></td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (Trang chủ)
    =========================================== -->
    <section id="du-an-da-nang" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-city"></i> CÁC DỰ ÁN CUNG ỨNG SẮT THÉP TIÊU BIỂU TẠI ĐÀ NẴNG
                </h2>
                <span class="hidden md:inline text-xs text-slate-500 px-3">Đối tác cung ứng vật tư sắt thép tin cậy cho nhà thầu</span>
            </div>

            <div class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                <!-- Dự án 1 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1Dz_1MZMU99r7DqSzzMaLD1Y_vvAOHkSO=w600';" alt="Dự án Nhà xưởng KCN Hòa Khánh Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">KCN Hòa Khánh - Liên Chiểu</div>
                            <h3 class="ux-product-title">Cung ứng thép hình I, H, xà gồ C-Z & tôn lợp nhà xưởng sản xuất tại KCN Hòa Khánh, Đà Nẵng</h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-2 border-t border-slate-100">Hạng mục: Thép kết cấu & Xà gồ</div>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1RBZ53twfh7RfMHmGSsxXBuQrmJ7U2_N1&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1RBZ53twfh7RfMHmGSsxXBuQrmJ7U2_N1=w600';" alt="Dự án KCN Liên Chiểu và Hòa Cầm Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">KCN Liên Chiểu & Hòa Cầm</div>
                            <h3 class="ux-product-title">Cung cấp thép xây dựng Hòa Phát, thép tấm bản mã và thép ống cho cụm kho vận tại Đà Nẵng</h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-2 border-t border-slate-100">Hạng mục: Thép xây dựng & Bản mã</div>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1kkBpX1zoFCondPWW7mL15dBj0gTFS9yx=w600';" alt="Dự án Khu đô thị Tây Bắc Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">Quận Liên Chiểu & Cẩm Lệ</div>
                            <h3 class="ux-product-title">Cung ứng sắt thép xây dựng dân dụng, nhà phố thương mại và biệtự khu vực Tây Bắc Đà Nẵng</h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-2 border-t border-slate-100">Hạng mục: Thép cuộn & Thép thanh vằn</div>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="ux-product-box">
                    <div class="aspect-[4/3] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1upDLEeXug763LVa9OBD11F9yQwBayIjr&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1upDLEeXug763LVa9OBD11F9yQwBayIjr=w600';" alt="Dự án Hạ tầng và Cầu đường Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-2.5 md:p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">Sơn Trà & Ngũ Hành Sơn</div>
                            <h3 class="ux-product-title">Cung cấp thép hộp mạ kẽm, thép hình U-V, lưới B40 và phụ kiện cho công trình du lịch ven biển Đà Nẵng</h3>
                        </div>
                        <div class="text-[11px] text-slate-500 pt-2 border-t border-slate-100">Hạng mục: Thép hộp mạ kẽm & Lưới B40</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU SẮT THÉP
    =========================================== -->
    <section id="doi-tac" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-handshake"></i> ĐỐI TÁC & THƯƠNG HIỆU SẮT THÉP PHÂN PHỐI CHÍNH HÃNG
                </h2>
            </div>

            <div class="bg-white border border-slate-200 rounded-md p-3.5 shadow-sm">
                <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-2.5 text-center">
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP HÒA PHÁT</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng • Ống • Hộp</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP VIỆT NHẬT</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Vina Kyoei • Tiêu chuẩn JIS</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP POMINA</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép cuộn & Thép thanh vằn</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP MIỀN NAM</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">VNSTEEL Chính Hãng</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP VIỆT MỸ VAS</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép dự án tại Miền Trung</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">TẬP ĐOÀN HOA SEN</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Tôn Hoa Sen • Hộp mạ kẽm</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">TÔN ĐÔNG Á</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Tôn lạnh • Tôn màu • Thép hộp</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">POSCO YAMATO VINA</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép hình H, I, U cỡ lớn</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP NAM KIM</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Tôn mạ & Ống kẽm chất lượng</div>
                    </div>
                    <div class="border border-slate-200 rounded p-3 bg-slate-50 hover:border-brand-navy transition">
                        <div class="font-extrabold text-brand-navy text-xs md:text-sm">THÉP VIỆT ÚC</div>
                        <div class="text-[11px] text-slate-500 mt-0.5">Thép xây dựng cường độ cao</div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- ==========================================
         DANH MỤC CÁC BÀI VIẾT & TIN TỨC TRANG CHỦ
    =========================================== -->
    <section id="tin-tuc" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-newspaper"></i> BÀI VIẾT & CẬP NHẬT BẢNG GIÁ SẮT THÉP TẠI ĐÀ NẴNG
                </h2>
                <span class="hidden md:inline text-xs text-slate-500 px-3">Cập nhật kiến thức quy cách & giá thép mới nhất</span>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-3 md:gap-4">
                <!-- Bài viết 1 -->
                <article class="ux-product-box">
                    <div class="aspect-[16/9] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1t5c8wkoFmY_uZaqOQb-MHzAUBaca24K2=w600';" alt="Bảng báo giá sắt thép xây dựng tại Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">Bảng giá sắt thép Đà Nẵng</div>
                            <h3 class="ux-product-title">Cập nhật bảng báo giá sắt thép xây dựng Hòa Phát, Việt Nhật, Việt Mỹ tại Đà Nẵng mới nhất</h3>
                            <p class="text-xs text-slate-600 leading-relaxed mb-2">
                                Công ty TNHH TM & DV Xuân Tín gửi đến quý nhà thầu và khách hàng bảng giá tham khảo thép cuộn phi 6, phi 8 và thép thanh vằn D10 - D32 giao tận công trình tại Đà Nẵng.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-brand-navy hover:text-brand-red">Nhận bảng giá chi tiết hôm nay &rarr;</a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="ux-product-box">
                    <div class="aspect-[16/9] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1M3DTZCbeDKiBrnkvcavfeYu0zbrYEs1P&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1M3DTZCbeDKiBrnkvcavfeYu0zbrYEs1P=w600';" alt="Cách chọn thép hình U I V H làm nhà tiền chế" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">Kinh nghiệm chọn vật tư</div>
                            <h3 class="ux-product-title">Hướng dẫn tra cứu quy cách thép hình U, I, V, H và thép hộp mạ kẽm cho nhà xưởng tiền chế</h3>
                            <p class="text-xs text-slate-600 leading-relaxed mb-2">
                                Tổng hợp thông số kỹ thuật, độ dày, trọng lượng tiêu chuẩn (kg/m) của các dòng thép hình I, H, U, V và xà gồ C-Z giúp chủ đầu tư tính toán chính xác khối lượng vật tư.
                            </p>
                        </div>
                        <a href="#barem-thep" class="text-xs font-bold text-brand-navy hover:text-brand-red">Xem bảng tra quy cách thép &rarr;</a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="ux-product-box">
                    <div class="aspect-[16/9] w-full bg-slate-100 overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=14GsWqWRJeaxCcFw0allxCFHKUlKOnD68&sz=w600" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/14GsWqWRJeaxCcFw0allxCFHKUlKOnD68=w600';" alt="Gia công cắt thép tấm và bản mã tại Đà Nẵng" class="w-full h-full object-cover">
                    </div>
                    <div class="p-3.5 flex flex-col flex-1 justify-between">
                        <div>
                            <div class="text-[11px] text-brand-red font-semibold mb-1">Dịch vụ kho bãi & gia công</div>
                            <h3 class="ux-product-title">Dịch vụ cung ứng thép tấm SS400, cắt bản mã theo yêu cầu và vận chuyển xe cẩu tại KCN Hòa Khánh</h3>
                            <p class="text-xs text-slate-600 leading-relaxed mb-2">
                                Với 2 cơ sở lớn tại 178 Tôn Đức Thắng - 04 Nam Trân và Đường số 6 KCN Hòa Khánh, Sắt Thép Xuân Tín đáp ứng nhanh tiến độ giao hàng cho mọi dự án lớn nhỏ.
                            </p>
                        </div>
                        <a href="#bao-gia-lien-he" class="text-xs font-bold text-brand-navy hover:text-brand-red">Liên hệ đặt hàng & gia công &rarr;</a>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- ==========================================
         FORM YÊU CẦU BÁO GIÁ + FANPAGE FACEBOOK NGOÀI TRANG CHỦ + GOOGLE MAPS 2 CƠ SỞ
    =========================================== -->
    <section id="bao-gia-lien-he" class="py-3">
        <div class="ux-container">
            <div class="ux-section-title">
                <h2 class="ux-section-heading">
                    <i class="fa-solid fa-file-signature"></i> GỬI YÊU CẦU BÁO GIÁ • KẾT NỐI FANPAGE & BẢN ĐỒ KHO HÀNG
                </h2>
            </div>

            <!-- Hàng 1: Form Yêu Cầu Báo Giá + Fanpage Chính Thức -->
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4 mb-4">
                
                <!-- Cột Form Yêu Cầu & Báo Giá (7 cột) -->
                <div class="lg:col-span-7 bg-white border border-slate-200 rounded-md p-4 md:p-5 shadow-sm">
                    <h3 class="text-sm md:text-base font-extrabold text-brand-navy uppercase mb-1">
                        ĐĂNG KÝ NHẬN BÁO GIÁ SẮT THÉP NHANH TRONG 5 PHÚT
                    </h3>
                    <p class="text-xs text-slate-600 mb-3.5">
                        Quý khách vui lòng điền thông tin chủng loại và khối lượng sắt thép cần mua, Phòng Kinh Doanh Xuân Tín sẽ liên hệ báo giá chiết khấu tốt nhất.
                    </p>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Họ và tên / Tên đơn vị *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên hoặc tên công ty..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Số điện thoại / Zalo nhận báo giá *</label>
                                <input id="qPhone" type="tel" required placeholder="Ví dụ: 0908xxxxxx" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Danh mục sản phẩm quan tâm</label>
                                <select id="qCategory" class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy bg-white">
                                    <option value="Thép xây dựng (Hòa Phát, Việt Nhật, Pomina...)">Thép xây dựng (Hòa Phát, Việt Nhật, Pomina...)</option>
                                    <option value="Thép hình U, I, V, H, C, L">Thép hình U, I, V, H, C, L</option>
                                    <option value="Thép hộp vuông & chữ nhật (Đen / Mạ kẽm)">Thép hộp vuông & chữ nhật (Đen / Mạ kẽm)</option>
                                    <option value="Thép ống đen, ống mạ kẽm, ống đúc">Thép ống đen, ống mạ kẽm, ống đúc</option>
                                    <option value="Thép tấm SS400, tấm gân, cắt bản mã">Thép tấm SS400, tấm gân, cắt bản mã</option>
                                    <option value="Xà gồ C - Z & Tôn lợp công trình">Xà gồ C - Z & Tôn lợp công trình</option>
                                    <option value="Lưới B40, Kẽm gai, Inox, Máng xối">Lưới B40, Kẽm gai, Inox, Máng xối</option>
                                </select>
                            </div>
                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Địa điểm giao hàng dự kiến</label>
                                <input id="qAddress" type="text" placeholder="Ví dụ: Hòa Khánh, Liên Chiểu, Đà Nẵng..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy">
                            </div>
                        </div>

                        <div>
                            <label class="block font-bold text-slate-700 mb-1">Chi tiết quy cách & số lượng cần báo giá *</label>
                            <textarea id="qNote" rows="3" required placeholder="Nhập quy cách thép, độ dày, số lượng cây/tấn cần báo giá..." class="w-full px-3 py-2 border border-slate-300 rounded focus:outline-none focus:border-brand-navy"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center gap-2.5 pt-1">
                            <button type="submit" class="bg-brand-red hover:bg-brand-redDark text-white font-bold px-5 py-2.5 rounded transition uppercase text-xs">
                                <i class="fa-solid fa-paper-plane mr-1.5"></i>Gửi yêu cầu báo giá
                            </button>
                            <a href="https://zalo.me/0908767778" target="_blank" rel="noopener" class="bg-brand-navy hover:bg-brand-blue text-white font-bold px-4 py-2.5 rounded transition text-xs">
                                <i class="fa-solid fa-comment-dots mr-1.5"></i>Chat Zalo: 0908.767.778
                            </a>
                        </div>

                        <!-- Hộp thông báo trạng thái gửi form (Thay thế hoàn toàn alert) -->
                        <div id="quoteStatusBox" class="hidden p-3 rounded border border-emerald-300 bg-emerald-50 text-emerald-900 text-xs font-medium"></div>
                    </form>
                </div>

                <!-- Cột Fanpage Facebook Ngoài Trang Chủ (5 cột) -->
                <div class="lg:col-span-5 bg-white border border-slate-200 rounded-md p-4 md:p-5 shadow-sm flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between mb-2">
                            <h3 class="text-sm font-extrabold text-brand-navy uppercase flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i> FANPAGE FACEBOOK CHÍNH THỨC
                            </h3>
                            <a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="text-[11px] font-bold text-[#1877F2] hover:underline">
                                Mở Fanpage &rarr;
                            </a>
                        </div>

                        <!-- Khung nhúng Facebook Page Plugin kết hợp Thẻ thông tin trực tiếp -->
                        <div class="border border-slate-200 rounded overflow-hidden bg-slate-50 mb-3">
                            <div class="p-3 bg-gradient-to-r from-[#0c2d57] to-[#1877F2] text-white flex items-center gap-3">
                                <img src="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w200" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP=w200';" alt="Logo Fanpage Xuân Tín" class="w-11 h-11 rounded bg-white p-0.5 object-contain shrink-0">
                                <div class="min-w-0">
                                    <div class="font-bold text-xs md:text-sm truncate">Sắt Thép Xuân Tín Đà Nẵng</div>
                                    <div class="text-[11px] text-white/90 truncate">facebook.com/satthepxuantin</div>
                                </div>
                            </div>
                            <div class="w-full overflow-hidden flex justify-center bg-white py-2">
                                <iframe 
                                    title="Fanpage Sắt Thép Xuân Tín"
                                    src="https://www.facebook.com/plugins/page.php?href=https%3A%2F%2Fwww.facebook.com%2Fsatthepxuantin&tabs=timeline&width=340&height=210&small_header=true&adapt_container_width=true&hide_cover=false&show_facepile=true" 
                                    width="340" 
                                    height="210" 
                                    style="border:none;overflow:hidden;max-width:100%;" 
                                    scrolling="no" 
                                    frameborder="0" 
                                    allowfullscreen="true" 
                                    allow="autoplay; clipboard-write; encrypted-media; picture-in-picture; web-share">
                                </iframe>
                            </div>
                        </div>
                    </div>

                    <div class="bg-slate-50 border border-slate-200 rounded p-3 text-xs space-y-1.5">
                        <div class="font-bold text-brand-navy">THÔNG TIN LIÊN HỆ TRỰC TIẾP:</div>
                        <div><i class="fa-solid fa-phone text-brand-red mr-1.5"></i><strong>Hotline:</strong> 02363.767.779 - 02363.769.769</div>
                        <div><i class="fa-solid fa-mobile-screen text-brand-red mr-1.5"></i><strong>Mobile / Zalo:</strong> 0908.767.778</div>
                        <div><i class="fa-solid fa-envelope text-brand-navy mr-1.5"></i><strong>Email:</strong> xuantinsteel79@gmail.com</div>
                        <div class="pt-1">
                            <a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="inline-flex items-center gap-1.5 bg-[#1877F2] text-white font-bold px-3 py-1.5 rounded text-[11.5px] hover:opacity-95">
                                <i class="fa-brands fa-facebook-messenger"></i> Nhắn tin qua Fanpage Xuân Tín
                            </a>
                        </div>
                    </div>
                </div>

            </div>

            <!-- Hàng 2: Đưa Bản Đồ Google Maps 2 Cơ Sở Ra Ngoài Trang Chủ -->
            <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
                
                <!-- Google Map Cơ sở 1 -->
                <div class="bg-white border border-slate-200 rounded-md overflow-hidden shadow-sm">
                    <div class="p-3 bg-brand-navy text-white flex items-center justify-between gap-2">
                        <div class="text-xs font-bold">
                            <i class="fa-solid fa-map-location-dot text-amber-400 mr-1.5"></i>CƠ SỞ 1: 178 TÔN ĐỨC THẮNG & 04 NAM TRÂN, P. HÒA KHÁNH, TP. ĐÀ NẴNG
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=178+Tôn+Đức+Thắng,+Hòa+Khánh,+Liên+Chiểu,+Đà+Nẵng" target="_blank" rel="noopener" class="bg-amber-400 text-slate-950 font-bold text-[11px] px-2.5 py-1 rounded shrink-0">
                            Chỉ đường
                        </a>
                    </div>
                    <div class="w-full h-60 bg-slate-100">
                        <iframe 
                            title="Bản đồ Cơ sở 1 Sắt Thép Xuân Tín - 178 Tôn Đức Thắng Đà Nẵng"
                            src="https://maps.google.com/maps?q=178%20T%C3%B4n%20%C4%90%E1%BB%A9c%20Th%E1%BA%AFng%2C%20H%C3%B2a%20Kh%C3%A1nh%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Google Map Cơ sở 2 -->
                <div class="bg-white border border-slate-200 rounded-md overflow-hidden shadow-sm">
                    <div class="p-3 bg-brand-navy text-white flex items-center justify-between gap-2">
                        <div class="text-xs font-bold">
                            <i class="fa-solid fa-warehouse text-amber-400 mr-1.5"></i>CƠ SỞ 2: ĐƯỜNG SỐ 6, KCN HÒA KHÁNH, PHƯỜNG LIÊN CHIỂU, TP. ĐÀ NẴNG
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Đường+số+6+KCN+Hòa+Khánh+Liên+Chiểu+Đà+Nẵng" target="_blank" rel="noopener" class="bg-amber-400 text-slate-950 font-bold text-[11px] px-2.5 py-1 rounded shrink-0">
                            Chỉ đường
                        </a>
                    </div>
                    <div class="w-full h-60 bg-slate-100">
                        <iframe 
                            title="Bản đồ Cơ sở 2 Sắt Thép Xuân Tín - Đường số 6 KCN Hòa Khánh Đà Nẵng"
                            src="https://maps.google.com/maps?q=%C4%90%C6%B0%E1%BB%9Dng%20s%E1%BB%91%206%2C%20Khu%20c%C3%B4ng%20nghi%E1%BB%87p%20H%C3%B2a%20Kh%C3%A1nh%2C%20Li%C3%AAn%20Chi%E1%BB%83u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=15&ie=UTF8&iwloc=&output=embed" 
                            class="w-full h-full border-0" 
                            loading="lazy" 
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- ==========================================
         FOOTER CHUẨN FLATSOME (Đầy đủ thông tin Công ty TNHH TM & DV Xuân Tín)
    =========================================== -->
    <footer class="bg-brand-navy text-white mt-6 border-t-4 border-brand-red pb-16 md:pb-0">
        <div class="ux-container py-8">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 text-xs">
                
                <!-- Cột 1: Thông tin công ty (5 cột) -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://drive.google.com/thumbnail?id=1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP&sz=w200" onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ZgM2SzcqQ9psl6fuq9g-mvX-v_PoNycP=w200';" alt="Logo Công ty Xuân Tín" class="h-10 w-auto bg-white p-0.5 rounded object-contain shrink-0">
                        <div>
                            <div class="font-extrabold text-sm text-amber-400 uppercase">CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN</div>
                            <div class="text-[11px] text-slate-300">Website chính thức: satthepxuantin.com</div>
                        </div>
                    </div>
                    <p class="text-slate-300 leading-relaxed">
                        Nhà phân phối sỉ & lẻ Sắt Thép Xây Dựng, Thép Hình U-I-V-H, Thép Hộp, Thép Ống, Thép Tấm, Xà Gồ C-Z, Tôn Lợp, Lưới B40 và Inox uy tín hàng đầu tại Đà Nẵng và khu vực Miền Trung.
                    </p>
                    <div class="space-y-1.5 text-slate-200 pt-1">
                        <div><i class="fa-solid fa-location-dot text-amber-400 mr-1.5"></i><strong>Cơ sở 1:</strong> 178 Tôn Đức Thắng, Phường Hòa Khánh, Tp. Đà Nẵng - 04 Nam Trân, Phường Hòa Khánh, Tp. Đà Nẵng</div>
                        <div><i class="fa-solid fa-warehouse text-amber-400 mr-1.5"></i><strong>Cơ sở 2:</strong> Đường số 6, KCN Hòa Khánh, Phường Liên Chiểu, Tp. Đà Nẵng</div>
                        <div><i class="fa-solid fa-phone-volume text-amber-400 mr-1.5"></i><strong>Hotline:</strong> 02363.767.779 - 02363.769.769</div>
                        <div><i class="fa-solid fa-mobile-screen text-amber-400 mr-1.5"></i><strong>Mobile / Zalo:</strong> 0908.767.778</div>
                        <div><i class="fa-solid fa-envelope text-amber-400 mr-1.5"></i><strong>Email:</strong> xuantinsteel79@gmail.com</div>
                    </div>
                </div>

                <!-- Cột 2: Danh mục sản phẩm (4 cột) -->
                <div class="lg:col-span-4 space-y-2">
                    <h4 class="font-extrabold text-sm text-amber-400 uppercase border-b border-white/15 pb-1.5">DANH MỤC SẢN PHẨM CHÍNH</h4>
                    <div class="grid grid-cols-2 gap-1.5 text-slate-200">
                        <a href="#thep-xay-dung" class="hover:text-amber-300">&rsaquo; Thép xây dựng</a>
                        <a href="#thep-hinh" class="hover:text-amber-300">&rsaquo; Thép hình U-I-V-H</a>
                        <a href="#thep-hop" class="hover:text-amber-300">&rsaquo; Thép hộp vuông</a>
                        <a href="#thep-hop" class="hover:text-amber-300">&rsaquo; Thép hộp chữ nhật</a>
                        <a href="#thep-ong" class="hover:text-amber-300">&rsaquo; Thép ống mạ kẽm</a>
                        <a href="#thep-ong" class="hover:text-amber-300">&rsaquo; Thép ống đen & đúc</a>
                        <a href="#thep-tam" class="hover:text-amber-300">&rsaquo; Thép tấm & Bản mã</a>
                        <a href="#xa-go-ton" class="hover:text-amber-300">&rsaquo; Xà gồ C - Z</a>
                        <a href="#xa-go-ton" class="hover:text-amber-300">&rsaquo; Tôn lợp công trình</a>
                        <a href="#luoi-inox" class="hover:text-amber-300">&rsaquo; Lưới B40 & Inox</a>
                    </div>
                </div>

                <!-- Cột 3: Hỗ trợ khách hàng (3 cột) -->
                <div class="lg:col-span-3 space-y-2">
                    <h4 class="font-extrabold text-sm text-amber-400 uppercase border-b border-white/15 pb-1.5">CHÍNH SÁCH & HỖ TRỢ</h4>
                    <ul class="space-y-1.5 text-slate-200">
                        <li><a href="#barem-thep" class="hover:text-amber-300">&rsaquo; Bảng tra quy cách barem thép</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-300">&rsaquo; Dự án tiêu biểu tại Đà Nẵng</a></li>
                        <li><a href="#doi-tac" class="hover:text-amber-300">&rsaquo; Đối tác thương hiệu chính hãng</a></li>
                        <li><a href="#bao-gia-lien-he" class="hover:text-amber-300">&rsaquo; Chính sách vận chuyển & giao nhận</a></li>
                        <li><a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="hover:text-amber-300">&rsaquo; Fanpage Sắt Thép Xuân Tín</a></li>
                    </ul>
                </div>

            </div>
        </div>

        <div class="bg-[#081f3d] py-3 text-center text-[11px] text-slate-300 border-t border-white/10">
            <div class="ux-container flex flex-wrap items-center justify-between gap-2">
                <div>&copy; Bản quyền thuộc về <strong>CÔNG TY TNHH THƯƠNG MẠI & DỊCH VỤ XUÂN TÍN</strong> (satthepxuantin.com)</div>
                <div>Thiết kế chuẩn giao diện Flatsome UX Builder</div>
            </div>
        </div>
    </footer>

    <!-- ==========================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH TRÊN MÁY TÍNH & ĐIỆN THOẠI
    =========================================== -->
    <!-- Cụm nút nổi bên phải cho Máy tính & Điện thoại -->
    <div class="fixed right-2.5 bottom-16 md:bottom-6 z-40 flex flex-col gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0908767778" target="_blank" rel="noopener" class="group flex items-center gap-2 bg-[#0068ff] hover:bg-[#0052cc] text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition" aria-label="Chat Zalo 0908.767.778">
            <span class="w-7 h-7 rounded-full bg-white text-[#0068ff] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden md:inline text-xs font-bold pr-1">Zalo: 0908.767.778</span>
        </a>

        <!-- Nút Facebook Fanpage -->
        <a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#0d65d9] text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition" aria-label="Fanpage Sắt Thép Xuân Tín">
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-sm"></i>
            </span>
            <span class="hidden md:inline text-xs font-bold pr-1">Fanpage Xuân Tín</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0908767778" class="float-pulse flex items-center gap-2 bg-brand-red hover:bg-brand-redDark text-white rounded-full p-2.5 md:px-3.5 md:py-2 shadow-lg transition" aria-label="Gọi Hotline 0908.767.778">
            <span class="w-7 h-7 rounded-full bg-white text-brand-red flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="hidden md:inline text-xs font-bold pr-1">0908.767.778</span>
        </a>
    </div>

    <!-- Thanh liên hệ nhanh cố định dưới đáy màn hình Điện Thoại (Không tràn viền) -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 grid grid-cols-3 text-center shadow-lg">
        <a href="tel:02363767779" class="py-2 px-1 flex flex-col items-center justify-center text-brand-navy border-r border-slate-100">
            <i class="fa-solid fa-phone text-brand-red text-xs mb-0.5"></i>
            <span class="text-[10.5px] font-bold leading-tight">02363.767.779</span>
        </a>
        <a href="https://zalo.me/0908767778" target="_blank" rel="noopener" class="py-2 px-1 flex flex-col items-center justify-center bg-[#0068ff] text-white">
            <i class="fa-solid fa-comment-dots text-xs mb-0.5"></i>
            <span class="text-[10.5px] font-bold leading-tight">Zalo: 0908.767.778</span>
        </a>
        <a href="https://www.facebook.com/satthepxuantin" target="_blank" rel="noopener" class="py-2 px-1 flex flex-col items-center justify-center text-[#1877F2]">
            <i class="fa-brands fa-facebook text-xs mb-0.5"></i>
            <span class="text-[10.5px] font-bold leading-tight">Facebook</span>
        </a>
    </div>

    <!-- ==========================================
         JAVASCRIPT XỬ LÝ BANNER TỰ TRƯỢT, MENU MOBILE, TÌM KIẾM & BÁO GIÁ
    =========================================== -->
    <script>
        // 1. Điều khiển 2 Banner Tự Trượt (Kích thước bằng nhau)
        let currentBannerIndex = 0;
        const bannerSlides = document.querySelectorAll('.banner-slide');
        const slideDots = document.querySelectorAll('.slide-dot');
        let bannerInterval = null;

        function showBannerSlide(index) {
            if (!bannerSlides.length) return;
            currentBannerIndex = (index + bannerSlides.length) % bannerSlides.length;
            bannerSlides.forEach((slide, i) => {
                if (i === currentBannerIndex) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            slideDots.forEach((dot, i) => {
                if (i === currentBannerIndex) {
                    dot.classList.remove('bg-white/50');
                    dot.classList.add('bg-amber-400');
                } else {
                    dot.classList.remove('bg-amber-400');
                    dot.classList.add('bg-white/50');
                }
            });
        }

        function changeSlide(step) {
            showBannerSlide(currentBannerIndex + step);
            restartBannerTimer();
        }

        function goToSlide(index) {
            showBannerSlide(index);
            restartBannerTimer();
        }

        function restartBannerTimer() {
            if (bannerInterval) clearInterval(bannerInterval);
            bannerInterval = setInterval(() => {
                showBannerSlide(currentBannerIndex + 1);
            }, 5500);
        }

        window.addEventListener('load', () => {
            restartBannerTimer();
        });

        // 2. Bật/tắt Menu Danh Mục & Thanh Tìm Kiếm trên Điện Thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            if (drawer) {
                drawer.classList.toggle('hidden');
            }
        }

        function toggleMobileSearch() {
            const searchBar = document.getElementById('mobileSearchBar');
            if (searchBar) {
                searchBar.classList.toggle('hidden');
            }
        }

        // 3. Tìm kiếm nhanh sản phẩm trên trang
        function filterProductsByKeyword(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            if (!q) return;
            const cards = document.querySelectorAll('.ux-product-box');
            let firstMatch = null;
            cards.forEach(card => {
                const text = card.innerText.toLowerCase();
                if (text.includes(q)) {
                    card.style.borderColor = '#c81e1e';
                    if (!firstMatch) firstMatch = card;
                } else {
                    card.style.borderColor = '#e2e8f0';
                }
            });
            if (firstMatch) {
                firstMatch.scrollIntoView({ behavior: 'smooth', block: 'center' });
            }
        }

        function handleSearch(event) {
            event.preventDefault();
            const input = document.getElementById('desktopSearchInput');
            if (input) filterProductsByKeyword(input.value);
        }

        function handleMobileSearch(event) {
            event.preventDefault();
            const input = document.getElementById('mobileSearchInput');
            if (input) filterProductsByKeyword(input.value);
        }

        // 4. Chọn sản phẩm điền sẵn vào Form Báo Giá
        function selectProductForQuote(productName) {
            const noteField = document.getElementById('qNote');
            if (noteField) {
                noteField.value = 'Tôi cần nhận báo giá sản phẩm: ' + productName + ' (Số lượng: ...)';
                noteField.focus();
            }
        }

        // 5. Xử lý gửi Form Báo Giá (Hiển thị thông báo trực tiếp trên giao diện, không dùng alert)
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const address = document.getElementById('qAddress').value.trim();
            const note = document.getElementById('qNote').value.trim();
            const statusBox = document.getElementById('quoteStatusBox');

            if (statusBox) {
                statusBox.classList.remove('hidden');
                statusBox.innerHTML = `
                    <div class="font-bold text-emerald-950 mb-1">
                        <i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i> ĐÃ GHI NHẬN YÊU CẦU BÁO GIÁ CỦA QUÝ KHÁCH!
                    </div>
                    <div>Cảm ơn <strong>${name}</strong> (${phone}). Phòng Kinh Doanh <strong>Sắt Thép Xuân Tín</strong> sẽ liên hệ báo giá mục <strong>${category}</strong> ${address ? 'giao tại <strong>' + address + '</strong>' : ''} trong thời gian sớm nhất.</div>
                    <div class="mt-1 text-[11px] text-emerald-800">Hotline hỗ trợ tức thì: <strong>02363.767.779 - 0908.767.778</strong> | Email: <strong>xuantinsteel79@gmail.com</strong></div>
                `;
            }
        }
    </script>
</body>
</html>
