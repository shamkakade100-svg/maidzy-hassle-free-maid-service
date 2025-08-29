<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />
<title>Maidzy.in | Trusted Maid Services in Pune</title>
<meta name="description" content="Maidzy offers trusted maid services in Pune including house cleaning, babysitting, cooking, elder care and deep cleaning with speedy booking." />
<meta name="keywords" content="maid service Pune, house cleaning Pune, babysitter, cooking maid Pune, elder care, deep cleaning maid" />
<meta property="og:title" content="Maidzy.in | Trusted Maid Services in Pune" />
<meta property="og:description" content="Trusted, background-checked maid services in Pune for cleaning, babysitting, cooking, elder care & deep cleaning." />
<meta property="og:image" content="maidzy-logo-og.png" />
<meta property="og:url" content="https://maidzy.in" />
<meta name="twitter:card" content="summary_large_image" />
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap" rel="stylesheet" />
<style>
  :root {
    --pink-light: #f9e7f0;
    --pink-main: #e54e7a;
    --pink-accent: #ff7eb9;
    --gray-dark: #333;
    --black: #111;
    --white: #fff;
    --focus-outline: 3px solid #d03569;
  }
  * {
    box-sizing: border-box;
    scroll-behavior: smooth;
  }
  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: var(--pink-light);
    color: var(--gray-dark);
    line-height: 1.6;
  }
  header {
    background: var(--white);
    box-shadow: 0 2px 8px rgba(229,65,122,0.15);
    padding: 20px 32px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: sticky;
    top: 0;
    z-index: 1000;
  }
  .logo {
    display: flex;
    align-items: center;
    gap: 14px;
    user-select: none;
    animation: logoPulse 4s ease-in-out infinite;
  }
  .logo img {
    height: 85px;
    border-radius: 10px;
    transition: transform 0.3s ease, filter 0.3s ease;
  }
  .logo img:hover, .logo img:focus {
    transform: scale(1.1);
    filter: drop-shadow(0 0 8px var(--pink-main));
    outline: none;
  }
  .logo-text {
    font-size: 2.8rem;
    font-weight: 700;
    color: var(--pink-main);
    transition: text-shadow 0.3s ease;
  }
  nav a {
    margin-left: 30px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.15rem;
    color: var(--gray-dark);
    position: relative;
    transition: color 0.3s ease;
  }
  nav a::after {
    content: '';
    position: absolute;
    bottom: -6px;
    left: 50%;
    width: 0;
    height: 3px;
    background: var(--pink-main);
    border-radius: 3px;
    transition: width 0.3s ease, left 0.3s ease;
  }
  nav a:hover, nav a:focus {
    color: var(--pink-main);
    outline: var(--focus-outline);
  }
  nav a:hover::after, nav a:focus::after {
    width: 60%;
    left: 20%;
  }
  main {
    max-width: 1150px;
    margin: 48px auto 60px;
    padding: 0 24px;
  }
  section {
    margin-bottom: 80px;
  }
  h2 {
    font-size: 2.7rem;
    font-weight: 700;
    color: var(--pink-main);
    margin-bottom: 38px;
    user-select: none;
    position: relative;
  }
  .hero {
    background: var(--white);
    border-radius: 24px;
    box-shadow: 0 10px 34px rgba(229,65,122,0.15);
    padding: 62px 44px;
    text-align: center;
    animation: fadeSlideIn 1s ease forwards;
  }
  .hero h1 {
    font-size: 3.8rem;
    font-weight: 900;
    color: var(--pink-main);
    margin-bottom: 22px;
    text-shadow: 0 2px 6px rgba(229,78,122,0.6);
  }
  .hero p {
    font-size: 1.32rem;
    margin-bottom: 36px;
    font-weight: 600;
    color: var(--gray-dark);
  }
  .btn-primary {
    background: linear-gradient(90deg, var(--pink-main), var(--pink-accent));
    color: var(--white);
    font-weight: 700;
    font-size: 1.3rem;
    padding: 20px 60px;
    border-radius: 44px;
    border: none;
    cursor: pointer;
    box-shadow: 0 10px 20px rgba(229,65,122,0.48);
    user-select: none;
    transition: background 0.4s ease, box-shadow 0.4s ease, transform 0.3s ease;
    text-decoration: none;
    display: inline-block;
    outline-offset: 4px;
  }
  .btn-primary:hover, .btn-primary:focus {
    background: #d03569;
    box-shadow: 0 12px 28px rgba(208,53,105,0.8);
    transform: translateY(-4px) scale(1.05);
    outline: var(--focus-outline);
  }
  .btn-primary:active {
    transform: translateY(-2px) scale(1.02);
  }
  .sticky-book-btn {
    position: fixed;
    bottom: 24px;
    right: 24px;
    background: var(--pink-main);
    color: var(--white);
    font-weight: 700;
    font-size: 1.25rem;
    padding: 15px 28px;
    border-radius: 44px;
    box-shadow: 0 10px 26px rgba(229,65,122,0.5);
    cursor: pointer;
    z-index: 1100;
    user-select: none;
    transition: background-color 0.3s ease, box-shadow 0.3s ease, transform 0.3s ease;
    border: none;
  }
  .sticky-book-btn:hover, .sticky-book-btn:focus {
    background-color: #cd396b;
    box-shadow: 0 14px 34px rgba(205,57,107,0.8);
    transform: translateY(-4px) scale(1.05);
    outline: var(--focus-outline);
  }
  .sticky-book-btn:active {
    transform: translateY(-2px) scale(1.02);
  }
  .services-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(240px,1fr));
    gap: 32px;
  }
  .service-card {
    background: var(--pink-light);
    border-radius: 20px;
    box-shadow: 0 7px 26px rgba(229,65,122,0.13);
    padding: 36px 30px 26px;
    text-align: center;
    cursor: default;
    transition: box-shadow 0.35s cubic-bezier(0.25, 0.8, 0.25, 1), background-color 0.35s ease, transform 0.35s ease;
    transform-style: preserve-3d;
  }
  .service-card:hover, .service-card:focus {
    background: var(--pink-accent);
    box-shadow: 0 16px 48px rgba(229,65,122,0.35);
    outline: var(--focus-outline);
    transform: translateY(-8px) rotateX(4deg) rotateY(4deg) scale(1.03);
  }
  .service-card span {
    font-size: 3.8rem;
    margin-bottom: 18px;
    display: block;
    color: var(--pink-main);
    transition: transform 0.4s ease;
  }
  .service-card:hover span, .service-card:focus span {
    transform: rotate(10deg) scale(1.1);
  }
  .service-card h3 {
    font-weight: 700;
    font-size: 1.55rem;
    margin-bottom: 16px;
    color: var(--pink-main);
  }
  .service-card p {
    font-weight: 600;
    font-size: 1.1rem;
    color: var(--gray-dark);
  }
  .badges-group {
    display: flex;
    max-width: 880px;
    margin: 0 auto 40px;
    justify-content: center;
    gap: 38px;
    flex-wrap: wrap;
  }
  .badge {
    display: flex;
    align-items: center;
    gap: 16px;
    background: var(--pink-light);
    padding: 16px 30px;
    border-radius: 18px;
    box-shadow: 0 6px 20px rgba(229,65,122,0.1);
    user-select: none;
    cursor: default;
    transition: background-color 0.3s ease, box-shadow 0.3s ease, transform 0.3s ease;
  }
  .badge:hover, .badge:focus {
    background: var(--pink-accent);
    box-shadow: 0 10px 28px rgba(229,65,122,0.25);
    transform: translateY(-4px) scale(1.05);
    outline: var(--focus-outline);
  }
  .badge img {
    width: 52px;
    height: 52px;
    transition: transform 0.3s ease;
  }
  .badge:hover img, .badge:focus img {
    transform: rotate(15deg) scale(1.1);
  }
  .badge span {
    font-weight: 700;
    font-size: 1.2rem;
    color: var(--pink-main);
  }
  .testimonial {
    max-width: 750px;
    margin: 0 auto;
    background: var(--pink-light);
    border-radius: 24px;
    padding: 36px 30px;
    box-shadow: 0 8px 32px rgba(229,65,122,0.2);
    font-style: italic;
    font-weight: 600;
    font-size: 1.175rem;
    line-height: 1.5;
    color: var(--gray-dark);
    user-select: none;
    transition: box-shadow 0.4s ease;
  }
  .testimonial:hover, .testimonial:focus {
    box-shadow: 0 16px 48px rgba(229,65,122,0.3);
    outline: var(--focus-outline);
  }
  .testimonial strong {
    display: block;
    margin-top: 16px;
    color: var(--pink-main);
  }  
  footer {
    background: var(--white);
    text-align: center;
    padding: 20px 14px;
    color: var(--pink-main);
    font-weight: 600;
    font-size: 1.05rem;
    border-top: 2px solid #f1c3de;
    user-select: none;
  }
  footer a {
    color: var(--pink-main);
    text-decoration: none;
    font-weight: 700;
    margin: 0 14px;
    transition: text-decoration 0.3s ease;
  }
  footer a:hover,
  footer a:focus {
    text-decoration: underline;
    outline: var(--focus-outline);
  }
  .social-links {
    margin: 12px 0 8px;
  }
  .social-links a {
    display: inline-block;
    margin: 0 14px;
    transition: transform 0.3s ease;
  }
  .social-links a:hover, .social-links a:focus {
    transform: scale(1.15);
    outline: none;
  }
  .social-links img {
    width: 34px;
    vertical-align: middle;
  }
  @keyframes fadeSlideIn {
    from {opacity: 0; transform: translateY(-30px);}
    to {opacity: 1; transform: translateY(0);}
  }
  @keyframes logoPulse {
    0%, 100% {transform: scale(1);}
    50% {transform: scale(1.05);}
  }
  @media (max-width: 767px) {
    header {
      flex-wrap: wrap;
      padding: 20px 16px;
      justify-content: center;
      gap: 20px;
    }
    nav a {
      margin: 0 16px;
      font-size: 1rem;
    }
    .hero h1 {
      font-size: 2.45rem;
    }
    .services-grid {
      grid-template-columns: 1fr 1fr;
      gap: 24px;
    }
    .sticky-book-btn {
      bottom: 16px;
      right: 16px;
      padding: 12px 24px;
      font-size: 1rem;
    }
  }
