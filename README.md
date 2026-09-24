<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Vince Hikes - Discover hiking, mountain adventures and scenic trails around Nanyuki, Kenya.">
<title>Vince Hikes | Nanyuki Adventures</title>

<style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:Arial, sans-serif;
}

body{
  background:#f5f1e8;
  color:#26351f;
  line-height:1.6;
}

header{
  background:#1f3b24;
  color:white;
  padding:18px 7%;
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

.hero{
  min-height:80vh;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
  padding:60px 20px;
  background:
    linear-gradient(rgba(20,45,25,.65),rgba(20,45,25,.65)),
    url("https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=1600&q=80");
  background-size:cover;
  background-position:center;
  color:white;
}

.hero-content{
  max-width:800px;
}

.hero h1{
  font-size:55px;
  margin-bottom:15px;
}

.hero p{
  font-size:19px;
  margin-bottom:28px;
}

.button{
  display:inline-block;
  background:#d59b45;
  color:white;
  padding:13px 25px;
  border-radius:30px;
  text-decoration:none;
  font-weight:bold;
  margin:5px;
}

.button:hover{
  background:#b87e2e;
}

section{
  padding:65px 7%;
}

.title{
  text-align:center;
  margin-bottom:35px;
}

.title h2{
  font-size:32px;
  color:#1f3b24;
}

.title p{
  color:#687263;
}

.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(240px,1fr));
  gap:22px;
}

.card{
  background:white;
  border-radius:15px;
  overflow:hidden;
  box-shadow:0 5px 18px rgba(0,0,0,.1);
}

.card img{
  width:100%;
  height:210px;
  object-fit:cover;
}

.card-content{
  padding:20px;
}

.card h3{
  margin-bottom:8px;
  color:#1f3b24;
}

.about{
  background:#e5dfd0;
}

.about-box{
  max-width:850px;
  margin:auto;
  text-align:center;
}

.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(200px,1fr));
  gap:12px;
}

.gallery img{
  width:100%;
  height:220px;
  object-fit:cover;
  border-radius:12px;
}

.contact{
  background:#1f3b24;
  color:white;
  text-align:center;
}

.contact h2{
  font-size:34px;
  margin-bottom:15px;
}

.contact p{
  margin-bottom:20px;
}

footer{
  background:#142719;
  color:#ccc;
  text-align:center;
  padding:22px;
  font-size:14px;
}

.whatsapp{
  position:fixed;
  right:20px;
  bottom:20px;
  background:#25D366;
  color:white;
  width:58px;
  height:58px;
  border-radius:50%;
  display:flex;
  align-items:center;
  justify-content:center;
  text-decoration:none;
  font-size:27px;
  box-shadow:0 4px 12px rgba(0,0,0,.25);
  z-index:2000;
}

@media(max-width:700px){
  header{
    flex-direction:column;
    gap:10px;
  }

  nav a{
    margin:0 6px;
  }

  .hero h1{
    font-size:40px;
  }

  .hero p{
    font-size:16px;
  }
}
</style>
</head>

<body>

<header>
  <div class="logo">🥾 Vince Hikes</div>

  <nav>
    <a href="#home">Home</a>
    <a href="#hikes">Hikes</a>
    <a href="#gallery">Gallery</a>
    <a href="#about">About</a>
    <a href="#contact">Contact</a>
  </nav>
</header>

<section class="hero" id="home">
  <div class="hero-content">
    <h1>Explore Nanyuki</h1>
    <p>
      Discover trails, mountain views and unforgettable outdoor
      adventures around Nanyuki, Kenya.
    </p>

    <a class="button" href="#hikes">Explore Hikes</a>
    <a class="button" href="https://wa.me/254737315105">WhatsApp Me</a>
  </div>
</section>

<section id="hikes">

  <div class="title">
    <h2>Adventure Awaits</h2>
    <p>Experience the wild side of Nanyuki.</p>
  </div>

  <div class="cards">

    <div class="card">
      <img src="https://images.unsplash.com/photo-1551632811-561732d1e306?auto=format&fit=crop&w=900&q=80">
      <div class="card-content">
        <h3>Hiking Adventures</h3>
        <p>
          Discover beautiful trails, peaceful landscapes and
          exciting outdoor experiences.
        </p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1464278533981-50106e6176b1?auto=format&fit=crop&w=900&q=80">
      <div class="card-content">
        <h3>Mountain Experiences</h3>
        <p>
          Chase breathtaking views and challenge yourself
          on Kenya's incredible mountain terrain.
        </p>
      </div>
    </div>

    <div class="card">
      <img src="https://images.unsplash.com/photo-1526481280695-3c687fd643ed?auto=format&fit=crop&w=900&q=80">
      <div class="card-content">
        <h3>Scenic Trails</h3>
        <p>
          Find hidden viewpoints, beautiful landscapes and
          memorable spots around Nanyuki.
        </p>
      </div>
    </div>

  </div>
</section>

<section class="about" id="about">

  <div class="about-box">
    <div class="title">
      <h2>About Vince Hikes</h2>
    </div>

    <p>
      Vince Hikes is about exploring the trails, landscapes and
      outdoor adventures around Nanyuki, Kenya. From scenic walks
      to challenging mountain experiences, the goal is simple:
      get outside, explore and enjoy the journey.
    </p>

    <br>

    <p>
      Looking for a hiking adventure, a scenic spot or outdoor
      experience? Get in touch and let's plan your next adventure.
    </p>
  </div>

</section>

<section id="gallery">

  <div class="title">
    <h2>Trail Gallery</h2>
    <p>Moments from the outdoors.</p>
  </div>

  <div class="gallery">

    <img src="https://images.unsplash.com/photo-1551632811-561732d1e306?auto=format&fit=crop&w=900&q=80">

    <img src="https://images.unsplash.com/photo-1464278533981-50106e6176b1?auto=format&fit=crop&w=900&q=80">

    <img src="https://images.unsplash.com/photo-1526481280695-3c687fd643ed?auto=format&fit=crop&w=900&q=80">

    <img src="https://images.unsplash.com/photo-1464822759023-fed622ff2c3b?auto=format&fit=crop&w=900&q=80">

  </div>

</section>

<section class="contact" id="contact">

  <h2>Ready for an Adventure?</h2>

  <p>
    For hiking, outdoor experiences, collaborations or advertising,
    get in touch.
  </p>

  <p><strong>📞 0737 315 105</strong></p>

  <a class="button" href="tel:+254737315105">
    Call Me
  </a>

  <a class="button" href="https://wa.me/254737315105">
    WhatsApp
  </a>

</section>

<footer>
  © 2026 Vince Hikes • Nanyuki, Kenya
</footer>

<a class="whatsapp" href="https://wa.me/254737315105" aria-label="WhatsApp">
  ☎
</a>

</body>
</html>
