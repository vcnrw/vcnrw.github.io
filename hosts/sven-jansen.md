---
layout: page
title: Sven Jansen
comments: false
---
{% assign host = site.hosts['sven'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ host.picture | relative_url }}" alt="{{ host.display_name }}">Hi, I'm Sven!

<div class="social-button-member">

    {% if host.linkedin %}
        <a style="text-decoration: none;" href="{{host.linkedin}}" target="_blank"><img width="100" height="100" width="100" height="100" src="{{ site.baseurl }}/assets/images/social/027-linkedin.png" alt="linkedin"></a>
    {% endif %}

    {% if host.twitter %}
        <a style="text-decoration: none;" href="{{host.twitter}}" target="_blank"><img width="100" height="100" width="100" height="100" src="{{ site.baseurl }}/assets/images/social/008-twitter.png" alt="twitter"></a>
    {% endif %}

</div>