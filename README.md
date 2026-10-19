<!DOCTYPE html>
<html lang="bn">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Freshora | Fresh Juice Delivered</title>

    <meta name="description"
          content="Freshora - Fresh, delicious and refreshing juices delivered to your door in Sylhet.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            background: #fffdf6;
            color: #193b28;
            line-height: 1.6;
        }

        header {
            background: #174c32;
            color: white;
            padding: 18px 6%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            flex-wrap: wrap;
            gap: 12px;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            color: #ffad42;
        }

        .logo span {
            color: white;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 15px;
            font-size: 14px;
        }

        .hero {
            background: linear-gradient(135deg, #e5f5d8, #fff0d7);
            text-align: center;
            padding: 65px 20px;
        }

        .hero h1 {
            font-size: clamp(32px, 6vw, 52px);
            color: #174c32;
            line-height: 1.2;
            margin-bottom: 18px;
        }

        .hero h1 span {
            color: #ef8725;
        }

        .hero p {
            max-width: 550px;
            margin: 0 auto 25px;
            color: #465b4a;
        }

        .btn {
            display: inline-block;
            background: #f28b27;
            color: white;
            padding: 12px 24px;
            border-radius: 30px;
            text-decoration: none;
            font-weight: bold;
            border: none;
            cursor: pointer;
        }

        .btn:hover {
            background: #d96f12;
        }

        .section {
            padding: 45px 6%;
        }

        .section-title {
            text-align: center;
            margin-bottom: 30px;
        }

        .section-title h2 {
            font-size: 30px;
            color: #174c32;
        }

        .section-title p {
            color: #68776b;
        }

        .products {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 22px;
        }

        .card {
            background: white;
            border-radius: 18px;
            overflow: hidden;
            box-shadow: 0 5px 20px rgba(23, 76, 50, 0.09);
            border: 1px solid #edf0e7;
            text-align: center;
            padding-bottom: 22px;
        }

        .juice-image {
            height: 155px;
            display: flex;
            justify-content: center;
            align-items: center;
            font-size: 76px;
            background: #f0f7e8;
        }

        .card h3 {
            margin: 15px 10px 5px;
            font-size: 21px;
        }

        .card p {
            color: #68776b;
            font-size: 14px;
            margin: 0 10px 12px;
        }

        .price {
            color: #e57a1d;
            font-size: 16px;
            font-weight: bold;
            margin: 12px 0;
        }

        .card button {
            margin-top: 8px;
        }

        .about {
            background: #174c32;
            color: white;
            text-align: center;
            padding: 45px 8%;
        }

        .about h2 {
            color: #ffb34f;
            margin-bottom: 12px;
            font-size: 28px;
        }

        .about p {
            max-width: 650px;
            margin: auto;
        }

        .delivery {
            background: #fff0d7;
            padding: 35px 20px;
            text-align: center;
        }

        .delivery h2 {
            color: #174c32;
            margin-bottom: 10px;
        }

        .order-section {
            max-width: 600px;
            margin: auto;
            background: white;
            padding: 25px;
            border-radius: 18px;
            box-shadow: 0 5px 20px rgba(23, 76, 50, 0.08);
        }

        .order-section label {
            display: block;
            margin: 14px 0 5px;
            font-weight: bold;
        }

        .order-section input,
        .order-section select,
        .order-section textarea {
            width: 100%;
            padding: 12px;
            border: 1px solid #d8e0d5;
            border-radius: 9px;
            font-size: 16px;
            background: #fff;
        }

        .order-section button {
            width: 100%;
            margin-top: 18px;
            font-size: 16px;
        }

        footer {
            background: #103723;
            color: white;
            text-align: center;
            padding: 25px 15px;
        }

        footer p {
            margin: 5px 0;
        }

        .whatsapp {
            position: fixed;
            bottom: 18px;
            right: 18px;
            background: #20bd62;
            color: white;
            padding: 13px 18px;
            border-radius: 40px;
            text-decoration: none;
            font-weight: bold;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.2);
            z-index: 10;
        }

        @media (max-width: 480px) {
            header {
                justify-content: center;
                text-align: center;
            }

            nav a {
                margin: 0 7px;
            }

            .hero {
                padding: 48px 18px;
            }

            .section {
                padding: 35px 5%;
            }
        }
    </style>
</head>

<body>

