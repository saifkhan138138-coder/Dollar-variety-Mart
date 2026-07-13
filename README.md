<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dollar Variety Mart</title>

<style>
body{
font-family:Arial,sans-serif;
margin:0;
background:#f2f2f2;
}

header{
background:#d60000;
color:white;
text-align:center;
padding:20px;
font-size:30px;
font-weight:bold;
}

.products{
display:grid;
grid-template-columns:repeat(2,1fr);
gap:15px;
padding:15px;
}

.card{
background:white;
border-radius:10px;
padding:10px;
text-align:center;
box-shadow:0 2px 6px rgba(0,0,0,.2);
}

.card img{
width:100%;
height:150px;
object-fit:cover;
border-radius:10px;
}

.price{
color:red;
font-size:22px;
font-weight:bold;
}

button{
background:green;
color:white;
border:none;
padding:12px;
border-radius:8px;
width:100%;
font-size:18px;
margin-top:10px;
}
</style>
</head>

<body>

<header>
Dollar Variety Mart<br>
Everything Rs.280
</header>

<div class="products">

<div class="card">
<img src="https://via.placeholder.com/250">
<h3>Kitchen Item</h3>
<p class="price">Rs.280</p>
<input type="checkbox"> Select
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h3>Toy</h3>
<p class="price">Rs.280</p>
<input type="checkbox"> Select
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h3>Cosmetics</h3>
<p class="price">Rs.280</p>
<input type="checkbox"> Select
</div>

<div class="card">
<img src="https://via.placeholder.com/250">
<h3>Plastic Item</h3>
<p class="price">Rs.280</p>
<input type="checkbox"> Select
</div>

</div>

<div style="padding:20px;">
<a href="https://wa.me/923016708194">
<button>Order on WhatsApp</button>
</a>
</div>

</body>
</html>
