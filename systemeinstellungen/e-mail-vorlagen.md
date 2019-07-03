# E-Mail-Vorlagen

{% hint style="success" %}
CMS Admin → E-Mail-Vorlagen
{% endhint %}

Aus dem Backend heraus werden für diverse Aktionen E-Mails versendet.

Eine Ausnahme hiervon ist die E-Mail-Einstellung für die „Passwort vergessen“-Funktionalität welche, sich unter `CMS / Portal-Einstellungen → Extranet Konfiguration → Konfiguration: Passwort vergessen` befindet.

Eine E-Mail-Vorlage wird zentral verwaltet und kann an vielen Stellen im System über den Identifier _**ID-Code**_ einfach verwendet werden. Es ist darauf zu achten, dass der ID-Code nicht ohne wichtigen Grund geändert wird.

Alle E-Mail-Vorlagen werden in zwei Formaten _Html_ und _Text_ gepflegt. Im Shop kann der Kunde wählen, ob er Html- oder Text-E-Mails empfangen möchte. Ist der Hmtl-Inhalt einer Vorlage nicht gefüllt, so wird automatisch eine Text-E-Mail erstellt und versendet.

| Bezeichnung | Beschreibung |
| :--- | :--- |
| **ID-Code** | eindeutig identifizierbarer Code \(wird vom Entwickler benötigt, um die E-Mail-Vorlage eindeutig identifizieren zu können\). Der ID-Code sollte nicht ohne wichtigen Grund und Systemkenntnis geändert werden, da dies zu Fehlern führen kann bzw. dazu, dass keine E-Mails mehr versendet werden. |
| **Name** | Bezeichnung der E-Mail-Vorlage |
| **Betreff** | Betreff der E-Mail \(erscheint im Mailprogramm des Kunden\) |
| **To** | Gültige E-Mail-Adresse des Empfängers \(falls es eine E-Mailvorlage ist wie die „Bestellbestätigung“, wird die jeweilige E-Mail-Adresse des Kunden zur Laufzeit – also in dem Moment, in dem der Kunde die Bestellung absendet – vom System hinzugefügt. In dem Fall muss das Feld beim Formular leer bleiben.\) |
| **To \(Name\)** | Name des Kunden \(auch hier muss das Feld leer bleiben, wenn es eine E-Mailvorlage ist und die Empfänger während der Laufzeit vom System automatisch hinzugefügt werden\). |
| **Absender** | E-Mail-Adresse des Absenders \(diese E-Mail-Adresse sollte existieren, da der Empfänger diese in seinem E-Mail-Programm sieht um darauf antworten zu können\). |
| **Absender \(Name\)** | Name des Absenders \(z.B. Name des Shops\) |
| **BBC** | „BCC“ \(Blindkopie\) sollte grundsätzlich dann verwendet werden, wenn eine E-Mail an weitere Adressen als Kopie versendet werden soll, ohne dass der Empfänger sehen kann, welche das sind. Alle unter „BCC“ aufgenommenen Empfänger bleiben für sämtliche weitere Empfänger unsichtbar. |
| **Body** | Inhalt der Html-E-Mail |
| **Body \(Text\)** | Inhalt der Text-E-Mail |
| **Folgende Dateien der E-Mail beifügen** | Dateien, die  hier hinzugefügt wurden, werden automatisch der E-Mail angehängt und mit versendet. |
| **Vorlage** | die Html-Vorlage \(in der Vorlage sind meistens Teile der E-Mail umgesetzt, die bei den meisten Mails des Systems gleich bleiben sollen/müssen, weil sie der CI des Unternehmens entsprechen. Diese „statischen“ Teile der E-Mail sind „Header“ – Kopf der E-Mail oder der „Footer“ – Fußbereich in welchen meist Zusatzangaben definiert sind\). |
| **Text-Vorlage** | Entspricht der „Vorlage“, formatiert als reiner Text |

Hinweis für Entwickler: Um während der Entwicklung der E-Mail-Vorlagen alle in der E-Mail möglichen Platzhalter erhalten zu können, muss der spezielle Platzhalter \[{\_\_FIELDS}\] hinzugefügt werden. Alle E-Mails laufen im Testsystem automatisch _an den Entwickler_.

