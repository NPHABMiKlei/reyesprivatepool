<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Reyes Hotspring Private Pool | Pansol Laguna</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

:root{
    --primary:#0077b6;
    --secondary:#00b4d8;
    --dark:#023047;
    --light:#ffffff;
    --accent:#fb8500;
    --gray:#f5f9fc;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:white;
    color:#333;
}

/* NAVIGATION */

header{
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
    background:rgba(255,255,255,.95);
    backdrop-filter:blur(10px);
    box-shadow:0 2px 15px rgba(0,0,0,.05);
}

nav{
    width:90%;
    max-width:1200px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 0;
}

.logo{
    display:flex;
    align-items:center;
    gap:10px;
}

.logo img{
    height:55px;
}

.logo h2{
    color:var(--dark);
    font-size:1.1rem;
}

nav ul{
    display:flex;
    list-style:none;
}

nav ul li{
    margin-left:25px;
}

nav ul li a{
    text-decoration:none;
    color:var(--dark);
    font-weight:500;
}

nav ul li a:hover{
    color:var(--primary);
}

/* HERO */

.hero{
    min-height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    padding:100px 20px;

    background:
    radial-gradient(circle at 20% 20%, rgba(0,180,216,.15), transparent 30%),
    radial-gradient(circle at 80% 70%, rgba(0,119,182,.12), transparent 30%),
    linear-gradient(135deg,#f8fbff,#dff4ff,#f5fcff);
}

.hero-content{
    max-width:800px;
}

.hero img{
    width:220px;
    margin-bottom:20px;
}

.hero h1{
    font-size:3.5rem;
    color:var(--dark);
    margin-bottom:10px;
}

.hero p{
    font-size:1.2rem;
    color:#555;
    margin-bottom:30px;
}

.btn{
    display:inline-block;
    padding:15px 30px;
    background:var(--primary);
    color:white;
    text-decoration:none;
    border-radius:50px;
    margin:10px;
    transition:.3s;
}

.btn:hover{
    background:var(--dark);
}

.btn-outline{
    background:white;
    color:var(--primary);
    border:2px solid var(--primary);
}

.btn-outline:hover{
    color:white;
}

/* SECTIONS */

section{
    padding:90px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    font-size:2.5rem;
    color:var(--dark);
}

.section-title p{
    color:#777;
}

/* ABOUT */

.about{
    max-width:900px;
    margin:auto;
    text-align:center;
    line-height:2;
}

/* AMENITIES */

.amenities{
    background:var(--gray);
}

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    border-radius:20px;
    padding:30px;
    text-align:center;
    box-shadow:0 10px 30px rgba(0,119,182,.08);
    transition:.3s;
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:var(--primary);
    margin-bottom:10px;
}

/* GALLERY */

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:280px;
    object-fit:cover;
    border-radius:20px;
}

/* POLICY */

.policy{
    background:var(--gray);
}

.policy-box{
    max-width:900px;
    margin:auto;
    background:white;
    padding:40px;
    border-radius:20px;
    box-shadow:0 10px 25px rgba(0,0,0,.05);
}

.policy-box ul{
    margin-top:20px;
    margin-left:20px;
}

.policy-box li{
    margin-bottom:12px;
}

/* CONTACT */

.contact{
    text-align:center;
}

.contact-box{
    max-width:700px;
    margin:auto;
}

.contact-number{
    font-size:1.2rem;
    margin:15px 0;
}

/* FOOTER */

footer{
    background:var(--dark);
    color:white;
    text-align:center;
    padding:25px;
}

/* MOBILE */

@media(max-width:768px){

.hero h1{
    font-size:2.2rem;
}

nav{
    flex-direction:column;
}

nav ul{
    flex-wrap:wrap;
    justify-content:center;
    margin-top:10px;
}

nav ul li{
    margin:8px;
}

.hero img{
    width:180px;
}
}

</style>
</head>
<body>

<header>
<nav>

