# Klassen-Glücksrad

Ein animiertes Glücksrad zur zufälligen Auswahl von Schülern. Die App besteht aus einer einzelnen HTML-Datei und benötigt weder Python noch einen Webserver oder eine Internetverbindung.

## Starten

1. [index.html](./index.html) herunterladen oder den Projektordner öffnen.
2. `index.html` doppelklicken und in Microsoft Edge, Chrome oder Firefox öffnen.
3. Eine Klasse anlegen, Schüler hinzufügen und auf **Drehen** klicken.

## Funktionen

- Mehrere Klassen mit eigenen Schülerlisten verwalten.
- Schüler hinzufügen, entfernen sowie per Checkbox aktivieren oder deaktivieren.
- Der ausgewählte Schüler bleibt als hervorgehobenes Segment auf dem Rad sichtbar, wird in der Liste deaktiviert und mit dem Auswahldatum versehen.
- Inaktive Segmente bleiben bis zum nächsten Dreh sichtbar und verschwinden dann vom Rad.
- Wird ein Schüler manuell wieder aktiviert, werden Auswahldatum und Gewinner-Markierung entfernt.
- Klassen, Aktiv-Status, Auswahldaten und die aktuelle Gewinner-Markierung werden im lokalen Browserspeicher abgelegt.
- Das Rad erzeugt beim Drehen ein optional abschaltbares Rattergeräusch. Es bremst kurz vor einer zufälligen Segmentgrenze fast bis zum Stillstand ab und springt manchmal im letzten Moment ins Nachbarfeld.
- Über **Exportieren** lässt sich eine JSON-Sicherungsdatei speichern; **Importieren** lädt eine solche Datei wieder.
- Das Rad lässt sich mit der Leertaste drehen, wenn kein Eingabefeld fokussiert ist.

Die Daten bleiben auf diesem Gerät und in dem Browser, in dem die Datei geöffnet wurde. Exportiere regelmäßig eine JSON-Datei, wenn du deine Klassen sichern oder in einem anderen Browser verwenden möchtest. Die JSON-Datei enthält Namen, Aktiv-Status und Auswahldaten der Schüler; behandle sie daher vertraulich.
