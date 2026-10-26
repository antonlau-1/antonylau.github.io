---
layout: default
permalink: /contact/
page_css: contact
---

<div class="contact-card">
  <div class="contact-row">
    <svg class="icon" viewBox="0 0 24 24" aria-hidden="true">
      <rect x="3" y="5" width="18" height="14" rx="2"/>
      <path d="M3 7l9 6 9-6"/>
    </svg>
    <span class="label">Email:</span>
    <span id="email-slot">Enable JavaScript to see email</span>
  </div>

  <div class="contact-row">
    <svg class="icon" viewBox="0 0 24 24" aria-hidden="true">
      <path d="M5 4h4l2 5-2.5 1.5a11 11 0 0 0 5 5L15 13l5 2v4a2 2 0 0 1-2 2A16 16 0 0 1 3 6a2 2 0 0 1 2-2z"/>
    </svg>
    <span class="label">Phone:</span>
    <span id="phone-slot">Enable JavaScript to see phone</span>
  </div>

  <div class="contact-row">
    <svg class="icon" viewBox="0 0 24 24" aria-hidden="true">
      <rect x="4" y="3" width="16" height="18" rx="1"/>
      <path d="M8 7h2M14 7h2M8 11h2M14 11h2M8 15h2M14 15h2"/>
    </svg>
    <span class="label">Company:</span>
    <span>Something LLP</span>
  </div>
</div>

<script>
(function () {
    var addr = 'moc.liamg@gnihtemos'.split('').reverse().join('');
    var a = document.createElement('a');
    a.href = 'mailto:' + addr;
    a.textContent = addr;
    document.getElementById('email-slot').replaceWith(a);

    var p = document.createElement('a');
    p.href = 'tel:+447123456789';
    p.textContent = '+44 (0) 7123 456789';
    document.getElementById('phone-slot').replaceWith(p);
})();
</script>