<div class="logo">
<img src="IMG_6131.jpeg" alt="Reyes Hotspring Logo">
<h2>Reyes Hotspring Private Pool</h2>
</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#amenities">Amenities</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<section class="hero" id="home">

<div class="hero-content">

<img src="IMG_6131.jpeg" alt="Logo">

<h1>Reyes Hotspring Private Pool</h1>

<p>
Relax. Recharge. Reconnect.
<br>
Natural Hot Spring Resort in Pansol, Calamba City, Laguna.
</p>

<a href="#contact" class="btn">Reserve Now</a>
<a href="#gallery" class="btn btn-outline">View Gallery</a>

</div>

</section>

<section id="about">

<div class="section-title">
<h2>About Us</h2>
<p>Your private hot spring getaway.</p>
</div>

<div class="about">
Experience a relaxing stay with family and friends at Reyes Hotspring Private Pool.
Enjoy natural hot spring pools, comfortable accommodations, spacious facilities,
and exclusive privacy for birthdays, reunions, team buildings, and weekend vacations.
</div>

</section>

<section class="amenities" id="amenities">

<div class="section-title">
<h2>Resort Amenities</h2>
<p>Everything you need for a comfortable stay.</p>
</div>

<div class="cards">

<div class="card">
<h3>💦 Adult Pool</h3>
<p>Natural Hot Spring Pool</p>
</div>

<div class="card">
<h3>🛝 Kiddie Pool</h3>
<p>Natural Hot Spring Pool</p>
</div>

<div class="card">
<h3>🛌 Rooms</h3>
<p>2 Fully Airconditioned Rooms with Own Bathroom</p>
</div>

<div class="card">
<h3>🛏️ Capacity</h3>
<p>15–20 Guests</p>
</div>

<div class="card">
<h3>📶 Free WiFi</h3>
<p>Fast Internet Access</p>
</div>

<div class="card">
<h3>🎤 Videoke</h3>
<p>Enjoy Singing with Friends & Family</p>
</div>

<div class="card">
<h3>🚘 Parking</h3>
<p>3–4 Vehicle Parking Slots</p>
</div>

<div class="card">
<h3>♨️ BBQ Griller</h3>
<p>Perfect for Outdoor Dining</p>
</div>

</div>

</section>

<section id="gallery">

<div class="section-title">
<h2>Gallery</h2>
<p>Replace these photos with your actual resort pictures.</p>
</div>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1571896349842-33c89424de2d?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1540541338287-41700207dee6?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?auto=format&fit=crop&w=1000&q=80">

<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?auto=format&fit=crop&w=1000&q=80">

</div>

</section>

<section class="policy">

<div class="section-title">
<h2>Reservation Policy</h2>
</div>

<div class="policy-box">

<ul>
<li>✅ 50% Reservation Fee Required</li>
<li>✅ No Downpayment = No Reservation</li>
<li>✅ First Come, First Served Basis</li>
<li>❌ Reservation Fee is Strictly Non-Refundable</li>
</ul>

<br>

<h3>Please Bring Your Own:</h3>

<ul>
<li>✔ Kitchen Utensils</li>
<li>✔ Blankets</li>
<li>✔ Towels</li>
<li>✔ Toiletries</li>
</ul>

</div>

</section>

<section class="contact" id="contact">

<div class="section-title">
<h2>Contact Us</h2>
<p>Book your stay today.</p>
</div>

<div class="contact-box">

<div class="contact-number">
📱 WhatsApp/Viber: 0917-806-4028
</div>

<div class="contact-number">
📱 WhatsApp/Viber: 0915-289-6007
</div>

<a class="btn" href="#" onclick="bookNow()">Reserve Now</a>

</div>

</section>

<footer>
© 2026 Reyes Hotspring Private Pool • Pansol, Calamba City, Laguna
</footer>

<script>

function bookNow(){
alert(
"Thank you for your interest in Reyes Hotspring Private Pool!\n\n"+
"Contact us for reservations:\n\n"+
"0917-806-4028\n"+
"0915-289-6007\n\n"+
"50% Reservation Fee Required."
);
}

</script>

</body>
</html>
