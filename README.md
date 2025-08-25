<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>MAIDZY | Trusted Maid Services in Pune</title>
  <meta name="description" content="Hire verified maids in Pune with Maidzy. Trusted, fully verified housekeeping, cooking, babysitting, elder care, and deep cleaning professionals." />
  <meta name="keywords" content="maid service Pune, housekeeping Pune, babysitting Pune, elder care Pune, cooking service Pune, deep cleaning Pune" />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700&family=Open+Sans&display=swap" rel="stylesheet" />
  <link rel="icon" href="maidzy-icon.png" type="image/png" />
  <style>
    /* Reset base */
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
    a:hover, a:focus {
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

    /* Animated glowing pulsing logo */
    @keyframes logoPulse {
      0%, 100% { transform: scale(1); filter: drop-shadow(0 0 5px #ff66b2);}
      50% { transform: scale(1.1); filter: drop-shadow(0 0 15px #ff3399);}
    }
    header img.brand-logo {
      height: 110px;
      border-radius: 12px;
      animation: logoPulse 4s ease-in-out infinite;
      margin-right: 16px;
      transition: transform 0.3s ease;
    }
    header img.brand-logo:hover,
    header img.brand-logo:focus {
      transform: scale(1.15);
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

    /* Hero Section */
    .hero-section {
      max-width: 800px;
      padding: 60px 20px 40px 20px;
      margin: 0 auto;
      text-align: center;
    }
    /* Animated title with fade, slide and subtle hue shift */
    @keyframes fadeSlideIn {
      0% { opacity: 0; transform: translateY(-20px); }
      100% { opacity: 1; transform: translateY(0); }
    }
    @keyframes hueShift {
      0% { filter: hue-rotate(0deg);}
      50% { filter: hue-rotate(20deg);}
      100% { filter: hue-rotate(0deg);}
    }
    .hero-headline {
      font-family: 'Montserrat', sans-serif;
      font-size: 3rem;
      font-weight: 700;
      margin-bottom: 16px;
      color: #d6006e;
      animation: fadeSlideIn 1s ease forwards, hueShift 6s ease-in-out infinite;
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
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      transition: background 0.3s ease, box-shadow 0.3s ease;
    }
    .cta-btn:hover, .cta-btn:focus {
      background: linear-gradient(90deg, #cc2a6e, #ff85b5);
      box-shadow: 0 8px 16px rgba(255, 51, 153, 0.55);
      outline: none;
    }
    .cta-btn.secondary {
      background: #fff;
      color: #ff3399;
      border: 2.7px solid #ff3399;
    }
    .cta-btn.secondary:hover, .cta-btn.secondary:focus {
      color: #cc2a6e;
      border-color: #cc2a6e;
      text-decoration: none;
      outline: none;
    }

    /* ... The rest CSS same as previous versions for services, testimonials, form, footer etc ... */

  </style>
</head>
<body>
  <header>
    <div class="brand-row">
      <img src="maidzy-icon.png" class="brand-logo" alt="Maidzy Logo" />
      <span class="site-title">MAIDZY – Maid Services in Pune</span>
    </div>
    <div class="top-icons">
      <a href="https://wa.me/918796832083" target="_blank" rel="noopener noreferrer" aria-label="Chat on WhatsApp"><img src="whatsapp-logo.png" alt="WhatsApp Logo" /></a>
      <a href="tel:+918796832083" aria-label="Call Us"><img src="call-logo.png" alt="Call Icon" /></a>
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

  <!-- Add the rest of your website content (services, testimonials, form, footer) here, as before -->

  <script>
    // JS as in previous versions (accordion, testimonial carousel, form submission with loading state etc.)
  </script>
</body>
</html>
