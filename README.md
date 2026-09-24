<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<meta name="description" content="Vince Hikes - Mountain trails, scenic viewpoints, nature walks, hiking adventures and outdoor experiences around Nanyuki, Kenya.">

<title>Vince Hikes | Explore Nanyuki</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
}

html{
  scroll-behavior:smooth;
}

body{
  font-family:Arial, sans-serif;
  background:#f4f0e5;
  color:#263728;
  line-height:1.6;
}

/* HEADER */

header{
  background:#173b24;
  color:white;
  padding:16px 7%;
  display:flex;
  justify-content:space-between;
  align-items:center;
  position:sticky;
  top:0;
  z-index:1000;
}

.logo{
  font-size:25px;
  font-weight:bold;
}

nav a{
  color:white;
  text-decoration:none;
  margin-left:18px;
  font-size:14px;
}

nav a:hover{
  color:#d9a84e;
}

/* HERO */

.hero{
  min-height:88vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:50px 20px;

  background:
  linear-gradient(rgba(12,38,20,.62),rgba(12,38,20,.62)),
  url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1800&q=85");

  background-size:cover;
  background-position:center;

  color:white;
}

.hero-content{
  max-width:850px;
}

.hero h1{
  font-size:60px;
  margin-bottom:10px;
}

.hero h2{
  font-size:24px;
  font-weight:normal;
  margin-bottom:15px;
  color:#e2bd72;
}

.hero p{
  font-size:18px;
  margin-bottom:28px;
}

.button{
  display:inline-block;
  background:#c99543;
  color:white;
  text-decoration:none;
  padding:13px 25px;
  border-radius:30px;
  font-weight:bold;
  margin:5px;
}

.button:hover{
  background:#a9772e;
}

/* SECTIONS */

section{
  padding:70px 7%;
}

.section-title{
  text-align:center;
  margin-bottom:40px;
}

.section-title h2{
  color:#173b24;
  font-size:34px;
  margin-bottom:8px;
}

.section-title p{
  color:#687266;
}

/* SERVICES */

.services{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
  gap:22px;
}

.service{
  background:white;
  padding:28px 22px;
  border-radius:16px;
  text-align:center;
  box-shadow:0 5px 18px rgba(0,0,0,.08);
  transition:.2s;
}

.service:hover{
  transform:translateY(-5px);
}

.icon{
  font-size:40px;
  margin-bottom:12px;
}

.service h3{
  color:#173b24;
  margin-bottom:8px;
}

/* ABOUT */

.about{
  background:#e3ddcc;
}

.about-box{
  max-width:850px;
  margin:auto;
  text-align:center;
}

/* GALLERY */

.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
  gap:15px;
}

.gallery img{
  width:100%;
  height:230px;
  object-fit:cover;
  border-radius:14px;
}

/* CTA */

.cta{
  background:#173b24;
  color:white;
  text-align:center;
}

.cta h2{
  font-size:35px;
  margin-bottom:12px;
}

.cta p{
  margin-bottom:20px;
}

/* FOOTER */

footer{
  background:#102719;
  color:#c8cec9;
  text-align:center;
  padding:24px;
  font-size:14px;
}

/* WHATSAPP */

.whatsapp{
  position:fixed;
  right:20px;
  bottom:20px;

  width:58px;
  height:58px;

  background:#25D366;
  color:white;

  border-radius:50%;

  display:flex;
  align-items:center;
  justify-content:center;

  text-decoration:none;
  font-size:27px;

  box-shadow:0 5px 15px rgba(0,0,0,.3);

  z-index:2000;
}

/* MOBILE */

@media(max-width:700px){

  header{
    flex-direction:column;
    gap:10px;
  }

  nav a{
    margin:0 6px;
    font-size:13px;
  }

  .hero h1{
    font-size:42px;
  }

  .hero h2{
    font-size:20px;
  }

  .hero p{
    font-size:16px;
  }
}
</style>
</head>


<body>

<!-- HEADER -->

<header>

  <div class="logo">
    🥾 Vince Hikes
  </div>

  <nav>
    <a href="#home">Home</a>
    <a href="#adventures">Adventures</a>
    <a href="#about">About</a>
    <a href="#gallery">Gallery</a>
    <a href="#contact">Contact</a>
  </nav>

</header>


<!-- HERO -->

