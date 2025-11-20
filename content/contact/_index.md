+++
title = "Contact"
date = 2025-11-07
draft = false
menu.main.weight = 40
description = "Contact TSWebDev — Get in Touch"
+++

<form 
  name="contact" 
  method="POST" 
  data-netlify="true" 
  netlify-honeypot="bot-field"
  data-aos="fade-up"
>

  <!-- Honeypot field (spam protection) -->
  <input type="hidden" name="form-name" value="contact">
  <p style="display:none;">
    <label>Don’t fill this out: <input name="bot-field"></label>
  </p>

  <div class="form-group" data-aos="fade-up">
    <label>Your Name</label>
    <input type="text" name="name" required>
  </div>

  <div class="form-group" data-aos="fade-up" data-aos-delay="150">
    <label>Your Email</label>
    <input type="email" name="email" required>
  </div>

  <div class="form-group" data-aos="fade-up" data-aos-delay="300">
    <label>Your Message</label>
    <textarea name="message" rows="5" required></textarea>
  </div>

  <button type="submit" class="contact-button" data-aos="zoom-in">
    Send Message
  </button>

</form>
