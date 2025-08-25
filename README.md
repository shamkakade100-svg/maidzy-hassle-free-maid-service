<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MAIDZY | Trusted Maid Services in Pune</title>
  <meta name="description"
    content="Hire verified maids in Pune with Maidzy. Trusted, fully verified housekeeping, cooking, babysitting, elder care, and deep cleaning professionals." />
  <meta name="keywords"
    content="maid service Pune, housekeeping Pune, babysitting Pune, elder care Pune, cooking service Pune, deep cleaning Pune" />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&display=swap" rel="stylesheet" />
  <link rel="icon" href="maidzy-icon.png" type="image/png" />
  <style>
    /* Reset and base */
    * {
      box-sizing: border-box;
      scroll-behavior: smooth;
    }

    body {
      margin: 0;
      font-family: 'Open Sans', sans-serif;
      background: #fff0f6;
      color: #4b235a;
      line-height: 1.5;
    }

    a {
      color: #ff3380;
      text-decoration: none;
      transition: color 0.3s ease;
    }

    a:hover,
    a:focus {
      color: #cc2a6e;
      outline: none;
    }

    /* Header */
    header {
      position: sticky;
      top: 0;
      background: linear-gradient(90deg, #ff3399, #ff66b2);
      display: flex;
      align-items: center;
      justify-content: space-between;
      padding: 12px 24px;
      box-shadow: 0 3px 8px rgba(255, 51, 153, 0.2);
      z-index: 1000;
      transition: background 0.3s ease;
    }

    /* Increased logo size */
    header img.brand-logo {
      height: 110px;
      border-radius: 12px;
      transition: transform 0.3s ease;
      margin-right: 16px;
    }

    header img.brand-logo:hover,
    header img.brand-logo:focus {
      transform: scale(1.1);
      outline: none;
    }

    .top-icons a img {
      width: 36px;
      height: 36px;
      border-radius: 50%;
      background: #fff;
      padding: 3px;
      box-shadow: 0 2px 10px #ffcde2;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .top-icons a img:hover,
    .top-icons a img:focus {
      transform: scale(1.2);
      box-shadow: 0 4px 14px #ff95bb;
      outline: none;
    }

    /* Hero */
    .hero-section {
      max-width: 800px;
      padding: 60px 20px;
      margin: 0 auto;
      text-align: center;
      animation: fadeSlideDown 0.9s ease forwards;
      opacity: 0;
      transform: translateY(-20px);
    }

    @keyframes fadeSlideDown {
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }

    .hero-headline {
      font-family: 'Montserrat', sans-serif;
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 16px;
      color: #d6006e;
    }

    .hero-sub {
      font-size: 1.17rem;
      margin-bottom: 28px;
      max-width: 680px;
      margin-left: auto;
      margin-right: auto;
      color: #661a55;
    }

    .cta-bar {
      display: flex;
      gap: 20px;
      justify-content: center;
      flex-wrap: wrap;
    }

    .cta-btn {
      background: linear-gradient(90deg, #ff3399, #ff66b2);
      border: none;
      border-radius: 25px;
      padding: 16px 36px;
      color: #fff;
      font-weight: 700;
      font-size: 1.1rem;
      cursor: pointer;
      box-shadow: 0 6px 12px rgba(255, 51, 153, 0.35);
      box-sizing: content-box;
      transition: background 0.3s ease, box-shadow 0.3s ease;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      justify-content: center;
    }

    .cta-btn:hover,
    .cta-btn:focus {
      background: linear-gradient(90deg, #cc2a6e, #ff85b5);
      box-shadow: 0 8px 16px rgba(255, 51, 153, 0.55);
      outline: none;
    }

    .cta-btn.secondary {
      background: #fff;
      color: #ff3399;
      border: 2.7px solid #ff3399;
    }

    .cta-btn.secondary:hover,
    .cta-btn.secondary:focus {
      color: #cc2a6e;
      border-color: #cc2a6e;
      text-decoration: none;
      outline: none;
    }

    /* Services */
    .services-section {
      max-width: 880px;
      margin: 50px auto 80px;
      background: #fff;
      border-radius: 20px;
      padding: 42px 32px;
      box-shadow: 0 4px 20px rgba(198, 131, 141, 0.14);
    }

    .services-title {
      font-family: 'Montserrat', sans-serif;
      font-size: 2.28rem;
      font-weight: 600;
      color: #bf1d66;
      margin-bottom: 36px;
      text-align: center;
    }

    .service-card {
      background: #ffe6f0;
      border-radius: 18px;
      padding: 30px 25px 22px;
      box-shadow: 0 2px 12px rgba(255, 179, 202, 0.45);
      margin-bottom: 20px;
      cursor: pointer;
      transition: box-shadow 0.25s ease, background 0.25s ease;
      outline: none;
      display: flex;
      align-items: flex-start;
      gap: 20px;
    }

    .service-card:hover,
    .service-card:focus {
      background: #ffd6eb;
      box-shadow: 0 6px 28px rgba(255, 102, 178, 0.5);
      outline-offset: 4px;
    }

    .service-emoji {
      font-size: 2.6rem;
      user-select: none;
      flex-shrink: 0;
    }

    .service-info {
      flex-grow: 1;
    }

    .service-title {
      font-weight: 700;
      font-size: 1.3rem;
      margin-bottom: 8px;
    }

    .service-desc {
      font-size: 1rem;
      line-height: 1.5;
      margin: 0;
      color: #722e62;
    }

    /* Testimonials */
    .testimonials-section {
      max-width: 720px;
      margin: 0 auto 70px;
      padding: 30px 20px;
      background: #fff;
      border-radius: 20px;
      box-shadow: 0 6px 22px rgba(255, 51, 153, 0.18);
      text-align: center;
      font-style: italic;
      color: #5b2e57;
      position: relative;
      overflow: hidden;
    }

    .testimonials-title {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 2.1rem;
      color: #d6006e;
      margin-bottom: 25px;
    }

    .testimonial-item {
      opacity: 0;
      transform: translateY(30px);
      transition: opacity 0.6s ease, transform 0.6s ease;
      position: absolute;
      top: 60px;
      left: 50%;
      transform-origin: center;
      max-width: 600px;
      padding: 0 20px;
      box-sizing: border-box;
      user-select: none;
    }

    .testimonial-item.active {
      opacity: 1;
      transform: translateX(-50%) translateY(0);
      position: relative;
    }

    .testimonial-stars {
      color: gold;
      font-size: 1.4rem;
      margin-bottom: 12px;
      user-select: none;
    }

    .testimonial-author {
      font-weight: 700;
      font-style: normal;
      font-size: 1.1rem;
      margin-top: 10px;
      color: #af2664;
    }

    /* Contact Form */
    .form-section {
      max-width: 420px;
      margin: 0 auto 70px;
      background: #fff0f6;
      padding: 40px 32px;
      border-radius: 24px;
      box-shadow: 0 5px 25px rgba(255, 51, 153, 0.18);
    }

    .form-title {
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 2rem;
      color: #bf1d66;
      margin-bottom: 28px;
      text-align: center;
    }

    form input,
    form select {
      width: 100%;
      padding: 14px 18px;
      margin-bottom: 20px;
      border: 1.5px solid #d7a7c0;
      border-radius: 10px;
      font-size: 1.03rem;
      font-family: 'Open Sans', sans-serif;
      transition: border-color 0.3s ease;
      color: #5b3362;
    }

    form input:focus,
    form select:focus {
      border-color: #ff3399;
      outline: none;
      box-shadow: 0 0 10px #ffb0d0aa;
    }

    form button {
      width: 100%;
      background: linear-gradient(90deg, #ff3399, #ff66b2);
      border: none;
      padding: 16px;
      font-family: 'Montserrat', sans-serif;
      font-weight: 700;
      font-size: 1.2rem;
      color: white;
      border-radius: 30px;
      cursor: pointer;
      box-shadow: 0 5px 18px rgba(255, 51, 153, 0.45);
      transition: background 0.3s ease;
      user-select: none;
    }

    form button:hover,
    form button:focus {
      background: linear-gradient(90deg, #cc2a6e, #ff85b5);
      outline: none;
    }

    form button.loading {
      cursor: wait;
      opacity: 0.7;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 20px 12px;
      background: linear-gradient(90deg, #ff3399, #ff66b2);
      color: white;
      font-weight: 600;
      font-family: 'Montserrat', sans-serif;
      font-size: 1rem;
      border-radius: 0 0 20px 20px;
    }

    footer a {
      color: #ffe0f0;
      text-decoration: underline;
    }

    footer a:hover,
    footer a:focus {
      color: #fff;
      outline: none;
    }


    /* Responsive */
    @media (max-width: 640px) {
      .hero-headline {
        font-size: 2.1rem;
      }

      .services-section {
        padding: 30px 20px;
      }

      .testimonial-item {
        max-width: 90%;
        left: 5%;
        transform: translateY(0);
      }

      header {
        padding: 20px;
      }

      .form-section {
        padding: 30px 22px;
      }
    }

    /* Footer smaller icons */
    .form-section .contact-info a img {
      width: 18px;
      height: 18px;
      margin-right: 6px;
      vertical-align: middle;
    }

    .form-section .contact-info {
      gap: 14px;
      font-size: 1rem;
    }
  </style>
</head>

<body>
  <header>
    <div class="brand-row">
      <img src="maidzy-icon.png" class="brand-logo" alt="Maidzy Logo" />
      <span class="site-title">MAIDZY – Maid Services in Pune</span>
    </div>
    <div class="top-icons">
      <a href="https://wa.me/918796832083" target="_blank" rel="noopener noreferrer" aria-label="Chat on WhatsApp">
        <img src="whatsapp-logo.png" alt="WhatsApp Logo" />
      </a>
      <a href="tel:+918796832083" aria-label="Call Us">
        <img src="call-logo.png" alt="Call Icon" />
      </a>
    </div>
  </header>

  <section class="hero-section" role="banner">
    <h1 class="hero-headline">Trusted & Verified Maid Services in Pune</h1>
    <p class="hero-sub">On-demand cleaning, cooking, babysitting, and elder care with fully screened, local, and reliable professionals. Fast booking and dedicated customer support.</p>
    <div class="cta-bar" role="navigation" aria-label="Call to action buttons">
      <a href="#enquiryFormReal" class="cta-btn">Book Your Maid Today</a>
      <a href="tel:+918796832083" class="cta-btn secondary">Call 8796832083</a>
    </div>
    <div style="font-size:.98em; color:#aa1e77;">
      <img src="whatsapp-logo.png" alt="WhatsApp" style="height:20px;vertical-align:middle;" /> Chat on WhatsApp: <strong>8796832083</strong>
    </div>
  </section>

  <section class="services-section" aria-label="Our Services">
    <h2 class="services-title">Our Services</h2>
    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="cleaning-desc" role="region"
      aria-label="Daily Home Cleaning">
      <div class="service-emoji" aria-hidden="true">🧹</div>
      <div class="service-info">
        <h3 class="service-title">Daily Home Cleaning</h3>
        <p id="cleaning-desc" class="service-desc">Routine sweeping, mopping, dusting for all rooms. Flexible timing, eco-safe products, and polite housekeepers ensure a sparkling home every day.</p>
      </div>
    </article>

    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="cooking-desc" role="region" aria-label="Cooking">
      <div class="service-emoji" aria-hidden="true">🍳</div>
      <div class="service-info">
        <h3 class="service-title">Cooking</h3>
        <p id="cooking-desc" class="service-desc">Home-style cooking for all cuisines, including veg and non-veg, breakfast, lunch, and dinner. Recipe customization and grocery help available.</p>
      </div>
    </article>

    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="babysitting-desc" role="region"
      aria-label="Babysitting and Childcare">
      <div class="service-emoji" aria-hidden="true">👶</div>
      <div class="service-info">
        <h3 class="service-title">Babysitting & Childcare</h3>
        <p id="babysitting-desc" class="service-desc">Experienced, vetted babysitters for infants and children. Includes feeding, playing, homework support, and hygiene.</p>
      </div>
    </article>

    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="eldercare-desc" role="region"
      aria-label="Elder Care">
      <div class="service-emoji" aria-hidden="true">👵</div>
      <div class="service-info">
        <h3 class="service-title">Elder Care</h3>
        <p id="eldercare-desc" class="service-desc">Compassionate elder care including bathing, meal prep, light exercise, and companionship. On-demand nurse care available.</p>
      </div>
    </article>

    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="deepclean-desc" role="region"
      aria-label="Deep Cleaning">
      <div class="service-emoji" aria-hidden="true">🧼</div>
      <div class="service-info">
        <h3 class="service-title">Deep Cleaning</h3>
        <p id="deepclean-desc" class="service-desc">Festive or move-in/out deep cleaning including sofa, carpet, kitchen degreasing, bathroom sanitization with advanced equipment.</p>
      </div>
    </article>

    <article class="service-card" tabindex="0" aria-expanded="false" aria-controls="housekeeping-desc" role="region"
      aria-label="Housekeeping and Pantry">
      <div class="service-emoji" aria-hidden="true">🛋️</div>
      <div class="service-info">
        <h3 class="service-title">Housekeeping + Pantry</h3>
        <p id="housekeeping-desc" class="service-desc">Complete household management: organizing, laundry, ironing, errands, and pantry services for families, bachelors, and offices.</p>
      </div>
    </article>
  </section>

  <section class="testimonials-section" aria-label="Client Testimonials">
    <h2 class="testimonials-title">What Our Clients Say</h2>
    <div id="testimonialCarousel" role="list">
      <blockquote class="testimonial-item active" role="listitem">
        <div class="testimonial-stars" aria-hidden="true">⭐⭐⭐⭐⭐</div>
        <p>"Maidzy helped me find a caring, punctual maid – started within 24 hours. Highly recommend!"</p>
        <footer class="testimonial-author">- Priya S.</footer>
      </blockquote>
      <blockquote class="testimonial-item" role="listitem">
        <div class="testimonial-stars" aria-hidden="true">⭐⭐⭐⭐⭐</div>
        <p>"Got professional, polite staff for my parents. Great support from the Maidzy team."</p>
        <footer class="testimonial-author">- Ramesh K.</footer>
      </blockquote>
      <blockquote class="testimonial-item" role="listitem">
        <div class="testimonial-stars" aria-hidden="true">⭐⭐⭐⭐⭐</div>
        <p>"Quick booking & thorough background checks gave me peace of mind."</p>
        <footer class="testimonial-author">- Neha M.</footer>
      </blockquote>
      <blockquote class="testimonial-item" role="listitem">
        <div class="testimonial-stars" aria-hidden="true">⭐⭐⭐⭐⭐</div>
        <p>"Booking via WhatsApp was simple & Maidzy responded quickly. The maid is respectful and skilled."</p>
        <footer class="testimonial-author">- Vinayak D.</footer>
      </blockquote>
      <blockquote class="testimonial-item" role="listitem">
        <div class="testimonial-stars" aria-hidden="true">⭐⭐⭐⭐⭐</div>
        <p>"Our babysitter handles our kids' routines wonderfully. Super happy!"</p>
        <footer class="testimonial-author">- Farah P.</footer>
      </blockquote>
    </div>
  </section>

  <section class="form-section" id="enquiryFormReal" aria-label="Enquiry Form">
    <h2 class="form-title">Request a Maid in Pune</h2>
    <p style="color:#7c417a; margin-bottom:15px;">
      Fill the form below – Our team will call within 30 minutes during working hours!<br />
      For instant help, <a href="tel:+918796832083" class="contact-link" style="color:#ff7bb5;font-weight:700;">Call 8796832083</a> or
      <a href="https://wa.me/918796832083" class="contact-link" style="color:green;font-weight:700;">WhatsApp</a>
    </p>
    <form id="enquiryFormRealForm" novalidate>
      <input id="name" name="name" type="text" placeholder="Full Name" required aria-required="true" />
      <input id="phone" name="phone" type="tel" placeholder="Phone Number" maxlength="12" required aria-required="true"
        pattern="[0-9\s+-]{6,12}" />
      <input id="location" name="location" type="text" placeholder="Your Area in Pune" required aria-required="true" />
      <select id="service" name="service" required aria-required="true">
        <option value="">Select Service Needed</option>
        <option>Daily Cleaning</option>
        <option>Cooking</option>
        <option>Babysitting</option>
        <option>Elder Care</option>
        <option>Deep Cleaning</option>
        <option>Housekeeping</option>
      </select>
      <button type="submit">Submit Request</button>
    </form>
    <div class="contact-info" style="margin-top:18px;">
      <a href="tel:+918796832083" class="contact-link"><img src="call-logo.png" alt="Call icon" /> +91 8796832083</a>
      <a href="https://wa.me/918796832083" target="_blank" class="contact-link"><img src="whatsapp-logo.png" alt="WhatsApp icon" /> Chat on WhatsApp</a>
      <span style="color:#c2185b;margin-left:14px;">Working Hours: 9am–9pm, All Days</span>
    </div>
  </section>

  <footer>
    &copy; 2025 Maidzy. All Rights Reserved. | <a href="privacy-policy.html" style="color:#ff82bd; text-decoration:none;">Privacy Policy</a>
  </footer>

  <script>
    // Accordion accessibility toggling
    document.querySelectorAll('.service-card').forEach(card => {
      card.addEventListener('click', () => {
        const expanded = card.getAttribute('aria-expanded') === 'true';
        document.querySelectorAll('.service-card').forEach(c => {
          c.setAttribute('aria-expanded', 'false');
          c.querySelector('.service-desc').style.display = 'none';
        });
        if (!expanded) {
          card.setAttribute('aria-expanded', 'true');
          card.querySelector('.service-desc').style.display = 'block';
        }
      });
      card.addEventListener('keydown', e => {
        if (e.key === 'Enter' || e.key === ' ') {
          e.preventDefault();
          card.click();
        }
      });
    });

    // Testimonials carousel
    const testimonials = document.querySelectorAll('.testimonial-item');
    let testimonialIndex = 0;
    function showTestimonial(i) {
      testimonials.forEach((t, idx) => {
        t.classList.toggle('active', idx === i);
      });
    }
    showTestimonial(testimonialIndex);
    setInterval(() => {
      testimonialIndex = (testimonialIndex + 1) % testimonials.length;
      showTestimonial(testimonialIndex);
    }, 7000);

    // Sticky CTA for mobile
    const stickyCTA = document.querySelector('.sticky-cta-bar');
    function handleStickyCTA() {
      stickyCTA.style.display = window.innerWidth <= 680 ? 'flex' : 'none';
    }
    window.addEventListener('resize', handleStickyCTA);
    window.addEventListener('DOMContentLoaded', handleStickyCTA);

    // Form submission handler with validation and loading state
    const form = document.getElementById('enquiryFormRealForm');
    const scriptURL = 'https://script.google.com/macros/s/AKfycbzwi2Kh3A8tnWOipqZ2TV0yALUc-c9NFT7_LumjQcRUmSs4Q-OyvC_39Hu_M4lLQi0j/exec';

    form.addEventListener('submit', e => {
      e.preventDefault();

      if (!form.checkValidity()) {
        alert('Please fill all required fields correctly.');
        return;
      }

      const btn = form.querySelector('button[type="submit"]');
      btn.disabled = true;
      btn.classList.add('loading');
      btn.textContent = 'Submitting...';

      fetch(scriptURL, { method: 'POST', body: new FormData(form) })
        .then(response => {
          if (response.ok) {
            alert('✅ Success! Your enquiry has been submitted.');
            form.reset();
          } else {
            alert('⚠️ Submission failed. Please try again later.');
          }
        })
        .catch(err => alert('⚠️ Error: ' + err.message))
        .finally(() => {
          btn.disabled = false;
          btn.classList.remove('loading');
          btn.textContent = 'Submit Request';
        });
    });
  </script>
</body>

</html>
