<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1, user-scalable=no" />
<title>Maidzy.in | Trusted Maid Services in Pune</title>
<meta name="description" content="Maidzy offers trusted maid services in Pune including house cleaning, babysitting, cooking, elder care and deep cleaning with speedy booking." />
<meta name="keywords" content="maid service Pune, house cleaning Pune, babysitter, cooking maid Pune, elder care, deep cleaning maid" />
<!-- Open Graph for social sharing -->
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
    transition: transform 0.3s ease;
  }
  .logo img:hover, .logo img:focus {
    transform: scale(1.1);
    outline: none;
  }
  .logo-text {
    font-size: 2.8rem;
    font-weight: 700;
    color: var(--pink-main);
  }
  nav a {
    margin-left: 30px;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.15rem;
    color: var(--gray-dark);
    transition: color 0.3s ease;
  }
  nav a:hover, nav a:focus {
    color: var(--pink-main);
    outline: var(--focus-outline);
    outline-offset: 2px;
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
  }
  /* Hero */
  .hero {
    background: var(--white);
    border-radius: 24px;
    box-shadow: 0 10px 34px rgba(229,65,122,0.15);
    padding: 62px 44px;
    text-align: center;
    animation: fadeSlideIn 1s ease forwards;
    position: relative;
  }
  .hero h1 {
    font-size: 3.8rem;
    font-weight: 900;
    color: var(--pink-main);
    margin-bottom: 22px;
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
    transition: background 0.3s ease;
    text-decoration: none;
    display: inline-block;
    outline-offset: 4px;
  }
  .btn-primary:hover, .btn-primary:focus {
    background: #d03569;
    outline: var(--focus-outline);
  }

  /* Sticky Book Now Button */
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
    transition: background-color 0.3s ease;
    border: none;
  }
  .sticky-book-btn:hover, .sticky-book-btn:focus {
    background-color: #cd396b;
    outline: var(--focus-outline);
  }

  /* Services */
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
    transition: box-shadow 0.3s ease, background-color 0.3s ease;
  }
  .service-card:hover, .service-card:focus {
    background: var(--pink-accent);
    box-shadow: 0 12px 40px rgba(229,65,122,0.28);
    outline: var(--focus-outline);
  }
  .service-card span {
    font-size: 3.8rem;
    margin-bottom: 18px;
    display: block;
    color: var(--pink-main);
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
  /* Why Choose Us */
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
  }
  .badge img {
    width: 52px;
    height: 52px;
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
  }
  .testimonial strong {
    display: block;
    margin-top: 16px;
    color: var(--pink-main);
  }
  /* Pricing */
  .pricing-grid {
    max-width: 1000px;
    margin: 0 auto;
    display: grid;
    gap: 34px;
    grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
  }
  .plan-card {
    background: var(--pink-light);
    padding: 42px 34px;
    border-radius: 22px;
    box-shadow: 0 8px 32px rgba(229,65,122,0.18);
    cursor: default;
    transition: box-shadow 0.3s ease;
    text-align: center;
    user-select: none;
  }
  .plan-card:hover, .plan-card:focus {
    box-shadow: 0 14px 46px rgba(229,65,122,0.32);
    outline: var(--focus-outline);
  }
  .plan-card h3 {
    font-size: 1.9rem;
    font-weight: 800;
    color: var(--pink-main);
    margin-bottom: 28px;
  }
  .plan-price {
    font-size: 2.7rem;
    font-weight: 900;
    color: var(--pink-main);
    margin-bottom: 24px;
  }
  .plan-features {
    font-size: 1.15rem;
    font-weight: 600;
    color: var(--gray-dark);
    line-height: 1.65;
    margin-bottom: 32px;
  }
  .btn-choose {
    background: var(--pink-main);
    border: none;
    padding: 18px 60px;
    font-weight: 700;
    font-size: 1.25rem;
    border-radius: 36px;
    cursor: pointer;
    box-shadow: 0 10px 26px rgba(229,65,122,0.5);
    color: var(--white);
    user-select: none;
    transition: background-color 0.3s ease;
    outline-offset: 4px;
  }
  .btn-choose:hover, .btn-choose:focus {
    background-color: #cd396b;
    outline: var(--focus-outline);
  }
  /* Contact */
  #contact {
    max-width: 580px;
    margin: 0 auto;
  }
  #contact h2 {
    text-align: center;
    font-size: 2.6rem;
    font-weight: 700;
    color: var(--pink-main);
    margin-bottom: 34px;
  }
  .contact-form label {
    font-weight: 700;
    color: var(--pink-main);
    display: block;
    margin-bottom: 6px;
    user-select: none;
  }
  .contact-form input,
  .contact-form textarea {
    width: 100%;
    border-radius: 14px;
    border: 1.8px solid #f3c6db;
    padding: 14px 18px;
    margin-bottom: 26px;
    font-size: 1.02rem;
    font-family: 'Poppins', sans-serif;
    transition: border-color 0.3s ease;
  }
  .contact-form input:focus,
  .contact-form textarea:focus {
    outline: none;
    border-color: var(--pink-main);
    box-shadow: 0 0 6px var(--pink-main);
  }
  .contact-form textarea {min-height: 120px;resize: vertical;}
  .contact-form button {
    background: var(--pink-main);
    border: none;
    border-radius: 42px;
    color: var(--white);
    font-weight: 800;
    font-size: 1.28rem;
    padding: 20px 50px;
    cursor: pointer;
    box-shadow: 0 12px 34px rgba(229,65,122,0.6);
    user-select: none;
    transition: background-color 0.3s ease;
    outline-offset: 4px;
  }
  .contact-form button:hover,
  .contact-form button:focus {
    background: #ca376a;
    outline: var(--focus-outline);
  }
  /* Footer */
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
  }
  .social-links img {
    width: 34px;
    vertical-align: middle;
  }
  /* Animations */
  @keyframes fadeSlideIn {
    from {
      opacity: 0;
      transform: translateY(-30px);
    }
    to {
      opacity: 1;
      transform: translateY(0);
    }
  }
  @keyframes logoPulse {
    0%, 100% { transform: scale(1); }
    50% { transform: scale(1.05); }
  }
  /* Responsive */
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
    .pricing-grid {
      grid-template-columns: 1fr;
      gap: 24px;
    }
    /* Sticky book button smaller on small screens */
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
    <a href="#pricing" tabindex="0">Pricing</a>
    <a href="#contact" tabindex="0">Contact</a>
  </nav>
