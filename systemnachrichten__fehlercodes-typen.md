## Systemnachrichten / Fehlercodes-Typen

    CMS / Portal-Einstellungen → Portale / Webseiten

Alle im System vorhandenen Meldungen und Fehlercodes werden zentral an dieser Stelle gepflegt. Sollte eine der Meldungen dem System noch nicht bekannt sein, wird eine Meldung *<span style="color:#9ACD32">„Unbekannter Fehler: [ERROR-IDENTIFIER]“</span>* angezeigt.

Bei unbekannten Meldungen wird der Identifizierungs-Code *<span style="color:#9ACD32">„ERROR-IDENTIFIER“</span>* und die Meldung, die angezeigt wurde, zugleich unter `Systemmeldungen / Fehlercodes` eingetragen. Im Feld `Beschreibung der Meldung` wird bei unbekannter Meldung die technische Information hinterlegt, an welcher Stelle im System die Meldung generiert wurde, sowie eine Auflistung aller verfügbaren Parameter. Treten solche unbekannten Fehler auf, sollten diese sinnvoll für den Portalbesucher umgeschrieben werden.

---

| Bezeichnung | Beschreibung |
| -- | -- |
| **Gehört zu Portal** | eindeutige Zugehörigkeit zum Portal |
| **Code** | dieser Code wird vom System verwendet, um die Meldung zu identifizieren (sollte nicht geändert werden) |
| **Meldungsart** | typisiert die Meldung (wird für die Darstellung verwendet) |
| **Beschreibung der Meldung** | Erklärung, wann die Meldung generiert wird und genaue Beschreibung, welche Parameter in der Meldung verwendet werden können |
| **Meldung** | der Meldungstext mit allen verwendeten Parametern (wird dem Besucher angezeigt) |
| **Art** | gibt an, zu welchem Quellcode-Bereich der Applikation die Meldung gehört bzw. aus welchem Quellcode-Bereich die zur Darstellung verwendete Ansicht (View) verwendet werden soll. Beim Quellcode-Bereich “Core” stammt die Meldung aus dem CHAMELEON-Standardcode, beim Bereich “Customer” aus einer kundenspezifischen Entwicklung.  |
| **View** | Die Ansicht der Meldung (wird für die Darstellung verwendet) |
