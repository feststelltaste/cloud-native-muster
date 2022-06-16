---
title: Datengetriebene Entscheidungsfindung
titel_en: Data-Driven Decision Making
description: Sammeln Sie Daten, extrahieren Sie Muster und Fakten und nutzen Sie diese, um Schlussfolgerungen zu ziehen sowie objektive Entscheidungen zu treffen.
layout: pattern
---

![Data-Driven Decision Making]({{ site.baseurl }}/assets/images/data-driven%20decision%20making.png)

## Ausgangslage

Ein Unternehmen wechselt zu Cloud Native und sieht die Komplexität und Anzahl der Komponenten exponentiell wachsen. Jede Komponente wird separat aufgebaut. Wettbewerber wechseln täglich ihre Produkte.

## In diesem Kontext

Manager treffen Entscheidungen auf der Grundlage ihrer Erwartungen aus früheren Erfahrungen, die in der neuen und unbekannten Umgebung eines Cloud-Native-Systems möglicherweise nicht zutreffen.

* Lange Entwicklungs- und Release-Zyklen (sechs Monate bis zu einem Jahr oder sogar länger), die typisch für den Wasserfall-basierten Entwicklungsansatz sind, führen zu Produkten, die nicht mehr relevant sind, wenn sie beim Kunden ankommen.
* Softwaresysteme und Anwender sind komplexe Systeme. Es ist unmöglich, das Verhalten beider vorherzusagen.
* In hierarchischen Organisationen schützen Manager ihren Status, indem nur sie alles selbst wissen und entscheiden.
* Technisch gesehen ist es einfach, Daten zu sammeln.
* Falsche Messungen können zu schlechten Ergebnissen führen.

## Deshalb

Treffen Sie Produktentscheidungen auf der Grundlage von Daten, die von den tatsächlichen Nutzern gesammelt werden (Observability; Messen, was wichtig ist).
Die Daten können automatisch gesammelt werden, indem die Datenerfassungswerkzeuge in die Plattform und alle Anwendungen eingebettet werden, bevor sie an die Kunden weitergegeben werden.
Allerdings müssen Entwickler\*innen darauf achten, sich nicht zu sehr auf das Feedback/Daten der Benutzer zu verlassen oder ihnen blind zu vertrauen.
Die Benutzer wissen oft nicht, was sie wollen, insbesondere im Hinblick auf radikale Innovationen.

* Wenden Sie das A/B-Testing an, um verschiedene Lösungsvarianten zu evaluieren, indem Sie sie den realen Kunden aussetzen.
* In ähnlicher Weise baut das Muster der Lernschleife auf der datengesteuerten Entscheidungsfindung auf.
* Sammeln Sie Feedback und Klicks/Business-Messungen nach dem Rollout von Änderungen.

## Folglich

Das Team kann schnell Entscheidungen treffen, die auf objektiven Messungen basieren.

{:.plusminus}
- {:.plus} Anstatt sich über die Richtung zu streiten, kann das Team Experimente aufstellen und messen.
- {:.minus} Es ist einfacher, der Herde zu folgen.
- {:.minus} Es ist nicht immer einfach, die richtigen Dinge zu messen und zu interpretieren.
- {:.minus} Manchmal sind Daten und Benutzer falsch. Hier muss das Team seinem Instinkt vertrauen und sich auf eine radikale Veränderung einstellen.
