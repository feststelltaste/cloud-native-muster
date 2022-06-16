## Muster: Monolithische Organisation abbauen

So wie die neuen Instrumente, Technologien und Infrastrukturen im Laufe einer Transformationsinitiative allmählich eingeführt werden, müssen sich auch die Organisation und ihre Teams weiterentwickeln, um mit ihnen richtig zu arbeiten.

![](../_images/5e15e5c078f3a384ae17bf4b_Strangle%20monolithic%20organisation.png)

## Ausgangslage

Eine Cloud-Native-Transformation ist im Gange.
Einige Teams gehen auf Cloud Native über, während andere vielleicht für lange Zeit nicht auf Cloud Native umsteigen.

## In diesem Kontext

Die Migration eines bestehenden Unternehmens in die Cloud kann Jahre dauern und sie erfolgt sehr langsam.
Es gibt zwei Arten von Umzügen, die selten funktionieren.
Erstens: Der Versuch, alle auf einmal rüberzubringen, hat sich nicht als eine gute Übung herausgestellt.
Ohne einen soliden Hintergrund in der neuen Technologie sind die Teams weniger effektiv und werden mit der Zeit frustriert oder greifen auf alte Gewohnheiten zurück, die in der Cloud nicht gut funktionieren.
Wenn der kulturelle und organisatorische Wandel nicht unterstützt wird, damit sich die Cloud-Native-Technologie in gleichem Maße weiterentwickelt, führt dies ebenfalls zu Frustration.
Zweitens: Wenn ein Teil des Unternehmens einfach in der Altlast verbleibt, während alle anderen auf die Cloud-Native-Technologie umsteigen, wird das Unternehmen so strukturiert, dass die Teams, die nie auf die Cloud-Native-Technologie umsteigen, professionell blockiert werden.
Sie werden nie mit der coolen neuen Technologie spielen und moderne Entwicklerfähigkeiten aufbauen können, wenn sie zurückgelassen werden, um das Altsystem zu betreuen.
Dies führt natürlich zu Frustration, Ressentiments und verminderter Motivation, ganz zu schweigen von den Schwierigkeiten, Techniker einzustellen und zu halten.

* Die Umwandlung zu Cloud Native nimmt viel Zeit in Anspruch.

* Wenn Menschen etwas lernen, müssen sie es sehr bald anwenden.

* Eine Fehlausrichtung von Technik und Organisationskultur führt zu Frustration.

* Die Menschen werden durch die Hoffnung auf zukünftige Verbesserungen motiviert oder durch mangelnde Hoffnung frustriert.

## Deshalb

Die Teams werden schrittweise von der alten Organisationsstruktur in die neue überführt (Gradweise Einarbeitung).
Strukturieren Sie die Teams um und wechseln Sie kurz vor dem neuen Onboarding von der Hierarchie zur Cloud-Native-Plattform (wenn diese voll einsatzbereit ist).
Dies ist eine organisatorische Version von Martin Fowlers architektonischem Würgemuster (Strangler Fig Application):
Langsames Würgen des Prozesses und Wasserfall-Kulturdenkmäler (wie etwa Spezialistenteams) inkl. des Monolithen selbst.
Die beiden Systeme, das alte und das neue, können während des Migrationsprozesses gut koexistieren.
Sobald der Prozess abgeschlossen ist, können die verbleibenden Teile des Altsystems auf die neue Cloud-Native-Plattform portiert werden (Lift and Shift am Ende) und nach und nach in Microservices umgestaltet werden, bis der alte Monolith nicht mehr vorhanden ist und die Wartungsmitarbeiter nun Erfahrung mit Cloud Native haben.

* Ständige Weiterbildung.

* Fördern Sie das Experimentieren.

* Wechsel von der Hierarchie zu Stämmen und Delegation.

* Vermeiden Sie Training und Umstrukturierung, wenn das Team nicht plant, bald auf Cloud Native umzusteigen.

* Erstellen Sie einen Plan für alle Legacy-Teams, führen Sie ihn aber erst aus, wenn der Umzug kurz bevorsteht.

## Folglich

Das alte System funktioniert wie immer während das neue System aufgebaut wird.
Die Teams werden nach und nach umgestellt.
Die Teams werden erst dann umstrukturiert und umgeschult, wenn es Zeit für sie ist, tatsächlich umzuziehen.
Während Sie auf der alten Plattform arbeiten, liefern Sie weiterhin hervorragende Leistungen.
Anschließend wechseln Sie zur neuen Plattform und liefern dort ebenso gut.

- {:.plus} Es gibt einen klaren Plan für alle Teams.

- {:.plus} Organisatorische / kulturelle Veränderungen sind auf die technischen Veränderungen abgestimmt.

- {:.plus} Ursprüngliche und neue Kulturen existieren nebeneinander, aber nur vorübergehend, bis der vollständige Transfer in die Cloud abgeschlossen ist.

- {:.minus} Mögliche Zusammenstöße zwischen den Teams.

- {:.minus} Legacy-Teams könnten durch mangelnde Veränderungen enttäuscht werden.
