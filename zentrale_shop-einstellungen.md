## Zentrale Shop-Einstellungen
----
### Shops

    Shop-Einstellungen → Shops

Unter `Shops` werden alle vom System verwalteten Shops aufgelistet. Ist nur ein Shop definiert, gelangt man direkt in die Einstellungen des Shops, sind jedoch mehrere definiert, wird eine Auswahl eingeblendet.

| Tab | Beschreibung |
| -- | -- |
| Basisdaten | Pflege der grundlegenden Daten zum Besitzer und Zugehörigkeit des Shops |
| Standardeinstellungen | Einstellungen (z.B. Standard-MwSt-Satz, Standardsortierung der Artikellisten), die verwendet werden, wenn keine abweichenden Detail-Einstellungen (z.B. in Kategorien) vorgenommen wurden. |
| Sucheinstellungen | Für den Suchindex und die Suche relevante Angaben |
| Konfiguration | Die zentrale Konfiguration des Shops |
| Systemeinstellungen | Angaben über die zuletzt verwendeten Bestell-/Kundennummern sowie den zentralen Shop-Handler sowie max. Größe des Artikelhistorie-Cookies und welche SEO-URLs-Version aktiv ist. |
| Bewertung | Nach wieviel Tagen erhält der Kunde eine Bewertungsaufforderung, wieviel Prozent der Kunden erhalten diese, erhält der Kunde bei jeder Bestellung eine Bewertungsaufforderung |
| Trusted Shops | TrustedShop-Konfiguration |

<br>

[währungen](zentrale_shop-einstellungen.md#w-hrungen)

#### Shop-Textbausteine

    Shop-Einstellungen → Shops → Konfiguration → Shop-Textbausteine (z.B. AGB)
    

Hier können Textbausteine, die ausschließlich für Shops gedacht sind, erstellt werden. Somit können Sie z.B. eine Seite mit Informationen wie AGB, Datenschutz etc. erstellen. Natürlich lassen sich einzelne Bausteine auch auf verschiedenen Seiten anlegen. 

Im Backend ist dafür auf einer Seite das Modul `Shop spezifische Informationen` anzulegen. Im Modul können Sie dann einfach per Klick auswählen, welche Textbausteine auf der Seite angezeigt werden sollen. 

![](/assets/Shopspezifische_Textbausteine.png)

Der Unterschied zu den [Textbausteinen](/textbausteine.md) ist, dass die Shop-Textbausteine ausschließlich den Shop betreffen, die Textbausteine (`Website → Textbausteine`) jedoch global eingesetzt werden können, also auch auf reinen Content-Webseiten.

### Benutzereinstellungen (Extranet-Konfiguration)

    CMS / Portal-Einstellungen → Extranet-Konfiguration

In der Extranet-Konfiguration können Einstellungen vorgenommen werden, die für die Interaktion mit dem Portal-/Shop-Besucher notwendig sind, z.B. bei der Registrierung, bei ungültigem Login oder bei vergessenem Passwort. 
Unter `Seiten` können entsprechende Landing-Pages definiert werden, die dem Kunden bei Aktionen wie „verweigertem Zugriff“ oder nach einer „erfolgreichen Registrierung“ angezeigt werden sollen.

### Benutzerländer

    Shop-Einstellungen → Benutzerländer

Die zur Registrierung verfügbaren Länder. In welche Länder generell Ware geliefert wird, wird in den [Versandkostenarten](/versandkostenart.md) definiert.

### Maßeinheiten

    Shop-Einstellungen → Maßeinheiten

Hier werden die Maßeinheiten für die Grundpreisberechnung hinterlegt.

Jede Einheit besteht dabei aus folgendem:

* Name: *Gramm*
* Symbol oder Abkürzung: *g*
* Faktor, mit dem eine Einheit multipliziert werden muss, um auf die Grundeinheit zu kommen. <u>Beispiel</u>: Für die Einheit Gramm muss der Faktor *0,001* sein, um auf die Grundeinheit kg zu kommen.
* Die Grundeinheit (ein Verweis auf eine Maßeinheit mit dem Faktor 1): <u>Kilogramm</u>

### Umsatzsteuergruppen

    Shop-Einstellungen → Umsatzsteuergruppen

Alle über den Shop verwaltbaren Steuergruppen. 

### Variantensets

Werden mehrere Varianten eines Artikels angeboten, müssen hier die passenden Variantensets angelegt werden, wie z.B. ein Variantenset *Rahmengröße und Farbe* bei Fahrrädern.

Das Anlegen von Variantensets und Varianten eines Artikels wird im Kapitel [Artikelvarianten](/artikelvarianten.md) beschrieben.

### Währungen

Wenn Ihr Shop über mehrere Währungen verfügt, werden diese hier definiert. Dabei wird ein Umrechnungsfaktor zur Basiswährung angegeben.



