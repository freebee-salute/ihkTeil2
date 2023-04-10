# 3-Schichten-Architektur

Die 3-Schichten-Architektur für Webanwendungen ist ein Designmuster für die Strukturierung von Anwendungen, bei dem die Anwendung in drei logische Schichten aufgeteilt wird: Präsentation, Logik und Daten.

Die Präsentationsschicht (auch Benutzerschnittstelle genannt) ist die oberste Schicht, die die Anwendung dem Benutzer zugänglich macht. Hier werden die Benutzereingaben entgegengenommen und angezeigt.

Die Logikschicht (auch Geschäftsschicht genannt) ist die Schicht, die die Geschäftslogik der Anwendung beinhaltet. Hier werden die Datenvalidierung, Geschäftsregeln und Prozesse implementiert.

Die Datenschicht (auch Datenzugriffsschicht genannt) ist die Schicht, in der auf Datenbanken oder andere Datenquellen zugegriffen wird. Hier werden Datenabfragen und -aktualisierungen durchgeführt.

Durch die Trennung in diese drei Schichten wird die Anwendung modular und flexibel. Jede Schicht kann unabhängig von den anderen Schichten entwickelt und getestet werden, was die Wartbarkeit und Skalierbarkeit der Anwendung erleichtert.
