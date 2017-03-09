### Einen redaktionellen Artikel anlegen

    Artikel (redaktionell) → Artikel (redaktionell)

`Basisdaten`

In den Basisdaten wird der Inhalt des Artikels sowie alle relevanten Daten zur Veröffentlichung hinterlegt.

Wie bereits oben beschrieben, muss hier der `Artikeltyp` ausgewählt werden. Damit der Artikel in einer automatisierten Liste oder an einer bestimmten Stelle in der Navigation erscheint, muss er ebenfalls einer vorher definierten `Kategorie` zugewiesen werden.[^1]

Der eigentliche Text wird im Feld `Artikeltext` eingetragen. Hier stehen alle Funktionen des [WYSIWYG-Editors](/ckeditor.md) zur Verfügung.



`Teaser`

Über das Teaser-Format wird festgelegt, wie der Teaser auf der Website erscheint, ob z.B. als Slider, Bild mit Link, nur Bild, Bild mit Überschrift und Text usw.

Zusätzlich zur Überschrift und dem eigentlichen Teasertext kann noch ein Bild eingefügt werden.

Für einen Artikel können beliebig viele Teaser mit unterschiedlichen Ausgabearten (Formaten angelegt werden). So kann ein Artikel an mehreren Stellen in unterschiedlicher Form eingebunden werden.

### Redaktionelle Artikel über Artikellisten anzeigen

Das Listenmodul stellt eine Liste von Artikeln dar, die mit Filtern eingeschränkt werden kann. Die Liste kann dabei auf einzelne Artikel, Artikelkategorien oder Artikeltypen eingeschränkt werden. Für die Liste kann zudem eine Sortierung und ein Filter angegeben werden. Außerdem kann gewählt werden, welche Sortierung und Filter im Frontend zur Auswahl stehen sollen. 

Das Artikellistenmodul kann z.B. auch auf Artikeldetailseiten verwendet werden, um passende Artikel zum aktuell aktiven Artikel darzustellen, einfach den entsprechenden Filter verwenden. Der Name des Listviews ergibt sich aus dem Namen des Views vom Listenmodul. 

Um eine Artikelliste anzulegen, wählen Sie im Modul `Artikel-Liste (redaktionell)`. Wählen Sie sodann die gewünschte Teaservorlage aus, zum Beispiel `Bild mit Überschrift auf schwarzem Overlay (Bildergalerie)`.

![](/assets/red_artikelliste1.png)

<br>
Über `Editieren` und `Neu` legen Sie eine Liste an.
<br>

Tab `Basisdaten`

`Sortierung`: Sie können beliebig viele Listen im Modul unterbringen. Über Sortierung kann die Reihenfolge der Liste verschoben werden.

`Standardsortierung`: Wählen Sie, in welcher Reihenfolge die Artikel erscheinen sollen (nach Datum, Überschrift oder manueller Selektion

`Überschrift:` Wird im Frontend über der Liste angezeigt

`Einträge je Seite`: Hier können Sie angeben, wieviele Artikel auf einer Seite erscheinen dürfen (bei mehr Artikeln als angegeben wird eine nächste Seite erstellt, die über Blättern erreichbar ist)

`Artikelanzahl beschränken auf`: Hier können Sie angeben, wieviele Artikel insgesamt ausgespielt werden dürfen (z.B. von 30 Artikeln maximal 10)

Die Liste kann nun weiter eingeschränkt werden, z.B. nach **Artikeltyp** oder **Kategorie** (z.B. Thema _Literatur_ / Kategorie _Zeitgenössische Autoren_ - in der Liste werden nur Teaser von Artikeln angezeigt, die der Kategorie *Zeitgenössische Autoren* zugewiesen sind).

<br>
Tab `Filter`

Es ist auch möglich, einer Liste manuell Artikel zuzuweisen, indem man bei  `Auf folgende Artikel einschränken` den entsprechenden Datensatz (Artikel) verknüpft). Dann ist eine Einschränkung über Typen oder Kategorien nicht notwendig.

<br>


[^1]: Ausnahme: manuelle Zuweisung von Artikeln in einer Liste, sh. nachfolgenden Abschnitt _Redaktionelle Artikel über Artikellisten anzeigen_.




