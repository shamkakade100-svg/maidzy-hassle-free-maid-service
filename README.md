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
      background-color: #ffe6f0;
    }

    header {
      background-color: #ff4da6;
      padding: 20px;
      text-align: center;
    }

    header img {
      height: 120px; /* Doubled size */
    }

    h1 {
      text-align: center;
      color: #e91e63;
      margin-top: 20px;
    }

    .services {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
      padding: 40px;
      text-align: center;
    }

    .service {
      background: white;
      border-radius: 10px;
      padding: 20px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
    }

    .form-container {
      display: flex;
      justify-content: center;
      margin: 40px 0;
    }

    form {
      background: white;
      padding: 30px;
      border-radius: 10px;
      box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
      width: 100%;
      max-width: 400px;
    }

    form input, form select, form button {
      width: 100%;
      padding: 12px;
      margin: 10px 0;
      border-radius: 5px;
      border: 1px solid #ccc;
      font-size: 16px;
    }

    form button {
      background-color: #ff4da6;
      color: white;
      font-weight: bold;
      cursor: pointer;
      border: none;
      transition: background 0.3s;
    }

    form button:hover {
      background-color: #e91e63;
    }

    #responseMessage {
      margin-top: 20px;
      text-align: center;
    }

    footer {
      background-color: #ff4da6;
      color: white;
      text-align: center;
      padding: 15px;
      margin-top: 40px;
    }

    /* Floating Buttons */
    .floating-buttons {
      position: fixed;
      bottom: 20px;
      right: 20px;
      display: flex;
      flex-direction: column;
      gap: 15px;
      z-index: 999;
    }

    .floating-buttons a {
      display: flex;
      align-items: center;
      justify-content: center;
      width: 55px;
      height: 55px;
      border-radius: 50%;
      background: #25d366; /* WhatsApp Green */
      color: white;
      font-size: 26px;
      text-decoration: none;
      box-shadow: 0 3px 10px rgba(0,0,0,0.3);
      transition: transform 0.3s;
    }

    .floating-buttons a.call {
      background: #34b7f1; /* Blue for Call */
    }

    .floating-buttons a:hover {
      transform: scale(1.1);
    }
  </style>
  <!-- Font Awesome for Icons -->
  <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
</head>
<body>

  <!-- Header -->
  <header>
    <img src="maidzy-icon.png" alt="Maidzy Logo">
  </header>

  <!-- Hero Text -->
  <h1>Hire Trusted & Verified Maids in Pune</h1>
  <p style="text-align:center; color:#d81b60; font-weight:bold;">
    Daily Cleaning · Cooking · Babysitting · Elder Care · More
  </p>

  <!-- Services Section -->
  <section class="services">
    <div class="service">
      <h3>Daily Cleaning</h3>
      <p>Keep your home sparkling clean with our professional cleaning maids.</p>
    </div>
    <div class="service">
      <h3>Cooking</h3>
      <p>Skilled cooks to prepare delicious and hygienic meals for your family.</p>
    </div>
    <div class="service">
      <h3>Babysitting</h3>
      <p>Reliable babysitters who care for your little ones with love.</p>
    </div>
    <div class="service">
      <h3>Elder Care</h3>
      <p>Compassionate helpers to take care of senior family members.</p>
    </div>
  </section>

  <!-- Enquiry Form -->
  <div class="form-container">
    <form id="enquiryForm">
      <input type="text" name="name" placeholder="Full Name" required>
      <input type="text" name="phone" placeholder="Phone Number" required>
      <input type="text" name="location" placeholder="Location" required>
      <select name="service" required>
        <option value="">Select Service</option>
        <option value="Cleaning">Cleaning</option>
        <option value="Cooking">Cooking</option>
        <option value="Babysitting">Babysitting</option>
        <option value="Elder Care">Elder Care</option>
      </select>
      <button type="submit">Submit Request</button>
    </form>
  </div>

  <!-- Response Message -->
  <div id="responseMessage"></div>

  <!-- Footer -->
  <footer>
    © 2025 MAIDZY. All Rights Reserved.
  </footer>

  <!-- Floating Contact Buttons -->
  <div class="floating-buttons">
    <!-- WhatsApp -->
    <a href="https://wa.me/918796832083" target="_blank" title="Chat on WhatsApp">
      <i class="fab fa-whatsapp"></i>
    </a>
    <!-- Call -->
    <a href="tel:+918796832083" class="call" title="Call Us">
      <i class="fas fa-phone-alt"></i>
    </a>
  </div>

  <!-- Script -->
  <script>
    const scriptURL = "https://script.google.com/macros/s/AKfycbwHAwuKXMDZtAh7r1i4Clsx2JtAixN6BdlIZ-sx3_-Hp-vUmTAcm0vDU_u8_jI7o8A/exec";
    const form = document.getElementById("enquiryForm");
    const btn = form.querySelector("button[type=submit]");
    const responseMessage = document.getElementById("responseMessage");

    form.addEventListener("submit", e => {
      e.preventDefault();
      btn.disabled = true;
      btn.innerText = "Submitting...";

      const formData = new FormData(form);

      fetch(scriptURL, { method: "POST", body: formData })
        .then(response => {
          form.style.display = "none";
          responseMessage.innerHTML = `
            <div style="padding:20px; background:#fff; border-radius:10px; box-shadow:0 2px 8px rgba(0,0,0,0.1); text-align:center;">
              <h2 style="color:#e91e63;">✅ Thank you!</h2>
              <p>Your request has been submitted successfully. Our team will contact you shortly.</p>
            </div>
          `;
        })
        .catch(error => {
          btn.disabled = false;
          btn.innerText = "Submit Request";
          responseMessage.innerHTML = `<p style="color:red;">❌ Something went wrong, please try again.</p>`;
          console.error("Error!", error.message);
        });
    });
  </script>

</body>
</html>
