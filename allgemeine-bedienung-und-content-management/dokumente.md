# Dokumente

Über den Punkt `Dokumente` gelangt man zur zentralen Dokumentenverwaltung im Chameleon-System. Hier werden alle Daten abgelegt, die den Besuchern der Webseite als Download zur Verfügung gestellt werden sollen.

Von hier aus kann man neue Dokumente hochladen sowie bestehende entfernen oder aktualisieren. Die Verzeichnisstruktur links und die Suchfunktion ermöglichen ein schnelles Auffinden der gesuchten Datei. Für die genaue Beschreibung der Funktionen aus dem Kontextmenü siehe Kapitel [Medien](medien.md).

Die Dateigröße darf die unter `CMS / Portal-Einstellungen → CMS Einstellungen → Uploader Konfiguration` eingestellten Werte nicht überschreiten.

Eine Besonderheit der Dokumente ist die Einstellung _geschützt: NEIN/JA_. Für nicht geschützte Dokumente wird ein öffentlich verfügbarer und menschlich lesbarer Link auf die Datei angelegt \([http://ww.mydomain.de/chameleon/outbox/public/categoryId/FileName.pdf](http://ww.mydomain.de/chameleon/outbox/public/categoryId/FileName.pdf)\).

Als _geschützt_ markierte Dateien werden hingegen nicht direkt verlinkt, sondern durch einen Download-Manager ausgeliefert \(SEO Handler\). Dieser reagiert auf eine per config einstellbare URL \(Config Konstante: URL\_PROTECTED\_DOCUMENT\_VIRTUAL\_OUTBOX\). Außerdem kann aktiviert werden, dass der Download nur für angemeldete Benutzer zugreifbar ist \(CHAMELEON\_CHECK\_VALID\_USER\_SESSION\_ON\_PROTECTED\_DOWNLOADS\). Für z.B. kaufbare Downloadprodukte kann alternativ zu Login-Prüfungen ein Download auch mit einem temporären "Schlüssel" \(Token\) versehen werden, der nach Zeit x ausläuft \(einstellbar über: CHAMELEON\_DOCUMENT\_AUTH\_TOKEN\_LIFE\_TIME\_IN\_MINUTES\).

