# katalog-jednorazowek
Jednorazowki 
<!DOCTYPE html>
<html lang="pl">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Katalog Jednorazówek</title>

<link rel="stylesheet" href="style.css">
</head>

<body>

<div id="ageOverlay">
  <div class="ageBox">
    <h2>🔞 Ostrzeżenie</h2>
    <p>
      Strona zawiera informacje o produktach nikotynowych.<br>
      Tylko dla osób pełnoletnich (18+).<br>
      Nikotyna jest substancją silnie uzależniającą.
    </p>
    <button onclick="acceptAge()">Mam ukończone 18 lat</button>
  </div>
</div>

<header>
  <h1>Jednorazowe e-papierosy</h1>
  <p>Katalog modeli i dostępnych smaków</p>
</header>

<section class="products" id="products"></section>

<footer>
© 2026 • Katalog jednorazowych e-papierosów • 18+
</footer>

<script src="script.js"></script>
</body>
</html>



body{
  margin:0;
  font-family:'Segoe UI',sans-serif;
  background:#0b0b0f;
  color:#e6e6e6;
}

/* HEADER */

header{
  background:linear-gradient(145deg,#050505,#111);
  padding:35px;
  text-align:center;
  border-bottom:1px solid #222;
}

h1{
  margin:0;
  font-size:32px;
}

/* GRID */

.products{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:25px;
  padding:25px;
}

/* CARD */

.card{
  background:linear-gradient(160deg,#111,#1a1a1f);
  border-radius:18px;
  overflow:hidden;
  transition:.25s;
  box-shadow:0 10px 30px rgba(0,0,0,.6);
}

.card:hover{
  transform:translateY(-8px) scale(1.02);
}

/* IMAGE */

.card img{
  width:100%;
  height:240px;
  object-fit:cover;
}

/* CONTENT */

.content{
  padding:18px;
}

.meta{
  color:#8b8b8b;
  font-size:13px;
  margin-bottom:10px;
}

ul{
  max-height:180px;
  overflow:auto;
  padding-left:18px;
  color:#bdbdbd;
}

/* FOOTER */

footer{
  text-align:center;
  padding:20px;
  color:#777;
  border-top:1px solid #222;
}

/* AGE */

#ageOverlay{
  position:fixed;
  inset:0;
  background:#000;
  display:flex;
  align-items:center;
  justify-content:center;
  z-index:999;
}

.ageBox{
  background:#111;
  padding:35px;
  border-radius:20px;
  text-align:center;
  max-width:420px;
  border:1px solid #333;
}

button{
  margin-top:15px;
  padding:12px 24px;
  border:none;
  border-radius:10px;
  background:#6a5cff;
  color:white;
  font-weight:bold;
  cursor:pointer;
  transition:.2s;
}

button:hover{
  background:#5848ff;
}




const products = [
{
name:"Merryblade",
img:"images/model1.jpg",
meta:"30000 puff • 5% • regulacja mocy 10–26W",
flavors:[
"Prime Strawberry",
"Kiwi Passion Fruit Guava",
"Aloe Blackcurrant",
"Lush Ice",
"Peach Lemonade"
]
},
{
name:"ETS Dual Galaxy",
img:"images/model2.jpg",
meta:"30000 puff • 5% • dual flavor",
flavors:[
"Juicy Peach / Double Apple",
"Blackberry Gum / Fresh Mint Gum",
"Blueberry Raspberry / Strawberry Ice"
]
}
];

const container = document.getElementById("products");

products.forEach(p=>{
const card = document.createElement("div");
card.className="card";

card.innerHTML=`
<img src="${p.img}" loading="lazy">
<div class="content">
<h3>${p.name}</h3>
<div class="meta">${p.meta}</div>
<ul>
${p.flavors.map(f=>`<li>${f}</li>`).join("")}
</ul>
</div>
`;

container.appendChild(card);
});

/* AGE */

function acceptAge(){
localStorage.setItem("ageAccepted","yes");
document.getElementById("ageOverlay").style.display="none";
}

if(localStorage.getItem("ageAccepted")==="yes"){
document.getElementById("ageOverlay").style.display="none";
}
