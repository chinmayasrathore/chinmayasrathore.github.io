---
layout: page
title: contact
permalink: /contact/
description: some useful projects
nav: true
nav_order: 6
---

<form
  action="https://formspree.io/f/xwpqzvkl"
  method="POST"
>
    <label for="name">Name:</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email:</label>
    <input type="email" id="email" name="email" required>

    <label for="subject">Subject:</label>
    <input type="text" id="subject" name="subject" required>

    <label for="message">Message:</label>
    <textarea id="message" name="message" rows="5" required></textarea>

    <button type="submit">Send Email</button>
</form>