<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Estate Fashion | Luxury Clothing Brand</title>

<meta name="description"
content="Estate Fashion - Timeless Luxury Clothing crafted with elegance, sophistication and modern minimalism.">

<meta name="keywords"
content="Estate Fashion, Luxury Clothing, Fashion Brand, Premium Fashion">

<meta name="author"
content="Estate Fashion">

<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>

<link href="https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Inter:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>

/* ==============================
RESET
============================== */

*{
margin:0;
padding:0;
box-sizing:border-box;
scroll-behavior:smooth;
}

html{
scroll-behavior:smooth;
}

body{

font-family:'Inter',sans-serif;
background:#111;
color:white;
overflow-x:hidden;

}

/* ==============================
LOADER
============================== */

#loader{

position:fixed;
inset:0;
background:#000;
display:flex;
justify-content:center;
align-items:center;
z-index:99999;

}

.loader-circle{

width:70px;
height:70px;
border-radius:50%;
border:4px solid rgba(255,255,255,.2);
border-top:4px solid #fff;
animation:spin 1s linear infinite;

}

@keyframes spin{

100%{
transform:rotate(360deg);
}

}

/* ==============================
NAVBAR
============================== */

header{

position:fixed;
top:0;
left:0;
width:100%;
z-index:999;

backdrop-filter:blur(12px);

background:rgba(0,0,0,.35);

transition:.4s;

}

nav{

max-width:1300px;
margin:auto;

display:flex;
justify-content:space-between;
align-items:center;

padding:22px 30px;

}

.logo{

font-family:'Cormorant Garamond',serif;

font-size:34px;

letter-spacing:5px;

font-weight:700;

color:#fff;

}

.logo span{

color:#d4c3a3;

}

.nav-links{

display:flex;
gap:35px;
list-style:none;

}

.nav-links a{

text-decoration:none;
color:white;
font-size:14px;
letter-spacing:2px;
text-transform:uppercase;

transition:.3s;

position:relative;

}

.nav-links a::after{

content:'';

position:absolute;

left:0;
bottom:-7px;

height:2px;
width:0%;

background:#d8c29d;

transition:.3s;

}

.nav-links a:hover{

color:#d8c29d;

}

.nav-links a:hover::after{

width:100%;

}

.menu{

display:none;
font-size:32px;
cursor:pointer;

}

/* ==============================
HERO
============================== */

.hero{

height:100vh;

background:
linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.55)),

url("https://images.unsplash.com/photo-1529139574466-a303027c1d8b?auto=format&fit=crop&w=1600&q=80");

background-size:cover;
background-position:center;

display:flex;
justify-content:center;
align-items:center;

text-align:center;

padding:20px;

}

.hero-content{

max-width:850px;

animation:fadeUp 1.2s ease;

}

.hero small{

letter-spacing:8px;

color:#d8c29d;

font-size:14px;

}

.hero h1{

font-family:'Cormorant Garamond',serif;

font-size:90px;

line-height:1.05;

margin:20px 0;

font-weight:700;

}

.hero p{

font-size:18px;

line-height:1.8;

color:#ddd;

margin-bottom:40px;

}

.hero-buttons{

display:flex;

justify-content:center;

gap:20px;

flex-wrap:wrap;

}

.btn{

padding:16px 38px;

text-decoration:none;

font-size:14px;

letter-spacing:2px;

text-transform:uppercase;

transition:.35s;

cursor:pointer;

}

.btn-light{

background:#fff;

color:#111;

}

.btn-light:hover{

background:#d4c3a3;

transform:translateY(-5px);

}

.btn-outline{

border:1px solid #fff;

color:white;

}

.btn-outline:hover{

background:white;

color:#111;

}

/* ==============================
ABOUT
============================== */

section{

padding:110px 8%;

}

.about{

background:#f7f2eb;

color:#222;

}

.section-title{

font-family:'Cormorant Garamond',serif;

font-size:55px;

text-align:center;

margin-bottom:25px;

}

.section-sub{

max-width:850px;

margin:auto;

text-align:center;

line-height:2;

font-size:17px;

color:#555;

}

/* ==============================
FEATURED COLLECTION
============================== */

.collection{

background:#111;

}

