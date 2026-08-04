<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Royal Feast Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#fafafa;
color:#333;
}

header{
position:fixed;
top:0;
left:0;
width:100%;
padding:18px 8%;
display:flex;
justify-content:space-between;
align-items:center;
background:#ffffffee;
backdrop-filter:blur(10px);
box-shadow:0 3px 12px rgba(0,0,0,.08);
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#e67e22;
}

nav a{
text-decoration:none;
margin-left:25px;
font-weight:500;
color:#333;
transition:.3s;
}

nav a:hover{
color:#e67e22;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:0 10%;
background:linear-gradient(rgba(0,0,0,.55),rgba(0,0,0,.55)),
url('https://images.unsplash.com/photo-1504674900247-0877df9cc836?auto=format&fit=crop&w=1400&q=80');
background-size:cover;
background-position:center;
color:white;
}

.hero h1{
font-size:60px;
margin-bottom:20px;
}

.hero p{
font-size:20px;
margin-bottom:30px;
}

.btn{
padding:14px 35px;
border:none;
border-radius:40px;
background:#e67e22;
color:white;
font-size:17px;
cursor:pointer;
transition:.3s;
text-decoration:none;
display:inline-block;
}

.btn:hover{
transform:translateY(-4px);
background:#cf711b;
}

section{
padding:90px 8%;
}

.title{
text-align:center;
font-size:38px;
margin-bottom:15px;
color:#222;
}

.subtitle{
text-align:center;
color:#777;
margin-bottom:50px;
}

.about{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:40px;
align-items:center;
}

.about img{
width:100%;
border-radius:20px;
}

.about h2{
margin-bottom:20px;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:18px;
overflow:hidden;
box-shadow:0 8px 25px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:220px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.price{
font-size:20px;
font-weight:bold;
color:#e67e22;
margin-top:10px;
}

.features{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
margin-top:50px;
}

.feature{
background:white;
padding:30px;
border-radius:18px;
text-align:center;
box-shadow:0 6px 20px rgba(0,0,0,.08);
}

.feature h3{
margin:15px 0;
}

.testimonials{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:25px;
}

.review{
background:white;
padding:25px;
border-radius:18px;
box-shadow:0 6px 20px rgba(0,0,0,.08);
}

.review h4{
margin-top:15px;
color:#e67e22;
}

.contact{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:40px;
}

form input,
form textarea{
width:100%;
padding:15px;
margin-bottom:15px;
border:1px solid #ddd;
border-radius:10px;
}

form textarea{
height:130px;
resize:none;
}

footer{
background:#111;
color:white;
text-align:center;
padding:25px;
margin-top:60px;
}

@media(max-width:768px){

.hero h1{
font-size:40px;
}

nav{
display:none;
}

}

</style>

</head>

<body>

<header>

<div class="logo">Royal Feast</div>

<nav>

<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#menu">Menu</a>
<a href="#features">Services</a>
<a href="#reviews">Reviews</a>
<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero" id="home">

<div>

<h1>Experience Fine Dining</h1>

<p>Delicious meals prepared with love by our world-class chefs.</p>

<a href="#menu" class="btn">Explore Menu</a>

</div>

</section>

<section id="about">

<h2 class="title">About Us</h2>

<p class="subtitle">
Serving delicious food with premium quality ingredients.
</p>

<div class="about">

<img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5?auto=format&fit=crop&w=900&q=80">

<div>

<h2>Welcome to Royal Feast</h2>

<p>

We provide an unforgettable dining experience with authentic recipes,
luxurious ambience and exceptional customer service.

<br><br>

Our chefs use only fresh ingredients to create memorable meals for every guest.

</p>

<br>

<a href="#contact" class="btn">Book Table</a>

</div>

</div>

</section>

<section id="menu">

<h2 class="title">Popular Dishes</h2>

<p class="subtitle">Customer favourites</p>

<div class="cards">

<div class="card">

<img src="https://images.unsplash.com/photo-1513104890138-7c749659a591?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Italian Pizza</h3>

<p>Crispy crust with fresh toppings.</p>

<div class="price">$14</div>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1565299624946-b28f40a0ae38?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Cheese Burger</h3>

<p>Juicy grilled burger with fries.</p>

<div class="price">$12</div>

</div>

</div>

<div class="card">

<img src="https://images.unsplash.com/photo-1544025162-d76694265947?auto=format&fit=crop&w=900&q=80">

<div class="card-content">

<h3>Grilled Steak</h3>

<p>Premium grilled steak served hot.</p>

<div class="price">$24</div>

</div>

</div>

</div>

</section>
