<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Katalog Jednorazówek</title>
<style>
body{margin:0;font-family:Arial,sans-serif;background:#0e0e0e;color:#eaeaea;}
header{background:#000;padding:25px;text-align:center;border-bottom:1px solid #222;}
.products{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:20px;padding:20px;}
.card{background:#161616;border-radius:14px;overflow:hidden;box-shadow:0 6px 18px rgba(0,0,0,.6);transition: transform 0.2s ease, box-shadow 0.2s ease;}
.card:hover{transform: translateY(-5px);box-shadow: 0 10px 25px rgba(0,0,0,0.7);}
.card img{width:100%;height:230px;object-fit:cover;}
.content{padding:15px;}
h3{margin:0 0 6px;color:#fff;}
.meta{font-size:13px;color:#aaa;margin-bottom:8px;}
.content ul{padding-left:18px;margin:0;font-size:13px;color:#bbb;max-height:180px;overflow-y:auto;}
footer{text-align:center;font-size:12px;color:#777;padding:15px;border-top:1px solid #222;}
#ageOverlay{position:fixed;inset:0;background:rgba(0,0,0,.95);display:flex;align-items:center;justify-content:center;z-index:9999;}
.ageBox{background:#111;padding:30px;border-radius:14px;max-width:420px;text-align:center;border:1px solid #333;}
.ageBox button{margin-top:15px;padding:10px 20px;font-weight:bold;border:none;border-radius:6px;cursor:pointer;}
</style>
</head>
<body>
<div id="ageOverlay">
<div class="ageBox">
<h2>🔞 Ostrzeżenie</h2>
<p>Strona zawiera informacje o produktach nikotynowych.<br>Tylko dla osób pełnoletnich (18+).<br>Nikotyna jest substancją silnie uzależniającą.</p>
<button onclick="acceptAge()">Mam ukończone 18 lat</button>
</div>
</div>

<header>
<h1>Jednorazowe e-papierosy</h1>
<p>Katalog modeli i dostępnych smaków</p>
</header>

<section class="products">

<!-- MODEL 1 -->
<div class="card">
<img src="test.jfif" alt="Merryblade" width="300" loading="lazy">
<div class="content">
<h3>Merryblade</h3>
<div class="meta">30000 puff • 5% • regulacja mocy 10–26W</div>
<ul>
<li>Prime Strawberry</li><li>Kiwi Passion Fruit Guava</li><li>Aloe Blackcurrant</li>
<li>Lush Ice</li><li>Peach Lemonade</li><li>Strawberry Raspberry Cherry Ice</li>
<li>Mixed Berries</li><li>Red Energy Ice</li><li>Dragon Fruit Ice</li>
<li>Sunset Lime</li><li>Honey Peach</li><li>Green Apple</li>
<li>Frozen Grape</li><li>Fizzy Cherry</li><li>Crazy Blueberry</li>
<li>Grapefruit Refresher</li><li>Aperol</li><li>Desert Candy</li>
<li>Vimto</li><li>Breezy Lemon Berry</li><li>Summer Blaze</li>
<li>Tropical Citrus Fizz</li><li>Mr. Blue</li><li>Fanta</li>
<li>Love 66</li><li>Lemon Mojito</li><li>Jager Red Energy</li>
<li>Orange Dragon</li><li>Iced Peach Melon</li><li>Dr Pepper</li>
<li>Grape Berry</li><li>Peach Guava</li><li>Forest Berries</li>
<li>Wicks</li><li>Wilderness Forest</li><li>Grape Slush</li>
</ul>
</div>
</div>

<!-- MODEL 2 -->
<div class="card">
<img src="model2.jpg" alt="ETS Dual Galaxy" loading="lazy">
<div class="content">
<h3>ETS Dual Galaxy</h3>
<div class="meta">30000 puff • 5% • dual flavor</div>
<ul>
<li>Juicy Peach / Double Apple</li>
<li>Blackberry Gum / Fresh Mint Gum</li>
<li>Blueberry Raspberry / Strawberry Ice</li>
<li>Watermelon Ice / Triple Melon</li>
<li>Passion Berry / Cherry Ice</li>
<li>Lemon Lime / Pink Lemon</li>
<li>Blueberry Sour Raspberry / Blackberry Ice</li>
<li>Summer Dream / Aloe Grape</li>
<li>Mr Black / Blue Razz Ice</li>
<li>Apple Peach / Mango Peach</li>
<li>Cherry Cola Ice / Watermelon Cherry</li>
<li>Strawberry Pomegranate / Strawberry Kiwi Pomegranate</li>
<li>Skittles / Orange Melon</li>
<li>Kiwi Guava / Strawberry Kiwi</li>
<li>Blueberry cherry cranberry / Strawberry Raspberry Cherry Ice</li>
</ul>
</div>
</div>

<!-- MODEL 3 -->
<div class="card">
<img src="model3.jpg" alt="MerryMi M-Mecha" loading="lazy">
<div class="content">
<h3>MerryMi M-Mecha</h3>
<div class="meta">16000 puff • 3%</div>
<ul>
<li>Watermelon Ice</li><li>Strawberry Kiwi</li><li>Pink Peach</li>
<li>Black Cherry Lime</li><li>Cactus Candy</li><li>Lychee Ice</li>
<li>Blue Razz Ice</li><li>Sour Apple</li><li>Grape Ice</li>
<li>Cherry Cola</li><li>Dragon Fruit Ice</li><li>Mix Berries</li>
<li>Red Energy Ice</li><li>Orange Ice Kiwi</li><li>Pineapple Orange Soda</li>
<li>Kiwi Passion Fruit Guava</li><li>Pink Lemonade</li><li>Jagermeister Red Bull</li>
<li>Miami Mint</li><li>Blueberry Watermelon</li><li>Mr Blue</li>
<li>Prime Strawberry</li><li>Love66</li><li>Vimto</li>
<li>Fanta</li><li>Sour Lemon Mojito</li><li>Pine Needle Berry</li>
<li>Cranberry Lime</li><li>White Peach Berries</li><li>Sour Strawberry Daiquiri</li>
<li>Dr. Pepper</li><li>Wicks</li><li>Peach Guava</li>
<li>Grapefruit Refresher</li><li>Grape Berry</li>
</ul>
</div>
</div><!-- MODEL 4 -->
<div class="card">
<img src="model4.jpg" alt="MerryMi 20000" loading="lazy">
<div class="content">
<h3>MerryMi 20000</h3>
<div class="meta">20000 puff • 5%</div>
<ul>
<li>Blackcurrant Dragon Fruit</li>
<li>Mixed Berry</li>
<li>Blueberry Raspberry</li>
<li>Kiwi Passion Fruit Guava</li>
<li>Love 66</li>
<li>Summer Blaze</li>
<li>Red Energy Ice</li>
<li>Cactus Candy</li>
<li>Vimto</li>
<li>Summer Peach Ice</li>
<li>Watermelon Ice</li>
<li>Prime Strawberry</li>
</ul>
</div>
</div>

<!-- MODEL 5 -->
<div class="card">
<img src="model5.jpg" alt="MerryMi Mecha Pro" loading="lazy">
<div class="content">
<h3>MerryMi Mecha Pro</h3>
<div class="meta">35000 puff • 5%</div>
<ul>
<li>Cactus Candy</li>
<li>White Peach Berries</li>
<li>Summer Blaze</li>
<li>Watermelon Ice</li>
<li>Blue Razz Ice</li>
<li>Jager Red Energy</li>
<li>Blueberry Cherry Cranberry</li>
<li>Fanta</li>
<li>Vimto</li>
</ul>
</div>
</div>

<!-- MODEL 6 -->
<div class="card">
<img src="model6.jpg" alt="Airmez Fox 4in1" loading="lazy">
<div class="content">
<h3>Airmez Fox 4in1</h3>
<div class="meta">120000 puff • 2% • 4 smaki</div>
<ul>
<li>Strawberry Raspberry / Strawberry Kiwi / Strawberry Ice / Peach Mango Watermelon</li>
<li>Pink Lemonade / Passion Kiss / Mixed Berries / Triple Berry</li>
<li>Love 66 / Cherry / Blueberry On Ice / Kiwi Passion Fruit Guava</li>
<li>Mango Peach / Tropical Fruit / Peach Ice / Sour Mango Pineapple</li>
<li>Watermelon Ice / Raspberry Watermelon / Blueberry Raspberry / Strawberry Watermelon</li>
<li>Peach Mango Watermelon / Blueberry Cherry / Watermelon Dragon Fruit / Passion Kiss</li>
<li>Peach Ice / Pink Lemonade / Watermelon Ice / Dr Blue</li>
<li>Grape Ice / Love 66 / Blueberry On Ice / Dragonfruit Ice</li>
<li>Red Mojito / Love 66 / Mixed Berries / Strawberry Watermelon</li>
<li>Cherry / Love 66 / Berry Lemonade / Grape Ice</li>
</ul>
</div>
</div><!-- MODEL 7 -->
<div class="card">
<img src="model7.jpg" alt="Tornado" loading="lazy">
<div class="content">
<h3>Tornado</h3>
<div class="meta">15000 puff • 5% / 2%</div>
<ul>
<li>Kiwi Passion Fruit Guava</li>
<li>Grape Ice</li>
<li>Blueberry On Ice</li>
<li>Dragon Fruit</li>
<li>Mixed Berry</li>
<li>Blue Razz Lemonade</li>
</ul>
</div>
</div>

<!-- MODEL 8 -->
<div class="card">
<img src="model8.jpg" alt="Fumot Tornado" loading="lazy">
<div class="content">
<h3>Fumot Tornado</h3>
<div class="meta">20000 puff • 5%</div>
<ul>
<li>Blueberry Raspberry Hard Candy</li>
<li>Strawberry Kiwi</li>
<li>Peach Pineapple Orange</li>
<li>Skittles</li>
<li>Pear Ice</li>
<li>Cotton Candy</li>
<li>Jelly Beans</li>
<li>Huckleberry</li>
<li>Watermelon Ice</li>
<li>Strawberry Watermelon</li>
<li>Mixed Berry</li>
<li>Lychee Hami Melon</li>
<li>Cherry Lime</li>
<li>Pineapple Lemon Green Apple</li>
<li>Banana Cake</li>
<li>Mr Blue</li>
<li>Blueberry Raspberry</li>
<li>Cherry Cola</li>
<li>Kiwi Passion Fruit Guava</li>
<li>Strawberry Raspberry Cherry Ice</li>
<li>Cherry Berry</li>
<li>Blueberry Sour Raspberry</li>
<li>Peach Berry</li>
<li>Blue Razz Gummy Bear</li>
<li>Cool Mint</li>
<li>Cactus Ice</li>
<li>Red Grape Lime</li>
<li>Cola Lemon</li>
<li>Blackcurrant Apple</li>
<li>Cactus Kiwi</li>
<li>Cola Ice</li>
<li>Mango Grape Ice</li>
<li>Blueberry Cactus Ice</li>
<li>Grape Kiwi</li>
<li>Apple Grapefruit</li>
</ul>
</div>
</div>

<!-- MODEL 9 -->
<div class="card">
<img src="model9.jpg" alt="Fumot Digital Monkey" loading="lazy">
<div class="content">
<h3>Fumot Digital Monkey</h3>
<div class="meta">40000 puff • 5%</div>
<ul>
<li>Banana Ice</li>
<li>Strawberry Watermelon</li>
<li>Blueberry Raspberry</li>
<li>Black Ice</li>
<li>White Gummy Ice</li>
<li>Watermelon Ice</li>
<li>Juicy Peach Ice</li>
<li>Pink Lemonade</li>
<li>Strawberry Mango</li>
<li>Peach Mango Watermelon</li>
<li>Grape Lemon</li>
<li>Tropical Rainbow Blast</li>
<li>Cherry Bomb</li>
<li>Strawberry Mint Candy</li>
<li>Double Apple</li>
</ul>
</div>
</div><!-- MODEL 10 -->
<div class="card">
<img src="model10.jpg" alt="Movkin Tycoon" loading="lazy">
<div class="content">
<h3>Movkin Tycoon</h3>
<div class="meta">40000 puff • 5% • tryby ICE & nikotyny</div>
<ul>
<li>Watermelon Strawberry</li>
<li>Blueberry Blackberry</li>
<li>Miami Mint</li>
<li>Raspberry Peach Lime</li>
<li>Sour Mango Pineapple</li>
<li>Blue Razz Ice</li>
<li>Sour Apple</li>
<li>Berry Cherry Lime</li>
<li>Watermelon Ice</li>
<li>Blackcurrant Strawberry</li>
<li>Banana Taffy Freze</li>
<li>Orange Fucking Fab</li>
<li>Grape Lemon</li>
<li>Peachy Mango Watermelon</li>
<li>Strawberry B-Pop</li>
<li>Juicy Peach</li>
</ul>
</div>
</div>

<!-- MODEL 11 -->
<div class="card">
<img src="model11.jpg" alt="RandM Tornado 60k 3in1" loading="lazy">
<div class="content">
<h3>RandM Tornado 60k 3in1</h3>
<div class="meta">60000 puff • 5% • 3 smaki</div>
<ul>
<li>Watermelon Ice / Strawberry Red Bull / Strawberry Kiwi</li>
<li>Strawberry Watermelon / Blueberry on Ice / Kiwi Lemon</li>
<li>Mixed Berries / Peach Apple Ice / Lady Killer</li>
<li>Mango Ice / Banana Ice / Blue Razz Lemonade</li>
<li>Peach Mango Pineapple / Strawberry Raspberry Ice / Triple Mango</li>
<li>Strawberry Grape / Peach Mango / Ice Pop</li>
<li>Strawberry Ice / Sour Apple / Blueberry Raspberry</li>
<li>Grape Ice / Cherry Ice / Blue Sour Raspberry</li>
<li>Peach Ice / Red Apple / Blueberry Cherry Cranberry</li>
<li>Kiwi Passion Fruit Guava / Green Apple / Juicy Peach</li>
</ul>
</div>
</div>

<!-- MODEL 12 -->
<div class="card">
<img src="model12.jpg" alt="WGA Crystal Plus" loading="lazy">
<div class="content">
<h3>WGA Crystal Plus</h3>
<div class="meta">20000 puff • 5% • 2 smaki</div>
<ul>
<li>Blue Razz Gummy / Blue Raspberry</li>
<li>Strawberry Raspberry Ice / Blueberry Cherry Cranberry</li>
<li>Lemon Lime / Lemonade Sherbet Ice</li>
<li>Blueberry Ice / Strawberry Ice</li>
<li>Blue Razz Lemonade / Cola Lemon</li>
<li>Heisenberg / Pinkman</li>
<li>Watermelon Cherry / Mr Pink</li>
<li>Strawberry Ice Cream / Strawberry Banana</li>
<li>Blueberry Ice Pop / Strawberry Ice Pop</li>
<li>Cherry Ice / Orange Ice</li>
</ul>
</div>
</div>

</section>

<footer>
© 2026 • Katalog jednorazowych e-papierosów • 18+
</footer>

<script>
function acceptAge(){
  localStorage.setItem("ageAccepted","yes");
  document.getElementById("ageOverlay").style.display = "none"; // natychmiast ukryj overlay
}
if(localStorage.getItem("ageAccepted") === "yes"){
  document.getElementById("ageOverlay").style.display = "none";
}
</script>

</body>
</html>
