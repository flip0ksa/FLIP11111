<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FL!P</title>
    <style>
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        body {
            min-height: 100vh;
            background: #071525;
            color: white;
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            overflow-x: hidden;
        }
        /* Flying stars */
        .stars {
            position: fixed;
            inset: 0;
            overflow: hidden;
            z-index: 0;
        }
        .star {
            position: absolute;
            width: 3px;
            height: 3px;
            background: white;
            border-radius: 50%;
            opacity: 0.7;
            animation: fly linear infinite;
        }
        @keyframes fly {
            from {
                transform: translateY(110vh);
                opacity: 0;
            }
            20% {
                opacity: 0.8;
            }
            80% {
                opacity: 0.8;
            }
            to {
                transform: translateY(-10vh);
                opacity: 0;
            }
        }
        .container {
            position: relative;
            z-index: 2;
            width: 100%;
            max-width: 500px;
            padding: 60px 25px 40px;
            text-align: center;
        }
        .logo {
            font-size: 55px;
            font-weight: 900;
            letter-spacing: -4px;
            margin-bottom: 12px;
        }
        .logo span {
            color: #ff2b2b;
        }
        .description {
            color: #aeb8c5;
            font-size: 14px;
            margin-bottom: 35px;
        }
        .links {
            display: flex;
            flex-direction: column;
            gap: 14px;
        }
        .link {
            display: block;
            text-decoration: none;
            color: white;
            border: 1px solid rgba(255,255,255,0.15);
            background: rgba(255,255,255,0.06);
            padding: 17px;
            border-radius: 12px;
            font-size: 15px;
            font-weight: 600;
            transition: 0.3s;
            backdrop-filter: blur(8px);
        }
        .link:hover {
            transform: translateY(-3px);
            background: rgba(255,255,255,0.12);
            border-color: rgba(255,255,255,0.35);
        }
        .shop {
            background: white;
            color: #071525;
            border-color: white;
        }
        .shop:hover {
            background: #eeeeee;
        }
        .footer {
            margin-top: 45px;
            color: #687587;
            font-size: 11px;
            letter-spacing: 2px;
        }
    </style>
</head>
<body>
    <!-- Flying stars -->
    <div class="stars">
        <div class="star" style="left:5%; animation-duration:8s; animation-delay:1s;"></div>
        <div class="star" style="left:15%; animation-duration:11s; animation-delay:3s;"></div>
        <div class="star" style="left:25%; animation-duration:7s; animation-delay:2s;"></div>
        <div class="star" style="left:38%; animation-duration:10s; animation-delay:5s;"></div>
        <div class="star" style="left:50%; animation-duration:8s; animation-delay:1s;"></div>
        <div class="star" style="left:62%; animation-duration:12s; animation-delay:4s;"></div>
        <div class="star" style="left:74%; animation-duration:9s; animation-delay:2s;"></div>
        <div class="star" style="left:85%; animation-duration:7s; animation-delay:6s;"></div>
        <div class="star" style="left:95%; animation-duration:10s; animation-delay:3s;"></div>
    </div>
    <main class="container">
        <!-- FL!P Logo -->
        <div class="logo">
            FL<span>!</span>P
        </div>
        <p class="description">
            Flip the way you live.
        </p>
        <!-- Links -->
        <div class="links">
            <a class="link shop" href="YOUR_STORE_LINK" target="_blank">
                SHOP FL!P
            </a>
            <a class="link" href="YOUR_INSTAGRAM_LINK" target="_blank">
                INSTAGRAM
            </a>
            <a class="link" href="YOUR_TIKTOK_LINK" target="_blank">
                TIKTOK
            </a>
            <a class="link" href="YOUR_CONTACT_LINK" target="_blank">
                CONTACT
            </a>
        </div>
        <div class="footer">
            FL!P — SAUDI BRAND
        </div>
    </main>
</body>
</html>