<header>
    <div class="logo">Fresh<span>ora</span> 🍃</div>

    <nav>
        <a href="#home">Home</a>
        <a href="#juices">Juices</a>
        <a href="#about">About</a>
        <a href="#order">Order</a>
    </nav>
</header>

<section class="hero" id="home">
    <h1>Freshness in<br><span>Every Sip!</span></h1>

    <p>
        Enjoy refreshing, delicious fruit juices with Freshora.
        আপনার প্রতিদিনের সতেজতা পৌঁছে যাবে আপনার দরজায়।
    </p>

    <a href="#juices" class="btn">Explore Our Juices 🍹</a>
</section>

<section class="section" id="juices">

    <div class="section-title">
        <h2>Our Fresh Juices</h2>
        <p>Choose your favourite refreshing flavour.</p>
    </div>

    <div class="products">

        <div class="card">
            <div class="juice-image">🍊</div>
            <h3>Orange Juice</h3>
            <p>সতেজ কমলার জুস</p>
            <div class="price">250 ml: ৳80<br>500 ml: ৳140</div>
            <button class="btn" onclick="chooseJuice('Orange Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🍎</div>
            <h3>Apple Juice</h3>
            <p>মিষ্টি আপেলের জুস</p>
            <div class="price">250 ml: ৳100<br>500 ml: ৳180</div>
            <button class="btn" onclick="chooseJuice('Apple Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🍍</div>
            <h3>Pineapple Juice</h3>
            <p>টাটকা আনারসের জুস</p>
            <div class="price">250 ml: ৳70<br>500 ml: ৳120</div>
            <button class="btn" onclick="chooseJuice('Pineapple Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🥭</div>
            <h3>Mango Juice</h3>
            <p>মজাদার আমের জুস</p>
            <div class="price">250 ml: ৳80<br>500 ml: ৳140</div>
            <button class="btn" onclick="chooseJuice('Mango Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🍉</div>
            <h3>Watermelon Juice</h3>
            <p>গ্রীষ্মের সতেজ তরমুজের জুস</p>
            <div class="price">250 ml: ৳60<br>500 ml: ৳100</div>
            <button class="btn" onclick="chooseJuice('Watermelon Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🍋</div>
            <h3>Lemon Mint</h3>
            <p>লেবু ও পুদিনার সতেজ পানীয়</p>
            <div class="price">250 ml: ৳50<br>500 ml: ৳90</div>
            <button class="btn" onclick="chooseJuice('Lemon Mint')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🍇</div>
            <h3>Grape Juice</h3>
            <p>আঙুরের মজাদার জুস</p>
            <div class="price">250 ml: ৳100<br>500 ml: ৳180</div>
            <button class="btn" onclick="chooseJuice('Grape Juice')">
                Order Now
            </button>
        </div>

        <div class="card">
            <div class="juice-image">🥕</div>
            <h3>Carrot Juice</h3>
            <p>গাজরের সুস্বাদু জুস</p>
            <div class="price">250 ml: ৳70<br>500 ml: ৳120</div>
            <button class="btn" onclick="chooseJuice('Carrot Juice')">
                Order Now
            </button>
        </div>

    </div>
</section>

<section class="about" id="about">
    <h2>Why Choose Freshora?</h2>

    <p>
        Freshora is your destination for refreshing juice experiences.
        We aim to bring delicious flavours, convenient ordering
        and friendly delivery service to Sylhet.
    </p>
</section>

<section class="delivery">
    <h2>📍 Delivery in Sylhet</h2>
    <p>সিলেট শহরে জুস ডেলিভারির জন্য অর্ডার করুন।</p>
    <p>ডেলিভারি চার্জ ও সময় অর্ডার নিশ্চিত করার সময় জানানো হবে।</p>
</section>

