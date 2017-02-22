# Versandkostenart

```Bestellprozess-Einstellungen → Versandkostenart```

Bei jeder Versandkostenart kann festgelegt werden, für welche Warengruppe, Kategorie, Artikel, Benutzergruppe, Benutzer oder Lieferland die Versandkostenart wirksam sein soll. 

Eine Versandkostenart kann auf die Anzahl Artikel, eine Gewicht- oder Größenspanne oder einen Warenwert eingeschränkt sein. Sollte bei der Versandkostenart festgelegt worden sein, dass diese nur auf bestimmte Artikel wirken soll (entweder über die Angabe der Kategorien oder Warengruppen oder durch die Angabe eines oder mehrerer Artikel), dann kann zusätzlich festgelegt werden, ob sich die Angaben von Menge, Gewicht, Größe oder Preis nur auf die Summe aller Artikel beziehen soll, auf die Summe der für diese Versandkostenart relevanten Artikel oder einzeln auf jeden für diese Versandkostenart relevanten Artikel.

Da manche Artikel immer versandkostenfrei behandelt werden müssen (wie z.B. ein Hörbuchdownload), besteht außerdem die Möglichkeit, einen Artikel von der Berechnung auszuschließen. Hierfür muss bei dem Artikel ein entsprechendes Häkchen gesetzt werden.

Sollte die Versandkostenart nicht nur bei dem Kauf bestimmter Artikel gelten, kann festgelegt werden, ob die Berechnung je Artikel im Warenkorb gilt oder für die Summe der Artikel im Warenkorb.

Um die Versandkostenberechnung auch bei nicht angemeldeten Benutzern (bei welchen das Lieferland nicht bekannt ist) zuzulassen, kann zusätzlich zu der Länderdefinition festgelegt werden, ob die Versandkostenart auch bei nicht angemeldeten Benutzern aktiv sein soll. In diesem Fall werden die Länder-, Benutzer- und Benutzergruppen-Einstellungen für diese Versandkostenart bei nicht angemeldeten Benutzern ignoriert.

Generell gilt, dass kein Artikel bei der Versandkostenberechnung mehr als einmal verwendet wird. Um eine Mehrfachberechnung zu verhindern, arbeitet der Shop die Versandkostenarten nacheinander ab (sortiert wird nach Wert „teuerste Versandkostenart zuerst“ - diese Sortierung lässt sich aber beeinflussen).

Alle Artikel, die bei der Berechnung einer Versandkostenart einbezogen wurden, werden bei der Nächsten nicht mehr berücksichtigt. Sollte also z.B. die teuerste Versandkostenart auf den gesamten Warenkorb wirken (weil z.B. keine Artikeleinschränkungen bei dieser Versandkostenart hinterlegt wurden), dann werden alle weiteren Versandkostenarten ignoriert. Es ist möglich, dieses Verhalten für einzelne Versandkostenarten zu deaktivieren.

Versandkostenarten können über eine Checkbox aktiviert/deaktiviert werden. Es besteht ebenfalls die Möglichkeit, eine Versandkostenart „zeitgesteuert“ nur für eine bestimmte Zeitspanne zu aktiveren. Für jede Versandkostenart kann festgelegt werden, ob es sich bei den Versandkosten um einen absoluten oder um einen prozentualen Wert handelt. Handelt es sich um eine prozentuale Angabe, bezieht sich diese immer auf die von der Versandkostenart betroffenen Artikel (also nur dann auf den ganzen Warenkorb, wenn sich die Versandkostenart auf den ganzen Warenkorb bezog).