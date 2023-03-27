---
layout: page
title: GOEUC
comments: false
---
{% assign community = site.communities['goeuc'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ community.picture | relative_url }}" alt="{{ community.display_name }}">
Hi! Wir sind {{community.name}}. 

GO-EUC glaubt an:

    Forschen heißt neues Wissen schaffen.
    Neil Armstrong

Die Aufgabe von GO-EUC ist:

    Dem Einzelnen die Möglichkeit zu geben, neue Technologien zu erforschen, die Gemeinschaft zu inspirieren und ihr zu dienen, indem neues Wissen bereitgestellt wird.

Unsere Plattform soll dieser Aufgabe dienen. Wir glauben, dass dies wertvolle Informationen für jeden IT-Administrator, Berater oder Manager sind, der etwas mit Endbenutzer-Computing zu tun hat. GO-EUC dient der Community durch unsere Website und verschiedene Community-Veranstaltungen, die die GO-EUC-Forscher unterstützen. Alles, was auf GO-EUC veröffentlicht wird, ist offen und frei auf der Website verfügbar, ohne dass eine Registrierung erforderlich ist.

Da GO-EUC eine gemeinnützige Stiftung ist, wird auf diese Weise sichergestellt, dass die Plattform völlig unabhängig und unvoreingenommen der Gemeinschaft dient. Alle Forschungen werden auf der Grundlage von Erkenntnissen und Vorschlägen der Gemeinschaft durchgeführt.

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