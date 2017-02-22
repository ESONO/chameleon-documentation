### Changelog

#### Zweck / Nutzen
Änderungen im CMS werden protokolliert. 

#### Voraussetzungen
Chameleon Core 4.0.x 

#### Verwendung

Das Changelog kann pro Tabelle (= ein Menüpunkt oder Menüunterpunkt im CMS) aktiviert werden. Die Aktivierung wird vom CMS-Administrator (in der Regel Ihr technischer Ansprechpartner) in den Tabelleneinstellungen vorgenommen.
 
Es werden folgende Änderungsarten unterschieden:

* neu (insert)
* geändert (update)
* gelöscht (delete) 

Die Änderungen können an 3 Stellen eingesehen werden:
 
1. Im Datensatz selbst – klicken Sie hier auf den Button „Änderungen anzeigen“ oberhalb des Datensatzes. Es werden alle Änderungen angezeigt, die diesen Datensatz betreffen. 
2. Beim Menüpunkt, auch hier gibt es den Button „Änderungen anzeigen“. Die Changelog-Liste zeigt hier alle Änderungen, die zu diesem Menüpunkt gehören. 
3. Beim Menüpunkt „CMS Changelog“ (unter CMS Admin). Hier werden alle Änderungen, die im gesamten CMS vorgenommen wurden und für die das Changelog aktiviert wurde, angezeigt. 
 
Die Änderungen werden als Liste angezeigt, innerhalb dieser jede Änderung als einzelner Datensatz mit Detailinformationen aufrufbar ist. 
<br>
###### Liste (Übersicht)
![](/assets/changelog_liste.png)
<br>
###### Datensatz
![](/assets/changelog_datensatz.png)
Im Datensatz werden diese Änderungsinformationen angezeigt: 
* Änderungsdatum
* Benutzer, der die Änderung durchgeführt hat
* Haupttabelle, die geändert wurde
* ID des veränderten Datensatzes
* Name des veränderten Datensatzes
* Art der Änderung (neu, geändert, gelöscht)
* Was wurde geändert (alter Wert / neuer Wert) 

<br>
###### CSV-Datei
Das Changelog kann außerdem auch in eine CSV-Datei exportiert werden. Rufen Sie hierfür im Hauptmenü den Menüpunkt `Generischer Tabellen-Export → ExportChangelog` auf und betätigen den Button `Export als Download ausführen`. 