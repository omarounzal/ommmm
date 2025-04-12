<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>متجر الحسابات المميزة</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background: linear-gradient(-45deg, #1a1a2e, #16213e, #0f3460, #1e1e1e);
            background-size: 400% 400%;
            color: #fff;
            margin: 0;
            padding: 0;
            text-align: center;
            overflow-x: hidden;
            animation: backgroundAnimation 12s infinite alternate;
        }
        
        @keyframes backgroundAnimation {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        .container {
            width: 90%;
            margin: auto;
            padding: 20px;
        }
        
        header {
            background: linear-gradient(45deg, #ff416c, #ff4b2b);
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
            box-shadow: 0px 4px 15px rgba(0, 0, 0, 0.4);
            border-radius: 0 0 10px 10px;
            margin-bottom: 30px;
        }
        
        .products-grid {
            display: grid;
            grid-template-columns: repeat(auto-fill, minmax(300px, 1fr));
            gap: 25px;
            padding: 20px;
        }
        
        .product {
            background: rgba(34, 34, 34, 0.8);
            padding: 25px;
            border-radius: 15px;
            box-shadow: 0px 5px 20px rgba(0, 0, 0, 0.3);
            transition: all 0.3s ease;
            backdrop-filter: blur(5px);
            border: 1px solid rgba(255, 255, 255, 0.1);
        }
        
        .product:hover {
            transform: translateY(-10px);
            box-shadow: 0px 15px 30px rgba(0, 0, 0, 0.5);
        }
        
        .product img {
            width: 100px;
            height: 100px;
            object-fit: contain;
            margin-bottom: 15px;
            filter: drop-shadow(0 0 10px rgba(255, 255, 255, 0.3));
            border-radius: 15px;
        }
        
        .product h3 {
            color: #ff4b2b;
            font-size: 22px;
            margin: 10px 0;
        }
        
        .price {
            font-size: 24px;
            font-weight: bold;
            color: #4CAF50;
            margin: 15px 0;
        }
        
        .features {
            text-align: right;
            margin: 15px 0;
            padding: 0;
            list-style-type: none;
        }
        
        .features li {
            padding: 5px 0;
            position: relative;
            padding-right: 20px;
        }
        
        .features li:before {
            content: "✓";
            color: #4CAF50;
            position: absolute;
            right: 0;
        }
        
        button {
            background: linear-gradient(45deg, #ff416c, #ff4b2b);
            color: white;
            padding: 12px 25px;
            border: none;
            cursor: pointer;
            border-radius: 30px;
            font-size: 18px;
            transition: all 0.3s;
            margin-top: 10px;
            width: 100%;
            font-weight: bold;
            letter-spacing: 1px;
        }
        
        button:hover {
            background: linear-gradient(45deg, #ff4b2b, #ff416c);
            transform: scale(1.05);
            box-shadow: 0 5px 15px rgba(255, 75, 43, 0.4);
        }
        
        .guarantee-badge {
            background: rgba(76, 175, 80, 0.2);
            border: 1px solid #4CAF50;
            border-radius: 20px;
            padding: 5px 15px;
            display: inline-block;
            margin: 10px 0;
            font-size: 14px;
        }
        
        footer {
            margin-top: 50px;
            padding: 20px;
            background: rgba(0, 0, 0, 0.3);
            border-radius: 10px 10px 0 0;
        }
        
        .contact-methods {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
            flex-wrap: wrap;
        }
        
        .contact-btn {
            background: rgba(255, 255, 255, 0.1);
            padding: 10px 20px;
            border-radius: 30px;
            display: flex;
            align-items: center;
            gap: 10px;
            transition: all 0.3s;
            text-decoration: none;
            color: white;
        }
        
        .contact-btn:hover {
            background: rgba(255, 255, 255, 0.2);
        }
        
        .phone-number {
            direction: ltr;
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 10px 15px;
            border-radius: 30px;
            margin: 10px 0;
            font-weight: bold;
        }
        
        .email-contact {
            direction: ltr;
            display: inline-block;
            background: rgba(255, 255, 255, 0.1);
            padding: 10px 15px;
            border-radius: 30px;
            margin: 10px 0;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <header>
        متجر الحسابات المميزة - بيع حسابات بضمان 30 يومًا
    </header>
    
    <div class="container">
        <div class="products-grid">
            <!-- Netflix Premium -->
            <div class="product">
                <img src="https://i.ibb.co/6n0hL3X/netflix-logo.png" alt="Netflix Premium">
                <h3>Netflix Premium</h3>
                <div class="guarantee-badge">ضمان 30 يومًا</div>
                <div class="price">$25</div>
                <ul class="features">
                    <li>حساب بريميوم كامل</li>
                    <li>4 شاشات في نفس الوقت</li>
                    <li>دقة 4K UHD</li>
                    <li>جميع المحتويات المتاحة</li>
                </ul>
                <button>اشتري الآن</button>
            </div>
            
            <!-- Spotify Premium -->
            <div class="product">
                <img src="https://i.ibb.co/8X3xYyH/spotify-logo.png" alt="Spotify Premium">
                <h3>Spotify Premium</h3>
                <div class="guarantee-badge">ضمان 30 يومًا</div>
                <div class="price">$12</div>
                <ul class="features">
                    <li>حساب مميز مدفوع</li>
                    <li>استماع بدون إعلانات</li>
                    <li>تحميل الأغاني</li>
                    <li>جودة عالية 320kbps</li>
                </ul>
                <button>اشتري الآن</button>
            </div>
            
            <!-- Shahid VIP -->
            <div class="product">
                <img src="https://i.ibb.co/0jQ2Y0J/shahid-logo.png" alt="Shahid VIP">
                <h3>Shahid VIP</h3>
                <div class="guarantee-badge">ضمان 30 يومًا</div>
                <div class="price">$20</div>
                <ul class="features">
                    <li>حساب VIP مدفوع</li>
                    <li>جميع المحتويات الحصرية</li>
                    <li>دقة 4K UHD</li>
                    <li>متعدد الأجهزة</li>
                </ul>
                <button>اشتري الآن</button>
            </div>
            
            <!-- Canva Pro -->
            <div class="product">
                <img src="https://i.ibb.co/7Yk1Z6G/canva-logo.png" alt="Canva Pro">
                <h3>Canva Pro</h3>
                <div class="guarantee-badge">ضمان 30 يومًا</div>
                <div class="price">$15</div>
                <ul class="features">
                    <li>حساب مدفوع بالكامل</li>
                    <li>مكتبة صور ومقاطع مميزة</li>
                    <li>أدوات تصميم متقدمة</li>
                    <li>دعم فني متكامل</li>
                </ul>
                <button>اشتري الآن</button>
            </div>
        </div>
        
        <footer>
            <h3>طرق التواصل والدعم الفني</h3>
            <div class="phone-number">0600966363</div>
            <div class="email-contact">omarounzal10@gmail.com</div>
            <div class="contact-methods">
                <a href="https://wa.me/212600966363" class="contact-btn">
                    <img src="https://cdn-icons-png.flaticon.com/512/220/220236.png" width="20" alt="WhatsApp"> واتساب
                </a>
                <a href="https://t.me/yourchannel" class="contact-btn">
                    <img src="https://cdn-icons-png.flaticon.com/512/2111/2111646.png" width="20" alt="Telegram"> تيليجرام
                </a>
                <a href="mailto:omarounzal10@gmail.com" class="contact-btn">
                    <img src="https://cdn-icons-png.flaticon.com/512/732/732200.png" width="20" alt="Email"> البريد الإلكتروني
                </a>
            </div>
            <p style="margin-top: 20px;">© 2023 متجر الحسابات المميزة. جميع الحقوق محفوظة.</p>
        </footer>
    </div>
</body>
</html>
