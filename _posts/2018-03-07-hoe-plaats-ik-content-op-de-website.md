---
layout: post
title: Hoe plaats ik content op de website?
date:   2018-03-07 16:16:01
---

# Hoe plaats ik content op de website?

* Fork de [websiterepository](https://github.com/MADspace/MADspace.github.io) op github
* Maak of bewerk de content 
* Na het maken van de aanpassingen, push de repository en maak een pull request

We volgen de methode zoals deze wordt beschreven op de pagina's over [forking](https://help.github.com/articles/fork-a-repo/) en [syncing](https://help.github.com/articles/syncing-a-fork/)

## Hoe plaats ik een projectpagina op de website?

* Maak een nieuwe projectpagina aan in de _projects directory

### Waar moet ik op letten?

Begin de pagina met wat frontmatter:

    ---
    layout: project
    title: Embedded Systems Eindhoven
    ---

Daarna kun je er voor kiezen om de content in html of in markdown in het document te zetten.


## Hoe plaats ik een deelnemerspagina op de website?

* Maak een nieuwe deelnemerspagina aan in de _participants directory

### Waar moet ik op letten?

Begin de pagina met wat frontmatter:

    ---
    layout: participant
    title: Doe, John
    ---

Daarna kun je er voor kiezen om de content in html of in markdown in het document te zetten.

## Hoe plaats ik een blogpost op de website?

* Maak een nieuwe blogpost pagina aan in de _posts directory

### Waar moet ik op letten?

Geef de pagina een bestandsnaam zoals: 9999-99-99-dit-is-de-titel.md

Begin de pagina met wat frontmatter:

    ---
    layout: post
    title: Hoe plaats ik een blogpost op de website?
    date:   2018-03-05 10:49:50
    ---

Daarna kun je er voor kiezen om de content in html of in markdown in het document te zetten.




# Nuttige links
* https://jekyllrb.com/docs/home/
* https://guides.github.com/features/mastering-markdown/
