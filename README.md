
<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Каталог товаров - iPhone</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #fff;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 40px 20px;
        }
        h1 {
            text-align: center;
            margin-bottom: 40px;
            font-size: 36px;
            color: #fff;
        }
        .product {
            background-color: #111;
            border: 1px solid #333;
            border-radius: 10px;
            padding: 20px;
            margin-bottom: 20px;
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
        }
        .product img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
            margin-bottom: 15px;
        }
        .product h2 {
            font-size: 24px;
            margin-bottom: 10px;
        }
        .price {
            font-size: 20px;
            margin-bottom: 10px;
            color: #ccc;
        }
        .order-button {
            display: inline-block;
            padding: 10px 20px;
            background-color: #fff;
            color: #000;
            text-decoration: none;
            border-radius: 5px;
            font-weight: bold;
            transition: background-color 0.3s;
        }
        .order-button:hover {
            background-color: #ccc;
        }

        @media (min-width: 768px) {
            .product-list {
                display: flex;
                flex-wrap: wrap;
                gap: 20px;
                justify-content: center;
            }
            .product {
                width: calc(33% - 20px);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Каталог iPhone</h1>
        <div class="product-list">

            <div class="product">
                <img src="https://store.storeimages.cdn-apple.com/4668/as-images.apple.com/is/iphone13-select-2021?wid=470&hei=556&fmt=png-alpha&.v=1629842707000" alt="iPhone 13">
                <h2>iPhone 13</h2>
                <div class="price">Цена: $699</div>
                <a class="order-button" href="https://t.me/malecat1?start=iphone13" target="_blank">Заказать в Telegram</a>
            </div>

            <div class="product">
                <img src="https://store.storeimages.cdn-apple.com/4668/as-images.apple.com/is/iphone-13-pro-family-hero?wid=470&hei=556&fmt=png-alpha&.v=1631652955000" alt="iPhone 13 Pro">
                <h2>iPhone 13 Pro</h2>
                <div class="price">Цена: $999</div>
                <a class="order-button" href="https://t.me/malecat1?start=iphone13pro" target="_blank">Заказать в Telegram</a>
            </div>

            <div class="product">
                <img src="https://store.storeimages.cdn-apple.com/4668/as-images.apple.com/is/iphone-13-pro-max-family-hero?wid=470&hei=556&fmt=png-alpha&.v=1631652955000" alt="iPhone 13 Pro Max">
                <h2>iPhone 13 Pro Max</h2>
                <div class="price">Цена: $1099</div>
                <a class="order-button" href="https://t.me/malecat1?start=iphone13promax" target="_blank">Заказать в Telegram</a>
            </div>

        </div>
    </div>
</body>
</html>