</style>
</head>
<body>
<header>
  <div class="logo" tabindex="0" aria-label="Maidzy logo">
    <img src="maidzy-icon.png" alt="Maidzy Logo" loading="lazy" />
    <div class="logo-text">Maidzy</div>
  </div>
  <nav aria-label="Main navigation">
    <a href="#about" tabindex="0">About Us</a>
    <a href="#services" tabindex="0">Services</a>
    <a href="#why-choose-us" tabindex="0">Why Choose Us</a>
  </nav>
</header>
<main>
  <section class="hero" role="banner" aria-labelledby="hero-title" aria-describedby="hero-subtitle">
    <h1 id="hero-title">Hire Reliable Maids in Pune</h1>
    <p id="hero-subtitle">Trusted, background-checked professionals for your home. Book now for fast and safe help.</p>
    <a href="https://wa.me/918484925800?text=Hello%20Maidzy%2C%20I%20am%20interested%20in%20your%20maid%20services.%20Please%20contact%20me." 
       class="btn-primary" 
       tabindex="0" 
       target="_blank" 
       rel="noopener" 
       aria-label="Chat on WhatsApp to book Maidzy services">
      Book Now
    </a>
  </section>
  <section id="about">
    <h2>About Maidzy</h2>
    <p>Maidzy is Pune's premium maid service provider launching this month. We connect you with background-checked, vetted, and experienced professionals who care as much as you do.</p>
  </section>
  <section id="services">
    <h2>Our Services</h2>
    <div class="services-grid" role="list">
      <article class="service-card" role="listitem" tabindex="0" aria-label="House Cleaning Service">
        <span aria-hidden="true" aria-label="Broom icon">🧹</span>
        <h3>House Cleaning</h3>
        <p>Comprehensive home cleaning for a spotlessly fresh environment.</p>
      </article>
      <article class="service-card" role="listitem" tabindex="0" aria-label="Babysitting Service">
        <span aria-hidden="true" aria-label="Baby icon">👶</span>
        <h3>Babysitting</h3>
        <p>Experienced babysitters trusted to care for your little ones.</p>
      </article>
      <article class="service-card" role="listitem" tabindex="0" aria-label="Cooking Service">
        <span aria-hidden="true" aria-label="Cooking pan icon">🍳</span>
        <h3>Cooking</h3>
        <p>Delicious home-cooked meals tailored to your preferences.</p>
      </article>
      <article class="service-card" role="listitem" tabindex="0" aria-label="Elder Care Service">
        <span aria-hidden="true" aria-label="Elderly person icon">👵</span>
        <h3>Elder Care</h3>
        <p>Compassionate and attentive care for your senior family members.</p>
      </article>
      <article class="service-card" role="listitem" tabindex="0" aria-label="Deep Cleaning Service">
        <span aria-hidden="true" aria-label="Soap icon">🧼</span>
        <h3>Deep Cleaning</h3>
        <p>Thorough cleaning solutions for a hygienic, fresh home.</p>
      </article>
    </div>
  </section>
  <section id="why-choose-us">
    <h2>Why Choose Us</h2>
    <div class="badges-group" role="list">
      <div class="badge" role="listitem" tabindex="0">
        <img src="badge1.png" alt="Certified Professionals" loading="lazy" />
        <span>Certified Professionals</span>
      </div>
      <div class="badge" role="listitem" tabindex="0">
        <img src="badge2.png" alt="Background Checked" loading="lazy" />
        <span>Background Checked</span>
      </div>
      <div class="badge" role="listitem" tabindex="0">
        <img src="badge3.png" alt="5 Star Ratings" loading="lazy" />
        <span>5 Star Ratings</span>
      </div>
    </div>
    <article class="testimonial" tabindex="0" aria-label="Client testimonial">
      "Fast and trustworthy service! Maidzy always delivers exactly what they promise." — <strong>Priya, Pune</strong>
    </article>
  </section>
