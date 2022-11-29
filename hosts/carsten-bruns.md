---
layout: page
title: Carsten Bruns
comments: false
---
{% assign host = site.hosts['carsten'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ host.picture | relative_url }}" alt="{{ host.display_name }}">Hi, I'm Carsten!

<div class="social-button-member">
{% if host.linkedin %}
<a style="text-decoration: none;" href="{{host.linkedin}}" target="_blank"><img class="host-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/027-linkedin.png" alt="linkedin"></a>
{% endif %}

{% if host.twitter %}
<a style="text-decoration: none;" href="{{host.twitter}}" target="_blank"><img class="host-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/008-twitter.png" alt="twitter"></a>
{% endif %}

{% if host.web %}
<a style="text-decoration: none;" href="{{host.web}}" target="_blank"><img class="host-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/030-html-5.png" alt="website"></a>
{% endif %}

{% if host.github %}
<a style="text-decoration: none;" href="{{host.github}}" target="_blank"><img class="host-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/050-github.png" alt="github"></a>
{% endif %}

{% if host.reddit %}
<a style="text-decoration: none;" href="{{host.reddit}}" target="_blank"><img class="host-box-socials-icon" src="{{ site.baseurl }}/assets/images/social/018-reddit.png" alt="reddit"></a>
{% endif %}
</div>