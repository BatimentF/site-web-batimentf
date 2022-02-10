---
layout: default
text: 'Nous joindre'
street: 610-41 Simon-Lussier
city: Blainville
province: Qc
postalcode: J7C 0R2
telephone: 514-830-9883
email1: info@batimentf.com
email2: soumission@batimentf.com
---

<section class="contact-container">
  <div class="contact-item contact-info">
    <h3 class="title--margin-bottom">{{ page.text }}</h3>
    <div class="contact-address">
      <p>{{ page.street }}</p>
      <p>{{ page.city }}, {{ page.province }}</p>
      <p>{{ page.postalcode }}</p>
      <p>{{ page.telephone }}</p>
    </div>
    <p class="text--gap"><span class="text--bold">Informations générales:</span> {{ page.email1 }}</p>
    <p class="text--gap"><span class="text--bold">Département d'estimation:</span> {{ page.email2 }}</p>
  </div>
  {% include map.html %}
</section>

