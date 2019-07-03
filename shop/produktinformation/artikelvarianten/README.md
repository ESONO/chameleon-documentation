# Artikelvarianten

Varianten eines Artikels, wie z.B. verschiedene Größen und/oder Farben bei Bekleidung, können im Chameleon Backend mithilfe des **Variantengenerators** erzeugt werden.

Dafür wird zunächst ein generisches **Variantenset** erzeugt \(z.B. _Größe und Farbe_\), welches für alle Artikel des gleichen Produkttyps verwendet werden kann. Mithilfe des intelligenten **Generators** können dann mögliche Varianten vorgeschlagen und automatisch erzeugt, z.B. T-Shirt gelb S, gelb M, gelb L, rot S, rot M, rot L usw..

Zur Veranschaulichung dieser Dokumentation wird dieses Produkt aus dem Chameleon Demoshop in verschiedenen **Größen und Farben** verwendet.

## Variantenset

Ein `Variantenset` ist eine Kombination aus einem oder mehreren `Variantenarten` eines Produktes. Jede Variantenart verfügt wiederum über entsprechende `Variantenwerte`.

Das Variantenset unseres Beispiels sieht folgendermaßen aus:

**Variantenset:** Größe und Farbe \(= Name/Bezeichnung\)

**Variantenarten:** 1. Größe 2. Farbe

**Variantenwerte:** Jede Variantenart hat entsprechende Werte

* Variantenart _Größe_ hat die Werte S, M, L
* Variantenart _Farbe_ hat die Werte schnee, neon grün, grau marmor, nuss anthrazit, weinrot pink, petrol violet

