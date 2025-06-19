<!--
author: @(Autor.name)
email: @(Autor.mail)
language: @(Projekt.shortlang)
version: @(GetShortGITHash "")
date: @(Monat[heute.month].MMMM) @(heute.year)

icon: images/favicon.png
titel: @(Projekt.title)
logo: images/ich-zeichnung.png
-->


# @titel


@(br)
@author@(br)
@email

@(br)
@date@(br)
Git: @version

# Einleitung
<section>
@include "einfuehrung.md" 
</section>



# Ceterum censeo

@include "ceterum_censeo.md" 
