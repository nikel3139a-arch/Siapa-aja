<!DOCTYPE html>
<html lang="id">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>tulisan</title>
  <style>
    body {
      background: #fofofo;
      text-align: center;
      font-family: Arial, sans-serif;
      margin-top: 50px;
    }

    /* Tulisan bergerak ke kanan dan kiri */
    .marquee {
      width: 100%;
      overflow: hidden;
      white-space: nowrap;
      box-sizing: border-box;
    }

    .marquee span {
      display: inline-block;
      padding-left: 100%;
      animation: marquee 10s linear infinite;
      font-size: 2em;
      color: #333;
      font-weight: bold;
    }

    @keyframes marquee {
      0% { transform: translateX(0); }
      50% { transform: translateX(-100%); }
      100% { transform: translateX(0); }
    }

    /* Gambar berputar 360 derajat */
    .rotate {
      width: 200px;
      height: 200px;
      margin-top: 50px;
      animation: spin 1s linear infinite;
    }

    @keyframes spin {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
  </style>
</head>
<body>

  <div class="marquee">
    <span>🖕😸🖕</span>
  </div>

  <img src="https://share.google/hTZlSKvLhnkRDOcHB" alt="Gambar Berputar" class="rotate">

</body>
</html>
