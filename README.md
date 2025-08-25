<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Maidzy | Hire Verified Maids in Pune</title>

<section style="background:#ffe4f1; padding:20px; text-align:center; border-radius:12px; margin:20px;">
  <h2 style="color:#d63384;">Our Service Cost</h2>
  <p style="font-size:18px; margin:10px 0;">One-Time Registration Fee: <b>₹500</b></p>
  <p style="font-size:18px; margin:10px 0;">Monthly Service Charge: <b>₹300</b></p>
  <p style="color:#555;">Simple, Transparent, Hassle-Free Pricing</p>
</section>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@400;600;700&display=swap" rel="stylesheet">

  <!-- PWA Support -->
  <link rel="manifest" href="manifest.json">
  <meta name="theme-color" content="#ec4899">
  <link rel="icon" href="maidzy-icon.png" type="image/png">
  <header>
  <img src="maidzy-icon.png" alt="MAIDZY Logo" style="height:60px;">
  <h1>MAIDZY</h1>
</header>


  <style>
    body { font-family: 'Poppins', sans-serif; margin: 0; background:#fff; color:#1e293b; }

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

    .hero { 
      text-align:center; 
      padding:100px 20px; 
      background: linear-gradient(135deg, rgba(236,72,153,0.6), rgba(139,92,246,0.6)), 
                  url('maidzy-hero.jpg') 
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

    .form-section { padding:60px; text-align:center; background:#fdf2f8; }
    .form-section h2 { color:#ec4899; font-size:28px; margin-bottom:20px; }
    form { max-width:400px; margin:auto; text-align:left; }
    input, textarea { width:100%; padding:10px; margin:8px 0; border:1px solid #ccc; border-radius:6px; font-family:'Poppins',sans-serif; }
    button { background:#ec4899; color:white; padding:12px 20px; border:none; border-radius:6px; font-weight:bold; cursor:pointer; transition:0.3s; }
    button:hover { background:#8b5cf6; }

    #formStatus { margin-top:15px; font-weight:bold; }

    .footer { background:#1e1b4b; color:#f9fafb; text-align:center; padding:20px; font-size:14px; }
  </style>
</head>
<body>

  <header>
    <div class="logo">
      <img src="maidzy-icon.png" alt="Maidzy Logo" width="40" height="40">
      <h1 class="brand">Maidzy</h1>
    </div>
  </header>

  <section class="hero">
    <h1>Hire Verified Maids in Pune</h1>
    <p>Daily Cleaning · Cooking · Babysitting · More</p>
    <a class="cta" href="https://wa.me/918796832083?text=Hi,%20I%20want%20to%20book%20a%20maid%20via%20Maidzy" target="_blank">📲 Book on WhatsApp</a>
  </section>

  <section class="services">
    <div class="card">
      <h3>Cleaning</h3>
      <p>Daily dusting, mopping and deep cleaning services.</p>
    </div>
    <div class="card">
      <h3>Cooking</h3>
      <p>Healthy home-cooked meals tailored to your taste.</p>
    </div>
    <div class="card">
      <h3>Babysitting</h3>
      <p>Experienced nannies to take care of your loved ones.</p>
    </div>
    <div class="card">
      <h3>More Services</h3>
      <p>Washing, elderly care, part-time & full-time maids.</p>
    </div>
  </section>

  <!-- Enquiry Form -->
  <section class="form-section">
    <h2>📋 Book a Maid</h2>
    <p>Fill the form below and we’ll connect you to the right maid.</p>
    
    <form id="enquiryForm">
      <label>Name</label>
      <input type="text" name="name" required>
      <label>Phone</label>
      <input type="text" name="phone" required>
      <label>Requirement</label>
      <textarea name="requirement" required></textarea>
      <button type="submit">Submit</button>
    </form>

    <p id="formStatus"></p>
  </section>

  <footer class="footer">
    © <script>document.write(new Date().getFullYear())</script> Maidzy. All rights reserved.
  </footer>

  <!-- Service Worker -->
  <script>
    if ("serviceWorker" in navigator) {
      navigator.serviceWorker.register("/service-worker.js")
        .then(() => console.log("Service Worker Registered"));
    }
  </script>

  <!-- Enquiry Form Script -->
  <script>
  document.getElementById("enquiryForm").addEventListener("submit", function(e){
    e.preventDefault();
    const form = e.target;
    const data = {
      name: form.name.value,
      phone: form.phone.value,
      requirement: form.requirement.value
    };
    fetch("https://script.google.com/macros/s/AKfycbyGCeiAhaCof5FjpKGOQCFFIyXqm1aUj2lo5Ve94Y5ZkhOBOvoFwNaFpVnnfEirfCsG/exec", {
      method: "POST",
      body: JSON.stringify(data)
    })
    .then(res => res.text())
    .then(() => {
      document.getElementById("formStatus").innerText = "✅ Enquiry submitted!";
      form.reset();
    })
    .catch(() => {
      document.getElementById("formStatus").innerText = "❌ Error, try again.";
    });
  });
  </script>

</body>
</html>

