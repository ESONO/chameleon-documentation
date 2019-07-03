# Kundengruppen

{% hint style="success" %}
Shopkunden / Benutzer → Kundengruppen
{% endhint %}

Kundengruppen können in CHAMELEON frei definiert werden und finden ihre Anwendung in den verschiedensten Bereichen des CMS/Shops. Im Backend können Gruppen z.B. zur Zugangsbeschränkung oder bei der User-Auswahl im Newsletter-Modul verwendet werden. Im Shop dagegen können Kunden nach Ihrem Bestellverhalten automatisch den Kundengruppen zugewiesen werden. Des Weiteren können im Shop die Zahlmethoden, Versandkosten usw. unter Verwendung der Kundengruppen genauestens konfiguriert werden.

| Bezeichnung | Beschreibung |
| :--- | :--- |
| **Name** | Bezeichnung der Kundengruppe |
| **Autozuweisung aktiv** | Gibt an, ob die Kundengruppe anhand der Einstellungen automatisch zugewiesen bzw. die Zuweisung automatisch wieder aufgehoben werden soll. |
| **Autozuweisung ab Bestellwert** | Kundengruppe wird dem Benutzer automatisch zugewiesen, wenn die Bestellung des Kunden einen definierten Wert überschreitet |
| **Autozuweisung bis Bestellwert** | Erreicht der Kunde diesen Bestellwert, dann wird er automatisch aus der Gruppe genommen \(die Gruppe greift also nur für Kunden mit Bestellungen UNTER diesem Betrag\). Wird hier 0 angegeben, dann gilt die Gruppe bis zu einem beliebigen Bestellwert. |

Kunden können nicht nur automatisch einer Kundengruppe zugewiesen werden, sondern auch direkt im Kundendatensatz:

{% hint style="success" %}
Kunde → Basisdaten → Kundengruppen → Haken bei entsprechender Kundengruppe setzen
{% endhint %}

## Zugriffsbeschränkung

Außerdem kann der Zugriff auf eine Seite auf bestimmte Kundengruppen eingeschränkt werden. Hierfür in den Seiten-Einstellungen `Zugriff einschränken` aktivieren, dann können nur angemeldete Benutzer die Seite sehen. Dies kann zusätzlich auf einzelne Kundengruppen eingeschränkt werden, indem man beim Feld _Auf folgende Extranet-Gruppen einschränken_ einen Haken bei der gewünschten Kundengruppe setzt.

![](https://github.com/esono-ag/chameleon-documentation-de/tree/5b0a385112ca4bca11418aab4404f78598f48ec6/assets/2017-01-17%2015_21_39-Fotos.png)

sh. auch [Zugriff auf eine Seite einschränken](../../allgemeine-bedienung-und-content-management/seitenverwaltung/zugriff-auf-eine-seite-einschranken.md)