<section class="section" id="order">

    <div class="section-title">
        <h2>Place Your Order</h2>
        <p>নিচের ফর্মটি পূরণ করে WhatsApp-এ অর্ডার পাঠাও।</p>
    </div>

    <div class="order-section">

        <form id="orderForm">

            <label for="customerName">Your Name</label>
            <input
                type="text"
                id="customerName"
                placeholder="তোমার নাম"
                required
            >

            <label for="customerPhone">Phone Number</label>
            <input
                type="tel"
                id="customerPhone"
                placeholder="তোমার মোবাইল নম্বর"
                required
            >

            <label for="juice">Select Juice</label>
            <select id="juice" required>
                <option value="Orange Juice">Orange Juice</option>
                <option value="Apple Juice">Apple Juice</option>
                <option value="Pineapple Juice">Pineapple Juice</option>
                <option value="Mango Juice">Mango Juice</option>
                <option value="Watermelon Juice">Watermelon Juice</option>
                <option value="Lemon Mint">Lemon Mint</option>
                <option value="Grape Juice">Grape Juice</option>
                <option value="Carrot Juice">Carrot Juice</option>
            </select>

            <label for="size">Bottle Size</label>
            <select id="size" required>
                <option value="250 ml">250 ml</option>
                <option value="500 ml">500 ml</option>
            </select>

            <label for="quantity">Quantity</label>
            <input
                type="number"
                id="quantity"
                min="1"
                max="100"
                value="1"
                required
            >

            <label for="address">Delivery Address</label>
            <textarea
                id="address"
                rows="3"
                placeholder="সিলেটের তোমার ঠিকানা"
                required
            ></textarea>

            <button type="submit" class="btn">
                Order via WhatsApp 📲
            </button>

        </form>

    </div>
</section>

<footer>
    <div class="logo">Freshora 🍃</div>
    <p>Freshness in Every Sip!</p>
    <p>Fresh Juice Delivery | Sylhet, Bangladesh</p>
    <p>© <span id="year"></span> Freshora. All rights reserved.</p>
</footer>

<a class="whatsapp"
   href="#order"
   aria-label="Order Freshora Juice">
   WhatsApp Order
</a>

<script>
    // IMPORTANT:
    // Replace this example with your WhatsApp number.
    // Use country code and digits only, without + or spaces.
    // Bangladesh example format: 8801XXXXXXXXX

    const WHATSAPP_NUMBER = "8801XXXXXXXXX";

    const prices = {
        "Orange Juice": { "250 ml": 80, "500 ml": 140 },
        "Apple Juice": { "250 ml": 100, "500 ml": 180 },
        "Pineapple Juice": { "250 ml": 70, "500 ml": 120 },
        "Mango Juice": { "250 ml": 80, "500 ml": 140 },
        "Watermelon Juice": { "250 ml": 60, "500 ml": 100 },
        "Lemon Mint": { "250 ml": 50, "500 ml": 90 },
        "Grape Juice": { "250 ml": 100, "500 ml": 180 },
        "Carrot Juice": { "250 ml": 70, "500 ml": 120 }
    };

    document.getElementById("year").textContent =
        new Date().getFullYear();

    function chooseJuice(name) {
        document.getElementById("juice").value = name;

        document.getElementById("order").scrollIntoView({
            behavior: "smooth"
        });
    }

    document.getElementById("orderForm").addEventListener(
        "submit",
        function(event) {
            event.preventDefault();

            if (!/^8801\d{9}$/.test(WHATSAPP_NUMBER)) {
                alert(
                    "WhatsApp অর্ডার চালু করতে কোডে তোমার " +
                    "সঠিক WhatsApp নম্বর বসাতে হবে।"
                );
                return;
            }

            const name =
                document.getElementById("customerName").value.trim();

            const phone =
                document.getElementById("customerPhone").value.trim();

            const juice =
                document.getElementById("juice").value;

            const size =
                document.getElementById("size").value;

            const quantity =
                Number(document.getElementById("quantity").value);

            const address =
                document.getElementById("address").value.trim();

            if (!name || !phone || !address ||
                !Number.isInteger(quantity) ||
                quantity < 1 || quantity > 100) {
                alert("সব তথ্য সঠিকভাবে পূরণ করো।");
                return;
            }

            const unitPrice = prices[juice][size];
            const total = unitPrice * quantity;

            const message =
                "Freshora Juice Order 🍹\n\n" +
                "Name: " + name + "\n" +
                "Customer Phone: " + phone + "\n" +
                "Juice: " + juice + "\n" +
                "Size: " + size + "\n" +
                "Quantity: " + quantity + "\n" +
                "Unit Price: Tk " + unitPrice + "\n" +
                "Estimated Total: Tk " + total + "\n" +
                "Delivery Address: " + address + "\n\n" +
                "Please confirm availability and delivery charge.";

            const url =
                "https://wa.me/" + WHATSAPP_NUMBER +
                "?text=" + encodeURIComponent(message);

            window.open(url, "_blank");
        }
    );
</script>

</body>
</html>
