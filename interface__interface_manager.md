## Interface / Interface Manager

    CMS Admin → CMS Interface-Manager (Im- und Export)

Das Interface („Schnittstelle“) ist die zentrale Stelle im CMS, an welcher der Benutzer die Möglichkeit hat, manuell Prozesse zur Kommunikation/Datenaustausch mit externen Systemen zu starten. Neue Schnittstellen sollten grundsätzlich nur von Entwicklern eingerichtet werden, da hierfür unter anderem Datenbankzugriffe korrekt konfiguriert werden müssen.

Alle vorhandenen Interfaces, welche im System hinterlegt sind, können auch automatisch über einen sogenannten `Cronjob`, einem zeitgesteuerten System-Dienst (ähnlich dem Windows-Scheduler) ausgeführt werden. Damit ein Interface zeitgesteuert und automatisch aufgerufen wird, muss dafür zuerst ein Cronjob eingerichtet werden.

Neue Interfaces werden zentral (durch einen Entwickler) über den CMS Interface Manager definiert. Interfaces können für die verschiedensten Aufgaben im System definiert werden, die typischen Aufgaben eines Interfaces sind Wartungs- /Datenpflegeaufgaben, wie z.B. „Import der Artikeldaten“ oder „Import der Bestell-Statusinformationen“. Diese Daten stammen meist aus externen Datenquellen, wie z.B. der Warenwirtschaft des Kunden.

| Bezeichnung | Beschreibung |
| -- | -- |
| **Name** | beschreibender Name des Interfaces im Manager |
| **Systemname** | über diesen Namen kann das Interface eindeutig identifiziert werden |
| **Die verwendete Klasse** | Dateiname der Interface-Klasse |
| **Klassenart** | Definition, von welchem Typ die verwendete Klasse ist |
| **Klassenunterart** | Das Verzeichnis, in welchem sich die Klasse befindet (relativ zum *./classes/* Verzeichnis) |
| **Beschreibung** | ausführliche Beschreibung des Interfaces mit allen benötigten Parametern |
| **Parameter** | Liste aller Parameter, welche für das Interface benötigt werden |
