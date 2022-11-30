---
layout: page
title: Marcel Meurer
comments: false
---
{% assign speaker = site.speakers['marcel'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ speaker.picture | relative_url }}" alt="{{ speaker.display_name }}">This is Marcel!
<div class="social-button-member">
{% if speaker.linkedin %}
<a style="text-decoration: none;" href="{{speaker.linkedin}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/027-linkedin.png" alt="linkedin"></a>
{% endif %}

{% if speaker.twitter %}
<a style="text-decoration: none;" href="{{speaker.twitter}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/008-twitter.png" alt="twitter"></a>
{% endif %}

{% if speaker.web %}
<a style="text-decoration: none;" href="{{speaker.web}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/030-html-5.png" alt="website"></a>
{% endif %}

{% if speaker.github %}
<a style="text-decoration: none;" href="{{speaker.github}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/050-github.png" alt="github"></a>
{% endif %}