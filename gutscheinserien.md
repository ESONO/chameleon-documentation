### Gutscheine erstellen


    Rabatte & Gutscheine → Gutscheinserien

Gutscheine können entweder einen absoluten oder einen prozentualen Wert zur Nachlassgewährung haben. Prozentuale Nachlässe beziehen sich immer auf den Gesamtwert des Warenkorbes (Bruttosumme der Produkte). 

Es wird zwischen Aktionsgutscheinen und gesponserten Gutscheinen (= Kaufgutschein, d.h. jemand hat für den Gutschein gezahlt) unterschieden.
Bei Aktionsgutscheinen wird der Gutscheinwert von der Bruttosumme des Warenwertes abgezogen, dementsprechend reduziert sich die berechnete Mehrwertsteuer.


![](/assets/gutschein_aktion.png)
<br>

Gesponserte Gutscheine hingegen werden wie ein Zahlungsmittel verwendet, werden also nach der Steuer abgezogen und wirken sich daher **nicht** auf die berechnete MwSt. aus. Diese Option sollte also für Gutscheine verwendet werden, für die ein Kunde oder Partner tatsächlich bezahlt hat (wie z.B. ein Kaufgutschein, sh. auch [Gutscheinsponsoren](gutscheinsponsoren.md)).

Geldwert-Gutscheine (gesponsert) erscheinen im Warenkorb unterhalb der Produktbruttosumme mit Namen und Wert. 

![](/assets/gutschein_gesponsert1.png)
<br>


Der Gutscheinwert selbst wird immer aus der Gutscheinserie genommen (verändert man diesen Wert, verändert sich auch automatisch der Gutscheinwert). Bei jeder Verwendung eines Gutscheins wird das Datum, der Benutzer sowie der Verbrauchswert beim Gutschein in der Gutscheinverwendungsliste hinterlegt. Sobald der Gutschein komplett verbraucht ist, wird das Verbrauchsdatum hinterlegt und der Gutschein als verbraucht markiert. 

![](/assets/gutschein_verbrauch.png)

Artikel können von der Verwendung von Aktionsgutscheinen ausgeschlossen werden: ```Artikel → Preis/Versand → keine Gutscheine zulassen```. Gesponserte Gutscheinen hingegen können auch für Artikel verwendet werden, bei denen sonst keine Gutscheine zugelassen sind.

Zusätzlich kann bei einem Gutschein ein Gratisartikel hinterlegt werden (wenn das entsprechende Modul installiert ist). Wird ein solcher Gutschein mit Gratisartikel eingelöst, legt das System den Artikel mit einem Wert von 0,- € in den Warenkorb. Es erscheint der Hinweis, über welchen Gutschein der Artikel in den Warenkorb gelegt wurde.

Folgende weitere Einstellungen und Einschränkungen sind möglich:

* Über ein Start- und Enddatum kann ein Gutschein auf eine Zeitspanne eingeschränkt werden.
* Es kann ein Mindestbestellwert definiert werden, der überschritten werden muss, bevor der Gutschein akzeptiert wird.
* Ob der Gutschein mit einem anderen Gutschein der gleichen Gutscheinserie verwendet werden kann.
* Ob der Gutschein mit anderen Gutscheinen (egal von welcher Gutscheinserie) verwendet werden kann.
* Ob ein Kunde Gutscheine dieser Gutscheinserie generell nur einmal verwenden darf (also auch nicht bei zwei getrennten Bestellungen).
* Ob der Gutschein nur bei der ersten Bestellung des Benutzers verwendet werden kann.
* Ob der Gutschein die Versandkosten aufheben soll.
* Es ist möglich, den Gutschein als einen „gesponserten“ Gutschein zu markieren. Zusätzlich können der Name des Sponsors, ein Bild und ein Logo hinterlegt werden. „Gesponserte“ Gutscheine ignorieren die Einstellung „keine Gutscheine zulassen“ der Warenkorbartikel im Warenkorb.
* Gutscheine können eingeschränkt werden auf bestimmte Kunden, Kundengruppen, einzelne Produkte, Hersteller, Artikelgruppen, Produktekategorien


<br>
###### Gutscheine anlegen

Gutscheine werden generell in Gutscheinserien angelegt. Alle Einstellungen (sh. oben) beziehen sich auf die Gutscheinserie und damit auf alle Gutscheine in dieser Serie. Für eine Gutscheinserie können automatisch Gutscheine generiert werden. Hier kann entweder ein fester Gutscheincode angegeben werden oder ein vom System automatisch generierter Code verwendet werden.


Gutscheine zur Serie werden über den Button `Gutscheine erstellen` generiert. 
![](/assets/gutscheine_erstellen.png)

Bei der Generierung muss die Anzahl der Gutscheine, die erstellt werden soll sowie der Gutschein-Code angegeben werden.[^1] Soll jeder Gutschein dieser Serie den gleichen Code besitzen, wie z.B. "Frühlingsaktion", dann geben Sie dies in den Pop-Up-Dialog ein. 

![](/assets/gutscheine_erstellen1.png)

![](/assets/gutscheine_erstellen2.png)


Wird kein Gutschein-Code angegeben, wird für jeden Gutschein vom System ein eineindeutiger Code generiert.

![](/assets/gutscheine_erstellen3.png)
<br>

Innerhalb einer Gutscheinserie darf ein Gutscheincode mehr als einmal vorkommen, ein Gutscheincode darf aber nie in mehr als einer Gutscheinserie verwendet werden[^2]. Bei jedem Gutschein wird ein Erstellungsdatum hinterlegt.



<br>

###### Gutscheine exportieren
Die Gutscheine einer Gutscheinserie können als CSV-Datei exportiert werden. 
![](/assets/gutscheine_exportieren.png)

Für jeden Gutschein werden folgende Daten exportiert:
* Code: Identifikationscode des Gutscheins
* Datum: Erstellungsdatum
* Verbraucht (Ja / Nein)
* Verbrauchsdatum: wird hinterlegt, sobald ein Gutschein komplett verbraucht wurde
* Restwert: möglicher unverbrauchter Restwert des Gutscheines

<br>

[^1]: Wollen Sie nur 1 Gutschein erstellen, geben Sie ins Dialogfenster eine `1` ein. Alternativ können Sie auch bei `Gutscheine der Serie` auf `Neu` klicken und dann den gewünschten Code eingeben.

[^2]: Grund: Das System sucht den Gutschein mit dem im Warenkorb eingegebenen Code und nimmt den ersten entsprechenden Gutschein, den es findet. Würde der gleiche Code in mehr als einer Serie vorkommen, wäre nicht gewährleistet, dass die richtige Serie ausgewählt wird. Das System verhindert bereits das Anlegen des gleichen Codes in mehr als einer Serie.




