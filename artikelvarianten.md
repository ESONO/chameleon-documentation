### Artikelvarianten


Varianten eines Artikels, wie z.B. verschiedene Größen und/oder Farben bei Bekleidung, können im Chameleon Backend mithilfe des **Variantengenerators** erzeugt werden.

Dafür wird zunächst ein generisches **Variantenset** erzeugt (z.B. *Größe und Farbe*), welches für alle Artikel verwendet werden kann. Mithilfe des intelligenten **Generators** können dann mögliche Varianten vorgeschlagen und automatisch erzeugt, z.B. T-Shirt gelb S, gelb M, gelb L, rot S, rot M, rot L usw..

Zur Veranschaulichung dieser Dokumentation wird als Produkt ein **T-Shirt** in verschiedenen **Größen und Farben** verwendet.

#### Variantenset


Ein `Variantenset` ist eine Kombination aus einem oder mehreren `Variantenarten` eines Produktes. Jede Variantenart verfügt wiederum über entsprechende `Variantenwerte`.

Das Variantenset unseres Beispiels sieht folgendermaßen aus:

<br>

**Variantenset:** Größe und Farbe (= Name)
    
2. Variantenarten:
     2.1. Größe
     2.2. Farbe
    
3. Variantenwerte: Jede Variantenart hat entsprechende Werte
           * S, M, L (Variantenart *Größe*)
           * rot, pink, gelb, indigo, olive (Variantenart *Farbe*)
      







