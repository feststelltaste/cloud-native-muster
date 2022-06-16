## Muster: Plattformteam

Ein Team zu bilden, das für die Architektur, den Aufbau und den Betrieb einer einzigen, konsistenten und stabilen Cloud-Native-Plattform für die gesamte Organisation verantwortlich ist, so dass sich die Entwickler auf die Entwicklung von Anwendungen konzentrieren können, anstatt die Infrastruktur zu konfigurieren.

![](../_images/5e15b1c2b3b448ca02b891b9_47.%20Personalised%20Co-creation.png)

## Ausgangslage

Ein Unternehmen wechselt in die Cloud und führt eine Microservices-Architektur ein.
Viele Teams bauen viele verschiedene Services auf und sie benötigen zusätzliche Tools, um die Infrastruktur für den Betrieb ihrer Anwendungsteile zu schaffen.

## In diesem Kontext

Wenn es kein einziges Team gibt, das für die Schaffung einer offiziellen Cloud-Native-Produktionsplattform für die Transformation verantwortlich ist, muss jedes Team, das für verschiedene Microservices zuständig ist, seine eigene Plattform aufbauen.
Dies führt zu Doppelarbeit, verschwendet Zeit und &ndash; was am kritischsten ist &ndash; zu Konflikten, wenn es um den Einsatz geht.
Da jeder Service mit einem anderen Ansatz auf einer maßgeschneiderten Plattform aufgebaut wurde, werden diese widersprüchliche Bedürfnisse haben und es wird schwierig (wenn nicht gar unmöglich sein), alles auf einer einheitlichen Plattform zu betreiben.
Die Betriebsmitarbeiter stecken in dem Versuch fest, eine Art Frankenstein-Lösung zu finden, aber es ist unwahrscheinlich, dass sie in der Lage sein wird, sie zum Funktionieren zu bringen.

* Verschiedene Teams werden unterschiedliche Lösungen entwickeln, wenn sie nicht koordiniert werden.

* Eine einfache Cloud reicht nicht aus: eine komplexe und benutzerdefinierte Konfiguration ist erforderlich.

* Die Standardisierung maximiert die Möglichkeit der Wiederverwendung.

* Wahlfreiheit ist erforderlich, um die besten Lösungen zu finden.

* Die Menschen sind kreativ bei der Suche nach Möglichkeiten, die durch den Mangel an einer Plattform gesetzten Hindernisse zu umgehen, was zu einem "Schatten-IT"-Effekt führt.

## Deshalb

Das Plattformteam wird die Plattform selbst verwalten.
Dies umfasst alles zwischen der Cloud und den Anwendungen (oder, um es mit der aktuellen technologischen Landschaft auszudrücken, Kubernetes und darunter).
Die Entwickler sind nur für die Erstellung der Anwendungen selbst verantwortlich (auch hier, in der aktuellen technischen Landschaft, Kubernetes und darüber).

* Stellen Sie ein separates Team zusammen, das für die Auswahl, Erstellung und Konfiguration eines grundlegenden Satzes von Werkzeugen und Praktiken verantwortlich ist, die von allen Entwicklungsteams verwendet werden.

* Bauen Sie eine Plattform, die von der gesamten Organisation verwendet wird.

* Erstellen Sie einen standardisierten und wiederverwendbaren Werkzeugsatz, um die Arbeit für die Entwickler zu vereinfachen.

## Folglich

Die Entwickler können sich auf die Entwicklung individueller Anwendungsdienste, Features und Funktionen konzentrieren, während sich das Plattformteam um den Betrieb der Plattform selbst kümmert.
Entwickler können zwar eigene Tools einführen, müssen diese jedoch als Teil ihrer eigenen Anwendung unterstützen, es sei denn, die Tools haben sich als stabil erwiesen und/oder werden von anderen Entwicklungs-Teams angefordert.

- {:.plus} Es gibt eine konsistente, wiederverwendbare und vor allem stabile Plattform, die sicherstellt, dass alle Dienste nahtlos zusammenarbeiten.

- {:.plus} Es gibt weniger Arbeit für die Entwickler: sie können sich einfach auf die Entwicklung von Anwendungen konzentrieren und müssen sich keine Gedanken über die Plattform machen, auf der sie laufen werden.

- {:.minus} Es gibt auch weniger Freiheit für die Entwickler, ihre Werkzeuge zu wählen, obwohl die Wahl immer noch möglich ist.
