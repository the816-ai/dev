<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tâm_xinggai - Link Bio</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 400px;
            margin: 0 auto;
            background: white;
            border-radius: 20px;
            padding: 30px 20px;
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }

        .profile-section {
            text-align: center;
            margin-bottom: 30px;
        }

        .profile-pic {
            width: 80px;
            height: 80px;
            border-radius: 50%;
            margin: 0 auto 15px;
            background: linear-gradient(45deg, #ff6b6b, #ffa500);
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 30px;
            font-weight: bold;
            color: white;
        }

        .shop-name {
            font-size: 22px;
            font-weight: bold;
            color: #333;
            margin-bottom: 5px;
        }

        .shop-tagline {
            color: #666;
            font-size: 14px;
            margin-bottom: 20px;
        }

        .products-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 15px;
        }

        .product-card {
            background: white;
            border-radius: 15px;
            overflow: hidden;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            transition: all 0.3s ease;
            text-decoration: none;
            color: inherit;
        }

        .product-card:hover {
            transform: translateY(-5px);
            box-shadow: 0 8px 25px rgba(0,0,0,0.15);
        }

        .product-image {
            width: 100%;
            height: 140px;
            background: #f8f9fa;
            display: flex;
            align-items: center;
            justify-content: center;
            font-size: 40px;
            position: relative;
            overflow: hidden;
        }

        .product-image img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.3s ease;
        }

        .product-card:hover .product-image img {
            transform: scale(1.05);
        }

        .product-info {
            padding: 12px;
        }

        .product-title {
            font-size: 13px;
            font-weight: 600;
            color: #333;
            line-height: 1.3;
            margin-bottom: 5px;
            display: -webkit-box;
            -webkit-line-clamp: 2;
            -webkit-box-orient: vertical;
            overflow: hidden;
        }

        .product-price {
            font-size: 12px;
            color: #ff6b6b;
            font-weight: bold;
        }

        .new-badge {
            position: absolute;
            top: 8px;
            right: 8px;
            background: #ff4757;
            color: white;
            font-size: 10px;
            padding: 3px 6px;
            border-radius: 10px;
            font-weight: bold;
            z-index: 1;
        }

        .hot-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            background: #ffa500;
            color: white;
            font-size: 10px;
            padding: 3px 6px;
            border-radius: 10px;
            font-weight: bold;
            z-index: 1;
        }

        /* Image loading placeholder */
        .product-image::before {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            background: linear-gradient(90deg, #f0f0f0 25%, #e0e0e0 50%, #f0f0f0 75%);
            background-size: 200% 100%;
            animation: loading 1.5s infinite;
            z-index: 0;
        }

        .product-image img {
            z-index: 1;
            position: relative;
        }

        @keyframes loading {
            0% { background-position: 200% 0; }
            100% { background-position: -200% 0; }
        }

        @media (max-width: 480px) {
            .container {
                margin: 10px;
                padding: 20px 15px;
            }
            
            .products-grid {
                gap: 10px;
            }
            
            .product-image {
                height: 120px;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <!-- Profile Section -->
        <div class="profile-section">
            <div class="profile-pic">MA</div>
            <h1 class="shop-name">Tâm_xingai</h1>
            <p class="shop-tagline">✨ Thời Trang Nữ Trendy - Chất Lượng Cao ✨</p>
        </div>

        <!-- Products Grid -->
        <div class="products-grid">
            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/sandal-bebe.jpg" alt="Dép Sandal tập đi cho bé">
                    <div class="new-badge">NEW</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Dép Sandal tập đi cho bé trai bé gái chống trượt phong...</div>
                    <div class="product-price">120.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/giay-the-thao.jpg" alt="Giày thể thao Sport cho bé">
                    <div class="hot-badge">HOT</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Giày thể thao Sport cho bé trai bé gái hàng QC size 16-31...</div>
                    <div class="product-price">150.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/quan-baggy.jpg" alt="Quần Baggy Kaki">
                </div>
                <div class="product-info">
                    <div class="product-title">Quần Baggy Kaki (chất kaki đẹp loại 1) có giãn form rộng...</div>
                    <div class="product-price">180.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/tu-quan-ao.jpg" alt="Tủ Quần Áo Tủ Vải">
                </div>
                <div class="product-info">
                    <div class="product-title">Tủ Quần Áo Tủ Vải Khung Thép 5 buồng tủ dựng...</div>
                    <div class="product-price">450.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/sandal-tap-di.jpg" alt="Sandal tập đi cho bé">
                </div>
                <div class="product-info">
                    <div class="product-title">Sandal tập đi cho bé mùi con chống vấp, chống trượt...</div>
                    <div class="product-price">110.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/giay-bup-be.jpg" alt="Giày Búp Bê Da">
                </div>
                <div class="product-info">
                    <div class="product-title">Giày Búp Bê Da Đế Mềm Phong Cách Hàn Quốc Thời Trang...</div>
                    <div class="product-price">165.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/quan-short.jpg" alt="Quần short ngố bò jean">
                </div>
                <div class="product-info">
                    <div class="product-title">Quần short ngố bò jean nữ cạp cao, sooc jeans nữ ống rộ...</div>
                    <div class="product-price">95.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/ao-be-trai.jpg" alt="Áo Bé Trai, Bé Gái">
                </div>
                <div class="product-info">
                    <div class="product-title">Áo Bé Trai, Bé Gái Minky Mom Vải Thun Lạnh, Bộ Cộc Tay C...</div>
                    <div class="product-price">75.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/dep-sandal-form-to.jpg" alt="Dép sandal tập đi thời trang">
                    <div class="new-badge">NEW</div>
                </div>
                <div class="product-info">
                    <div class="product-title">( FORM TO ) Dép sandal tập đi thời trang đế mềm chống tr...</div>
                    <div class="product-price">135.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/chan-vay-midi.jpg" alt="Chân váy midi Hàn">
                </div>
                <div class="product-info">
                    <div class="product-title">Chân váy midi Hàn xếp ly dáng dài phong cách Hàn Quốc...</div>
                    <div class="product-price">190.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/do-choi-giao-duc.jpg" alt="Đồ Chơi Giáo Dục">
                </div>
                <div class="product-info">
                    <div class="product-title">Đồ Chơi Giáo Dục Xếp Hình Lắp Ghép</div>
                    <div class="product-price">85.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/ao-crop-top.jpg" alt="Áo Crop Top Nữ">
                </div>
                <div class="product-info">
                    <div class="product-title">Áo Crop Top Nữ Trẻ Phong Cách Hàn Quốc</div>
                    <div class="product-price">65.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-13.jpg" alt="Sản phẩm 13">
                    <div class="hot-badge">HOT</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 13 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-14.jpg" alt="Sản phẩm 14">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 14 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-15.jpg" alt="Sản phẩm 15">
                    <div class="new-badge">NEW</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 15 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-16.jpg" alt="Sản phẩm 16">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 16 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-17.jpg" alt="Sản phẩm 17">
                    <div class="hot-badge">HOT</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 17 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-18.jpg" alt="Sản phẩm 18">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 18 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-19.jpg" alt="Sản phẩm 19">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 19 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-20.jpg" alt="Sản phẩm 20">
                    <div class="new-badge">NEW</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 20 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-21.jpg" alt="Sản phẩm 21">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 21 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-22.jpg" alt="Sản phẩm 22">
                    <div class="hot-badge">HOT</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 22 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-23.jpg" alt="Sản phẩm 23">
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 23 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>

            <a href="#" class="product-card">
                <div class="product-image">
                    <img src="https://raw.githubusercontent.com/TON-USERNAME/TON-REPO/main/images/product-24.jpg" alt="Sản phẩm 24">
                    <div class="new-badge">NEW</div>
                </div>
                <div class="product-info">
                    <div class="product-title">Tên sản phẩm 24 - Mô tả ngắn gọn về sản phẩm...</div>
                    <div class="product-price">XXX.000đ</div>
                </div>
            </a>
        </div>
    </div>
</body>
</html>