<section class="hero" id="home">

  <div class="hero-content">

    <h1>VINCE HIKES</h1>

    <h2>Explore. Hike. Discover.</h2>

    <p>
      Discover mountain trails, scenic viewpoints,
      nature walks and unforgettable outdoor experiences
      around Nanyuki, Kenya.
    </p>

    <a class="button" href="#adventures">
      Explore Adventures
    </a>

    <a class="button" href="https://wa.me/254737315105">
      WhatsApp Me
    </a>

  </div>

</section>


<!-- ADVENTURES -->

<section id="adventures">

  <div class="section-title">

    <h2>Adventure Awaits</h2>

    <p>
      Find your trail and experience the outdoors.
    </p>

  </div>


  <div class="services">


    <div class="service">

      <div class="icon">🥾</div>

      <h3>Mountain Trails</h3>

      <p>
        Explore beautiful mountain routes,
        challenging climbs and rewarding landscapes.
      </p>

    </div>


    <div class="service">

      <div class="icon">🌄</div>

      <h3>Scenic Viewpoints</h3>

      <p>
        Discover breathtaking viewpoints and
        landscapes worth stopping for.
      </p>

    </div>


    <div class="service">

      <div class="icon">🌿</div>

      <h3>Nature Walks</h3>

      <p>
        Slow down, explore nature and enjoy
        peaceful outdoor walks.
      </p>

    </div>


    <div class="service">

      <div class="icon">⛰️</div>

      <h3>Hiking Adventures</h3>

      <p>
        From relaxed hikes to challenging trails,
        find an adventure that fits you.
      </p>

    </div>


    <div class="service">

      <div class="icon">📸</div>

      <h3>Scenic Photography</h3>

      <p>
        Find beautiful landscapes and viewpoints
        for unforgettable outdoor shots.
      </p>

    </div>


    <div class="service">

      <div class="icon">⛺</div>

      <h3>Camping & Outdoors</h3>

      <p>
        Experience the outdoors through camping,
        exploration and outdoor activities.
      </p>

    </div>


    <div class="service">

      <div class="icon">🐾</div>

      <h3>Nature & Wildlife Tracking</h3>

      <p>
        Explore natural environments and learn
        about wildlife signs and tracks.
      </p>

    </div>


    <div class="service">

      <div class="icon">🧭</div>

      <h3>Trail Exploration</h3>

      <p>
        Discover new routes, hidden spots and
        interesting places around Nanyuki.
      </p>

    </div>

  </div>

</section>


<!-- ABOUT -->

<section class="about" id="about">

  <div class="about-box">

    <div class="section-title">

      <h2>About Vince Hikes</h2>

    </div>

    <p>
      Vince Hikes is an outdoor adventure project based around
      Nanyuki, Kenya, focused on exploring trails, mountains,
      scenic viewpoints and natural landscapes.
    </p>

    <br>

    <p>
      Whether you're looking for a peaceful nature walk,
      a challenging trail, a scenic viewpoint or a new place
      to explore, the journey starts here.
    </p>

  </div>

</section>


<!-- GALLERY -->

<section id="gallery">

  <div class="section-title">

    <h2>Explore The Outdoors</h2>

    <p>
      Mountains, trails and beautiful landscapes.
    </p>

  </div>


  <div class="gallery">

    <img src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1000&q=85">

    <img src="https://images.unsplash.com/photo-1551632811-561732d1e306?auto=format&fit=crop&w=1000&q=85">

    <img src="https://images.unsplash.com/photo-1464278533981-50106e6176b1?auto=format&fit=crop&w=1000&q=85">

    <img src="https://images.unsplash.com/photo-1526481280695-3c687fd643ed?auto=format&fit=crop&w=1000&q=85">

  </div>

</section>


<!-- CONTACT -->

<section class="cta" id="contact">

  <h2>Plan Your Adventure</h2>

  <p>
    Want to explore a trail, discover a viewpoint
    or plan an outdoor experience?
  </p>

  <p>
    <strong>📞 0737 315 105</strong>
  </p>

  <a class="button" href="tel:+254737315105">
    Call Me
  </a>

  <a class="button" href="https://wa.me/254737315105">
    WhatsApp
  </a>

</section>


<!-- FOOTER -->

<footer>

  © 2026 Vince Hikes • Nanyuki, Kenya

</footer>


<!-- FLOATING WHATSAPP -->

<a
  class="whatsapp"
  href="https://wa.me/254737315105"
  aria-label="WhatsApp Vince Hikes">

  ☎

</a>

</body>
</html>
