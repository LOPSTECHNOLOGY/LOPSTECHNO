<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Helvetia Token</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#050505;
color:#fff;
}

/* Navbar */

header{
position:fixed;
top:0;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:rgba(0,0,0,.8);
backdrop-filter:blur(15px);
z-index:999;
}

.logo{
font-size:28px;
font-weight:bold;
color:#00ff99;
}

nav a{
text-decoration:none;
color:white;
margin-left:30px;
transition:.3s;
}

nav a:hover{
color:#00ff99;
}

/* Hero */

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
padding:0 20px;
background:linear-gradient(135deg,#000,#021b13);
}

.hero h1{
font-size:70px;
color:#00ff99;
text-shadow:0 0 20px #00ff99;
}

.hero p{
margin:20px auto;
max-width:700px;
font-size:20px;
color:#ddd;
}

.btn{
display:inline-block;
padding:15px 35px;
background:#00ff99;
color:#000;
font-weight:bold;
text-decoration:none;
border-radius:50px;
margin:10px;
transition:.3s;
}

.btn:hover{
transform:translateY(-5px);
box-shadow:0 0 25px #00ff99;
}

/* Section */

section{
padding:100px 10%;
}

.title{
font-size:40px;
text-align:center;
margin-bottom:60px;
color:#00ff99;
}

/* About */

.about{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
gap:40px;
align-items:center;
}

.about img{
width:100%;
}

.about-text p{
line-height:1.8;
color:#bbb;
}

/* Card */

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:#111;
padding:30px;
border-radius:20px;
text-align:center;
border:1px solid #00ff99;
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
box-shadow:0 0 25px #00ff99;
}

.card h3{
color:#00ff99;
margin-bottom:15px;
}

/* Tokenomics */

.tokenomics{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
gap:25px;
text-align:center;
}

.token-box{
background:#111;
padding:30px;
border-radius:20px;
}

.token-box h2{
color:#00ff99;
margin-bottom:10px;
}

/* Roadmap */

.timeline{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.step{
background:#111;
padding:25px;
border-left:5px solid #00ff99;
border-radius:10px;
}

.step h3{
color:#00ff99;
margin-bottom:10px;
}

/* Footer */

footer{
padding:30px;
text-align:center;
background:#000;
color:#777;
margin-top:80px;
}

/* Responsive */

@media(max-width:768px){

.hero h1{
font-size:45px;
}

nav{
display:none;
}

}

</style>

</head>
<body>

<header>

<div class="logo">HELVETIA</div>

<nav>
<a href="#about">About</a>
<a href="#features">Features</a>
<a href="#tokenomics">Tokenomics</a>
<a href="#roadmap">Roadmap</a>
</nav>

</header>

<section class="hero">

<div>

<h1>HELVETIA TOKEN</h1>

<p>
The Future of Decentralized Finance.
Helvetia Token hadir sebagai cryptocurrency modern
yang cepat, aman, transparan, dan siap mendukung
ekosistem Web3.
</p>

<a href="#" class="btn">Buy Token</a>

<a href="#" class="btn">Whitepaper</a>

</div>

</section>

<section id="about">

<h2 class="title">About Helvetia</h2>

<div class="about">

<div class="about-text">

<p>

Helvetia Token merupakan aset digital generasi baru
yang dirancang untuk menghadirkan transaksi blockchain
yang cepat, aman, dan efisien.

Dengan teknologi modern dan komunitas yang kuat,
Helvetia siap menjadi bagian dari masa depan
keuangan digital.

</p>

</div>

</div>

</section>

<section id="features">

<h2 class="title">Features</h2>

<div class="cards">

<div class="card">
<h3>⚡ Fast Transaction</h3>
<p>Konfirmasi transaksi dalam hitungan detik.</p>
</div>

<div class="card">
<h3>🔒 Secure</h3>
<p>Didukung teknologi blockchain yang aman.</p>
</div>

<div class="card">
<h3>🌎 Community</h3>
<p>Dibangun bersama komunitas global.</p>
</div>

<div class="card">
<h3>📈 Scalable</h3>
<p>Siap berkembang untuk jutaan pengguna.</p>
</div>

</div>

</section>

<section id="tokenomics">

<h2 class="title">Tokenomics</h2>

<div class="tokenomics">

<div class="token-box">
<h2>40%</h2>
Liquidity
</div>

<div class="token-box">
<h2>25%</h2>
Community
</div>

<div class="token-box">
<h2>15%</h2>
Development
</div>

<div class="token-box">
<h2>10%</h2>
Marketing
</div>

<div class="token-box">
<h2>10%</h2>
Reserve
</div>

</div>

</section>

<section id="roadmap">

<h2 class="title">Roadmap</h2>

<div class="timeline">

<div class="step">
<h3>Q1</h3>
<p>Website Launch</p>
<p>Community Opening</p>
</div>

<div class="step">
<h3>Q2</h3>
<p>Token Launch</p>
<p>DEX Listing</p>
</div>

<div class="step">
<h3>Q3</h3>
<p>Staking</p>
<p>NFT Marketplace</p>
</div>

<div class="step">
<h3>Q4</h3>
<p>CEX Listing</p>
<p>Global Partnership</p>
</div>

</div>

</section>

<footer>

© 2026 Helvetia Token — All Rights Reserved.

</footer>

</body>
</html>
