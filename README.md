tiktok-recharge-ui
<html>
<head>
  <title>Coin Recharge</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<div class="container">
  <h2>Get Coins</h2>

  <div class="card">
    <h3>Recharge</h3>
    <p>Select a package</p>

    <div class="coins">
      <div class="box" onclick="selectCoin(30, 0.31)">30 Coins - $0.31</div>
      <div class="box" onclick="selectCoin(350, 3.65)">350 Coins - $3.65</div>
      <div class="box" onclick="selectCoin(700, 7.25)">700 Coins - $7.25</div>
      <div class="box" onclick="selectCoin(1400, 14.49)">1400 Coins - $14.49</div>
      <div class="box active" onclick="selectCoin(3500, 36.2)">3500 Coins - $36.2</div>
    </div>

    <button onclick="buyNow()">Buy Now</button>
  </div>
</div>

<script src="script.js"></script>
</body>
</html>