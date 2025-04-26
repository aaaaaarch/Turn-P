<!DOCTYPE html>
<html lang="ja">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>TURN P - Official Site</title>
  <style>
    body { margin: 0; font-family: Arial, sans-serif; }
    header { background: #00aaff; color: white; padding: 1rem; position: sticky; top: 0; display: flex; align-items: center; justify-content: space-between; }
    .logo {
      font-size: 2rem;
      font-weight: bold;
      animation: rotate 5s linear infinite;
    }
    @keyframes rotate {
      from { transform: rotate(0deg); }
      to { transform: rotate(360deg); }
    }
    nav { display: flex; flex-wrap: wrap; }
    nav a { margin: 0 0.5rem; color: white; text-decoration: none; font-weight: bold; }

    .hero { background: #cceeff; text-align: center; padding: 5rem 1rem; }
    .hero h1 { font-size: 2.5rem; }
    .section { padding: 4rem 1rem; max-width: 1000px; margin: auto; }
    .products { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 2rem; }
    .product { background: #f0f8ff; padding: 1rem; border-radius: 8px; text-align: center; }
    .product img { width: 100%; height: 150px; object-fit: cover; border-radius: 4px; }
    footer { background: #003344; color: white; text-align: center; padding: 2rem 1rem; margin-top: 2rem; }
    .sns a { margin: 0 0.5rem; color: white; font-size: 1.5rem; }

    @media (max-width: 600px) {
      nav { flex-direction: column; align-items: center; }
      nav a { margin: 0.5rem 0; }
      .hero h1 { font-size: 2rem; }
      .products { grid-template-columns: 1fr; }
    }
  </style>
</head>
<body>

<header>
  <div class="logo">P</div>
  <nav>
    <a href="#products">商品一覧</a>
    <a href="#about">会社情報</a>
    <a href="#interview">インタビュー</a>
    <a href="#sns">SNS</a>
  </nav>
</header>

<section class="hero">
  <h1>着るだけで“ラク”になる服。</h1>
  <p>TURN P 公式サイトへようこそ！</p>
</section>

<section id="products" class="section">
  <h2>商品一覧</h2>
  <div class="products">
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="AIR SHORTS">
      <h3>AIR SHORTS</h3>
      <p>軽量＆通気性抜群のショートパンツ</p>
      <strong>\4,800</strong>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="RELAX TEE">
      <h3>RELAX TEE</h3>
      <p>着心地を追求したシンプルTシャツ</p>
      <strong>\3,500</strong>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="MOVE JERSEY">
      <h3>MOVE JERSEY</h3>
      <p>アクティブにもリラックスにも使えるジャージ</p>
      <strong>\7,200</strong>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="SOFT SETUP">
      <h3>SOFT SETUP</h3>
      <p>家でも外でもいける万能セットアップ</p>
      <strong>\9,800</strong>
    </div>
    <div class="product">
      <img src="https://via.placeholder.com/200x150" alt="EASY SHORTS">
      <h3>EASY SHORTS</h3>
      <p>ワンマイルウェアにも最適な短パン</p>
      <strong>\4,300</strong>
    </div>
  </div>
</section>

<section id="about" class="section">
  <h2>会社情報</h2>
  <p>"ファッション＝我慢"ではなく、"ファッション＝自由"を目指して。<br>
  私たちTURN Pは、着る人の居心地と自由を最優先に考えた服作りをしています。</p>
</section>

<section id="interview" class="section">
  <h2>社長・社員インタビュー</h2>
  <p><strong>社長コメント：</strong>「毎日着たくなる服を、本気で作りました。」</p>
  <p><strong>社員コメント：</strong>「一度着たら、もう他の服には戻れないと思います！」</p>
</section>

<section id="sns" class="section">
  <h2>FOLLOW US</h2>
  <div class="sns">
    <a href="#">Instagram</a>
    <a href="#">X (Twitter)</a>
    <a href="#">YouTube</a>
  </div>
</section>

<footer>
  <p>&copy; 2025 TURN P. All Rights Reserved.</p>
</footer>

</body>
</html>
