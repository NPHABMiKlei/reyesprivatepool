<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Reyes Hotspring Private Pool</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

:root{
--primary:#0077ff;
--secondary:#00d4ff;
--dark:#002c6f;
--orange:#ff9800;
--white:#fff;
--light:#f5fbff;
}

body{
background:var(--light);
overflow-x:hidden;
}

/* NAVBAR */

header{
position:fixed;
top:0;
left:0;
width:100%;
background:rgba(255,255,255,.95);
backdrop-filter:blur(10px);
z-index:1000;
box-shadow:0 2px 15px rgba(0,0,0,.1);
}

nav{
max-width:1200px;
margin:auto;
padding:15px 20px;
display:flex;
justify-content:space-between;
align-items:center;
}

.logo{
display:flex;
align-items:center;
gap:10px;
font-weight:700;
color:var(--dark);
}

.logo img{
height:50px;
}

nav ul{
display:flex;
gap:25px;
list-style:none;
}

nav a{
text-decoration:none;
color:#333;
font-weight:600;
}

/* HERO */

.hero{
height:100vh;
background:
linear-gradient(rgba(0,0,0,.5),rgba(0,0,0,.5)),
url('B6851927-AF54-42A9-9695-B6C8ECC4A5C1.png');
background-size:cover;
background-position:center;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:20px;
color:white;
}

.hero-content h1{
font-size:4rem;
font-weight:800;
}

.hero-content p{
font-size:1.2rem;
margin:20px 0;
}

.btn{
display:inline-block;
padding:15px 35px;
background:var(--orange);
color:white;
text-decoration:none;
border-radius:50px;
font-weight:700;
transition:.3s;
}

.btn:hover{
transform:translateY(-5px);
}

/* SECTIONS */

section{
padding:100px 20px;
}

.container{
max-width:1200px;
margin:auto;
}

.section-title{
text-align:center;
font-size:2.5rem;
margin-bottom:50px;
color:var(--dark);
}

/* ABOUT */

.about{
display:grid;
grid-template-columns:1fr 1fr;
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

/* GALLERY */

.gallery-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:20px;
}

.gallery-grid img{
width:100%;
height:250px;
object-fit:cover;
border-radius:15px;
transition:.4s;
}

.gallery-grid img:hover{
transform:scale(1.05);
}

/* AMENITIES */

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
padding:30px;
border-radius:20px;
text-align:center;
box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.card h3{
color:var(--primary);
margin-bottom:10px;
}

/* RATES */

