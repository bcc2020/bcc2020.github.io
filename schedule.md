---
layout: default
title: Schedule
permalink: /schedule/
image: keynotes-top.jpg
logostyle: logo-light
---

{% include keynote-banner.html %}

<section id="schedule" class="schedule">
  <div class="col-lg-10 col-lg-offset-1  col-md-offset-1">
    <div class="col-md-8 col-xs-12">

      <p style="border: 2px solid black;margin: 4em;font-weight: bold;background-color: rgba(0,0,0,0.7);font-family:'Roboto',san-serif;color: #fff;">
        For up to date information about the conference, see <a style="color:orange;" href="https://bit.ly/bcc2020-info" alt="BCC2020 Info Hub">BCC2020 Info Hub</a>
      </p>

      {% include schedule.md %}

    </div>
    <div class="col-md-4 col-xs-12">
      <h4>Quick Links</h4>
      <ul>
        <li><a href="https://bcc2020.sched.com/">Conference Schedule</a></li>
        <li><a href="https://bit.ly/bcc2020-info">BCC2020 Info Hub</a></li>
        <li><a href="{{ '/discord/' | prepend: site.baseurl }}">Discord for Attendees</a></li>
        <li><a href="{{ '/code/' | prepend: site.baseurl }}">Code of Conduct</a></li>
      </ul>
    </div>
  </div>
</section>
