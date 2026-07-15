<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>HELVETIA Coin</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Poppins,sans-serif;
scroll-behavior:smooth;
}

body{
background:#07110d;
color:white;
overflow-x:hidden;
}

header{
position:fixed;
width:100%;
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:rgba(0,0,0,.5);
backdrop-filter:blur(15px);
z-index:1000;
}

.logo{
font-size:30px;
font-weight:700;
color:#00ff88;
letter-spacing:2px;
}

nav a{
color:white;
text-decoration:none;
margin-left:30px;
transition:.3s;
}

nav a:hover{
color:#00ff88;
}

.hero{
height:100vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
background:
radial-gradient(circle at top,#0b4d2a,#07110d 70%);
padding:30px;
}

.hero h1{
font-size:75px;
color:#00ff88;
text-shadow:0 0 20px #00ff88;
}

.hero p{
max-width:750px;
margin:25px auto;
line-height:1.8;
font-size:18px;
color:#ddd;
}

.button{
display:inline-block;
padding:15px 40px;
background:#00ff88;
color:#000;
text-decoration:none;
border-radius:50px;
font-weight:bold;
transition:.4s;
}

.button:hover{
transform:scale(1.05);
box-shadow:0 0 25px #00ff88;
}

section{
padding:100px 8%;
}

.title{
text-align:center;
font-size:40px;
margin-bottom:60px;
color:#00ff88;
}

.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.card{
background:#0f1d17;
padding:30px;
border-radius:20px;
border:1px solid rgba(0,255,136,.3);
transition:.3s;
}

.card:hover{
transform:translateY(-8px);
box-shadow:0 0 20px rgba(0,255,136,.3);
}

.card h3{
margin-bottom:15px;
color:#00ff88;
}

.tokenomics{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(180px,1fr));
gap:20px;
}

.token{
background:#0f1d17;
padding:25px;
border-radius:15px;
text-align:center;
border:1px solid #00ff88;
}

.timeline{
display:grid;
gap:20px;
}

.phase{
padding:25px;
background:#0f1d17;
border-left:5px solid #00ff88;
border-radius:10px;
}

.community{
text-align:center;
}

.community a{
display:inline-block;
margin:10px;
padding:15px 25px;
background:#00ff88;
color:#000;
text-decoration:none;
border-radius:50px;
font-weight:bold;
}

footer{
background:#000;
padding:40px;
text-align:center;
color:#888;
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
<a href="#community">Community</a>
</nav>

</header>

<section class="hero">

<h1>HELVETIA COIN</h1>

<p>
Building the Future of Digital Finance through Blockchain Technology.
Secure, Fast, Transparent, and Powered by Community.
</p>

<a href="#" class="button">Join Community</a>

</section>

<section id="about">

<h2 class="title">About Helvetia</h2>

<p style="text-align:center;max-width:900px;margin:auto;line-height:2;">
Helvetia Coin adalah aset digital berbasis blockchain yang dirancang
untuk memberikan transaksi cepat, biaya rendah, dan ekosistem yang
terdesentralisasi. Proyek ini berfokus pada inovasi Web3,
komunitas global, dan utilitas nyata dalam dunia digital.
</p>

</section>

<section id="features">

<h2 class="title">Why Choose Helvetia?</h2>

<div class="grid">

<div class="card">
<h3>⚡ Lightning Fast</h3>
<p>Transaksi selesai hanya dalam hitungan detik.</p>
</div>

<div class="card">
<h3>🔒 Secure</h3>
<p>Didukung teknologi blockchain yang aman dan transparan.</p>
</div>

<div class="card">
<h3>🌍 Global</h3>
<p>Dapat digunakan oleh siapa saja di seluruh dunia.</p>
</div>

<div class="card">
<h3>💎 Community Driven</h3>
<p>Dibangun bersama komunitas dan berkembang secara terbuka.</p>
</div>

</div>

</section>

<section id="tokenomics">

<h2 class="title">Tokenomics</h2>

<div class="tokenomics">

<div class="token">
<h3>Total Supply</h3>
<h2>1B HLV</h2>
</div>

<div class="token">
<h3>Liquidity</h3>
<h2>40%</h2>
</div>

<div class="token">
<h3>Staking</h3>
<h2>20%</h2>
</div>

<div class="token">
<h3>Development</h3>
<h2>15%</h2>
</div>

<div class="token">
<h3>Marketing</h3>
<h2>15%</h2>
</div>

<div class="token">
<h3>Community</h3>
<h2>10%</h2>
</div>

</div>

</section>

<section id="roadmap">

<h2 class="title">Roadmap</h2>

<div class="timeline">

<div class="phase">
<h3>Phase 1</h3>
<p>Website Launch, Whitepaper, Community Building</p>
</div>

<div class="phase">
<h3>Phase 2</h3>
<p>DEX Listing & Marketing Campaign</p>
</div>

<div class="phase">
<h3>Phase 3</h3>
<p>Staking Platform & NFT Integration</p>
</div>

<div class="phase">
<h3>Phase 4</h3>
<p>Global Partnership & CEX Listing</p>
</div>

</div>

</section>

<section id="community">

<h2 class="title">Join Our Community</h2>

<div class="community">

<a href="#">Telegram</a>
<a href="#">Discord</a>
<a href="#">X (Twitter)</a>

</div>

</section>

<footer>

<h3>HELVETIA COIN</h3>

<p>© 2026 Helvetia Coin. All Rights Reserved.</p>

</footer>

</body>
</html>