</header>
<main>
  <section class="hero" role="banner" aria-labelledby="hero-title" aria-describedby="hero-subtitle">
    <h1 id="hero-title">Hire Reliable Maids in Pune</h1>
    <p id="hero-subtitle">Trusted, background-checked professionals for your home. Book now for fast and safe help.</p>
    <a href="#contact" class="btn-primary" tabindex="0">Book Now</a>
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
  <section id="pricing">
    <h2>Pricing Plans</h2>
    <div class="pricing-grid" role="list">
      <article class="plan-card" role="listitem" tabindex="0" aria-label="Basic Plan">
        <h3>Basic</h3>
        <div class="plan-price">₹5,000 / mo</div>
        <p class="plan-features">
          Weekly cleaning<br />Basic support<br />1 service per week
        </p>
        <button class="btn-choose" tabindex="0">Choose Plan</button>
      </article>
      <article class="plan-card" role="listitem" tabindex="0" aria-label="Standard Plan">
        <h3>Standard</h3>
        <div class="plan-price">₹8,500 / mo</div>
        <p class="plan-features">
          Biweekly cleaning<br />Priority support<br />2 services per week
        </p>
        <button class="btn-choose" tabindex="0">Choose Plan</button>
      </article>
      <article class="plan-card" role="listitem" tabindex="0" aria-label="Premium Plan">
        <h3>Premium</h3>
        <div class="plan-price">₹12,000 / mo</div>
        <p class="plan-features">
          Daily cleaning<br />Dedicated support<br />Full service package
        </p>
        <button class="btn-choose" tabindex="0">Choose Plan</button>
      </article>
    </div>
  </section>
  <section id="contact">
    <h2>Contact Us</h2>
    <form class="contact-form" aria-label="Contact form">
      <label for="name">Your Name</label>
      <input type="text" id="name" name="name" required aria-required="true" />
      <label for="phone">Phone Number</label>
      <input type="tel" id="phone" name="phone" required aria-required="true" pattern="[0-9]{10}" title="Enter a 10-digit phone number" />
      <label for="message">Message</label>
      <textarea id="message" name="message" required aria-required="true"></textarea>
      <button type="submit">Submit</button>
      <div role="alert" aria-live="polite" id="formFeedback" style="color: var(--pink-main); font-weight: 600; margin-top: 10px;"></div>
    </form>
  </section>
</main>

<button class="sticky-book-btn" onclick="document.getElementById('contact').scrollIntoView({behavior: 'smooth'});" aria-label="Book Now">Book Now</button>

<footer>
  <div class="social-links" aria-label="Social media links">
    <a href="https://www.facebook.com/share/1761Lv135m/" target="_blank" rel="noopener" tabindex="0" aria-label="Facebook"><img src="fb-logo.png" alt="Facebook"></a>
    <a href="https://www.instagram.com/maidzy11?igsh=MWdsOW1pbzk1ZnZyeQ==" target="_blank" rel="noopener" tabindex="0" aria-label="Instagram"><img src="insta-logo.png" alt="Instagram"></a>
    <a href="https://wa.me/918484925800" target="_blank" rel="noopener" tabindex="0" aria-label="WhatsApp"><img src="whatsapp-logo.png" alt="WhatsApp"></a>
  </div>
  <p>Phone: <a href="tel:+918484925800">+91 84849 25800</a> | Pune, Maharashtra, India</p>
  <p>&copy; 2025 Maidzy. All rights reserved.</p>
</footer>

<script>
  const scriptURL = 'https://script.google.com/macros/s/AKfycbyUJR1Xmms4U2LKgYwBcANC6nD3kb5klkZBnb-6CA94DEEkuwzrwNLAr-IbqYeGTaF4/exec';
  const form = document.querySelector('.contact-form');
  const formFeedback = document.getElementById('formFeedback');

  form.addEventListener('submit', e => {
    e.preventDefault();
    formFeedback.textContent = '';
    const phoneInput = form.phone.value.trim();
    if (!/^\d{10}$/.test(phoneInput)) {
      formFeedback.textContent = 'Please enter a valid 10-digit phone number.';
      form.phone.focus();
      return;
    }
    const formData = new FormData(form);

    // Basic anti-spam honeypot - invisible input added dynamically
    if(document.querySelector('input[name="honeypot"]')) {
      const hp = document.querySelector('input[name="honeypot"]').value;
      if(hp) {
        return; // Spam detected, do not submit
      }
    }

    fetch(scriptURL, { method: 'POST', body: formData })
      .then(response => {
        if (response.ok) {
          formFeedback.textContent = 'Thank you for contacting Maidzy. We will get back to you shortly.';
          form.reset();
        } else {
          formFeedback.textContent = 'There was a problem submitting your form. Please try again.';
        }
      })
      .catch(error => {
        formFeedback.textContent = 'Error submitting form. Please check your connection and try again.';
        console.error('Error!', error.message);
      });
  });
</script>
</body>
</html>
