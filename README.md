# index.html

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Chambal Safari Dholpur | Wildlife River Safari</title>
  <meta name="description" content="Explore Chambal Safari Dholpur, Rajasthan. Discover gharials, Gangetic river dolphins, turtles, river birds and beautiful Chambal ravines. Plan your wildlife river safari.">
  <meta name="keywords" content="Chambal Safari Dholpur, Chambal River Safari, Dholpur Wildlife Safari, Gharial Safari, Gangetic River Dolphin, Chambal Boat Safari, Rajasthan Wildlife">
  <meta name="author" content="Chambal Safari Dholpur">
  <meta name="theme-color" content="#123c2b">

  <meta property="og:title" content="Chambal Safari Dholpur">
  <meta property="og:description" content="Nature • Wildlife • Adventure! Experience the beauty of the Chambal River.">
  <meta property="og:type" content="website">

  <style>
    :root {
      --green: #123c2b;
      --green2: #20563b;
      --gold: #d6b46a;
      --cream: #f8f5ec;
      --white: #ffffff;
      --text: #26352b;
      --muted: #657267;
      --shadow: 0 12px 35px rgba(18,60,43,.12);
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }

    html { scroll-behavior: smooth; }

    body {
      font-family: Arial, Helvetica, sans-serif;
      color: var(--text);
      background: var(--cream);
      line-height: 1.7;
    }

    a { text-decoration: none; }

    .topbar {
      background: #0c2c20;
      color: #f7f1df;
      padding: 8px 5%;
      display: flex;
      justify-content: space-between;
      gap: 12px;
      flex-wrap: wrap;
      font-size: 13px;
    }

    header {
      background: var(--green);
      color: white;
      padding: 16px 5%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 20px;
      flex-wrap: wrap;
    }

    .brand {
      color: white;
      font-weight: 800;
      font-size: 21px;
      letter-spacing: .4px;
      line-height: 1.3;
    }

    .brand span {
      color: var(--gold);
      display: block;
      font-size: 11px;
      font-weight: 500;
      letter-spacing: 2px;
      margin-top: 4px;
    }

    nav {
      display: flex;
      flex-wrap: wrap;
      align-items: center;
      gap: 18px;
    }

    nav a {
      color: white;
      font-size: 14px;
      font-weight: 600;
    }

    nav a:hover { color: var(--gold); }

    .hero {
      min-height: 560px;
      display: flex;
      align-items: center;
      padding: 80px 7%;
      color: white;
      background:
        linear-gradient(90deg, rgba(5,28,19,.88), rgba(5,28,19,.48)),
        url("https://images.unsplash.com/photo-1472396961693-142e6e269027?auto=format&fit=crop&w=2000&q=85")
        center/cover no-repeat;
    }

    .hero-content { max-width: 720px; }

    .eyebrow {
      color: var(--gold);
      font-size: 13px;
      font-weight: 800;
      letter-spacing: 3px;
      text-transform: uppercase;
      margin-bottom: 15px;
    }

    h1 {
      font-size: clamp(34px, 5.5vw, 62px);
      line-height: 1.12;
      margin-bottom: 20px;
      letter-spacing: .5px;
    }

    .hero p {
      font-size: clamp(16px, 2vw, 19px);
      max-width: 590px;
      color: #f2f4ef;
      margin-bottom: 28px;
    }

    .hero-tagline {
      color: var(--gold);
      font-weight: 700;
      letter-spacing: 1px;
      margin-bottom: 25px;
    }

    .buttons {
      display: flex;
      gap: 12px;
      flex-wrap: wrap;
      align-items: center;
    }

    .btn {
      display: inline-flex;
      align-items: center;
      justify-content: center;
      padding: 12px 21px;
      min-height: 46px;
      border-radius: 7px;
      font-weight: 700;
      font-size: 14px;
      transition: .2s ease;
      border: 1px solid transparent;
    }

    .btn:hover { transform: translateY(-2px); }

    .btn-gold {
      color: #17291d;
      background: var(--gold);
    }

    .btn-outline {
      color: white;
      border-color: rgba(255,255,255,.75);
      background: rgba(255,255,255,.07);
    }

    .btn-green {
      color: white;
      background: var(--green);
    }

    .btn-light {
      color: var(--green);
      background: white;
      border-color: #dfe6dc;
    }

    .section {
      padding: 75px 6%;
      scroll-margin-top: 20px;
    }

    .section-white { background: white; }

    .section-heading {
      text-align: center;
      max-width: 760px;
      margin: 0 auto 38px;
    }

    .section-heading .eyebrow {
      color: #94712b;
      margin-bottom: 8px;
    }

    h2 {
      color: var(--green);
      font-size: clamp(27px, 3.5vw, 39px);
      line-height: 1.25;
      margin-bottom: 14px;
    }

    .section-heading p { color: var(--muted); }

    .intro-grid {
      display: grid;
      grid-template-columns: 1.1fr .9fr;
      gap: 38px;
      align-items: center;
      max-width: 1150px;
      margin: auto;
    }

    .intro-grid h2 { margin-bottom: 18px; }

    .intro-photo {
      width: 100%;
      height: 370px;
      object-fit: cover;
      border-radius: 14px;
      box-shadow: var(--shadow);
    }

    .intro-copy p { margin-bottom: 15px; }

    .wildlife-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 22px;
      max-width: 1200px;
      margin: auto;
    }

    .wildlife-card {
      overflow: hidden;
      background: white;
      border-radius: 13px;
      box-shadow: var(--shadow);
      border: 1px solid #e9e8df;
    }

    .wildlife-card img {
      display: block;
      width: 100%;
      height: 220px;
      object-fit: cover;
      background: #e4e9df;
    }

    .card-copy { padding: 22px; }

    .card-copy h3 {
      color: var(--green);
      font-size: 20px;
      margin-bottom: 9px;
    }

    .card-copy p {
      font-size: 14px;
      color: var(--muted);
    }

    .experience {
      background: var(--green);
      color: white;
    }

    .experience .section-heading h2 { color: white; }
    .experience .section-heading p { color: #d9e5dc; }
    .experience .section-heading .eyebrow { color: var(--gold); }

    .experience-grid {
      display: grid;
      grid-template-columns: repeat(3, minmax(0, 1fr));
      gap: 20px;
      max-width: 1150px;
      margin: auto;
    }

    .experience-card {
      padding: 28px 22px;
      border: 1px solid rgba(214,180,106,.45);
      border-radius: 12px;
      background: rgba(255,255,255,.055);
    }

    .experience-card .symbol {
      font-size: 30px;
      margin-bottom: 12px;
    }

    .experience-card h3 {
      color: var(--gold);
      margin-bottom: 8px;
      font-size: 19px;
    }

    .experience-card p {
      color: #e3ebe4;
      font-size: 14px;
    }

    .visit-box {
      max-width: 1000px;
      margin: auto;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 28px;
      align-items: start;
    }

    .info-panel {
      padding: 28px;
      background: white;
      border: 1px solid #e8e7dd;
      border-radius: 13px;
      box-shadow: var(--shadow);
    }

    .info-panel h3 {
      color: var(--green);
      font-size: 21px;
      margin-bottom: 15px;
    }

    .distance-list {
      list-style: none;
    }

    .distance-list li {
      display: flex;
      justify-content: space-between;
      gap: 12px;
      padding: 10px 0;
      border-bottom: 1px solid #ecece5;
    }

    .distance-list li:last-child { border-bottom: 0; }

    .distance-list strong { color: var(--green); }

    .small-note {
      color: var(--muted);
      font-size: 12px;
      margin-top: 13px;
    }

    .booking-banner {
      max-width: 1100px;
      margin: auto;
      padding: 42px 30px;
      border-radius: 16px;
      color: white;
      text-align: center;
      background: linear-gradient(135deg, #123c2b, #286443);
      box-shadow: var(--shadow);
    }

    .booking-banner h2 { color: white; }
    .booking-banner p { margin: 0 auto 23px; max-width: 650px; color: #e6eee7; }

    .review-grid {
      display: grid;
      grid-template-columns: repeat(2, minmax(0, 1fr));
      gap: 22px;
      max-width: 850px;
      margin: auto;
    }

    .review-card {
      padding: 28px;
      background: white;
      border: 1px solid #e6e6dd;
      border-radius: 13px;
      text-align: center;
    }

    .review-card h3 {
      color: var(--green);
      margin-bottom: 8px;
    }

    .review-card p {
      color: var(--muted);
      font-size: 14px;
      margin-bottom: 18px;
    }

    .contact-box {
      max-width: 800px;
      margin: auto;
      text-align: center;
    }

    .contact-box p { margin-bottom: 10px; }

    .contact-box a.email {
      color: var(--green);
      overflow-wrap: anywhere;
    }

    footer {
      background: #0b291d;
      color: #dbe6dc;
      text-align: center;
      padding: 30px 6%;
      font-size: 13px;
    }

    footer strong { color: var(--gold); }

    .floating-whatsapp {
      position: fixed;
      z-index: 99;
      right: 18px;
      bottom: 18px;
      width: 57px;
      height: 57px;
      border-radius: 50%;
      display: flex;
      align-items: center;
      justify-content: center;
      background: #20bd5a;
      color: white;
      font-size: 27px;
      box-shadow: 0 5px 20px rgba(0,0,0,.25);
    }

    @media (max-width: 850px) {
      header { justify-content: center; text-align: center; }
      nav { justify-content: center; gap: 12px; }
      .intro-grid, .visit-box { grid-template-columns: 1fr; }
      .wildlife-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .experience-grid { grid-template-columns: repeat(2, minmax(0, 1fr)); }
      .hero { min-height: 500px; padding: 65px 6%; }
    }

    @media (max-width: 560px) {
      .topbar { justify-content: center; text-align: center; }
      .brand { font-size: 19px; }
      nav { gap: 9px 14px; }
      nav a { font-size: 12px; }
      .hero { min-height: 490px; padding: 55px 6%; }
      .hero p { font-size: 16px; }
      .btn { padding: 11px 15px; font-size: 13px; }
      .section { padding: 55px 5%; }
      .wildlife-grid, .experience-grid, .review-grid { grid-template-columns: 1fr; }
      .intro-photo { height: 260px; }
      .wildlife-card img { height: 215px; }
      .info-panel { padding: 22px 18px; }
      .booking-banner { padding: 32px 20px; }
    }
  </style>
</head>

<body>

  <div class="topbar">
    <span>📍 Chambal River, Dholpur, Rajasthan</span>
    <span>Nature • Wildlife • Adventure!</span>
  </div>

  <header>
    <a class="brand" href="#home">
      CHAMBAL SAFARI DHOLPUR
      <span>WILDLIFE RIVER SAFARI</span>
    </a>

    <nav aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#wildlife">Wildlife</a>
      <a href="#experience">Experience</a>
      <a href="#reach">How to Reach</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <div class="hero-content">
        <div class="eyebrow">Discover the Wild Chambal</div>
        <h1>CHAMBAL SAFARI DHOLPUR</h1>
        <p>
          Discover the natural beauty of the Chambal River, dramatic ravines,
          fascinating wildlife and unforgettable river landscapes.
        </p>
        <div class="hero-tagline">Nature • Wildlife • Adventure!</div>

        <div class="buttons">
          <a class="btn btn-gold"
             href="https://script.google.com/macros/s/AKfycbxPgvz8-7zv1YoxKZKMWTjMEsicVts6Ojk6iSKkcOr7eCdwy0oM0a7em_LoRLXW3qzo/exec"
             target="_blank" rel="noopener">Book Your Safari</a>

          <a class="btn btn-outline"
             href="https://wa.me/918619073416?text=Hello%2C%20I%20want%20to%20enquire%20about%20Chambal%20Safari%20Dholpur."
             target="_blank" rel="noopener">WhatsApp Us</a>
        </div>
      </div>
    </section>

    <section class="section section-white" id="about">
      <div class="intro-grid">
        <div class="intro-copy">
          <div class="eyebrow">Welcome to Chambal</div>
          <h2>Experience the Wild Side of Dholpur</h2>
          <p>
            Chambal Safari Dholpur offers an opportunity to explore the beautiful
            Chambal River landscape and its remarkable wildlife. The region is
            known for its ravines, river habitats and diverse birdlife.
          </p>
          <p>
            Depending on natural conditions and the season, visitors may have
            opportunities to look for gharials, Gangetic river dolphins, turtles
            and river birds during a safari.
          </p>
          <p>
            Enjoy the peaceful river scenery, observe nature responsibly and
            discover a special part of Rajasthan's natural heritage.
          </p>

          <div class="buttons">
            <a class="btn btn-green" href="#wildlife">Explore Wildlife</a>
            <a class="btn btn-light" href="#reach">How to Reach</a>
          </div>
        </div>

        <img class="intro-photo"
             src="https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=1100&q=80"
             alt="Natural landscape and wilderness"
             loading="lazy">
      </div>
    </section>

    <section class="section" id="wildlife">
      <div class="section-heading">
        <div class="eyebrow">Nature's Treasures</div>
        <h2>Wildlife of the Chambal River</h2>
        <p>
          Explore the river's fascinating wildlife and habitats.
          Sightings depend on weather, season and natural conditions.
        </p>
      </div>

      <div class="wildlife-grid">
        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1564760055775-d63b17a55c44?auto=format&fit=crop&w=900&q=80"
               alt="Crocodilian wildlife" loading="lazy">
          <div class="card-copy">
            <h3>Gharial</h3>
            <p>
              The gharial is a distinctive fish-eating crocodilian associated
              with river habitats. The Chambal is an important stronghold for
              this endangered species.
            </p>
          </div>
        </article>

        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1568430462989-44163eb1752f?auto=format&fit=crop&w=900&q=80"
               alt="Dolphin in water" loading="lazy">
          <div class="card-copy">
            <h3>Gangetic River Dolphin</h3>
            <p>
              This rare freshwater dolphin lives in river systems of the Indian
              subcontinent. Seeing one in the wild is a special experience,
              but sightings are never guaranteed.
            </p>
          </div>
        </article>

        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1511497584788-876760111969?auto=format&fit=crop&w=900&q=80"
               alt="Natural river habitat" loading="lazy">
          <div class="card-copy">
            <h3>Freshwater Turtles</h3>
            <p>
              Chambal's river ecosystem supports freshwater turtles and other
              aquatic wildlife. Observe animals from a respectful distance.
            </p>
          </div>
        </article>

        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1444464666168-49d633b86797?auto=format&fit=crop&w=900&q=80"
               alt="Wild bird perched in nature" loading="lazy">
          <div class="card-copy">
            <h3>River Birds</h3>
            <p>
              The river and its sandbanks attract a variety of birds.
              Patient visitors may enjoy birdwatching along the river landscape.
            </p>
          </div>
        </article>

        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1472396961693-142e6e269027?auto=format&fit=crop&w=900&q=80"
               alt="Wildlife in its natural habitat" loading="lazy">
          <div class="card-copy">
            <h3>Chambal Ravines</h3>
            <p>
              The rugged ravines and open landscapes create a distinctive
              setting for nature exploration and photography.
            </p>
          </div>
        </article>

        <article class="wildlife-card">
          <img src="https://images.unsplash.com/photo-1500375592092-40eb2168fd21?auto=format&fit=crop&w=900&q=80"
               alt="River and water landscape" loading="lazy">
          <div class="card-copy">
            <h3>River Safari</h3>
            <p>
              Experience the river scenery and look for wildlife with respect
              for the natural environment and local safari instructions.
            </p>
          </div>
        </article>
      </div>
    </section>

    <section class="section experience" id="experience">
      <div class="section-heading">
        <div class="eyebrow">Make It Memorable</div>
        <h2>A Nature Experience to Remember</h2>
        <p>
          Enjoy the landscape, appreciate wildlife and make time for the
          peaceful beauty of the Chambal River.
        </p>
      </div>

      <div class="experience-grid">
        <article class="experience-card">
          <div class="symbol">🛶</div>
          <h3>River Safari</h3>
          <p>Experience the river landscape and observe nature from the water when safari services are operating.</p>
        </article>

        <article class="experience-card">
          <div class="symbol">🦅</div>
          <h3>Birdwatching</h3>
          <p>Look for river birds and other species that use the Chambal's diverse habitats.</p>
        </article>

        <article class="experience-card">
          <div class="symbol">📷</div>
          <h3>Nature Photography</h3>
          <p>Capture river scenery, ravines and wildlife without disturbing animals or their habitat.</p>
        </article>
      </div>
    </section>

    <section class="section section-white" id="reach">
      <div class="section-heading">
        <div class="eyebrow">Plan Your Visit</div>
        <h2>How to Reach Chambal Safari</h2>
        <p>Plan your journey to the Chambal River area near Dholpur, Rajasthan.</p>
      </div>

      <div class="visit-box">
        <div class="info-panel">
          <h3>Approximate Distances</h3>
          <ul class="distance-list">
            <li><span>Agra</span><strong>46 km</strong></li>
            <li><span>Gwalior</span><strong>55 km</strong></li>
            <li><span>Bharatpur</span><strong>110 km</strong></li>
            <li><span>Ranthambore</span><strong>220 km</strong></li>
            <li><span>Jaipur</span><strong>262 km</strong></li>
          </ul>
          <p class="small-note">
            Distances are approximate and may vary by route and exact starting point.
            Confirm the safari meeting point before travelling.
          </p>
        </div>

        <div class="info-panel">
          <h3>Get Directions</h3>
          <p>
            Use the location link to view directions and check your route before
            leaving. Contact us if you need help confirming the meeting point.
          </p>
          <br>
          <div class="buttons">
            <a class="btn btn-green"
               href="https://maps.app.goo.gl/PLgQ8aZs875sREaRA"
               target="_blank" rel="noopener">Open Location Map</a>

            <a class="btn btn-light"
               href="https://wa.me/918619073416?text=Hello%2C%20please%20share%20the%20Chambal%20Safari%20meeting%20point."
               target="_blank" rel="noopener">Ask for Directions</a>
          </div>
        </div>
      </div>
    </section>

    <section class="section" id="booking">
      <div class="booking-banner">
        <div class="eyebrow">Your Chambal Adventure Awaits</div>
        <h2>Plan Your Chambal Safari</h2>
        <p>
          Contact us to enquire about safari availability, timings, meeting
          point and booking details before your visit.
        </p>
        <div class="buttons" style="justify-content:center">
          <a class="btn btn-gold"
             href="https://script.google.com/macros/s/AKfycbxPgvz8-7zv1YoxKZKMWTjMEsicVts6Ojk6iSKkcOr7eCdwy0oM0a7em_LoRLXW3qzo/exec"
             target="_blank" rel="noopener">Book Now</a>

          <a class="btn btn-outline"
             href="https://wa.me/918619073416?text=Hello%2C%20I%20want%20to%20book%20Chambal%20Safari."
             target="_blank" rel="noopener">WhatsApp Booking</a>

          <a class="btn btn-outline" href="tel:+919694715732">Call Us</a>
        </div>
      </div>
    </section>

    <section class="section section-white" id="reviews">
      <div class="section-heading">
        <div class="eyebrow">Share Your Experience</div>
        <h2>Reviews & Feedback</h2>
        <p>
          Visited us? Your feedback helps other travellers plan their trip.
        </p>
      </div>

      <div class="review-grid">
        <div class="review-card">
          <h3>Google Reviews</h3>
          <p>Share your experience and help future visitors discover Chambal Safari Dholpur.</p>
          <a class="btn btn-green"
             href="https://maps.app.goo.gl/AhcrNYaSq9E9HdTa9"
             target="_blank" rel="noopener">Write a Google Review</a>
        </div>

        <div class="review-card">
          <h3>TripAdvisor</h3>
          <p>Explore our TripAdvisor listing and share your feedback with fellow travellers.</p>
          <a class="btn btn-green"
             href="https://www.tripadvisor.in/Attraction_Review-g2285520-d19595396-Reviews-Munna_Chambal_River_Safari_Dholpur-Dholpur_Dholpur_District_Rajasthan.html"
             target="_blank" rel="noopener">View TripAdvisor</a>
        </div>
      </div>
    </section>

    <section class="section" id="contact">
      <div class="contact-box">
        <div class="eyebrow">Get in Touch</div>
        <h2>Contact Chambal Safari Dholpur</h2>
        <p>For booking enquiries, directions and safari information, contact us.</p>
        <p><strong>Location:</strong> Chambal River area, Dholpur, Rajasthan, India</p>
        <p><strong>Phone:</strong> <a class="email" href="tel:+918619073416">+91 86190 73416</a></p>
        <p><strong>Phone:</strong> <a class="email" href="tel:+919694715732">+91 96947 15732</a></p>
        <p><strong>Email:</strong>
          <a class="email" href="mailto:munnachambalsafaridholpur@gmail.com">
            munnachambalsafaridholpur@gmail.com
          </a>
        </p>

        <br>
        <div class="buttons" style="justify-content:center">
          <a class="btn btn-green"
             href="https://wa.me/918619073416"
             target="_blank" rel="noopener">WhatsApp</a>
          <a class="btn btn-light"
             href="https://maps.app.goo.gl/PLgQ8aZs875sREaRA"
             target="_blank" rel="noopener">Get Directions</a>
        </div>
      </div>
    </section>
  </main>

  <footer>
    <p><strong>CHAMBAL SAFARI DHOLPUR</strong></p>
    <p>Nature • Wildlife • Adventure!</p>
    <p>© <span id="year"></span> Chambal Safari Dholpur. All rights reserved.</p>
    <p>Wildlife sightings depend on natural conditions and are not guaranteed.</p>
  </footer>

  <a class="floating-whatsapp"
     href="https://wa.me/918619073416"
     target="_blank" rel="noopener"
     aria-label="Chat with Chambal Safari Dholpur on WhatsApp">☏</a>

  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>

</body>
</html>
