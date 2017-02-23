## Artikelvarianten


Varianten eines Artikels, wie z.B. verschiedene Größen und/oder Farben bei Bekleidung, können im Chameleon Backend mithilfe des **Variantengenerators** erzeugt werden.

Dafür wird zunächst ein generisches **Variantenset** erzeugt (z.B. *Größe und Farbe*), welches für alle Artikel verwendet werden kann. Mithilfe des intelligenten **Generators** können dann mögliche Varianten vorgeschlagen und automatisch erzeugt, z.B. T-Shirt gelb S, gelb M, gelb L, rot S, rot M, rot L usw..

Zur Veranschaulichung dieser Dokumentation wird als Produkt eine Mütze in verschiedenen **Größen und Farben** verwendet.
https://demo.chameleon-system.de/testmarke-3/gehaekeltes/merino-muetze-muetzen_pid_820_6702.html?_ref=spot3&url=%2FProdukte%2FGehaekeltes%2FMuetzen%2F

### Variantenset


Ein `Variantenset` ist eine Kombination aus einem oder mehreren `Variantenarten` eines Produktes. Jede Variantenart verfügt wiederum über entsprechende `Variantenwerte`.

Das Variantenset unseres Beispiels sieht folgendermaßen aus:

<br>

**Variantenset:** Größe und Farbe (= Name/Bezeichnung)
    
**Variantenarten:**
 1. Größe
 2. Farbe
    
**Variantenwerte:** Jede Variantenart hat entsprechende Werte
 * Variantenart _Größe_ hat die Werte S, M, L
 * Variantenart _Farbe_ hat die Werte rot, pink, gelb, indigo, olive
 
