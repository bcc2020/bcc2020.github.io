---
layout: default
title: Schedule
permalink: /schedule/
image: schedule.jpg
logostyle: logo-dark
---

<section id="schedule" class="schedule">
  <div class="col-lg-10 col-lg-offset-1  col-md-offset-1">
    <div class="col-md-8 col-xs-12">
      {% include schedule.md %}

    </div>
    <div class="col-md-4 col-xs-12">
      <div class="animated hiding" data-animation="fadeInDown" data-delay="{{ animationDelay }}">
        {% include keydates.html %}

      </div>
    </div>
  </div>
</section>
