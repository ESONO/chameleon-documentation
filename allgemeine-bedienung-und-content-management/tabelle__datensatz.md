# Tabelle / Datensatz

Im oberen Bereich eines Datensatzes werden - wie in der Listenansicht - die verfügbaren Funktionen aufgeführt. Diese können auch jederzeit über das Rechtsklick-Menü im Datensatz erreicht werden.

![](../.gitbook/assets/datensatz_funktionen.png)

## Speichern

Über den Button wird der aktuelle Stand der Daten in die Datenbank geschrieben. Sollten nicht alle Pflichtangaben ausgefüllt worden sein, wird der Speichervorgang mit einer entsprechenden Meldung unterbrochen \(es werden also keine Daten gespeichert\).

## Kopieren

Kopiert den aktuellen Datensatz _direkt aus der Datenbank_. Sollten also Änderungen gemacht worden sein, die noch nicht gespeichert wurden, dann sind diese Änderungen weder im Original-Datensatz noch in der Kopie enthalten.

## Neu

Legt einen neuen, leeren Datensatz an.

{% hint style="warning" %}
Auch wenn Sie den Datensatz nicht befüllen und noch nicht gespeichert haben, ist dieser angelegt. Wenn Sie also versehentlich einen neuen Datensatz erstellt haben, löschen Sie ihn wieder. Ansonsten weist das Backend zahlreiche leere Datensätze auf \(in der Listenansicht können Sie prüfen, ob leere Datensätze vorhanden sind\).
{% endhint %}

## Löschen

Löscht den aktiven Datensatz. Nach dem Löschen landet der Benutzer wieder auf der Listenansicht der Tabelle.

## Sprache kopieren

Hier werden Felder, die in der aktuellen Sprache nicht übersetzt sind, aus der anderen Sprache kopiert.

## Datensatz wechseln

Im oberen Bereich des Datensatzes steht ein Eingabefeld zur Verfügung über welches andere Datensätze aus der Datensatzliste geladen werden können. Angezeigt und durchsucht wird immer das Namensfeld der Datensätze.

![](../.gitbook/assets/datensatz_wechseln.png)

## Datensatz-Details

Im oberen linken Bereich wird die ID des aktiven Datensatzes angezeigt. Dabei werden sowohl eine ID wie auch eine GUID \(global unique identifier\) aufgeführt. Bei der GUID handelt es sich entweder um die gleiche Nummer wie ID, oder um ein 36 Zeichen langen Identifier \(je nachdem ob Komplexe ID Felder in den CMS-Einstellungen aktiviert wurden\).

Darauf folgt eine Liste aller Felder des Datensatzes. Neben manchen Feldern taucht Links neben dem Eingabefeld zusätzlich ein kleines Fragezeichen ![](../.gitbook/assets/hilfe.png) auf - hinter diesem Symbol verbirgt sich ein Hilfe/Erklärungstext für das Feld. Der Text wird durch einen Klick auf das Symbol eingeblendet.

{% hint style="warning" %}
Bei manchen Feldern wird bei Editieren die Seite gewechselt. Da das System Änderungen nicht automatisch speichert, sollte der Benutze diese vorher durch ein Klick auf den Speichern-Button sichern.
{% endhint %}

