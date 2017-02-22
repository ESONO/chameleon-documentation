### Grundlagen

Der **Freigabe Workflow** lässt sich Tabellen/Modul-bezogen aktivieren. Er ermöglicht das Anlegen, Ändern und Löschen von Inhalten, ohne dass diese Anpassungen am Inhalt sofort auf der Website ersichtlich sind. 

<u>Zusatzinfo für Entwickler:</u> Dazu werden neu angelegte Datensätze und gelöschte Datensätze markiert und in Website-Modulen darauf gefiltert. Neu angelegte Datensätze erscheinen somit nicht und gelöschte bleiben noch sichtbar. Geänderte Datensätze werden beim Speichern nicht in der Datenbank gespeichert, sondern als Objekte in einer Changelog-Tabelle abgelegt.

Änderungen werden als ```Aktionen``` bezeichnet. Aktionen werden zu ```Transaktionen``` zusammengefasst. Transaktionen können an andere Redakteure weitergeleitet werden, z.B. zur Kontrolle oder zur Freigabe. Es ist immer nur möglich, eine gesamte Transaktion zu veröffentlichen (Freigabe).

Transaktionen lassen sich für eine Vorschau aktivieren. In diesem Fall werden alle Änderungen der aktivierten Transaktion auf der Website angezeigt.