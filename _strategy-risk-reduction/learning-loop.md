---
title: Lernschleife
title_en: Learning Loop
description: Durch den Einbau der Feedback-Sammlung in den Auslieferungsprozess wird der Kreis zwischen den entwickelnden Teams und den Menschen, die ihre Produkte verwenden, geschlossen, wodurch der Kunde in den Mittelpunkt des Produktentwicklungszyklus gestellt wird.
layout: pattern
---

![](../_images/5e148523a18ed9397bac016d_69.%20Learning%20loop.png)

## Ausgangslage

Ein Unternehmen arbeitet daran, seine Unternehmenskultur so zu verändern wie sie erforderlich ist, um sich dem Auslieferungsansatz anzupassen erforderlich ist: Der Auslieferung einer verteilten Architektur von Cloud Native Microservices, die in der Cloud betrieben werden.

## In diesem Kontext

Lernen geschieht in einem dreiteiligen Zyklus:
Zielsetzung, Ausführung und Reflexion.
Der erste Schritt ist die Identifizierung einer Herausforderung oder eines Problems und die Ausarbeitung einer wahrscheinlichen Lösung.
Die zweite Stufe ist die Durchführung des Plans bis zum Erfolg oder Misserfolg.
Die dritte Phase ist die Untersuchung des Ergebnisses &ndash; das Zurückdenken über das, was passiert ist und wie es funktioniert hat.
Mit einem sehr langen Lieferprozess ist dieser Zyklus nur von begrenztem Nutzen, wenn die gelernten Lektionen erst Monate später angewendet werden können, wenn die Informationen nicht mehr frisch im Kopf des Entwicklers sind oder vielleicht nicht mehr relevant sind.
Die Lernschleife ist in einem organisatorischen Kontext nur dann nützlich, wenn sie geschlossen ist (eine Stufe führt direkt zur nächsten und zur nächsten, dann wiederholt sich der Zyklus).
Die meisten Unternehmen, die Cloud Native einsetzen, nennen die steigende Produktgeschwindigkeit als ihr Hauptmotiv.
Eng gekoppelte Release-Zyklen nach dem Wasserfall-Ansatz können bis zu sechs Monate bis zu einem Jahr oder sogar zwei betragen.

## Deshalb

Bauen Sie Mechanismen für die Sammlung von Benutzer-Feedback ein und füttern Sie die Erkenntnisse daraus schnell zurück in den Lieferzyklus. Damit fließen die Reaktionen vom Kunden zurück, so dass das Unternehmen besser informierte Entscheidungen treffen kann.
Im Cloud-Native-Umfeld können Organisationen den dreiteilige Lernzyklus äußerst effektiv als Feedback-Schleife für Entwickler nutzen.
Dies ermöglicht eine schnelle Iteration und Anpassung an sich ändernde Marktbedingungen und Kundenbedürfnissen.
Wenn ein Team seinen Teil einer Anwendung erstellt und diese schnell und häufig in der Produktion einsetzt, gelangt die Arbeit des Teams sofort zu den Benutzern.
Wenn zu diesem Zeitpunkt Kunden-Feedback gesammelt wird, kann es direkt in die Reflexionsphase einfließen, damit das Team es bei der Wiederholung der Schleife und der Festlegung der Ziele für den nächsten Arbeitszyklus berücksichtigen kann.
Verwenden Sie das Feedback, um die Änderungen zu erstellen, welche die Kunden Ihnen mitteilen.
Wenn Sie kein Feedback sammeln, verringert sich der Wert der von Cloud Native gebotenen, kürzeren Time-to-Market.

## Folglich

Wenden Sie die "Datenorientierte Entscheidungsfindung" auf den schnellen Bereitstellungszyklus von Cloud Native an. So fließt der Output des Systems kontinuierlich zurück, um das System zu verbessern. Sie können damit schnell vorgehen, ohne etwas kaputt zu machen.

{:.plusminus}
- {:.plus} Entwickler erfassen die Dynamik der Verbesserungen, was zu weiteren Verbesserungen führt.
- {:.minus} Observability ist kompliziert und muss sorgfältig entwickelt werden, um die richtigen Erkenntnisse zu gewinnen.
- {:.minus} Was Kunden wollen, ist nicht immer machbar oder kosteneffektiv.
