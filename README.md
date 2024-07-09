<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <title>中國風山水圖</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
      font-family: 'SimSun', serif;
    }

    .container {
      position: relative;
      width: 800px;
      height: 600px;
      overflow: hidden;
      border-radius: 10px;
      box-shadow: 0 0 20px rgba(0, 0, 0, 0.2);
    }

    .background {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background-image: url('data:image/svg+xml,%3Csvg viewBox="0 0 1000 800" xmlns="http://www.w3.org/2000/svg"%3E%3Cpath d="M0 0h1000v800H0z" fill="%23d0d0d0" /%3E%3Cpath d="M0 0h500v800H0z" fill="%23c0c0c0" /%3E%3Cpath d="M500 0h500v800H500z" fill="%23e0e0e0" /%3E%3Cpath d="M250 0h500v800H250z" fill="%23b0b0b0" /%3E%3Cpath d="M750 0h250v800H750z" fill="%23f0f0f0" /%3E%3C/svg%3E');
      background-size: cover;
      background-position: center;
    }

    .text {
      position: absolute;
      top: 50%;
      left: 50%;
      transform: translate(-50%, -50%);
      font-size: 80px;
      font-weight: bold;
      color: #333;
      text-shadow: 1px 1px 2px rgba(255, 255, 255, 0.5);
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="background"></div>
    <div class="text">雲煙繚繞,山色迷人</div>
  </div>
</body>
</html>
