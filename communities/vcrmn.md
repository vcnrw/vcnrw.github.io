---
layout: page
title: VCRMN
comments: false
---
{% assign community = site.communities['vcrmn'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ community.picture | relative_url }}" alt="{{ community.display_name }}">
Hi! Wir sind {{community.name}}. 

Virtualization Community Rhein-Main-Neckar ist ein lockerer Zusammenschluss zu den Themen Remote Windows Sessions, Virtual Desktops, Citrix XenApp & XenDesktop, Microsoft Remote Desktop Services, VMware Horizon und NVIDIA GRID in der Region Rhein-Main-Neckar.
Wenn das für Dich mehr als nur Schlagwörter sind, wenn Du Dich dazu austauschen möchtest und hören willst, wie andere die Architektur angehen, wie sie die Implementierung anpacken oder mit Problemen im Betrieb umgehen, dann ist diese Community wie für Dich gemacht.

Wir treffen uns regelmäßig in gemütlicher Runde im Séparée eines netten Gasthauses. Nach einer kurzen Vorstellung beginnt der Abend mit einem gemeinsamen Abendessen und netten Gesprächen. Daran schließen sich ab 20 Uhr zwei Fachvorträge zu je einer Stunde an. Natürlich ergeben sich dabei auch immer spannenede Diskussionsrunden: Welche Erfahrungen haben die Teilnehmer gemacht, die sie mit der Runde teilen möchten? Welche Ansätze sind empfehlenswert, was sollte eher gemieden werden? Das Treffen klingt aus mit individuellen Gesprächen und der Möglichkeit zum Networking.

Schaut mal auf unsere [Website]({{community.web}}){:target="_blank"}!

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