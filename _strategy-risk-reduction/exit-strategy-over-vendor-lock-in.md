---
title: Exit-Strategie über Vendor Lock-In
title_en: Exit Strategy Over Vendor Lock-in
description: Public-Cloud- oder andere große Produktanbieter können alle Aspekte des Aufbaus und Betriebs einer Cloud-Native-Plattform übernehmen
Ihre Tools sind oft hervorragend. Aber wenn man sich auf einen Anbieter/eine Technologie/Plattform festlegt, ist es wichtig, eine alternative Lösung und die mit der Umstellung verbundenen Kosten zu identifizieren.
layout: pattern
---

![Exit Strategy Over Vendor Lock-in]({{ site.baseurl }}/assets/images/exit%20strategy%20over%20vendor.png)

## Ausgangslage

Unternehmen müssen Werkzeuge/Produkte von Anbietern (kommerzielle oder Open-Source-Communities) verwenden, haben aber Angst, sich an einen einzigen Anbieter zu binden. 
Einige Branchen erfordern die Unterstützung mehrerer Auswahlmöglichkeiten für einige wichtige Plattformen, Tools oder Technologien, die zur Entwicklung von Unternehmensprodukten verwendet werden.
Das volle Commitment für ein einziges Tool oder eine einzige Technologie kann die Kosten in die Höhe treiben oder den technischen Fortschritt auf der ganzen Linie behindern.

## In diesem Kontext

Die Bindung an einen einzigen Anbieter (oder einfach nur an eine einzige große Lösung) schafft Vertrauen in deren kontinuierliche Stabilität und Verfügbarkeit sowie in der Preisgestaltung.
Aber die Kosten für die Aufrechterhaltung aktiver Alternativ-/Backup-Optionen sind unerschwinglich.
Dies führt zu einer vollständigen Abhängigkeit vom Anbieter.
Wenn der Anbieter in Schwierigkeiten ist oder eine bessere Option auf dem Markt verfügbar wird, kann sich das Unternehmen einen Wechsel nicht leisten.
Das führt dazu, dass nicht gewartete oder minderwertige Technologie verwendet wird.

- Jede Wahl ist mit Risiken verbunden.
- Jede Entscheidung kann rückgängig gemacht werden &ndash; es ist nur eine Frage der Kosten.
- Einige Branchen erfordern mehrere Anbieter für jede Lösung.

## Deshalb

Anstatt sich blind zu weigern, sich an einen einzigen Anbieter zu binden, sollten Sie die Optionen für eine zweite Migration, falls erforderlich, und deren Kosten ausloten.
Dann treffen Sie eine fundierte Entscheidung, die auf dem Kompromiss zwischen den kurzfristigen Gewinnen aus einem Anbieter mit dem besten Tool und dem langfristigen Risiko einer eventuellen Migration daraus entsteht.
Oftmals überwiegen niedrigere Kosten und höhere Produktivität das Risiko.

Erwägen Sie, Architekturänderungen zu bevorzugen, die die Kosten der Migration senken, falls diese einmal erforderlich sein wird.
Solche Änderungen können kostengünstig sein, wenn sie in den frühesten Phasen des Projekts durchgeführt werden, und sie können das Risiko einer zukünftigen Migration erheblich reduzieren.

- Bereiten Sie für den Fall der Fälle einen Migrationsplan vor.
- Erwägen Sie die Reduzierung von Abhängigkeiten, die das Risiko deutlich erhöhen.
- Cloud-Anbieter könnten jetzt durch ihre gute dokumentierte Migrationsunterstützung eine große Hilfe sein.
- Geschlossene Ökosysteme bieten oft ein ausgezeichnetes Set an Werkzeugen/Optionen.
- Investieren Sie in häufig verwendete Tools und Technologien, die zu Industriestandards werden können.

## Folglich

Das Team kann sich darauf konzentrieren, die maximale Leistung aus jedem Tool herauszuholen und davon zu profitieren.
Es ist sich bewusst, was die Migration zu alternativen Lösungen im Bedarfsfall kosten würde.

{:.plusminus}
- {:.plus} Es gibt ein gutes Verständnis für die verschiedenen Backup-Optionen.
- {:.plus} Es gibt einen hochrangigen Plan für ein größeres Migrationsszenario.
- {:.minus} Es besteht immer ein Risiko, wenn nur ein Tool verwendet wird.
