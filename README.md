<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SwishZone</title>

<style>

:root{
--dark:#3d0000;
--accent:#F97316;
--light:#F8FAFC;
--card:#FFFFFF;
--gray:#3d0000;
}

    *{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, Helvetica, sans-serif;
    }

    body{
    background:var(--light);
    }

    /* HEADER */

    header{
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 60px;
    background:var(--dark);
    color:white;
    position:sticky;
    top:0;
    z-index:1000;
    }

    /* LOGO */

    .logo{
    display:flex;
    align-items:center;
    gap:10px;
    font-size:24px;
    font-weight:bold;
    color:var(--accent);
    }

    .logo img{
    height:80px;
    }

    /* MENU */

    .menu{
    display:flex;
    gap:35px;
    }

    .menu a{
    text-decoration:none;
    color:white;
    font-weight:500;
    transition:0.4s;
    }

    .menu a:hover{
    color:var(--accent);
    }

    /* FRONT PAGE */

    .front-page{
    height:70vh;
    display:flex;
    justify-content:center;
    align-items:center;
    flex-direction:column;
    background:linear-gradient(120deg,#630000,#3d0000);
    color:white;
    text-align:center;
    padding:20px;
    }

    .front-page h1{
    font-size:48px;
    margin-bottom:10px;
    }

    .front-page p{
    max-width:600px;
    margin-bottom:25px;
    }

    .front-page button{
    padding:12px 28px;
    border:none;
    background:var(--accent);
    color:white;
    border-radius:8px;
    cursor:pointer;
    font-size:16px;
    }
    /* ABOUT */

    .about{
    padding:60px;
    text-align:center;
    background:#ffffff;
    }

    .about h2{
    font-size:32px;
    margin-bottom:15px;
    color:var(--gray);
    }

    .about p{
    max-width:700px;
    margin:auto;
    font-size:16px;
    line-height:1.6;
    }

    /* TRAINING */

    .training{
    padding:60px;
    background:#EEF2FF;
    text-align:center;
    }

    .training h2{
    font-size:32px;
    margin-bottom:10px;
    color:var(--gray);
    }

    .training p{
    max-width:700px;
    margin:auto;
    }

    /* FOOTER */

    footer{
    background:var(--dark);
    color:white;
    text-align:center;
    padding:20px;
    }

    </style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">
<img src="swishzone.jpg.png" alt="logo">
<span>SwishZone</span>
</div>

<div class="menu">
<a href="#home">Home</a>
<a href="#products">Products</a>
<a href="#training">Training</a>
<a href="#about">About</a>
</div>

</header>

<!-- HOME -->

<section class="front-page" id="home">

<h1>Welcome to SwishZone 🏀</h1>

<p>A place where you can find the best basketball gear and training resources. 
    We provide the best gear, from high-performance shoes and jerseys to 
    essential training equipment. We offer professional training programs designed to enhance your skills, 
    build confidence, and elevate your game on the court. Our mission is to
     support every player’s journey.</p>

</section>

<!-- PRODUCTS -->

<section class="products-section" id="products">

<h2>Shoes</h2>

<div class="products">

<div class="card">
<img src="underarmour.jpg.jpg">
<h3>Curry 12</h3>
<p class="price">$273</p>
<button>Buy</button>
</div>

<div class="card">
<img src="Curry9.jpg.jpg">
<h3>Curry 9</h3>
<p class="price">$196</p>
<button>Buy</button>
</div>

<div class="card">
<img src="Lebron20.jpg.jpg">
<h3>LeBron 20</h3>
<p class="price">$253</p>
<button>Buy</button>
</div>

<div class="card">
<img src="AE.JPG.jpg">
<h3>AE1</h3>
<p class="price">$147</p>
<button>Buy</button>
</div>

</div>

<h2>Jerseys</h2>

<div class="products">

<div class="card">
<img src="curry30.jpg.jpg">
<h3>Curry30 Jersey</h3>
<p class="price">$110</p>
<button>Buy</button>
</div>

<div class="card">
<img src="james.jpg.jpg">
<h3>Lebron23 Jersey</h3>
<p class="price">$115</p>
<button>Buy</button>
</div>

<div class="card">
<img src="wemby.jpg.jpg">
<h3>Wembanyama1 Jersey</h3>
<p class="price">$105</p>
<button>Buy</button>
</div>

<div class="card">
<img src="kd.jpg.jpg">
<h3>Kd35 Jersey</h3>
<p class="price">$108</p>
<button>Buy</button>
</div>

</div>

<h2>Bands</h2>

<div class="products">

<div class="card">
<img src="headband.jpg.jpg">
<h3>Head Band</h3>
<p class="price">$20</p>
<button>Buy</button>
</div>

<div class="card">
<img src="sleeve.jpg.jpg">
<h3>Arm Sleeve</h3>
<p class="price">$28</p>
<button>Buy</button>
</div>

<div class="card">
<img src="wristband.jpg.jpg">
<h3>Wrist Band</h3>
<p class="price">$15</p>
<button>Buy</button>
</div>

<div class="card">
<img src="kneepad.jpg.jpg">
<h3>Knee pads</h3>
<p class="price">$22</p>
<button>Buy</button>
</div>

</div>

<h2>Basketball Ball</h2>

<div class="products">

<div class="card">
<img src="molten.jpg.jpg">
<h3>Molten</h3>
<p class="price">$43</p>
<button>Buy</button>
</div>

<div class="card">
<img src="wilson.jpg.jpg">
<h3>Wilson</h3>
<p class="price">$65</p>
<button>Buy</button>
</div>

<div class="card">
<img src="spalding.jpg.jpg">
<h3>Spalding</h3>
<p class="price">$51</p>
<button>Buy</button>
</div>

<div class="card">
<img src="elite.jpg.jpg">
<h3>Elite</h3>
<p class="price">$36</p>
<button>Buy</button>
</div>

</div>

</section>

<!-- TRAINING -->

<section class="training" id="training">

<h2>Basketball Training</h2>

<p>
Improve your shooting, ball handling, defense, and basketball IQ
with our professional basketball training sessions designed for
players of all skill levels.
</p>

</section>

<!-- ABOUT -->

<section class="about" id="about">

<h2>About SwishZone</h2>

<p>
SwishZone was created for basketball players who want the best gear
and elite training. Our mission is to help athletes improve their
skills while providing high-quality basketball shoes, jerseys,
bands, and equipment to dominate the court.
</p>

</section>

<footer>

<p>© 2026 SwishZone</p>

</footer>

</body>
</html>
