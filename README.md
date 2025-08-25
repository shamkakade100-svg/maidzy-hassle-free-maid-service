<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Hire Verified Maids in Pune | MAIDZY</title>
  <meta name="description" content="Maidzy - Trusted Maid Services in Pune. Hire verified maids for cleaning, cooking, babysitting, elder care, and housekeeping. Quick booking, safe, and professional." />
  <meta name="keywords" content="maid service Pune, cook Pune, babysitter Pune, caretaker Pune, house help Maharashtra, verified maids Pune" />
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@700;500&family=Inter:wght@400;600&display=swap" rel="stylesheet" />
  <link rel="icon" type="image/png" href="maidzy-icon.png" />
  <style>
    /* Same styles as previous with minor adjustments */
    /* ... (use the same styling from the last full site code provided) */
    /* For brevity, replicate the full CSS from previous response here */
  </style>
</head>
<body>
  <!-- Header Section -->
  <header>
    <div class="brand-row">
      <img src="maidzy-icon.png" class="brand-logo" alt="Maidzy Logo" />
      <span class="site-title">MAIDZY – Maid Services in Pune</span>
    </div>
    <div class="top-icons">
      <a href="https://wa.me/918796832083" target="_blank" aria-label="WhatsApp Chat"><img src="whatsapp-logo.png" alt="WhatsApp Logo" /></a>
      <a href="tel:+918796832083" aria-label="Call Us"><img src="call-logo.png" alt="Call Icon" /></a>
    </div>
  </header>

  <!-- Hero Section -->
  <section class="hero-section" role="banner">
    <h1 class="hero-headline">Trusted & Verified Maid Services in Pune</h1>
    <p class="hero-sub">On-demand cleaning, cooking, babysitting, and elder care with fully screened, local, and reliable professionals. Fast booking and dedicated customer support.</p>
    <div class="cta-bar" role="navigation" aria-label="Call to action buttons">
      <a href="#enquiryFormRealForm" class="cta-btn">Book Your Maid Today</a>
      <a href="tel:+918796832083" class="cta-btn" style="background:#fff;color:#ff1097;border:1.5px solid #ff1199;">Call 8796832083</a>
    </div>
    <div style="font-size:.98em; color:#aa1e77;">
      <img src="whatsapp-logo.png" alt="WhatsApp" style="height:20px;vertical-align:middle;" /> Chat on WhatsApp: <strong>8796832083</strong>
    </div>
  </section>

  <!-- Sticky CTA Mobile -->
  <div class="sticky-cta-bar" aria-hidden="true" style="display:none;">
    <a href="#enquiryFormRealForm" class="sticky-cta-btn">Book Maid Now &rarr;</a>
  </div>

  <!-- Why Choose Us -->
  <section class="why-section" aria-label="Why choose Maidzy">
    <h2 class="why-title">Why Choose Maidzy?</h2>
    <div class="why-features">
      <!-- same boxes -->
    </div>
  </section>

  <!-- Services Section -->
  <section class="services-section" aria-label="Our Services">
    <h2 class="services-title">Our Services</h2>
    <div class="service-accordion" id="serviceAccordion" role="list">
      <!-- same service cards -->
    </div>
  </section>

  <!-- Testimonials -->
  <section class="testimonials-section" aria-label="Client Testimonials">
    <h2 class="testimonials-title">What Our Clients Say</h2>
    <div class="testimonial-carousel" id="testimonialCarousel" role="list">
      <!-- same testimonial items -->
    </div>
    <div class="carousel-btns" id="testimonialDots" role="tablist"></div>
  </section>

  <!-- Booking Form Section -->
  <section class="form-section" id="enquiryFormRealForm" aria-label="Enquiry Form">
    <h2 class="form-title">Request a Maid in Pune</h2>
    <p style="color:#7c417a; margin-bottom:15px;">
      Fill the form below – Our team will call within 30 minutes during working hours!<br />
      For instant help, <a href="tel:+918796832083" class="contact-link" style="color:#ff7bb5;font-weight:700;">Call 8796832083</a> or <a href="https://wa.me/918796832083" class="contact-link" style="color:green;font-weight:700;">WhatsApp</a>
    </p>
    <form id="enquiryFormReal">
      <input id="name" type="text" name="name" placeholder="Full Name" required aria-required="true" />
      <input id="phone" type="tel" name="phone" placeholder="Phone Number" maxlength="12" required aria-required="true" />
      <input id="location" type="text" name="location" placeholder="Your Area in Pune" required aria-required="true" />
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
      <a href="tel:+918796832083" class="contact-link"><img src="call-logo.png" alt="Call icon" />+91 8796832083</a>
      <a href="https://wa.me/918796832083" target="_blank" class="contact-link"><img src="whatsapp-logo.png" alt="WhatsApp icon" />Chat on WhatsApp</a>
      <span style="color:#c2185b;margin-left:14px;">Working Hours: 9am–9pm, All Days</span>
    </div>
  </section>

  <!-- Privacy Policy Link -->
  <footer>
    &copy; 2025 Maidzy. All Rights Reserved. | <a href="privacy.html" style="color:#ffd6eb; text-decoration:none;">Privacy Policy</a>
  </footer>

  <script>
    // ... JavaScript remains mostly same (accordion, testimonials, sticky CTA, form submit)

    const scriptURL = "https://script.google.com/macros/s/AKfycbzwi2Kh3A8tnWOipqZ2TV0yALUc-c9NFT7_LumjQcRUmSs4Q-OyvC_39Hu_M4lLQi0j/exec";

    const form = document.getElementById("enquiryFormReal");

    form.addEventListener("submit", (e) => {
      e.preventDefault();
      const submitBtn = form.querySelector('button[type="submit"]');
      submitBtn.disabled = true;
      submitBtn.classList.add("loading");
      submitBtn.textContent = "Submitting...";

      fetch(scriptURL, { method: "POST", body: new FormData(form) })
        .then(response => {
          if (response.ok) {
            alert("✅ Success! Your enquiry has been submitted.");
            form.reset();
          } else {
            alert("⚠️ Error! Unable to submit. Please try again later.");
          }
        })
        .catch(error => alert("⚠️ Error: " + error.message))
        .finally(() => {
          submitBtn.disabled = false;
          submitBtn.classList.remove("loading");
          submitBtn.textContent = "Submit Request";
        });
    });

    // Rest of JS for accordion, testimonials, sticky CTA as before
  </script>
</body>
</html>
