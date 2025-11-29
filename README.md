# music-service
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Music Service</title>

    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: #ffffff;
            color: #333;
            text-align: center;
        }

        /* ---------- FEATURES SECTION ---------- */

        .features h1 {
            color: #e45a48;
            margin-top: 40px;
            font-size: 28px;
        }

        .feature-box {
            display: flex;
            justify-content: center;
            gap: 40px;
            margin-top: 30px;
            flex-wrap: wrap;
        }

        .feature img {
            width: 70px;
        }

        .feature h3 {
            margin-top: 10px;
            font-size: 18px;
        }

        /* ---------- GUESTS ---------- */

        .guests h2 {
            margin-top: 70px;
            color: #e45a48;
        }

        .guest-container {
            display: flex;
            justify-content: center;
            gap: 30px;
            margin: 40px auto;
            flex-wrap: wrap;
        }

        .guest-card {
            width: 250px;
            padding: 20px;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            border-radius: 6px;
            background: #fff;
        }

        .avatar {
            width: 120px;
            height: 120px;
            border-radius: 50%;
            object-fit: cover;
        }

        .guest-card p {
            font-size: 14px;
            margin: 10px 0 20px;
        }

        .guest-card button {
            padding: 10px 20px;
            background: #a35757;
            color: white;
            border: none;
            border-radius: 4px;
            cursor: pointer;
        }

        /* ---------- PRODUCTS SECTION ---------- */

        .products h2 {
            margin-top: 60px;
            color: #e45a48;
        }

        .product-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
            gap: 30px;
            width: 90%;
            margin: 40px auto;
        }

        .product img {
            width: 100%;
            height: 180px;
            object-fit: cover;
            border-radius: 8px;
        }

        .product h3 {
            margin: 10px 0 0;
            font-size: 18px;
        }

        .product p {
            margin: 5px 0 20px;
            font-size: 14px;
            color: gray;
        }

        /* Mobile adjustments */
        @media (max-width: 600px) {
            .feature-box { gap: 20px; }
            .guest-card { width: 90%; }
        }
    </style>
</head>
<body>

    <!-- TOP FEATURES -->
    <section class="features">
        <h1>Get ready for seamless online music</h1>

        <div class="feature-box">
            <div class="feature">
                <img src="https://img.icons8.com/ios-filled/100/download.png" alt="">
                <h3>Offline mode</h3>
                <p>Save and listen anywhere.</p>
            </div>

            <div class="feature">
                <img src="https://img.icons8.com/ios-filled/100/high-volume.png" alt="">
                <h3>High quality audio.</h3>
                <p>Enjoy the full range of sound.</p>
            </div>

            <div class="feature">
                <img src="https://img.icons8.com/ios-filled/100/no-audio.png" alt="">
                <h3>No ads.</h3>
                <p>Enjoy nonstop music.</p>
            </div>

            <div class="feature">
                <img src="https://img.icons8.com/ios-filled/100/end.png" alt="">
                <h3>Unlimited skips.</h3>
                <p>Just tap skip.</p>
            </div>
        </div>
    </section>

    <!-- FEATURED GUESTS -->
    <section class="guests">
        <h2>Featured Guests</h2>

        <div class="guest-container">

            <div class="guest-card">
                <img class="avatar" src="https://randomuser.me/api/portraits/women/44.jpg" alt="">
                <h3>Megan Smith</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <button>Register</button>
            </div>

            <div class="guest-card">
                <img class="avatar" src="https://randomuser.me/api/portraits/women/68.jpg" alt="">
                <h3>Brooke Kagle</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <button>Register</button>
            </div>

            <div class="guest-card">
                <img class="avatar" src="https://randomuser.me/api/portraits/men/32.jpg" alt="">
                <h3>Philip Martin</h3>
                <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit.</p>
                <button>Register</button>
            </div>

        </div>
    </section>

    <!-- BUY WHAT'S NEW -->
    <section class="products">
        <h2>BUY WHAT’S NEW</h2>

        <div class="product-grid">

            <div class="product">
                <img src="https://images.unsplash.com/photo-1517914504725-b1e1a195c1f4?q=80&w=800" alt="">
                <h3>Garage Band</h3>
                <p>Radio Station</p>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1511671782779-c97d3d27a1d4?q=80&w=800" alt="">
                <h3>Garage Band</h3>
                <p>Radio Station</p>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1507668077129-56e32842fceb?q=80&w=800" alt="">
                <h3>Garage Band</h3>
                <p>Radio Station</p>
            </div>

            <div class="product">
                <img src="https://images.unsplash.com/photo-1504384308090-c894fdcc538d?q=80&w=800" alt="">
                <h3>Garage Band</h3>
                <p>Radio Station</p>
            </div>

        </div>
    </section>

</body>
</html>
