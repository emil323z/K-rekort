<!DOCTYPE html>
<html lang="da">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Kørekort App (Fake)</title>
  <style>
    body {
      background-color: #f0f2f5;
      font-family: 'Arial', sans-serif;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .card {
      background-color: white;
      width: 320px;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
      text-align: center;
    }
    .photo {
      width: 80px;
      height: 80px;
      border-radius: 50%;
      margin-bottom: 10px;
      object-fit: cover;
    }
    .info {
      margin-bottom: 15px;
    }
    .info h2 {
      margin: 10px 0 5px 0;
      font-size: 22px;
    }
    .info p {
      margin: 3px 0;
      font-size: 16px;
      color: #555;
    }
    .qr {
      margin-top: 15px;
    }
    .qr img {
      width: 100px;
      height: 100px;
    }
  </style>
</head>
<body>

<div class="card">
  <img src="https://i.imgur.com/6VBx3io.png" alt="Profilbillede" class="photo">
  <div class="info">
    <h2>Anders Jensen</h2>
    <p>Født: 01-01-1990</p>
    <p>Kørekortnr: 1234567890</p>
    <p>Gyldig til: 01-01-2035</p>
  </div>
  <div class="qr">
    <img src="https://api.qrserver.com/v1/create-qr-code/?size=100x100&data=FakeQRCode123" alt="QR-kode">
  </div>
</div>

</body>
</html>