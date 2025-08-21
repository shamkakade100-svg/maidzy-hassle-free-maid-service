<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maidzy | Hire Verified Maids in Pune</title>
  
  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">
  
  <style>
    body { font-family: 'Poppins', sans-serif; margin: 0; background:#fff; color:#1e293b; }

    /* Header with Logo */
    header { background:#fff; text-align:center; padding:20px; box-shadow: 0 2px 6px rgba(0,0,0,0.08); }
    .logo { display:flex; align-items:center; justify-content:center; gap:12px; }
    .brand { 
      font-family: 'Pacifico', cursive; 
      font-size: 42px; 
      background: linear-gradient(90deg, #ec4899, #8b5cf6); 
      -webkit-background-clip: text; 
      -webkit-text-fill-color: transparent; 
      text-shadow: 2px 2px 6px rgba(0,0,0,0.2); 
      margin:0;
    }

    /* Hero Section */
    .hero { 
      text-align:center; 
      padding:100px 20px; 
      background: linear-gradient(135deg, rgba(236,72,153,0.6), rgba(139,92,246,0.6)), 
                  url('https://images.unsplash.com/photo-1628851397632-7a3c7eca6e66?auto=format&fit=crop&w=1350&q=80') 
                  center/cover no-repeat; 
      color:white; 
    }
    .hero h1 { font-size:48px; margin-bottom:15px; font-weight:700; text-shadow: 1px 1px 6px rgba(0,0,0,0.6); }
    .hero p { font-size:20px; margin-bottom:30px; text-shadow: 1px 1px 6px rgba(0,0,0,0.6); }
    .cta { 
      background:white; 
      color:#ec4899; 
      padding:16px 36px; 
      border-radius:50px; 
      text-decoration:none; 
      font-weight:700; 
      font-size:18px;
      transition:0.3s; 
      box-shadow: 0 4px 10px rgba(0,0,0,0.2);
    }
    .cta:hover { background:#8b5cf6; color:white; }

    /* Services Section */
    .services { 
      display:grid; 
      grid-template-columns:repeat(auto-fit,minmax(220px,1fr)); 
      gap:25px; 
      padding:60px; 
      background:#fff0f6;
    }
    .card { 
      background:white; 
      padding:25px; 
      border-radius:20px; 
      box-shadow:0 6px 15px rgba(0,0,0,0.1); 
      text-align:center; 
      transition: transform 0.3s, box-shadow 0.3s; 
    }
    .card:hover { transform: translateY(-8px); box-shadow:0 8px 18px rgba(0,0,0,0.15); }
    .card h3 { margin-top:10px; color:#ec4899; font-size:22px; }

    /* Testimonials */
    .testimonials { 
      background:#fdf2f8; 
      padding:60px; 
      text-align:center; 
    }
    .testimonials h2 { color:#8b5cf6; font-size:32px; margin-bottom:20px; }
    .testimonials p { font-size:18px; margin:10px 0; color:#444; }

    /* Footer */
    .footer { 
      background:#1e1b4b; 
      color:#f9fafb; 
      text-align:center; 
      padding:20px; 
      font-size:14px;
    }
  </style>
</head>
<body>

  <!-- Brand Logo -->
  <header>
    <div class="logo">
      <!-- Maid Icon (SVG) -->
      <svg width="40" height="40" viewBox="0 0 24 24" fill="url(#grad)" xmlns="http://www.w3.org/2000/svg">
        <defs>
          <linearGradient id="grad" x1="0%" y1="0%" x2="100%" y2="0%">
            <stop offset="0%" style="stop-color:#ec4899;stop-opacity:1" />
            <stop offset="100%" style="stop-color:#8b5cf6;stop-opacity:1" />
          </linearGradient>
        </defs>
        <!-- Icon path: looks like maid’s head with apron -->
        <path d="M12 2C9.243 2 7 4.243 7 7v2H5v13h14V9h-2V7c0-2.757-2.243-5-5-5zM9 9V7c0-1.654 1.346-3 3-3s3 1.346 3 3v2H9z"/>
      </svg>
      <h1 class="brand">Maidzy</h1>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero">
    <h1>Hire Verified Maids in Pune</h1>
    <p>Daily Cleaning · Cooking · Babysitting · Elder Care</p>
    <a class="cta" href="https://wa.me/918796832083?text=Hi,%20I%20want%20to%20book%20a%20maid%20in%20Pune%20via%20Maidzy" target="_blank">📲 Book Now on WhatsApp</a>
  </section>

  <!-- Services -->
  <section class="services">
    <div class="card">
      <h3>🧹 Cleaning</h3>
      <p>Daily home cleaning, dusting, and mopping services.</p>
    </div>
    <div class="card">
      <h3>🍳 Cooking</h3>
      <p>Healthy & tasty meals prepared by skilled cooks.</p>
    </div>
    <div class="card">
      <h3>👶 Babysitting</h3>
      <p>Trustworthy babysitters to take care of your children.</p>
    </div>
    <div class="card">
      <h3>👵 Elder Care</h3>
      <p>Compassionate care for elderly family members.</p>
    </div>
  </section>

  <!-- Testimonials -->
  <section class="testimonials">
    <h2>💖 What Our Clients Say</h2>
    <p>"Maidzy helped me find a reliable maid within a day. Super smooth!"</p>
    <p>"Very professional, polite, and easy to book service."</p>
  </section>

  <!-- Footer -->
  <footer class="footer">
    © <script>document.write(new Date().getFullYear())</script> Maidzy | Built with 💕 in Pune
  </footer>

</body>
</html>
