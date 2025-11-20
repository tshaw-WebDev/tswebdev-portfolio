+++
title = "Contact"
date = 2025-11-07
draft = false
menu.main.weight = 40
description = "Contact TSWebDev — Get in Touch"
+++

<!-- Using HTML inside a section page requires a blank line and raw HTML formatting -->

<div data-aos="fade-up">
  <h2>Get in Touch</h2>
  <p>If you'd like to work together or have any questions, feel free to send a message using the form below.</p>
</div>

<form 
  name="contact" 
  method="POST" 
  data-netlify="true" 
  netlify-honeypot="bot-field"
  data-aos="fade-up"
  style="max-width:600px;margin:auto;"
>

  <!-- Honeypot spam field -->
  <input type="hidden" name="form-name" value="contact">
  <p style="display:none;">
    <label>Don’t fill this out:
      <input name="bot-field">
    </label>
  </p>

  <div class="form-group">
    <label>Your Name</label>
    <input type="text" name="name" required>
  </div>

  <div class="form-group">
    <label>Your Email</label>
    <input type="email" name="email" required>
  </div>

  <div class="form-group">
    <label>Your Message</label>
    <textarea name="message" rows="5" required></textarea>
  </div>

  <button type="submit" class="contact-button" data-aos="zoom-in">
    Send Message
  </button>

</form>
