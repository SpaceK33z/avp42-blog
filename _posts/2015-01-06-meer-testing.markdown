---
layout: post
title:  "Meer testing"
date:   2015-01-06 12:45:00
categories: v3
---

Na iteratie 3 heb ik de applicatie in zijn geheel aan meerdere mensen laten zien. Hieruit kwam de volgende feedback naar voren;

> Ik wil niet dat de magnetron meteen start, omdat ik vaak nog het voedsel erin moet stoppen.

Interessant, ik zou zelf altijd vantevoren het voedsel in de magnetron stoppen, de deur dicht doen en de app gebruiken. Het lijkt er echter op dat veel mensen dit niet doen.
Dit heb ik inmiddels opgelost door een startscherm te implementeren. Bij de ‘heat’ functie was dit al opgelost.

![Start scherm]({{ site.url }}/assets/article_images/2015-01-06-meer-testing/start-scherm.png)

> De tekst is niet altijd even goed leesbaar door de achtergrond.

Dit heb ik opgelost door een ‘zwarte laag’ over de achtergrond heen te leggen, waardoor deze een stuk minder fel is.

> Waarom staat er op de achtergrond een foto van boterhammen in de magnetron?

Dit moet een camera die in de magnetron zit voorstellen. In het prototype is dit wat minder duidelijk, maar in het echt zal dit wel meteen duidelijk zijn.

> Hoe kan ik de ‘last used functions’ gebruiken?

Hm, kennelijk is het nog steeds niet helemaal duidelijk dat je hoort te swipen.

Het tekstje ‘swipe to quick wave’ is niet duidelijk, twee testpersonen wilde op deze tekst swipen.

Hieronder heb ik weer een nieuwe variant geprobeerd, die wel goed lijkt te werken;

![Oude oplossing]({{ site.url }}/assets/article_images/2015-01-06-meer-testing/old_swipe.png)

![Nieuwe oplossing]({{ site.url }}/assets/article_images/2015-01-06-meer-testing/new_swipe.png)
