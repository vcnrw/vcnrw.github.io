---
layout: page
title: VCNDS
comments: false
---
{% assign community = site.communities['vcnds'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ community.picture | relative_url }}" alt="{{ community.display_name }}">
Hi! Wir sind {{community.name}}. 

Virtualization Community Niedersachsen ist ein lockerer Zusammenschluss zu den Themen Cloud, SBC, VDI, Citrix, Microsoft, VMware, XenApp, XenDesktop, Horizon View uvm. in Niedersachsen.
Wenn das für Dich mehr als nur Schlagwörter sind, wenn Du Dich dazu austauschen möchtest und hören willst, wie Gleichgesinnte die Planung, Architektur oder auch die Umsetzung angehen oder mit Problemen im Betrieb umgehen, dann ist diese Community wie für Dich geschaffen.

Wir treffen uns regelmäßig in gemütlicher Runde in  der grünsten Stadt Deutschlands in einem Gasthaus. Nach einer kurzen Vorstellung finden zwei Vorträge statt. Daran schließt sich jeweils eine Diskussionsrunde an: Welche Erfahrungen haben die Teilnehmer gemacht?
Welche Ansätze sind empfehlenswert, was sollte eher gemieden werden?
Das Treffen klingt aus mit individuellen Gesprächen und der Möglichkeit zum Networking.

Schaut mal auf unsere [Website]({{community.web}}){:target="_blank"}!

Hosts: Jan Hendrik Meier & Dennis Brandt

<div class="social-button-member">

    {% if community.linkedin %}

        <a style="text-decoration: none;" href="{{community.linkedin}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/027-linkedin.png" alt="linkedin"></a>

    {% endif %}

    {% if community.twitter %}

        <a style="text-decoration: none;" href="{{community.twitter}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/008-twitter.png" alt="twitter"></a>

    {% endif %}

    {% if community.web %}

        <a style="text-decoration: none;" href="{{community.web}}" target="_blank"><img width="100" height="100" src="{{ site.baseurl }}/assets/images/social/030-html-5.png" alt="website"></a>

    {% endif %}

</div>