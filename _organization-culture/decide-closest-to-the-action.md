---
title: Dort Entscheiden, wo es passiert
title_en: Decide Closest to the Action
description: Diejenigen, die einer Änderungsaktion am nächsten sind, erhalten die allererste Möglichkeit, alle damit verbundenen Entscheidungen zu treffen.
layout: pattern
---

![Decide Closest to the Action]({{ site.baseurl }}/assets/images/Decide%20closest%20to%20action.png)

## Ausgangslage

Die Transformation zu Cloud Native ist im Gange, und es herrscht eine große Unsicherheit.
Die Menschen lernen immer noch etwas über die Technologie, die sich selbst ständig weiterentwickelt, und der Markt verändert sich häufig und unregelmäßig.
Jedes Team ist für die Bereitstellung seines eigenen Microservices verantwortlich und es gibt viele bewegliche Teile.
Manager\*innen und leitende Architekt\*innen haben nur ein breites, grobes Verständnis für das Produkt und wenig Verständnis für die technischen Details, die dem eigentlichen Entwicklungsprozess zugrunde liegen.

## In diesem Kontext

Die Entscheidungsfindung über die Befehlskette ist in der Cloud-Welt nicht nachhaltig.
Die Nutzung von Hierarchien zur Lösung von Konflikten und zur Vereinbarung von Entscheidungen dauert zu lange.
Die Lösungen sind auf die Fähigkeiten der Manager beschränkt, die auf dieser Entscheidungsebene tätig sind.
Techniker\*innen könnten eine überlegene Lösung finden, die nie implementiert wird, weil es zu viel Zeit und Aufwand kostet, sich durch die Bürokratie zu navigieren und um eine Genehmigung zu erhalten.
Also werden sie aufgeben und einfach weitermachen, mit dem was sie auch immer haben.

* Die Geschwindigkeit des technologischen Wandels wächst in letzter Zeit exponentiell.
* Der Markt verändert sich nun auch häufig, wobei unerwartete neue Wettbewerber auftauchen.
* In traditionellen Organisationen treffen Manager\*innen alle Entscheidungen und geben den Techniker\*innen Anweisungen.
* Je weiter man sich von der Veränderung entfernt, desto langsamer wird die Entscheidungsfindung mit der Zeit.

## Deshalb

Schieben Sie die Entscheidungsbefugnis so nah wie möglich an jede Änderung, die gerade stattfindet. 
Da Ihr Team als Teil eines größeren Stammes von Teams arbeitet, muss Ihre Entscheidung manchmal andere miteinbeziehen.
Wenn Sie beispielsweise APIs ändern möchten, müssen Sie diejenigen, die sie verwenden, informieren &ndash; und diese können gegen die Änderung Einwände erheben.
Was auch immer also innerhalb eines Microservices geschieht, ist vollständig die Domäne seines Entwicklungsteams.
Aber alles, was rein oder raus geht, ist auch die Domäne der Teams, die diese den Microservice konsumieren.

* Setzen Sie Sicherheitsrichtlinien und Regulierungen ein, um sicherzustellen, dass die Leute diese Entscheidungen treffen dürfen.
* Komplette Trennung der Pflichten: Führungskräfte, die für die Strategie verantwortlich sind. Manager, die für die Festlegung der Ziele verantwortlich sind. Techniker\*innen, die ihre Arbeit so ausführen können, wie sie es am besten sehen.
* Bringen Sie ein, dass es in Ordnung ist, an den Werten der Organisation zu scheitern.
* Nutzen Sie hierarchisches Management zur Konfliktlösung.

## Folglich

Führungskräfte delegieren es, die Macht, die Vision und die Ziele zu schaffen, an das mittlere Management.
Das mittlere Management delegiert die Macht über technische Entscheidungen an die ausführenden Teams.

{:.plusminus}
- {:.plus} Starker Anreiz, Konflikte zuerst innerhalb des Teams, dann innerhalb des Stammes zu lösen und erst dann an das Management zu gehen.
- {:.minus} Zeit und Mühe sind erforderlich, um sich mit den Teams zu koordinieren, die Ihren speziellen Service in Anspruch nehmen, um sicherzustellen, dass es überall funktioniert.
