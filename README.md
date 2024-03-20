
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet"
        integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"
        integrity="sha384-YvpcrYf0tY3lHB60NNkmXc5s9fDVZLESaAA55NDzOxhy9GkcIdslK1eN7N6jIeHz"
        crossorigin="anonymous"></script>
    <link rel="stylesheet" href="style.css">
    <script src="https://kit.fontawesome.com/0ff8c738e5.js" crossorigin="anonymous"></script>
    <title>Document</title>
</head>

<body>
    <!--Phần đầu trang web và menu-->
    <header>
        <div class="container-fluid top-bar">
            <div class="container">
                <div class="row">
                    <div class="col-3">
                        <div class="container-fluid">
                            <div class="row">
                                <div class="col-6"><a href="#"><img src="logo.png" alt="logo OOO Clothes"
                                            style="width: 20px;"></a></div>
                                <div class="col-6"><a href="#">oooclthes.com.vn</a></div>
                            </div>
                        </div>
                    </div>
                    <div class="col-2"></div>
                    <div class="col-7">
                        <div class="container-fluid">
                            <div class="row">
                                <div class="col-4 right-top-bar"><a href="#">Blog</a></div>
                                <div class="col-4 right-top-bar"><a href="#">About</a></div>
                                <div class="col-4"><a href="#">CSKH</a></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <div class="container-fluid khuyen-mai">
            Ưu đãi dành cho bạn mới, <a href="#">
                <img src="img/kham-pha-link.png" alt="" style="width: 130px; padding-bottom: 4px;">
            </a>
        </div>

        <div class="container-fluid main-bar">
            <div class="row main-bar-container">
                <div class="col-3">
                    <a href="#"><img src="logo.png" alt="logo OOO Clothes" class="logo"></a>
                </div>
                <div class="col-5">
                    <div class="container-fluid">
                        <div class="row">
                            <div class="col-md-2" style="background-color: rgb(255, 38, 0);"><a href="#">SALE</a>
                            </div>
                            <div class="col-md-2 menu-bar"><a href="#">SẢN PHẨM</a></div>
                            <div class="col-md-2 menu-bar"><a href="#">THỂ THAO</a></div>
                            <div class="col-md-2 menu-bar"><a href="#">ĐỒ LÓT</a></div>
                            <div class="col-md-2 menu-bar"><a href="#">PHỤ KIỆN</a></div>
                            <div class="col-md-2 menu-bar"><a href="#">IN LOGO</a></div>
                        </div>
                    </div>
                </div>
                <div class="col-4">
                    <div class="row">
                        <div class="col-sm-6">
                            <div class="row">
                                <div class="col-md-6 search-bar-container">
                                    <div class="row">
                                        <div class="col-sm-6" style="display: flex; text-align: center;">
                                            <input class="search-box-input" type="text" placeholder="Tìm kiếm"
                                                name="search">
                                            <button class="search-box-btn" type="submit">
                                                <i class="fa fa-search"></i>
                                            </button>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="col-sm-6">
                            <div class="row">
                                <div class="col-6"><a href="#"><i class="fa-solid fa-bag-shopping"
                                            style="font-size: 30px; background-color: rgb(0, 50, 110); width: 45px; height: 35px; border-radius: 50px;"></i></a>
                                </div>
                                <div class="col-6"><a href="#"><i class="fa-solid fa-user"
                                            style="font-size: 30px; background-color: rgb(0, 50, 110);  width: 45px; height: 35px; border-radius: 50px;"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
        <!--Dòng chữ chạy-->
        <div class="container-fluid" style="background-color: rgb(28, 28, 28); color: aliceblue;">
            <marquee>
                Mua càng nhiều - ưu đãi càng lớn. Giảm tới 10% tối đa 100.000 đồng cho lần mua hàng thứ hai.
            </marquee>
        </div>
    </header>

    <!--Danh sách hàng bán chạy-->
    <section>
        <div class="section-style">
            <div class="container-fluid">
                <div class="container-section">
                    <div style="margin-bottom: 10px; font-size: 25px;">SẢN PHẨM HOT TRONG THÁNG</div>

                    <div class="row container-img" style="position: relative;">
                        <img src="hot-thang-banner.jpg" alt="">
                        <div
                            style="position: absolute; color: rgb(255, 255, 255); left: 30px; bottom: 20px; margin: 15px;">
                            <h3>Áo Parka Chống UV Bỏ Túi</h3>
                            <h4>980.000 VND</h4>
                            <a href="#" class="buy-link">mua ngay</a>
                        </div>
                    </div>

                    <div class="row card-style">
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="hot-thang-1.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Sơ Mi Extra Fine Cotton Ngắn Tay</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="hot-thang-2.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Thun Cổ Tròn Tay Ngắn Phối Viền Trắng</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">291.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="hot-thang-3.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Sơ Mi Vải Cotton Modal In Họa Tiết Cổ Mở Ngắn Tay</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="hot-thang-4.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Sơ Mi Extra Fine Cotton Ngắn Tay</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">431.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!--Áo-->
    <section>
        <div class="section-style">
            <div class="container-fluid">
                <div class="container-section">
                    <div style="margin-bottom: 20px; font-size: 30px; font-weight: bold;">ÁO NAM</div>

                    <div class="row container-ao-img" style="position: relative;">
                        <a href="#"><img src="ao-banner.png" alt="" style="width: 100%;"></a>
                    </div>

                    <div class="row card-style">
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-1.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Polo Dệt Ngắn Tay Phối Be</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-2.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Polo Dệt Ngắn Tay Phối Đen</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">431.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-3.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>AIRism Cotton Áo Polo Vải Jersey Cổ Mở Ngắn Tay</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-4.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Polo Vải Dry Pique Ngắn Tay (Kẻ Sọc)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-5.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Polo Ngắn Tay Phối Xanh</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">385.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-6.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Polo Vải Dry Pique Ngắn Tay (Kẻ Sọc)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-7.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>AIRism Cotton Áo Thun Tay Lỡ Dáng Relax</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">391.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="ao-8.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Áo Thun Dáng Rộng Kẻ Sọc Cổ Tròn Tay Lỡ</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>


    <!--Quần-->
    <section>
        <div class="section-style">
            <div class="container-fluid">
                <div class="container-section">
                    <div style="margin-bottom: 20px; font-size: 30px; font-weight: bold;">QUẦN NAM</div>

                    <div class="row container-ao-img" style="position: relative;">
                        <a href="#"><img src="quan-banner.png" alt="" style="width: 100%;"></a>
                    </div>

                    <div class="row card-style">
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-1.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Quần Short Thể Thao Siêu Co Giãn</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-2.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Quần Chino Short (Dáng Relax)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-3.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Miracle Air Quần Short (Họa Tiết)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">548.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-4.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Quần Short Parachute Túi Hộp (Cargo)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-5.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>DRY-EX Quần Short</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-6.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>DRY-EX Quần Short Siêu Co Giãn</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">489.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-7.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Miracle Air Quần Short (AirSense Quần Short)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">648.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="quan-8.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Quần Short Co Giãn Dáng Ôm</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">568.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>



    <!--Phụ kiện-->
    <section>
        <div class="section-style">
            <div class="container-fluid">
                <div class="container-section">
                    <div style="margin-bottom: 20px; font-size: 30px; font-weight: bold;">PHỤ KIỆN</div>

                    <div class="row container-ao-img" style="position: relative;">
                        <a href="#"><img src="phu-kien-banner.png" alt="" style="width: 100%;"></a>
                    </div>

                    <div class="row card-style">
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-1.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Balo Dâyy Dút</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">784.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-2.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Túi Vải Tái Chế (Cotton)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">48.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-3.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Thắt Lưng Cá Sấu Da Ý </h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">686.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-4.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Mũ Lưỡi Trai Local Brand</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">588.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-5.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Thắt Lưng Công Sở Da Bò</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">456.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-6.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Ô Chống Nắng Nhỏ Gọn Local Brand</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">391.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-7.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Mắt Kính Gọng Vuông Bản Lớn (Chống Nắng)</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">589.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                        <div class="col-md-3 col-sm-6 col-6">
                            <div class="card">
                                <a href="#">
                                    <img src="phu-kien-8.avif" class="card-img-top" alt="...">
                                    <div class="card-body">
                                        <a href="#">
                                            <h4>Kính Mắt Gọng Boston Đổi Màu</h4>
                                            <div style="font-size: 13px; color: rgba(115, 115, 115, 0.596);">
                                                M X XL XXL
                                            </div>
                                            <div style="color: rgb(255, 47, 0);">355.000 VND</div>
                                        </a>
                                    </div>
                                </a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>




    <!--Chân trang-->
    <footer>




        <div class="container-fluid p-5" style="background-color: rgb(228, 227, 227);">
            <p>Áo nam là một trong những trang phục phải có trong tủ đồ của bất kỳ ai. Thấu hiểu điều đó,
                OOOClothes cho ra mắt top sản phẩm áo nam đáp ứng mọi nhu cầu hằng ngày của chàng.</p>
            <h4>Lý do nên mua áo của OOOClothes?</h4>
            <p>
                Hướng đến sự tối giản, tiện lợi cho nam giới, áo nam OOOClothes mang phong cách thiết kế đơn giản, hiện
                đại, dễ mặc, dễ phối với mọi hoàn cảnh.

                Truy cập vào oooclothes.com.vn, bạn có thể dễ dàng xây dựng một tủ đồ nam giới với mức giá hợp lý. Với
                1,1
                triệu đơn hàng đã được giao đi (tính đến 2023), chính là minh chứng cho thấy khách hàng đã đánh giá cao
                và tin yêu OOOClothes như thế nào.

                Tất cả các sản phẩm áo nam OOOClothes đều được sản xuất bởi người Việt từ khâu thiết kế đến khâu hoàn
                thiện sản phẩm. OOOClothes hợp tác với các nhà máy, xưởng uy tín tại Việt Nam như Thiên Sơn, Sơn Hà,
                Nobland,... Sản phẩm luôn được đóng gói chắc chắn trong hộp giấy trước khi đến tay người tiêu dùng.
            </p>
        </div>



        <div class="container-fluid bg-black">
            <div class="container footer-style p-3">
                <div class="row fist-row" style="border-bottom: 1px solid gray;">
                    <div class="col-md-4 col-sm-12 p-3">
                        <div class="container-fluid">
                            <div class="row">
                                <div style="font-size: 20px; font-weight: bold;">OOOCLOTHES luôn lắng nghe bạn!</div>
                                <div style="font-size: 13px;">
                                    Chúng tôi luôn trân trọng và mong đợi nhận được mọi ý kiến đóng góp từ khách hàng để có
                                    thể nâng cấp trải nghiệm dịch vụ và sản phẩm tốt hơn nữa.
                                </div>
                            </div>
                            <div class="row">
                                <button class="button-footer">Đóng góp ý kiến</button>
                            </div>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-12 p-3">
                        <div class="container-fluid">
                            <div class="row">
                                <div>
                                    <h4>Hotline</h4>0123456789
                                </div>
                            </div>
                            <div class="row">
                                <div>
                                    <h4>Email</h4>abc@email.com
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="col-md-4 col-sm-12 p-3">
                        <div class="container-fluid">
                            <div class="row social-link">
                                <div class="col-3">
                                    <a href=""><i class="fa-brands fa-facebook-f fa-2xl"></i></a>
                                </div>
                                <div class="col-3">
                                    <a href=""><i class="fa-brands fa-youtube fa-2xl"></i></a>
                                </div>
                                <div class="col-3">
                                    <a href=""><i class="fa-brands fa-tiktok fa-2xl"></i></a>
                                </div>
                                <div class="col-3">
                                    <a href=""><i class="fa-brands fa-instagram fa-2xl"></i></a>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>


                <div class="row last-row">
                    <div class="comtainer-fluid p-3">
                        <p>
                            @Tổng công ty TNHH 3 thành viên
                            
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </footer>
</body>

</html>
