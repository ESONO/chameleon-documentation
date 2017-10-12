#### Varianten generieren

Nachdem Sie das Variantenset erstellt haben, können Sie nun die einzelnen Varianten des Hauptartikels (Parent) mithilfe des Variantengenerators anlegen. Gehen Sie beim Parent-Artikel (`Artikel → Artikel`) zum Tab `Varianten` und wählen Sie dort das entsprechende Variantenset aus dem Dropdown-Menü aus. 

Unter ```Variantenwerte``` erhalten Sie nun eine Matrix mit allen möglichen Kombinationen, die sich aus den Variantenarten und –werten ergeben. Hier können Sie bereits vorauswählen, welche Varianten überhaupt zur Verfügung stehen sollen. (Das ist vor allem dann sinnvoll, wenn Sie ein Variantenset erstellen wollen, welches für möglichst viele Artikel gilt, wie z.B. Basic T-Shirts in 30 verschiedenen Farben und 6 Größen.)

Wählen Sie die möglichen Varianten aus

Mit Klick auf den Button `Mögliche Varianten` anzeigen werden nun die ausgewählten Werte generiert. Hier können Sie bei Bedarf unterschiedliche Preise angeben.

![](/assets/artikelvarianten_varianten_generieren1.png)

erhalten Sie eine Matrix mit allen möglichen Kombinationen, die sich aus den Variantenarten und –werten ergeben. Wählen Sie aus den vorgeschlagenen Varianten die aus, die angelegt werden sollen, und klicken Sie auf `Varianten generieren`.

![](/assets/artikelvarianten_varianten_generieren2.png)


Die erzeugten Varianten werden Ihnen sowohl in der Artikelübersicht (`Artikel → Artikel`) angezeigt als auch direkt beim Parent-Artikel im Tab `Varianten → Artikelvarianten`.

![](/assets/artikelvarianten_varianten_generieren3.png)


Im Frontend wird der Artikel auf der [Produktdetailseite mit den auswählbaren Varianten](https://demo.chameleon-system.de/testmarke-3/gehaekeltes/merino-muetze-muetzen_pid_820_6702.html?_ref=spot3&url=%2FProdukte%2FGehaekeltes%2FMuetzen%2F) angezeigt:

![](/assets/artikelvarianten_varianten_generieren4.png)

<u>Hinweis</u>: Der Hauptartikel eines Variantensets kann nicht gekauft werden – ein Kunde muss also immer eine Variante wählen. Um Sortierung nach Preisen, Beliebtheit usw. sinnvoll durchführen zu können, werden folgende Felder der Varianten vom System automatisch summiert und beim Hauptartikel hinterlegt:
1. Preis
2. Lagerbestand

Sobald eine Variante aktiviert wird, wird automatisch auch der Parentartikel aktiv geschalten (sofern dieser vorher inaktiv war). 
