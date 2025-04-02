<!DOCTYPE html>
<html lang="fa">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="https://card.thecartek.com/images/ct.png">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/css/all.min.css">
    <style>
        .social-button {
            display: flex;
            align-items: center;
            padding: 10px;
            background-color: #f4f4f4;
            border-radius: 20px;
            width: 100%;
            margin-bottom: 10px;
            text-decoration: none;
            color: #333;
            transition: background-color 0.3s;
        }
        .social-button:hover {
            background-color: #3498db;
            color: white;
        }
        .icon {
            font-size: 20px;
            margin-left: 10px;
            color: white;
            padding: 5px;
            border-radius: 50%;
        }
        .phone { background-color: #34b7f1; }
        .telegram { background-color: #0088cc; }
        .whatsapp { background-color: #25d366; }
        .instagram { background-color: #e4405f; }
        .email { background-color: #d44638; }
        .address { background-color: #f39c12; }
    </style>
</head>
<body>

    <div class="social-buttons">
        <!-- لینک تماس با شماره تلفن -->
        <a href="tel:09189444481" class="social-button">
            <i class="fas fa-phone-alt icon phone"></i>
            <span>09189444481</span>
        </a>

        <!-- لینک تلگرام -->
        <a href="https://t.me/username" class="social-button">
            <i class="fab fa-telegram-plane icon telegram"></i>
            <span>تلگرام</span>
        </a>

        <!-- لینک واتس اپ -->
        <a href="https://wa.me/09189444481" class="social-button">
            <i class="fab fa-whatsapp icon whatsapp"></i>
            <span>واتس‌اپ</span>
        </a>

        <!-- لینک اینستاگرام -->
        <a href="https://instagram.com/username" class="social-button">
            <i class="fab fa-instagram icon instagram"></i>
            <span>اینستاگرام</span>
        </a>

        <!-- ایمیل -->
        <a href="mailto:example@example.com" class="social-button">
            <i class="fas fa-envelope icon email"></i>
            <span>ایمیل</span>
        </a>

        <!-- آدرس -->
        <a href="https://www.google.com/maps?q=your+address" class="social-button">
            <i class="fas fa-map-marker-alt icon address"></i>
            <span>آدرس</span>
        </a>
    </div>

</body>
</html>
