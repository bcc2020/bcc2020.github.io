---
layout: default
title: Registration
permalink: /Registration/
image: submission.jpg
logostyle: logo-light
color: olive

---

<section id="submit" class="submit">
  <div class="col-lg-10 col-lg-offset-1  col-md-offset-1">
    <div class="col-md-8 col-xs-12">
      {% include registration_fees.md %}

    </div>
    <div class="col-md-4 col-xs-12">
      <div class="animated hiding" data-animation="fadeInDown" data-delay="{{ animationDelay }}">
        {% include keydates.html %}

      </div>
    </div>
  </div>
</section>
