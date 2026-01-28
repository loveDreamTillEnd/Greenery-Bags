<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>🌱 Greenery&Bags - Túi Giấy Hạt Giống Siêu Cute!</title>
  <style>
    /* Reset & Fonts */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background: #f9f5f0;
      color: #4a4a4a;
      line-height: 1.6;
    }

    /* Header */
    header {
      background: linear-gradient(135deg, #a8e6cf, #dcedc1);
      padding: 2rem 1rem;
      text-align: center;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      position: relative;
      overflow: hidden;
    }
    header h1 {
      font-size: 2.5rem;
      color: #2e7d32;
      margin-bottom: 0.5rem;
      text-shadow: 2px 2px 4px rgba(255,255,255,0.5);
    }
    header p {
      font-size: 1.2rem;
      color: #558b2f;
      max-width: 600px;
      margin: 0 auto;
    }
    .leaf {
      position: absolute;
      opacity: 0.3;
      z-index: -1;
    }
    .leaf:nth-child(1) { top: 10%; left: 5%; transform: rotate(15deg); }
    .leaf:nth-child(2) { bottom: 10%; right: 5%; transform: rotate(-20deg); }

    /* Hero Image */
    .hero {
      padding: 2rem;
      text-align: center;
      background: #fff;
      margin: 2rem auto;
      max-width: 800px;
      border-radius: 20px;
      box-shadow: 0 6px 20px rgba(0,0,0,0.08);
    }
    .hero img {
      width: 100%;
      max-width: 400px;
      border-radius: 12px;
      box-shadow: 0 4px 16px rgba(0,0,0,0.1);
      transition: transform 0.3s ease;
    }
    .hero img:hover {
      transform: scale(1.03);
    }
    .hero h2 {
      font-size: 2rem;
      color: #2e7d32;
      margin: 1.5rem 0 0.5rem;
    }
    .hero p {
      font-size: 1.1rem;
      color: #558b2f;
      max-width: 600px;
      margin: 0 auto;
    }

    /* How to Use Section */
    .how-to {
      padding: 3rem 1rem;
      background: #f1f8e9;
      text-align: center;
    }
    .how-to h2 {
      font-size: 2.2rem;
      color: #2e7d32;
      margin-bottom: 1.5rem;
      position: relative;
    }
    .how-to h2::after {
      content: '';
      display: block;
      width: 60px;
      height: 4px;
      background: #8bc34a;
      margin: 1rem auto;
      border-radius: 2px;
    }

    .steps {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }
    .step {
      background: white;
      padding: 1.5rem;
      border-radius: 16px;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
      width: 280px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      cursor: pointer;
    }
    .step:hover {
      transform: translateY(-5px);
      box-shadow: 0 8px 20px rgba(0,0,0,0.1);
    }
    .step-number {
      font-size: 2.5rem;
      font-weight: bold;
      color: #8bc34a;
      margin-bottom: 0.5rem;
    }
    .step-title {
      font-size: 1.3rem;
      color: #2e7d32;
      margin-bottom: 0.5rem;
    }
    .step-desc {
      font-size: 1rem;
      color: #558b2f;
    }
    .step-icon {
      font-size: 3rem;
      margin-bottom: 1rem;
      color: #8bc34a;
    }

    /* Footer */
    footer {
      background: #333;
      color: white;
      padding: 2rem 1rem;
      text-align: center;
      margin-top: 3rem;
    }
    footer h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
      color: #a8e6cf;
    }
    footer p {
      font-size: 1.1rem;
      margin: 0.5rem 0;
    }
    .contact-info {
      font-size: 1.2rem;
      font-weight: bold;
      color: #a8e6cf;
      margin: 1rem 0;
    }
    .social-icons {
      margin-top: 1.5rem;
    }
    .social-icons a {
      display: inline-block;
      margin: 0 10px;
      font-size: 2rem;
      color: #a8e6cf;
      transition: transform 0.2s ease;
    }
    .social-icons a:hover {
      transform: scale(1.2) rotate(10deg);
      color: #8bc34a;
    }

    /* Animations */
    @keyframes float {
      0% { transform: translateY(0px); }
      50% { transform: translateY(-10px); }
      100% { transform: translateY(0px); }
    }
    .floating {
      animation: float 3s ease-in-out infinite;
    }

    /* Responsive */
    @media (max-width: 768px) {
      header h1 { font-size: 2rem; }
      .steps { flex-direction: column; align-items: center; }
      .step { width: 100%; max-width: 350px; }
    }
  </style>
</head>
<body>

  <!-- Header -->
  <header>
    <div class="leaf">🌿</div>
    <div class="leaf">🍃</div>
    <h1>🌱 Greenery&Bags</h1>
    <p>Túi giấy có hạt giống – Mua túi, trồng cây, cứu hành tinh!</p>
  </header>

<!-- Hero Section -->
<section class="hero">
  <img 
    src="https://i.postimg.cc/SxsL7NB6/z7471539768867-80e144df418abf5b5fbaca8fc5a2ffdc.jpg" 
    alt="Hai chiếc túi giấy hạt giống handmade từ bã mía, vỏ trứng và bã giấy — có thể trồng lại thành cây xanh" 
    class="floating"
    loading="lazy"
    width="400"
    height="500"
  >
  <h2>Chạm vào tương lai xanh cùng chúng mình!</h2>
  <p>Giấy từ bã mía, vỏ trứng, bã giấy thừa — thân thiện môi trường & có thể trồng lại thành cây xanh!</p>
</section>

  <!-- How to Use -->
  <section class="how-to">
    <h2>🌱 Cách dùng siêu đơn giản</h2>
    <div class="steps">
      <div class="step">
        <div class="step-icon">✂️</div>
        <div class="step-number">1</div>
        <h3 class="step-title">Cắt nhỏ</h3>
        <p class="step-desc">Cắt tờ giấy thành từng mảnh nhỏ — như đang cắt giấy origami vậy đó!</p>
      </div>
      <div class="step">
        <div class="step-icon">🪴</div>
        <div class="step-number">2</div>
        <h3 class="step-title">Cho vào chậu</h3>
        <p class="step-desc">Rải các mảnh giấy lên đất trong chậu — đừng quên chọn chậu đáng yêu nha!</p>
      </div>
      <div class="step">
        <div class="step-icon">💧</div>
        <div class="step-number">3</div>
        <h3 class="step-title">Tưới nước & chờ đợi</h3>
        <p class="step-desc">Tưới nhẹ mỗi ngày — vài tuần nữa, bạn sẽ thấy cây con mọc lên xanh mướt!</p>
      </div>
    </div>
  </section>

  <!-- Footer -->
  <footer>
    <h3>Liên hệ với Greenery&Bags 🌿</h3>
    <p>Chúng mình luôn sẵn sàng trả lời thắc mắc & nhận đặt hàng!</p>
    <div class="contact-info">
      📞 +84 3384840575<br>
      ✉️ trungvsquyen1212@gmail.com
    </div>
    <div class="social-icons">
      <a href="#" title="TikTok">🎵</a>
      <a href="#" title="Instagram">📸</a>
      <a href="#" title="Facebook">📘</a>
    </div>
    <p style="margin-top: 1rem; font-size: 0.9rem; opacity: 0.8;">© 2026 Greenery&Bags — Vì một thế giới xanh hơn, đáng yêu hơn.</p>
  </footer>

</body>
</html>
