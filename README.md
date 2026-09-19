# Activity

# Program: 
<!DOCTYPE html>
<html>
<head>
    <title>Product Cards</title>

    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f2f2f2;
            margin: 0;
            padding: 0;
        }

        .container {
            display: flex;
            justify-content: center;
            align-items: center;
            gap: 30px;
            min-height: 85vh;
        }

        .product-card {
            width: 300px;
            background-color: white;
            text-align: center;
            border-radius: 15px;
            padding: 20px;
            box-shadow: 0 4px 10px gray;
            transition: transform 0.3s, box-shadow 0.3s;
        }

        .product-card:hover {
            transform: translateY(-10px);
            box-shadow: 0 10px 25px gray;
        }

        .product-card img {
            width: 100%;
            height: 220px;
            object-fit: cover;
            border-radius: 10px;
            transition: transform 0.3s;
        }

        .product-card:hover img {
            transform: scale(1.05);
        }

        .product-card h2 {
            margin: 15px 0 10px;
            color: #333;
        }

        .product-card p {
            color: #666;
            line-height: 1.5;
        }

        .price {
            font-size: 22px;
            font-weight: bold;
            color: #e67e22;
            margin: 15px 0;
        }

        .cart-btn {
            background-color: #3498db;
            color: white;
            border: none;
            padding: 12px 25px;
            border-radius: 6px;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .product-card:hover .cart-btn {
            background-color: #27ae60;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 15px;
        }
    </style>
</head>

<body>

    <div class="container">

        <!-- Smart Watch -->
        <div class="product-card">

            <img src="https://images.unsplash.com/photo-1523275335684-37898b6baf30?auto=format&fit=crop&w=600&q=80"
                 alt="Smart Watch">

            <h2>Smart Watch</h2>

            <p>
                Stylish and smart watch with useful features
                for everyday use.
            </p>

            <div class="price">
                ₹2,499
            </div>

            <button class="cart-btn">
                Add to Cart
            </button>

        </div>


        <!-- Wireless Headphones -->
        <div class="product-card">

            <img src="https://images.unsplash.com/photo-1505740420928-5e560c06d30e?auto=format&fit=crop&w=600&q=80"
                 alt="Wireless Headphones">

            <h2>Wireless Headphones</h2>

            <p>
                Comfortable wireless headphones with clear
                sound quality for music and calls.
            </p>

            <div class="price">
                ₹1,999
            </div>

            <button class="cart-btn">
                Add to Cart
            </button>

        </div>

    </div>

    <footer>
        Learner Name: Nandhini M<br>
        Register Number: 212224040211
    </footer>

</body>
</html>

# Output:
<img width="1917" height="1091" alt="image" src="https://github.com/user-attachments/assets/f1ce8b3b-5156-44f5-8588-b75b3aa902f2" />
