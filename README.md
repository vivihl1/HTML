<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Online Store - Đại Ca Vĩ</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
            font-size: 24px;
        }
        nav {
            display: flex;
            justify-content: space-around;
            background-color: #444;
            padding: 10px;
        }
        nav a {
            color: white;
            text-decoration: none;
            font-weight: bold;
        }
        nav a:hover {
            color: #f4f4f4;
            background-color: #555;
            padding: 5px;
            border-radius: 5px;
        }
        .container {
            width: 80%;
            margin: auto;
            padding: 20px;
        }
        .product {
            display: inline-block;
            width: 30%;
            margin: 1%;
            padding: 20px;
            background-color: white;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
        }
        .product img {
            max-width: 100%;
            height: auto;
        }
        .product h3 {
            margin: 10px 0;
            color: #333;
        }
        .product p {
            color: #777;
        }
        .footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px 0;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
        .footer a {
            color: #4caf50;
            text-decoration: none;
        }
    </style>
</head>
<body>

<header>
    Cửa Hàng Online Đại Ca Vĩ
</header>

<nav>
    <a href="#">Trang Chủ</a>
    <a href="#">Sản Phẩm</a>
    <a href="#">Khuyến Mãi</a>
    <a href="#">Liên Hệ</a>
</nav>

<div class="container">
    <h2>Sản Phẩm Nổi Bật</h2>
    
    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản Phẩm 1">
        <h3>Sản Phẩm 1</h3>
        <p>Giá: 500,000đ</p>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản Phẩm 2">
        <h3>Sản Phẩm 2</h3>
        <p>Giá: 750,000đ</p>
    </div>

    <div class="product">
        <img src="https://via.placeholder.com/150" alt="Sản Phẩm 3">
        <h3>Sản Phẩm 3</h3>
        <p>Giá: 1,200,000đ</p>
    </div>
</div>

<footer class="footer">
    <p>Liên hệ với chúng tôi qua Facebook: <a href="https://fb.com/phuongvihl" target="_blank">fb.com/phuongvihl</a></p>
</footer>

</body>
</html>
