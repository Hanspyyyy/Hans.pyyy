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
      background-attachment: scroll; /* ganti dari fixed agar ringan */
    }

    .fire-text {
      font-size: 40px;
      margin-top: 60px;
      color: #fff;
      text-shadow: 0 0 8px black, 0 0 15px white;
      animation: floatText 3s ease-in-out infinite;
    }

    @keyframes floatText {
      0% { transform: translateY(0); }
      50% { transform: translateY(-6px); }
      100% { transform: translateY(0); }
    }

    .menu {
      margin-top: 30px;
    }

    .menu a {
      display: block;
      margin: 12px auto;
      padding: 12px 20px;
      width: 230px;
      background: rgba(0, 0, 0, 0.6);
      border-radius: 10px;
      text-decoration: none;
      color: white;
      font-size: 16px;
      transition: 0.3s;
      border: 1px solid #ffffff80;
    }

    .menu a:hover {
      background: #ffffffaa;
      color: black;
    }

    .footer {
      margin-top: 40px;
      font-size: 13px;
      color: #ccc;
    }
  </style>
</head>
<body>

  <div class="fire-text">Hai, ada yang bisa Hans bantu?</div>

  <div class="menu">
    <a href="https://linktr.ee/portfoliohans" target="_blank">Link Portofolio</a>
    <a href="https://instagram.com/hans_.py" target="_blank">Instagram Hans_.py</a>
    <a href="https://instagram.com/hans.expreptschips" target="_blank">Online Shop Hans</a>
    <a href="https://wa.me/6283877486039" target="_blank">WhatsApp Bisnis</a>
    <a href="galeri.html" target="_blank">Foto Kenangan</a>
  </div>

  <div class="footer">Powered by Hans</div>

</body>
