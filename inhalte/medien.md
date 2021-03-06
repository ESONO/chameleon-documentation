# Medien

Über den Punkt `Medien` gelangt man zu der zentralen Bilder- und Medienverwaltung im Chameleon-System. Hier können neue Medien wie Bilder und Videos hochgeladen sowie bestehende entfernt oder aktualisiert werden.

Die Verwaltung öffnet sich in einem neuen Fenster \(d.h. die aktuelle Seite, die man bearbeiten möchte, bleibt im Hintergrund geöffnet\).

![](../.gitbook/assets/medienverwaltung.png)

Die Verzeichnisstruktur links und die Suchfunktion unten ermöglichen ein schnelles Auffinden der gesuchten Datei. Über die rechte Maustaste erreicht man das Kontextmenü. Hier hat man die Möglichkeit, die Baumstruktur links zu bearbeiten \(Ordner anlegen, löschen, verschieben, umbenennen\) und Dateien hochzuladen, zu importieren oder zu verschieben. Es können mehrere Dateien gleichzeitig hochgeladen werden.

| Bezeichnung | Beschreibung |
| :--- | :--- |
| Neuer Ordner | Erstellt einen neuen Ordner. |
| Löschen | Verzeichnis sowie alle Unterverzeichnisse und Medien werden entfernt. Alle Zuweisungen in Seiten und Datensätzen werden entfernt. |
| Bewegen | Versetzen kompletter Baumknoten innerhalb der Baumstruktur. |
| Dateien hochladen | Manuelles Hochladen der Dateien vom Client-Rechner. |
| Dateien importieren \(FTP\) | Importieren aller Dateien, die im Verzeichnis _private/cmsdata/mediaImport_ liegen und zuvor per FTP _\(FTP-Zugang erforderlich\)_ hochgeladen wurden. |
| Dateien hierhin verschieben | Alle Dateien, die markiert und ausgeschnitten wurden, können über diese Funktion in das markierte Verzeichnis verschoben werden. |
| Umbenennen | Benennt ein Verzeichnis um. |

Möchten Sie ein Bild oder Video durch ein anderes ersetzen, rufen Sie den entsprechenden Bild-Datensatz in `Medien` auf und laden über `Mediendatei ersetzen` die neue Datei hoch. Das Bild \(Video, ...\) wird nun an allen hinterlegen Stellen auf der Website automatisch ersetzt.

Die Medienverwaltung ist auch im Datensatz, in dem das Bild eingefügt werden soll, über den Button `Medien verwalten` erreichbar. Zudem kann die Datei auch direkt im Datensatz in den entsprechenden Ordner hochgeladen werden.

![](../.gitbook/assets/medienverwaltung_datensatz.png)

Beim Bildmaterial muss grundsätzlich darauf geachtet werden, dass keine Bilder im CMYK-Format hochgeladen werden \(das Hochladen funktioniert in dem Fall nicht\). Des Weiteren sollte darauf geachtet werden, dass nach Möglichkeit keine Bilder in zu hoher Auflösung \(z.B. direkt von der Kamera\) hochgeladen werden - je nach Server-Konfiguration kann dies zu Problemen führen. Die Dateigröße darf die unter _CMS Einstellungen → Uploader Konfiguration_ eingestellten Upload-Werte nicht überschreiten.