.rate-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.rate-card{
background:white;
padding:40px;
text-align:center;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.rate-card h3{
color:var(--primary);
margin-bottom:15px;
}

.rate-card li{
list-style:none;
padding:8px;
font-weight:600;
}

/* POLICY */

.policy{
background:linear-gradient(135deg,#0077ff,#00d4ff);
color:white;
}

.policy-box{
max-width:800px;
margin:auto;
text-align:center;
line-height:2;
}

/* CONTACT */

.contact-card{
max-width:700px;
margin:auto;
padding:40px;
background:white;
border-radius:20px;
box-shadow:0 10px 25px rgba(0,0,0,.08);
text-align:center;
}

.contact-buttons{
margin-top:20px;
display:flex;
gap:15px;
justify-content:center;
flex-wrap:wrap;
}

.whatsapp{
background:#25D366;
}

.facebook{
background:#1877f2;
}

/* FOOTER */

footer{
background:var(--dark);
color:white;
padding:25px;
text-align:center;
}

/* FLOATING WHATSAPP */

.float{
position:fixed;
right:20px;
bottom:20px;
background:#25D366;
color:white;
width:60px;
height:60px;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
font-size:28px;
text-decoration:none;
box-shadow:0 10px 20px rgba(0,0,0,.2);
}

/* MOBILE */

@media(max-width:768px){

.about{
grid-template-columns:1fr;
}

.hero-content h1{
font-size:2.5rem;
}

nav ul{
display:none;
}

}

</style>
</head>
<body>

<header>
<nav>

<div class="logo">
<img src="F3876F75-3487-4E29-AED6-371773861C27.png" alt="">
<span>Reyes Hotspring</span>
</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#rates">Rates</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section class="hero">

<div class="hero-content">

<h1>Reyes Hotspring Private Pool</h1>

<p>
Your Private Tropical Escape in Pansol, Calamba Laguna
</p>

<a href="#rates" class="btn">
View Rates
</a>

</div>

</section>

<section id="about">

<div class="container">

<h2 class="section-title">
Welcome to Reyes Hotspring Private Pool
</h2>

<div class="about">

<div>
<p>
Enjoy a relaxing getaway with natural hotspring pools,
airconditioned rooms, videoke, WiFi and complete amenities
perfect for family gatherings, reunions and staycations.
</p>
</div>

<img src="Photoroom_20260612_230532.png">

</div>

</div>

</section>

<section id="gallery">

<div class="container">

<h2 class="section-title">
Gallery
</h2>

<div class="gallery-grid">

<img src="B6851927-AF54-42A9-9695-B6C8ECC4A5C1.png">
<img src="EFFD1B21-AB8C-4F92-AB3D-B7405D4554A2.png">
<img src="4C88AB56-F857-4DA4-8D00-6CE89556B0C5.png">
<img src="1C5A6D3D-30A5-4CD9-969B-BFD061B436F7.png">

</div>

</div>

</section>

<section>

<div class="container">

<h2 class="section-title">
Amenities
</h2>

<div class="cards">

<div class="card">
<h3>💦 Natural Hotspring Pool</h3>
</div>

<div class="card">
<h3>🛝Adult / Kiddie Pool</h3>
</div>

<div class="card">
<h3>🛏️ 2 Airconditioned Rooms</h3>
</div>

<div class="card">
<h3>📶 Free WiFi</h3>
</div>

<div class="card">
<h3>🎤 Videoke</h3>
</div>

<div class="card">
<h3>🚘 Parking Area</h3>
</div>

</div>

</div>

</section>

<section id="rates">

<div class="container">

<h2 class="section-title">
💰 Resort Rates
</h2>

<div class="rate-grid">

<div class="rate-card">
<h3>☀️ Day Tour</h3>
<ul>
<li>Weekday: ₱6,000</li>
<li>Weekend: ₱7,000</li>
</ul>
</div>

<div class="rate-card">
<h3>🌙 Night Tour</h3>
<ul>
<li>Weekday: ₱7,000</li>
<li>Weekend: ₱8,000</li>
</ul>
</div>

<div class="rate-card">
<h3>🏡 22 Hours Stay</h3>
<ul>
<li>Weekday: ₱10,000</li>
<li>Weekend: ₱12,000</li>
</ul>
</div>

</div>

</div>

</section>

<section class="policy">

<div class="container">

<h2 class="section-title" style="color:white;">
Reservation Policy
</h2>

<div class="policy-box">

<p>✅ 50% Reservation Fee Required</p>
<p>✅ No Downpayment = No Reservation</p>
<p>✅ First Come First Served</p>
<p>❌ Downpayment is Strictly Non-Refundable</p>

</div>

</div>

</section>

<section id="contact">

<div class="container">

<h2 class="section-title">
Contact Us
</h2>

<div class="contact-card">

<h3>📍 1-303 Kaimo
  St. Purok 1, Pansol, Calamba City, Laguna</h3>

<br>

<h2>0917-806-4028</h2>
<h2>0915-289-6007</h2>

<div class="contact-buttons">

<a href="https://wa.me/639178064028" class="btn whatsapp">
WhatsApp
</a>

<a href="https://www.facebook.com/ReyesHotspringPrivatePool" class="btn facebook">
Facebook
</a>

<a href="https://maps.app.goo.gl/f5ZqU8sMzpRiNgy3A?g_st=ic" class="btn">
Google Maps
</a>

</div>

</div>

</div>

</section>

<footer>
© 2025 Reyes Hotspring Private Pool | Pansol, Calamba Laguna
</footer>

<a href="https://wa.me/639178064028" class="float">
💬
</a>

</body>
</html>
