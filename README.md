<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Hans Branding</title>
  <link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      padding: 0;
      background: url('pou.png') no-repeat center center fixed;
      background-size: cover;
      font-family: 'Bebas Neue', sans-serif;
      color: white;
      text-align: center;
    }

    .fire-text {
      font-size: 48px;
      margin-top: 80px;
      color: #fff;
      text-shadow: 0 0 15px black, 0 0 25px black, 0 0 35px white;
      animation: floatText 3s ease-in-out infinite, fireGlow 2s linear infinite;
    }

    @keyframes fireGlow {
      0% { text-shadow: 0 0 10px black, 0 0 20px white, 0 0 30px black; }
      50% { text-shadow: 0 0 20px black, 0 0 40px white, 0 0 60px white; }
      100% { text-shadow: 0 0 10px black, 0 0 20px black, 0 0 30px white; }
    }

    @keyframes floatText {
      0% { transform: translateY(0); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0); }
    }

    .menu {
      margin-top: 40px;
    }

    .menu a {
      display: block;
      margin: 15px auto;
      padding: 15px 25px;
      width: 250px;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 12px;
      text-decoration: none;
      color: white;
      font-size: 18px;
      transition: 0.3s;
      border: 1px solid #ffffff99;
    }

    .menu a:hover {
      background: #ffffffcc;
      color: black;
    }

    .footer {
      margin-top: 50px;
      font-size: 14px;
      color: #ccc;
    }
  </style>
</head>
<body>

  <div class="fire-text">Hai, ada yang bisa Hans bantu?</div>

  <div class="menu">
    <a href="https://linktr.ee/portfoliohans" target="_blank"> Link Portofolio</a>
    <a href="https://instagram.com/hans_.py" target="_blank">   Instagram Hans_.py</a>
    <a href="https://Instagram.com/hans.expreptschips" target="_blank">   Online Shop Hans</a>
    <a href="https://wa.me/6283877486039" target="_blank">   WhatsApp Bisnis</a>
    <a href="galeri.html" target="_blank">   Foto Kenangan</a>
  </div>

  <div class="footer">Powered by Hans</div>

</body>
