---
layout: page2
title: Contact Us
tagline: Got questions? We've got answers.
group: pssaturday-drop-nav
tags : [contact, components]
img : pssaturday.png
img-mobile : pssaturday.png
author : rtpsug
creator : rtpsug
css: 
js:
keywords: components, demo
canonical: https://rtpsug.com
---
{% include JB/setup %}
<!-- Content Area Start -->
<div id="content">
  <div class="container">
    <div class="row">
      <div class="col-md-12">
        <div class="contact-info">
          <address>
            <i class="fa fa-map-marker icons cyan-color contact-info-icon"></i>
            Research Triangle PowerShell User Group
          </address>
          <a href="mailto:rtpsug@gmail.com"><i
              class="fa fa-envelope-o icons cyan-color contact-info-icon"></i>rtpsug@gmail.com</a>
          <a href="/"><i class="fa fa-tablet icons cyan-color contact-info-icon"></i>www.rtpsug.com</a>
          <ul class="social-links">

            {% if site.author.facebook %}
            <li>
              <a href="https://www.facebook.com/{{ site.author.facebook }}/" class="fa fa-facebook"></a>
            </li>
            {% endif %}
            {% if site.author.twitter %}
            <li>
              <a href="https://twitter.com/{{ site.author.twitter }}" class="fa fa-twitter"></a>
            </li>
            {% endif %}
            {% if site.author.github %}
            <li>
              <a href="https://github.com/{{ site.author.github }}" class="fa fa-github"></a>
            </li>
            {% endif %}
            {% if site.author.youtube %}
            <li>
              <a href="https://youtube.com/c/{{ site.author.youtube }}" class="fa fa-youtube"></a>
            </li>
            {% endif %}
            {% if site.author.linkedin %}
            <li>
              <a href="https://www.linkedin.com/company/{{ site.author.linkedin }}/" class="fa fa-linkedin"></a>
            </li>
            {% endif %}
          </ul>
        </div>
      </div>

    </div>

  </div>
</div>
<!-- Content Area End -->