</main>
<button class="sticky-book-btn" 
        onclick="window.open('https://wa.me/918484925800?text=Hello%20Maidzy%2C%20I%20am%20interested%20in%20your%20maid%20services.%20Please%20contact%20me.', '_blank')" 
        aria-label="Chat on WhatsApp to book Maidzy services">
  Book Now
</button>
<footer>
  <div class="social-links" aria-label="Social media links">
    <a href="https://www.facebook.com/share/1761Lv135m/" target="_blank" rel="noopener" tabindex="0" aria-label="Facebook"><img src="fb-logo.png" alt="Facebook"></a>
    <a href="https://www.instagram.com/maidzy11?igsh=MWdsOW1pbzk1ZnZyeQ==" target="_blank" rel="noopener" tabindex="0" aria-label="Instagram"><img src="insta-logo.png" alt="Instagram"></a>
    <a href="https://wa.me/918484925800" target="_blank" rel="noopener" tabindex="0" aria-label="WhatsApp"><img src="whatsapp-logo.png" alt="WhatsApp"></a>
  </div>
  <p>Phone: <a href="tel:+918484925800">+91 84849 25800</a> | Pune, Maharashtra, India</p>
  <p>&copy; 2025 Maidzy. All rights reserved.</p>
</footer>
</body>
</html>
