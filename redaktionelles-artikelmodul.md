## Redaktionelles Artikelmodul

Das redaktionelle Artikelmodul kann verwendet werden, um Artikel  in Form von Teasern, Listen und Detailseiten darzustellen. *Artikel* sind dabei in Typen unterteilt, die sich in der Darstellung stark unterscheiden und nahezu beliebigen Content enthalten können, sei es einfach nur Überschrift und Text, ein Video oder eine Bildergalerie. Die Artikel lassen sich in Kategorien einteilen, die dann z.B. bestimmen können, unter welchem Navigationspunkt ein Artikel erscheint. Es ist sogar möglich, die Navigation oder Teile davon automatisch aus den Artikelkategorien generieren zu lassen.

### Artikeltypen

    Artikel (redaktionell) → Artikeltypen

Jeder Artikel muss einem Artikeltyp zugeordnet sein. Der Artikeltyp bestimmt, welche Darstellung für den Artikel verwendet wird und welche Datenbankfelder aus pkg_article für diesen Typ freigeschaltet sind. Alle anderen Felder werden dann beim Editieren des Artikels im Backend ausgeblendet. So können z.B. bei einem Artikel vom Typ *Magazin* die Felder Herausgeber, Jahrgang, Heftnummer etc. angegeben werden, die aber bei einem Artikel vom Typ News/Text nicht erscheinen. Wenn es unterschiedliche Artikeltypen gibt oder die Artikel sich stark unterscheiden, ist es sinnvoll, eine zusätzliche Tabelle mit den benötigten Feldern anzulegen und die Einstellung „enthält nur einen Datensatz“ zu aktivieren. Dann in der Artikeltabelle nur eine Eigenschaft für diese Tabelle anlegen.
Außerdem kann für jeden Artikeltyp eine eigene Extension für das pkg_article-Objekt angegeben werden. 

In der Regel werden die Artikeltypen durch Ihren Dienstleister vorkonfiguriert.

### Artikelkategorien

    Artikel (redaktionell) → Artikelkategoriegruppen
    
Das Artikel-Package kennt Artikelkategoriegruppen und Kategorien. Kategorien sind Eigenschaften der Artikelkategoriegruppen und können beliebig verschachtelt sein. Artikel werden immer Kategorien zugeordnet, nicht Artikelkategoriegruppen. Kategorie und Kategoriegruppe sind auch Teil des SEO-Links. Die Kategorien können verwendet werden, um Listen danach zu filtern und Artikel  in die Navigation einzubinden.

Legen Sie zuerst eine Artikelkategoriegruppe an, danach entsprechenden Kategorien an.

![](/assets/artikelkategorien.png)

<br>

### Teaser

   
Mit dem Teaser-Modul können einzelne Teaser angelegt werden, die dann auf Artikel oder wahlweise auch auf eine CMS-Seite oder eine externe URL verweisen können. Für die Teaser kann ein Teaser-Format gewählt werden über das die Darstellung des Teasers bestimmt wird. Die Teaser-Formate können im Backend angelegt werden. 

    Artikel (redaktionell) → Artikel Teaser-Formate

Beispiele:
![](/assets/teaserformate.png)

<br>

### Einen redaktionellen Artikel anlegen

    Artikel (redaktionell) → Artikel (redaktionell)

`Basisdaten`
In den Basisdaten wird der Inhalt des Artikels sowie alle relevanten Daten zur Veröffentlichung hinterlegt.

Wie bereits oben beschrieben, muss hier der `Artikeltyp` ausgewählt werden. Damit der Artikel in einer automatisierten Liste oder an einer bestimmten Stelle in der Navigation erscheint, muss er ebenfalls einer vorher definierten `Kategorie` zugewiesen werden.

Der eigentliche Text wird im Feld `Artikeltext` eingetragen. Hier stehen alle Funktionen des [WYSIWYG-Editors](/ckeditor.md) zur Verfügung.


`Teaser`