.grid{

display:grid;

grid-template-columns:repeat(auto-fit,minmax(280px,1fr));

gap:35px;

margin-top:70px;

}

.card{

background:#1a1a1a;

overflow:hidden;

transition:.4s;

border-radius:8px;

}

.card:hover{

transform:translateY(-10px);

}

.card img{

width:100%;

height:420px;

object-fit:cover;

transition:.5s;

}

.card:hover img{

transform:scale(1.07);

}

.card-content{

padding:28px;

}

.card-content h3{

font-family:'Cormorant Garamond',serif;

font-size:30px;

margin-bottom:10px;

}

.card-content p{

color:#bbb;

line-height:1.8;

margin-bottom:20px;

}

.price{

font-size:20px;

color:#d4c3a3;

}

/* ==============================
ANIMATIONS
============================== */

.fade{

opacity:0;
transform:translateY(60px);
transition:1s;
}

.fade.show{

opacity:1;
transform:translateY(0);

}

@keyframes fadeUp{

from{

opacity:0;
transform:translateY(60px);

}

to{

opacity:1;
transform:translateY(0);

}

}

/* ==============================
RESPONSIVE
============================== */

@media(max-width:900px){

.hero h1{

font-size:60px;

}

.nav-links{

display:none;

}

.menu{

display:block;

}

}

@media(max-width:650px){

.hero h1{

font-size:45px;

}

.hero p{

font-size:16px;

}

.section-title{

font-size:42px;

}

}

</style>

</head>

<body>

<!-- ==========================
LOADER
========================== -->

<div id="loader">
<div class="loader-circle"></div>
</div>

<!-- ==========================
NAVBAR
========================== -->

<header>

<nav>

<div class="logo">
Estate <span>Fashion</span>
</div>

<ul class="nav-links">

<li><a href="#home">Home</a></li>

<li><a href="#about">About</a></li>

<li><a href="#collection">Collection</a></li>

<li><a href="#contact">Contact</a></li>

</ul>

<div class="menu">
☰
</div>

</nav>

</header>

<!-- ==========================
HERO
========================== -->

<section class="hero" id="home">

<div class="hero-content">

<small>ESTATE FASHION</small>

<h1>
Luxury Crafted For Modern Icons
</h1>

<p>

Where timeless tailoring meets contemporary elegance.
Every collection is designed with exceptional craftsmanship,
premium fabrics, and understated luxury.

</p>

<div class="hero-buttons">

<a href="#collection" class="btn btn-light">
Explore Collection
</a>

<a href="#about" class="btn btn-outline">
Discover More
</a>

</div>

</div>

</section>

<!-- ==========================
ABOUT
========================== -->

<section class="about fade" id="about">

<h2 class="section-title">

About Estate Fashion

</h2>

<p class="section-sub">

Estate Fashion is built upon the philosophy that luxury should
feel effortless. Our collections blend timeless silhouettes,
premium materials, and exceptional craftsmanship into garments
that transcend seasonal trends. Every piece is designed to
express confidence, sophistication, and individuality.

</p>

</section>

<!-- ==========================
FEATURED COLLECTION
========================== -->

<section class="collection fade" id="collection">

<h2 class="section-title">

Featured Collection

</h2>

<div class="grid">

<div class="card">

<img src="https://images.unsplash.com/photo-1496747611176-843222e1e57c?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Luxury Coat</h3>

<p>
Tailored perfection crafted from premium fabrics.
</p>

<div class="price">$320</div>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1515886657613-9f3515b0c78f?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Minimal Suit</h3>

<p>
Modern elegance with timeless sophistication.
</p>

<div class="price">$290</div>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1524504388940-b1c1722653e1?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Premium Jacket</h3>

<p>
Designed for effortless luxury every day.
</p>

<div class="price">$250</div>

</div>

</div>

</div>

</section>

<script>

// Part 1 JavaScript (loader and reveal)
// Remaining functionality will be added in Part 2 & Part 3.

window.addEventListener("load",()=>{

document.getElementById("loader").style.display="none";

});

const observer=new IntersectionObserver(entries=>{

entries.forEach(entry=>{

if(entry.isIntersecting){

entry.target.classList.add("show");

}

});

});

document.querySelectorAll(".fade").forEach(el=>observer.observe(el));

</script>

</body>
</html>
