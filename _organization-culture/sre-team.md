---
title: SRE-Team
title_en: SRE Team
description: Das SRE-Team (Site Reliability Engineering) hilft den Entwicklungsteams bei der Wartung und Verbesserung der Anwendung (nicht der Plattform oder der Infrastruktur).
layout: pattern
---

![SRE Team]({{ site.baseurl }}/assets/images/SRE%20team.png)

## Ausgangslage

Ein großes Unternehmen verfügt über eine große, geschäftskritische Anwendung mit sehr hohen Anforderungen an Qualität und Verfügbarkeit sowie über beträchtliche Ressourcen für die Bildung dedizierter Verbesserungsteams.

## In diesem Kontext

Sobald eine Plattform einmal gebaut und in Produktion ist, wird die Aufmerksamkeit oft von der Verbesserung der internen Prozesse und der Laufzeitleistung abgezogen.
Dies kann im Laufe der Zeit zu einer Verschlechterung der Qualität und Leistung führen.

* Entwicklungsteams werden an der Funktionalität, der Betrieb an der Stabilität und SRE an Verbesserungen gemessen.
* SRE ist ein sehr kostspieliges Team, da es die erfahrensten und sachkundigsten Techniker benötigt.
* Opportunitätskosten entstehen, wenn Sie Ihre besten Techniker aus den Entwicklungsteams zu SRE holen.
* Wenn Verbesserungen für dieses Team die Priorität haben, dann wird dies etwas von der Verantwortung / Priorität der Build-Run-Teams entfernt.
* SRE ist relevanter, wenn eine Anwendung in den Wartungsmodus geht, als während des anfänglichen Builds.

## Deshalb

Schaffen Sie ein Team, das sich zu 50 % auf die Zuverlässigkeit und zu 50 % auf die kontinuierliche Verbesserung der internen Prozesse und Entwicklungspraktiken konzentriert.
Dieses SRE-Team kümmert sich um die allgemeine Verfügbarkeit der Website (Plattform) insgesamt.
Jeder einzelne Service hat jedoch auch seine eigenen betrieblichen Bedürfnisse.
Es kann hilfreich sein, SREs in jedes einzelne Build-Team (oder zumindest in den Stamm) aufzunehmen, um sich auf die Verfügbarkeit der Services zu konzentrieren.

* Die SRE-Techniker sind dafür verantwortlich, alles zu verbessern, was zur Schaffung einer besseren Infrastruktur, einer besseren Laufzeit und eines besseren Benutzer-Supports erforderlich ist.
* Das SRE-Team erstellt die Fehlerbudgets und hilft dem Entwicklerteam bei der Definition seines Betriebsmodells und dem Plattformteam bei der Verbesserung der Plattform.
* Die meisten Aufgaben sind eher eine Automatisierung als ein manueller Support.
* Alle 18 Monate muss das SRE-Team alles, was es manuell tut, automatisieren (damit es in die Verantwortung des Plattformteams übergehen kann).
* Sie verfügen über ein sehr sachkundiges und erfahrenes Team mit guten Kenntnissen über den Betrieb, aber auch über Entwickler, die Code schreiben können.

## Folglich

Die Laufzeitstabilität und -qualität nimmt kontinuierlich zu.
Auch der Automatisierungsgrad wird erhöht.

{:.plusminus}
- {:.plus} Die Entwickler sind sich der betrieblichen Belange bewusst und beziehen dieses Wissen in ihren Entwicklungszyklus ein.
- {:.plus} Das SRE-Team arbeitet eng mit den Build-Run-Teams und dem Plattformteam zusammen.
- {:.minus} SRE-Teams sind kostspielig und nehmen Top-Talente von anderen Projekten weg.
