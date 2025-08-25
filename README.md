<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>MAIDZY | Hassle-Free Maid Service</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #ffe6f2;
      text-align: center;
    }

    header {
      background-color: #ff4da6;
      padding: 15px;
    }

    header img {
      height: 120px; /* big logo */
    }

    h1 {
      color: #e60073;
    }

    p {
      color: #333;
    }

    .services {
      background-color: #ffb3d9; /* darker pink */
      padding: 40px 20px;
      border-radius: 15px;
      margin: 20px auto;
      max-width: 900px;
    }

    .services h2 {
      font-size: 28px;
      margin-bottom: 20px;
      color: #99004d;
    }

    .service-list {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
      gap: 20px;
    }

    .service-item {
      background: #fff;
      padding: 20px;
      border-radius: 12px;
      font-size: 18px;
      font-weight: bold;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      transition: transform 0.2s;
    }

    .service-item:hover {
      transform: scale(1.05);
      background: #ffe6f7;
    }

    .form-container {
      background: white;
      padding: 20px;
      margin: 20px auto;
      max-width: 400px;
      border-radius: 10px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.2);
    }

    input, select, button {
      width: 90%;
      padding: 10px;
      margin: 8px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
    }

    button {
      background-color: #ff4da6;
      color: white;
      font-size: 16px;
      cursor: pointer;
    }

    button:hover {
      background-color: #e60073;
    }

    footer {
      background: #ff4da6;
      color: white;
      padding: 15px;
      margin-top: 20px;
    }

    .contact-icons {
      margin-top: 15px;
    }

    .contact-icons a img {
      height: 45px;
      margin: 0 10px;
      vertical-align: middle;
    }
  </style>
</head>
<body>

  <header>
    <img src="maidzy-icon.png" alt="Maidzy Logo">
  </header>

  <h1>Hire Trusted & Verified Maids in Pune</h1>
  <p>Daily Cleaning · Cooking · Babysitting · Elder Care · More</p>

  <!-- Services Section -->
  <section class="services">
    <h2>✨ Our Services</h2>
    <div class="service-list">
      <div class="service-item">🧹 Daily Cleaning</div>
      <div class="service-item">🍳 Cooking</div>
      <div class="service-item">👶 Babysitting</div>
      <div class="service-item">👵 Elder Care</div>
      <div class="service-item">🧼 Deep Cleaning</div>
      <div class="service-item">🐶 Pet Care</div>
    </div>
  </section>

  <!-- Enquiry Form -->
  <div class="form-container">
    <form id="enquiryForm">
      <input type="text" name="name" placeholder="Your Name" required><br>
      <input type="tel" name="phone" placeholder="Phone Number" required><br>
      <input type="text" name="location" placeholder="Location" required><br>
      <select name="service" required>
        <option value="">Select Service</option>
        <option value="Cleaning">Cleaning</option>
        <option value="Cooking">Cooking</option>
        <option value="Babysitting">Babysitting</option>
        <option value="Elder Care">Elder Care</option>
        <option value="Deep Cleaning">Deep Cleaning</option>
        <option value="Pet Care">Pet Care</option>
      </select><br>
      <button type="submit">Submit Request</button>
    </form>
  </div>

  <footer>
    <p>© 2025 MAIDZY. All Rights Reserved.</p>
    <div class="contact-icons">
      <a href="https://wa.me/919876543210" target="_blank">
        <img src="whatsapp-logo.png" alt="WhatsApp">
      </a>
      <a href="tel:+919876543210">
        <img src="call-logo.png" alt="Call Us">
      </a>
    </div>
  </footer>

  <script>
    const scriptURL = "https://script.google.com/macros/s/AKfycbwHAwuKXMDZtAh7r1i4Clsx2JtAixN6BdlIZ-sx3_-Hp-vUmTAcm0vDU_u8_jI7o8A/exec";
    const form = document.getElementById("enquiryForm");

    form.addEventListener("submit", e => {
      e.preventDefault();
      fetch(scriptURL, { method: "POST", body: new FormData(form)})
      .then(() => {
        alert("✅ Thank you! Your request has been submitted.");
        form.reset();
      })
      .catch(error => alert("❌ Error: " + error.message));
    });
  </script>

</body>
</html>
