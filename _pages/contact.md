---
layout: page
title: contact
permalink: /contact/
description: Get in Touch
nav: true
nav_order: 6
---

<style>
        button:hover {
            background-color: #6dc8a9ff;
        }
</style>
<form accept-charset="UTF-8"  action="https://formspree.io/f/xwpqzvkl"  method="POST" >
  <div class="form-group">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required style="padding:10px;border-radius: 4px;width: 94%;">
  </div>
  <div class="form-group">
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" required style="padding:10px;border-radius: 4px;width: 94%;">
  </div>
  <div class="form-group">
  <label for="subject">Subject:</label>
  <input type="text" id="subject" name="subject" required style="padding:10px;border-radius: 4px;width: 94%;">
  </div>
  <div class="form-group">
  <label for="message">Message:</label>
  <textarea id="message" name="message" rows="5" required style="padding:10px;border-radius: 4px;width: 94%;"></textarea>
  </div>
  <button type="submit" class="btn-primary" style="padding: 10px 15px; border-radius: 4px;border: none">Submit</button>
</form>