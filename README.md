maumasi-hut/
│── index.html
│── style.css
│── script.js
└── maumasihut.png  
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Maumasi Hut</title>

<link rel="stylesheet" href="style.css">
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

</head>

<body>

<header>

<img src="logo.jpg" class="logo">

<h1>Maumasi Hut</h1>

<p>Island Style • Family Owned • Authentic Polynesian Flavor</p>

<a href="tel:18018348735" class="button">
Call Now
</a>

</header>

<section>

<h2>About Us</h2>

<p>
Welcome to Maumasi Hut!
We bring authentic island flavors, fresh ingredients,
and warm Polynesian hospitality.
</p>

</section>

<section>

<h2>Menu</h2>

<div class="cards">

<div class="card">
<h3>Plate Lunches</h3>
<p>Island favorites served fresh.</p>
</div>

<div class="card">
<h3>Family Meals</h3>
<p>Perfect for gatherings.</p>
</div>

<div class="card">
<h3>Catering</h3>
<p>Book us for your next event.</p>
</div>

</div>

</section>

<section>

<h2>Contact</h2>

<p>📞 (801) 834-8735</p>

<p>Email: your@email.com</p>

</section>

<footer>

© 2026 Maumasi Hut

</footer>

<script src="script.js"></script>
body{
margin:0;
font-family:Poppins,sans-serif;
background:#fff8f2;
color:#333;
}

header{
background:linear-gradient(135deg,#ff7b54,#ffb347);
padding:50px;
text-align:center;
color:white;
}

.logo{
width:220px;
border-radius:50%;
box-shadow:0 5px 20px rgba(0,0,0,.3);
}

h1{
font-size:52px;
margin:20px 0 5px;
}

.button{
display:inline-block;
margin-top:20px;
padding:15px 35px;
background:white;
color:#ff6b35;
text-decoration:none;
font-weight:bold;
border-radius:40px;
}

section{
padding:60px 10%;
text-align:center;
}

.cards{
display:flex;
flex-wrap:wrap;
justify-content:center;
gap:25px;
}

.card{
background:white;
padding:30px;
width:250px;
border-radius:20px;
box-shadow:0 5px 20px rgba(0,0,0,.1);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
}

footer{
background:#222;
color:white;
padding:25px;
text-align:center;
} 


</body>
</html> 
