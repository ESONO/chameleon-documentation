# Vorbemerkungen

## Frontend und Backend

Im Frontend gehen wir \(falls nichts anderes während der Projektplanung vorgegeben\) davon aus, dass die Benutzer grundsätzlich Browser der neuesten Generation verwenden. Wir bitten Sie, für das Backend ebenfalls einen Browser der aktuellen Generation zu nutzen \(vorzugsweise Chrome oder Mozilla Firefox\).

## Testsystem und Live-System

Änderungen sollten grundsätzlich immer zuerst im Testsystem \(= Stage\) \(www.\[domainname.endung\].stage.esono.de\) vorgenommen und getestet werden. Nach erfolgreicher Abnahme werden sie per Deploy \(= Kopieren des kompletten Ist-Standes des Dateisystems einer Entwicklungsversion\) auf das Live-System überspielt. Die Datenbank und kundenprojektspezifische Mediadaten wie Bilder und Downloads, werden dabei nicht überspielt. Änderungen, die im Livesystem ebenfalls  dargestellt werden sollen, müssen daher dort erneut ins Backend eingegeben werden.

