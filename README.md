<!DOCTYPE html>
<html lang="zh-CN">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Akrovan 衣服展示</title>
  <style>
    body {
      margin: 0; padding: 0;
      font-family: "微软雅黑", sans-serif;
      background: #fafafa;
      color: #333;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
      padding: 40px 20px;
    }
    h1 {
      font-size: 3rem;
      color: #222;
      margin-bottom: 40px;
      font-weight: 700;
      letter-spacing: 3px;
      user-select: none;
    }
    .gallery {
      display: flex;
      gap: 30px;
      flex-wrap: wrap;
      justify-content: center;
      max-width: 1000px;
      width: 100%;
    }
    .card {
      background: white;
      border-radius: 12px;
      box-shadow: 0 6px 15px rgba(0,0,0,0.1);
      overflow: hidden;
      width: 260px;
      cursor: pointer;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }
    .card:hover {
      transform: translateY(-10px);
      box-shadow: 0 15px 30px rgba(0,0,0,0.2);
    }
    .card img {
      width: 100%;
      display: block;
      height: 340px;
      object-fit: cover;
      transition: transform 0.4s ease;
    }
    .card:hover img {
      transform: scale(1.05);
    }
    .info {
      padding: 15px 20px;
      text-align: center;
    }
    .info h2 {
      margin: 0;
      font-size: 1.3rem;
      color: #444;
    }
    .info p {
      margin: 6px 0 0;
      color: #888;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>
  <h1>Akrovan</h1>
  <div class="gallery">
    <div class="card">
      <img src="https://images.unsplash.com/photo-1503341455253-b2e723bb3dbb?auto=format&fit=crop&w=400&q=80" alt="白色连帽衫" />
      <div class="info">
        <h2>白色连帽衫</h2>
        <p>舒适休闲，百搭必备</p>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1521334884684-d80222895322?auto=format&fit=crop&w=400&q=80" alt="黑色皮夹克" />
      <div class="info">
        <h2>黑色皮夹克</h2>
        <p>帅气硬朗，彰显个性</p>
      </div>
    </div>
    <div class="card">
      <img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91?auto=format&fit=crop&w=400&q=80" alt="蓝色牛仔裤" />
      <div class="info">
        <h2>蓝色牛仔裤</h2>
        <p>经典百搭，日常首选</p>
      </div>
    </div>
  </div>
</body>
</html>
