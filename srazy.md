---
title: Srazy
nav: srazy
permalink: /srazy/
lead: Elon sraz Praha je pravidelné setkání majitelů a fanoušků elektromobilů. Přijít může kdokoli, i bez auta.
description: Elon sraz Praha v Hotelu Čertousy, e-SALON, ElektroFest a další akce Elon Clubu.
---
{% include rel.html %}

## Elon sraz Praha

Srazy pořádáme ve všední den večer, obvykle ve středu od 18:00, v [Hotelu Čertousy](https://www.google.com/maps/search/?api=1&query=Hotel+%C4%8Certousy+Praha) v Praze. Do navigace stačí zadat „Hotel Čertousy Praha“. Parkování a nabíjení je na místě.

Co na srazu bývá:

- diskuse o EV tématech a zkušenostech z provozu,
- představení příslušenství pro elektromobily,
- novinky z projektu Cybertruckin.EU,
- možnost objednat trička a další Elon Club věci,
- lightshow na parkovišti,
- příjemné posezení v zajímavé společnosti.

Aktuální termín a přihlášení najdete vždy ve [WhatsApp skupině]({{ site.cta.url }}) a v [novinkách]({{ rel }}novinky/). Nápady na další akce posílejte na [srazy@elonclub.cz](mailto:srazy@elonclub.cz).

<a class="btn" href="{{ site.cta.url }}">Přidat se do WhatsApp skupiny</a>

## Kde nás potkáte

Kromě pražských srazů míváme stánek na výstavě elektromobility **e-SALON** v Letňanech a jezdíme na **ElektroFest** v Pelhřimově. V listopadu 2023 jsme společně sledovali start Starship.

## Archiv srazů a akcí

{% assign events = site.posts | where_exp: "p", "p.categories contains 'srazy'" %}
<ul>
{% for p in events %}
<li><a href="{{ rel }}{{ p.url | remove_first: '/' }}">{{ p.title }}</a> ({{ p.date | date: site.t.date_format }})</li>
{% endfor %}
</ul>

Starší akce, které ještě nemají vlastní stránku:

- 28. 6. 2023 Elon sraz Praha, Hotel Čertousy
- 9.–10. 6. 2023 ElektroFest Pelhřimov (Eko Rally, předváděcí jízdy, lightshow)
- 31. 5. 2023 Elon sraz Praha, Hotel Čertousy
- 20. 4. 2023 Sledování startu Starship v restauraci v Praze
- 25. 1. 2023 Elon sraz Praha
- 26. 1. 2022 Tesla sraz Praha
