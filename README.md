Edirom-Editor
=============

Edirom Editor (a web technology based client application wrapped into an Eclipse RCP container) is an editor with which digital music editions are prepared.

## Edirom Editor 1.1.21 (2012-05-10)

* Fehler beim Backup der Datenbank unter Windows behoben
* Fehler beim Löschen von Quellen behoben

## Edirom Editor 1.1.20 (2012-03-01)

* Anpassung der Werkzeugfenster in der Ansicht "Synopse" im Werk an kleine Bildschirme

## Edirom Editor 1.1.19 (2012-02-02)

* Problem beim Speichern vieler Einzelaktionen (viele Takte angelegt, Taktkonkordanzen über viele Takte) gelöst. Es besteht weiterhin eine maximale Größe eines Speicherbefehls, sodass bei hinreichend vielen Änderungen der Fehler weiterhin auftreten könnte (siehe [Problemlösungen](http://www.edirom.de/edirom-projekt/software/problemloesungen/#c1117)).

## Edirom Editor 1.1.18 (2012-01-19)

* Auslesen von Anmerkungen in Werken beschleunigt
* Fehler im Export zur Edirom Anzeige behoben

## Edirom Editor 1.1.17 (2011-11-29)

* Ex- und Import einzelner Quellen wieder über das Menü "Extras" möglich. Dieses Feature ist noch im Beta-Stadium, es sollte also vor einem Import immer ein Backup angelegt werden.
* Im Menü "Extras" lassen sich unter "Bildbestand aufräumen..." die in der Installation enthaltenen Bilder entfernen, die keine Referenz in den Notentexten haben. Das sollte versehentlich nicht gelöschte Bilder aus der Installation entfernen.

## Edirom Editor 1.1.16 (2011-11-18)

* Export in die Edirom-Anzeige stark überarbeitet
	* neue ID-Strukturen
	* Fehlerbehebungen
	* BarGroups in Anmerkungen (ein Symbol bei zusammenhängenden Takten)
	* Quellendatierung kann beliebigen Wert enthalten
* Menü-Eintrag für das Neu-Laden von Fensterinhalten
* Geschwindigkeitsverbesserungen durch komprimierte Javascript- und CSS-Dateien
* Satz-Filter für Takte in Synopse

## Edirom Editor 1.1.15 (2011-11-07)

* Für den Editor ist nun eine aktive Internetverbindung nicht mehr nötig. Es könnte sein, dass das Programm über den Menüpunkt Extras -> Zurücksetzen und Neustarten neu gestartet werden muss, damit die Änderungen wirksam werden.
* Das MEI-Schema ist so geändert worden, dass beim Wiederherstellen einer Datenbank-Instanz Takte, die nicht korrekt mit Markierungen angelegt wurden, keinen Fehler verursachen.

## Edirom Editor 1.1.14 (2011-11-02)

* Reverse Index eingeführt, um schneller in Konkordanzen suchen zu können

## Edirom Editor 1.1.13 (2011-07-28)

* Mechanismus zum Aufräumen des Bildservers rausgenommen

## Edirom Editor 1.1.12 (2011-07-07)

* Bug beim Ersetzen von unerlaubten Zeichen im Exportnamen gefixt
* Beim Export werden die Quellennamen korrekt in die NavigatorDefinition geschrieben
* Vorschaubilder in der synoptischen Ansicht werden nachgeladen und sollten so das Arbeiten nicht aufhalten
* Vorschaubilder für Takte gibt es vorerst nicht mehr

## Edirom Editor 1.1.11 (2011-05-18)

* Name einer neuen Anmerkung von "Unbenannt" auf "Neue Anmerkung" geändert
* Hilfe für andere Browser überarbeitet und online (http://www.edirom.de/EdiromEditor/help/) gestellt
* Schemata werden beim Export für die Edirom Anzeige wieder mit ausgegeben


## Edirom Editor 1.1.10 (2011-04-26)

* Erste öffentliche Beta
* Kontextabhängiges Hilfesystem mit Videoanleitungen
* Neues Programm-Icon
* Anlegen und Bearbeiten von TEI-Texten
* Verknüpfen von TEI-Texten und Notentexten als Quellenbeschreibung
* Verbesserung der Geschwindigkeit von Lade- und Speichervorgängen
* Fehlerbehebungen an versch. Stellen

