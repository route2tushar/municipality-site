---
title: "Contact Us"
layout: "base.njk"
---

<form name="contact" method="POST" data-netlify="true" netlify-honeypot="bot-field">
  <input type="hidden" name="form-name" value="contact">
  <p>
    <label>Your Name: <input type="text" name="name" required></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" required></label>
  </p>
  <p>
    <label>Message: <textarea name="message" required></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
