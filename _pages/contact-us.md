---
layout: page
title: "Contact Us 📬"
permalink: /contact-us
description: Get in touch with the team at ecomm-seo.github.io for collaboration, questions, or advertising inquiries.
image: '/images/contact.webp'
---

We’d love to hear from you!

<div class="form-box">
  <div class="contact-head">
    {% if site.contact.description %}
    <p class="page-description">{{site.contact.description}}</p>
    {% endif %}
  </div>
  <form class="form" action="{% if site.contact.email %}https://formspree.io/{{site.contact.email}}{% else %}#{% endif %}" method="POST">
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-name">Your Name</label>
      <input class="form__input" id="form-name" type="text" name="name" placeholder="Name..." required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-email">Your Email</label>
      <input class="form__input" id="form-email" type="email" name="_replyto" placeholder="Email..." required>
    </div>
    <div class="form__group">
      <label class="form__label screen-reader-text" for="form-text">Your Message</label>
      <textarea class="form__input" id="form-text" name="text" rows="10" placeholder="Message..." required></textarea>
    </div>
    <div class="form__group">
      <button class="button" type="submit">Send Message</button>
    </div>
  </form>
</div>

Whether you have questions about our content, want to collaborate, or explore advertising opportunities, drop us a message:

📧 **Email:** [ecommseo.blog@gmail.com](mailto:ecommseo.blog@gmail.com)

We typically respond within 24–48 hours.
