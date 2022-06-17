---
title: Build-Run Teams ("CN DevOps")
description: Entwicklungsteams haben volle Autorität über die von ihnen erstellten Services, indem sie diese nicht nur erstellen, sondern auch implementieren und supporten.
layout: pattern
---

![Build-Run Teams (“CN DevOps”)]({{ site.baseurl }}/assets/images/build-run%20teams.png)

## Ausgangslage

Das Unternehmen hat cross-funktionale Teams (Agile) oder Teams, die nach technischer Spezialisierung (Wasserfall) aufgeteilt sind und muss in eine Struktur wechseln, die mit Cloud Native kompatibel ist.
Die Entwicklungsteams verlassen sich auf das Betriebsteam, um Artefakte für die Produktion bereitzustellen.
Das Unternehmen sucht nach dem richtigen Gleichgewicht zwischen Unabhängigkeit und Standardisierung für seine Entwicklungsteams.

## In diesem Kontext

Wenn Entwicklungsteams für die Erstellung einer Anwendung sowie für den Support der Anwendung in Produktion verantwortlich sind und auch noch versuchen, die Plattform für den Betrieb selbst zu stellen, kann das Unternehmen am Ende mit mehreren, unvereinbare Plattformen dastehen.
Dies ist unnötig, teuer im Betrieb (wenn überhaupt möglich) und nimmt den Teams, die sich auf die Bereitstellung von Funktionen und nicht auf die Plattform, auf der sie laufen, konzentrieren sollten, Zeit weg.

* Die Übergabe zwischen den Entwicklungs- und Betriebsteams beeinträchtigt die Produktionsgeschwindigkeit und -flexibilität.
* Wenn man eine Person aus dem Betrieb in viele Entwicklerteams einbringt, erhält man am Ende viele unvereinbare Plattformen.
* Conways Gesetz besagt, dass die Software-Architektur der Organisationsstruktur ähnelt. Wenn wir also wollen, dass die Plattform unabhängig ist, dann müssen die Teams, die eine Anwendung entwickeln, von dem Team, das die Plattform in Produktion betreibt, getrennt sein.
* Es gibt eine Grenze für die Fähigkeiten, die ein Team haben kann. Entwickler\*innen sind Entwickler\*innen: sie können ihr Wissen bis zu einem bestimmten Grad erweitern, aber sie sind keine Betriebsmitarbeiter*\innen.
* Die Beibehaltung von Betrieb und Entwicklung als getrennte Disziplinen/Teams ist in der Cloud nicht nachhaltig.
* Zu viel Freiheit bringt Chaos, aber zu viel Standardisierung erstickt die Innovation.

## Deshalb

Schaffen Sie Teams, die jeweils ihre eigenen Fähigkeiten haben, um ein verteiltes System mit Mikroservices zu erstellen, die durch dynamisches Scheduling verwaltet werden.
Build-Run-Teams sind für die Erstellung verteilter Anwendungen, deren Bereitstellung und die anschließende Unterstützung der laufenden Anwendungen verantwortlich.
Build-Run-Teams verwenden alle den gleichen standardisierten Satz an Plattformdiensten und stellen eine einzige, einheitlichen Plattform bereit, auf der alle Anwendungen für das gesamte Unternehmen ausgeführt werden.
Diese Plattform liegt in der Verantwortung des Plattform-Teams, das sie implementiert und unterstützt.

* Build-Run-Teams sind keine DevOps-Teams im herkömmlichen Sinne, bei denen Entwickler\*innen und Mitarbeiter\*innen des Betriebs zusammensitzen.
* In der agilen Entwicklung umfasst das Entwicklungsteam auch Software-Testmöglichkeiten, aber die Produkte werden an ein separates Betriebsteam übergeben, das sie an die Produktion ausliefert.
* In der Cloud-Native-Welt muss ein echtes funktionsübergreifendes Team in der Lage sein, verteilte Systeme zu erstellen.
* Das Plattform-Team ist eine besondere Art von Build-Run-Team, da es die Cloud-Native-Plattform und -Infrastruktur erstellt, bereitstellt, provisioniert und unterstützt, aber es arbeitet getrennt von den Anwendungsentwicklungsteams.

## Folglich

Es besteht eine starke Trennung der definierten Verantwortlichkeiten: Build-Run-Teams bearbeiten die Anwendungen.
Das Plattform-Team ist für den Aufbau und die Wartung der Betriebsplattform verantwortlich.
Das Plattform-Team muss nicht Teil der firmeneigenen öffentlichen Clouds wie Google/AWS/Azure, etc. sein, die mit ihren automatisierten Plattformen ein internes Plattform-Team überflüssig machen könnten.
Wenn ein Plattform-Team ernannt wird, sind sie typischerweise global und unterstützen alle Dienste/Anwendungen.
Build-Run-Teams sind getrennt davon und verlassen sich auf eine standardisierte Plattform, die vom Plattform-Team bereitgestellt wird.

{:.plusminus}
- {:.plus} Teams haben ein begrenztes Maß an Autonomie und die Möglichkeit, sich auf ihre eigentlichen Aufgaben zu konzentrieren.
- {:.plus} Entwickler\*innen haben immer noch die Freiheit, Komponenten auszuwählen, die auf der standardisierten Plattform laufen sollen, solange sie kompatibel sind.
