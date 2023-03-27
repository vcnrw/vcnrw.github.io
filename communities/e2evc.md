---
layout: page
title: E2EVC
comments: false
---
{% assign community = site.communities['e2evc'] %}

<img style="float: left; width: 250px; margin-right: 30px;" src="{{ site.url }}{{ community.picture | relative_url }}" alt="{{ community.display_name }}">
Hi! Wir sind {{community.name}}. 

Die E2EVC Virtualisierungskonferenz ist eine Reihe von weltweiten, nicht-kommerziellen Veranstaltungen der Virtualisierungsgemeinschaft.
Unser Hauptziel ist es, die besten Virtualisierungsexperten zusammenzubringen, um Wissen auszutauschen und neue Verbindungen zu knüpfen. Die E2EVC ist ein Wochenende vollgepackt mit Präsentationen, Master Classes und Diskussionen, die sowohl von den Produktteams der Virtualisierungsanbieter als auch von unabhängigen Experten gehalten werden.
Die E2EVC wurde im August 2003 mit nur 4 Teilnehmern ins Leben gerufen und hat sich nach über 50 sehr erfolgreichen Veranstaltungen zu einer anerkannten Veranstaltung mit etwa 250 Teilnehmern entwickelt. In den letzten 19 Jahren und über 50 Veranstaltungen hat unsere Konferenz in Städten wie Athen, München, London, Kopenhagen, Amsterdam, Barcelona, Berlin, Brüssel, Kapstadt, Frankfurt, Dublin, Orlando, Paris, Prag, Las Vegas, Los Angeles, München, New York, Nizza, Lissabon, Rom, Hamburg, Hongkong, Singapur, Sydney, Tokio, Tel Aviv und Wien stattgefunden. Im Durchschnitt finden bei jeder Veranstaltung 35-40 Sitzungen statt. Die Themen sind: Server-, Anwendungs-, Desktop- und Speichervirtualisierung mit Produkten von Anbietern wie Microsoft, Parallels, VMware, Citrix und vielen anderen. Über 50 Experten aus der Virtualisierungs-Community präsentieren ihre Themen, Gedanken und Ansichten zum aktuellen Stand der Dinge in der Branche. Viele der aktuellen Marktführer der Virtualisierungsbranche haben in der Vergangenheit an unseren Veranstaltungen teilgenommen oder nehmen noch immer daran teil. Es sind die Teilnehmer, die Referenten und unsere Sponsoren, die diese Veranstaltung möglich machen.

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