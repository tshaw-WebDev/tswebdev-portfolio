+++
title = "Contact"
date = 2025-11-07
draft = false
menu.main.weight = 40
description = "Contact TSWebDev — Get in Touch"
+++

<div data-aos="fade-up">
Have a question or want to work together?<br>
I'd love to hear from you. Please use the form below to send me a message.
</div>

<form name="contact" method="POST" netlify netlify-honeypot="bot-field" action="/success" data-aos="zoom-in" data-aos-delay="200">

  <!-- Honeypot field (for spam protection) -->
  <input type="text" name="bot-field" style="display:none">

  <label>Your Name</label>
  <input type="text" name="name" required>

  <label>Your Email</label>
  <input type="email" name="email" required>

  <label>Your Message</label>
  <textarea name="message" rows="6" required></textarea>

  <button class="cta-button" type="submit">Send Message</button>
</form>
