# Singapore-Trip-2026
<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Singapore Malaysia Family Trip 2026</title>
<style>
body{font-family:-apple-system,BlinkMacSystemFont,sans-serif;margin:0;background:#f5f7fb;color:#222;padding-bottom:70px}
header{background:#2563eb;color:white;padding:22px;border-radius:0 0 22px 22px}
h1{font-size:22px;margin:0}
section{padding:14px}
.card{background:white;border-radius:16px;padding:14px;margin:12px 0;box-shadow:0 4px 14px #0001}
h2{font-size:18px;margin:0 0 8px}
.small{color:#666;font-size:13px}
.btn{display:inline-block;background:#2563eb;color:white;padding:9px 12px;border-radius:10px;text-decoration:none;margin:4px 0}
nav{position:fixed;bottom:0;left:0;right:0;background:white;display:grid;grid-template-columns:repeat(5,1fr);border-top:1px solid #ddd}
nav button{border:0;background:white;padding:8px;font-size:11px}
.page{display:none}
.page.active{display:block}
</style>
</head>
<body>

<header>
<h1>Singapore & Malaysia Family Trip 2026</h1>
<p>2026/8/6 - 8/19｜Singapore → Johor → Desaru</p>
</header>

<section id="home" class="page active">
<div class="card">
<h2>今日の確認</h2>
<p>フライト予約番号：<b>V77DMI</b></p>
<p>緊急番号：Malaysia 999 / Singapore 999・995</p>
<p>Desaru滞在：8/11 - 8/13</p>
</div>
<div class="card">
<h2>重要メモ</h2>
<p>・パスポート、保険、予約番号をオフライン保存</p>
<p>・Singapore → Johorの国境越えは朝早め推奨</p>
<p>・Desaruは水着、虫除け、日焼け止め必須</p>
</div>
</section>

<section id="plan" class="page">
<div class="card"><h2>8/6</h2><p>15:50 KIX → SIN Scoot TR821<br>21:25 Singapore到着<br>Paradox Singapore Merchant Court宿泊</p></div>
<div class="card"><h2>8/11</h2><p>Singapore出発 → Kota Tinggi Fruit Farm → Desaru Check-in</p></div>
<div class="card"><h2>8/12</h2><p>Desaru Beach / River Cruise / Pasar Malam候補</p></div>
<div class="card"><h2>8/13</h2><p>Desaru Resort Morning / Free Time</p></div>
<div class="card"><h2>8/19</h2><p>06:55 SIN → KIX Scoot TR820<br>14:35 Kansai到着</p></div>
</section>

<section id="booking" class="page">
<div class="card"><h2>Flight</h2><p>Scoot TR821 / TR820<br>Booking Ref: V77DMI</p></div>
<div class="card"><h2>Hotel</h2><p>Paradox Singapore Merchant Court at Clarke Quay<br>8/6 - 8/8</p></div>
<div class="card"><h2>Desaru</h2><p>Desaru Hideout at Tiara Resort<br>8/11 - 8/13</p></div>
</section>

<section id="map" class="page">
<div class="card"><h2>Google Maps</h2>
<a class="btn" href="https://www.google.com/maps/search/Paradox+Singapore+Merchant+Court" target="_blank">Paradox Singapore</a><br>
<a class="btn" href="https://www.google.com/maps/search/Kota+Tinggi+Fruit+Farm" target="_blank">Kota Tinggi Fruit Farm</a><br>
<a class="btn" href="https://www.google.com/maps/search/Desaru+Beach" target="_blank">Desaru Beach</a><br>
<a class="btn" href="https://www.google.com/maps/search/Hospital+Kota+Tinggi" target="_blank">Hospital Kota Tinggi</a>
</div>
</section>

<section id="pack" class="page">
<div class="card"><h2>Packing</h2>
<label><input type="checkbox"> Passport</label><br>
<label><input type="checkbox"> Flight tickets</label><br>
<label><input type="checkbox"> Hotel reservations</label><br>
<label><input type="checkbox"> Travel insurance</label><br>
<label><input type="checkbox"> Swimwear</label><br>
<label><input type="checkbox"> Sunscreen</label><br>
<label><input type="checkbox"> Insect repellent</label><br>
<label><input type="checkbox"> Power bank</label>
</div>
</section>

<nav>
<button onclick="show('home')">🏠<br>Home</button>
<button onclick="show('plan')">📅<br>Plan</button>
<button onclick="show('booking')">✈️<br>Book</button>
<button onclick="show('map')">📍<br>Map</button>
<button onclick="show('pack')">🎒<br>Pack</button>
</nav>

<script>
function show(id){
document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));
document.getElementById(id).classList.add('active');
window.scrollTo(0,0);
}
</script>

</body>
</html>