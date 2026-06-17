#<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Vamvi | Creating Experiences. Elevating Brands.</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: Arial, sans-serif;
      scroll-behavior: smooth;
    }

    body {
      color: #222;
      line-height: 1.6;
    }

    /* NAV */
    header {
      position: fixed;
      width: 100%;
      background: #0f172a;
      color: white;
      padding: 15px 40px;
      display: flex;
      justify-content: space-between;
      align-items: center;
      z-index: 1000;
    }

    header h1 {
      font-size: 20px;
      letter-spacing: 2px;
    }

    nav a {
      color: white;
      margin-left: 20px;
      text-decoration: none;
      font-size: 14px;
    }

    nav a:hover {
      color: #38bdf8;
    }

    /* HERO */
    .hero {
      height: 100vh;
      background: linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
                  url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d') center/cover;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      color: white;
      text-align: center;
      padding: 0 20px;
    }

    .hero h2 {
      font-size: 40px;
      margin-bottom: 10px;
    }

    .hero p {
      font-size: 18px;
      max-width: 600px;
    }

    .btn {
      margin-top: 20px;
      padding: 12px 25px;
      background: #38bdf8;
      color: black;
      border: none;
      cursor: pointer;
      text-decoration: none;
      font-weight: bold;
      border-radius: 5px;
    }

    section {
      padding: 80px 20px;
      max-width: 1100px;
      margin: auto;
    }

    h2.section-title {
      text-align: center;
      margin-bottom: 40px;
      font-size: 30px;
    }

    /* SERVICES */
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 20px;
    }

    .card {
      padding: 20px;
      background: #f1f5f9;
      border-radius: 10px;
      text-align: center;
    }

    /* EVENTS */
    .event {
      background: #0f172a;
      color: white;
      padding: 20px;
      border-radius: 10px;
      text-align: center;
    }

    /* GALLERY */
    .gallery {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 10px;
    }

    .gallery img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      border-radius: 10px;
    }

    /* CONTACT */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
      max-width: 500px;
      margin: auto;
    }

    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }

    button {
      padding: 12px;
      background: #0f172a;
      color: white;
      border: none;
      cursor: pointer;
    }

    footer {
      text-align: center;
      padding: 20px;
      background: #0f172a;
      color: white;
    }
  </style>
</head>

<body>

  <!-- HEADER -->
  <header>
    <h1>VAMVI</h1>
    <nav>
      <a href="#about">About</a>
      <a href="#services">Services</a>
      <a href="#events">Events</a>
      <a href="#gallery">Gallery</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <!-- HERO -->
  <section class="hero">
    <h2>Creating Experiences. Elevating Brands.</h2>
    <p>We design unforgettable events, excursions, and marketing activations that bring people together.</p>
    <a class="btn" href="#contact">Book an Experience</a>
  </section>

  <!-- ABOUT -->
  <section id="about">
    <h2 class="section-title">About Us</h2>
    <p style="text-align:center; max-width:800px; margin:auto;">
      Vamvi is a creative events and experiences agency focused on corporate events,
      team building, excursions, and brand activations. We turn ideas into memorable experiences
      that connect people and elevate brands.
    </p>
  </section>

  <!-- SERVICES -->
  <section id="services">
    <h2 class="section-title">Our Services</h2>
    <div class="grid">
      <div class="card">Corporate Events</div>
      <div class="card">Team Building</div>
      <div class="card">Excursions & Hikes</div>
      <div class="card">Brand Activations</div>
    </div>
  </section>

  <!-- EVENTS -->
  <section id="events">
    <h2 class="section-title">Upcoming Event</h2>
    <div class="event">
      <h3>Father’s Day Experience</h3>
      <p>20th June 2026 | Village Market</p>
      <p>Bowling • Virtual Racing • Mini Golf • Board Games • Trampoline Park</p>
    </div>
  </section>

  <!-- GALLERY -->
  <section id="gallery">
    <h2 class="section-title">Gallery</h2>
    <div class="gallery">
      <img src="https://images.unsplash.com/photo-1521337706264-a414f153a5d3" />
      <img src="https://images.unsplash.com/photo-1503428593586-e225b39bddfe" />
      <img src="https://images.unsplash.com/photo-1524179091875-bf99a9a6af57" />
      <img src="https://images.unsplash.com/photo-1521737604893-d14cc237f11d" />
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact">
    <h2 class="section-title">Contact Us</h2>
    <form>
      <input type="text" placeholder="Your Name" required />
      <input type="email" placeholder="Your Email" required />
      <textarea rows="5" placeholder="Your Message"></textarea>
      <button type="submit">Send Message</button>
    </form>
  </section>

  <footer>
    <p>© 2026 Vamvi. Creating Experiences. Elevating Brands.</p>
  </footer>

</body>
</html> vamvi-agency-1
