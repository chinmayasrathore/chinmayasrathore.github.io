---
layout: page
title: contact
permalink: /contact/
description: Get in Touch
nav: true
nav_order: 6
---

<form accept-charset="UTF-8"  action="https://formspree.io/f/xwpqzvkl"  method="POST" >
  <div class="form-group">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  </div>
  <div class="form-group">
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required>
  </div>
  <div class="form-group">
  <label for="subject">Subject:</label>
  <input type="text" id="subject" name="subject" required>
  </div>
  <div class="form-group">
  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="5" required></textarea>
  </div>
  <button type="submit" class="btn-primary">Submit</button>
</form>