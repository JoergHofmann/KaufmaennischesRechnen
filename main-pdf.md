---
context-lang: @(Projekt.contextlang)
title: @(Projekt.title)
subtitle: @(Projekt.subtitle)
cover: @(Projekt.pdfCover)
date: @(Monat[heute.month].MMMM) @(heute.year)
git: @(GetShortGITHash "")
author: @(Autor.name)
---

# Einführung

@include "einfuehrung.md"

# Rechenregeln

*"Nach Adam Riese sind das ..."*

Diese Redewendung haben wir wohl alle schon mal gehört und benutzt, aber welcher Riese ist damit gemeint? Kein Riese, sondern Adam Ries, 1492 bis 1559, das ist der ältere Herr auf der Titelseite,  der als "Vater des modernen Rechnens" gilt. Dies und noch mehr können sie in der [Wikipedia](https://de.wikipedia.org/wiki/Adam_Ries) nachlesen.

Hier werden nur kurz die wichtigsten Rechenregeln wiederholt, fall sie ihnen aus der Schule nicht mehr präsent sind. 


@include "reihenfolge.md"


# Dreisatz

@include "dreisatz.md"
