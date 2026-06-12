<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Reyes Hotspring Private Pool</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: 'Segoe UI', sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#f8f9fa;
    color:#333;
}

/* Navigation */
header{
    position:fixed;
    width:100%;
    top:0;
    z-index:1000;
    background:rgba(0,0,0,0.8);
    backdrop-filter:blur(10px);
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:15px 8%;
}

.logo{
    color:#fff;
    font-size:1.4rem;
    font-weight:bold;
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
    color:white;
    transition:.3s;
}

nav ul li a:hover{
    color:#ffd166;
}

/* Hero */
.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,.5), rgba(0,0,0,.5)),
    url('https://images.unsplash.com/photo-1571896349842-33c89424de2d?auto=format&fit=crop&w=1600&q=80');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
}

.hero-content h1{
    font-size:3.5rem;
    margin-bottom:15px;
}

.hero-content p{
    font-size:1.2rem;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    padding:14px 30px;
    background:#ff8c42;
    color:white;
    text-decoration:none;
    border-radius:50px;
    transition:.3s;
}

.btn:hover{
    background:#ff6f00;
}

/* Sections */
section{
    padding:80px 10%;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
}

.section-title h2{
    color:#006d77;
    font-size:2rem;
}

/* About */
.about{
    text-align:center;
    line-height:1.8;
}

/* Amenities */
.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.card{
    background:white;
    padding:25px;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,.1);
    text-align:center;
    transition:.3s;
}

.card:hover{
    transform:translateY(-5px);
}

/* Gallery */
.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:15px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:15px;
}

/* Reservation */
.reservation{
    background:#006d77;
    color:white;
    text-align:center;
    border-radius:20px;
    margin:0 10%;
}

.reservation h2{
    margin-bottom:15px;
}

.contact-btn{
    margin-top:20px;
    background:#25D366;
    color:white;
    border:none;
    padding:15px 30px;
    border-radius:50px;
    cursor:pointer;
    font-size:16px;
}

/* Footer */
footer{
    background:#111;
    color:white;
    text-align:center;
    padding:25px;
    margin-top:50px;
}

/* Responsive */
@media(max-width:768px){

.hero-content h1{
    font-size:2.2rem;
}

nav{
    flex-direction:column;
}

nav ul{
    margin-top:10px;
    flex-wrap:wrap;
    justify-content:center;
}
}
</style>
</head>
<body>

<header>
<nav>
<div class="logo">🏖️ Reyes Hotspring Private Pool</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#amenities">Amenities</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#reserve">Reserve</a></li>
</ul>
</nav>
</header>

<section class="hero" id="home">
<div class="hero-content">
<h1>Reyes Hotspring Private Pool</h1>
<p>Your Private Hot Spring Escape in Pansol, Calamba City, Laguna</p>
<a href="#reserve" class="btn">Book Your Stay</a>
</div>
</section>

<section id="about">
<div class="section-title">
<h2>About Our Resort</h2>
</div>

<div class="about">
<p>
Relax and unwind at Reyes Hotspring Private Pool, located in the heart of
Pansol, Calamba City, Laguna. Enjoy natural hot spring pools, comfortable
air-conditioned rooms, and exclusive amenities perfect for family gatherings,
birthdays, reunions, and weekend getaways.
</p>
</div>
</section>

<section id="amenities">
<div class="section-title">
<h2>Resort Amenities</h2>
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
<h3>🛌 Air-Conditioned Rooms</h3>
<p>2 Rooms with Private Bathrooms</p>
</div>

<div class="card">
<h3>🛜 Free WiFi</h3>
<p>Fast Internet Access</p>
</div>

<div class="card">
<h3>🎤 Videoke</h3>
<p>Sing and Enjoy with Friends</p>
</div>

<div class="card">
<h3>🚘 Parking</h3>
<p>3–4 Inside Parking Slots</p>
</div>

<div class="card">
<h3>♨️ BBQ Area</h3>
<p>Perfect for Outdoor Dining</p>
</div>

<div class="card">
<h3>📹 CCTV Security</h3>
<p>Safe & Secure Stay</p>
</div>

</div>
</section>

<section id="gallery">
<div class="section-title">
<h2>Gallery</h2>
</div>

<div class="gallery">
<img src="https://images.unsplash.com/photo-1566073771259-6a8506099945" alt="">
<img src="https://images.unsplash.com/photo-1540541338287-41700207dee6" alt="">
<img src="https://images.unsplash.com/photo-1578683010236-d716f9a3f461" alt="">
<img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b" alt="">
</div>
</section>

<section id="reserve">
<div class="reservation">

<h2>Reservation Policy</h2>

<p>✅ 50% Reservation Fee Required</p>
<p>✅ No Down Payment = No Reservation</p>
<p>✅ First Come, First Served</p>
<p>❌ Reservation Fee is Non-Refundable</p>

<br>

<p><strong>Sleeping Capacity:</strong> 15–20 Guests</p>

<br>

<p>
📱 WhatsApp/Viber:<br>
0917-806-4028<br>
0915-289-6007
</p>

<button class="contact-btn" onclick="reserveNow()">
Reserve Now
</button>

</div>
</section>

<footer>
<p>© 2026 Reyes Hotspring Private Pool | Pansol, Calamba City, Laguna</p>
</footer>

<script>
function reserveNow() {
    alert(
        "Thank you for your interest in Reyes Hotspring Private Pool!\\n\\n" +
        "For reservations, contact:\\n\\n" +
        "0917-806-4028\\n" +
        "0915-289-6007\\n\\n" +
        "50% Reservation Fee Required."
    );
}
</script>

</body>
</html>
