# Soccer ERM

Für eine Sportzeitschrift wird eine Fußballdatenbank entworfen:
In dieser Datenbank werden verschiedene Fußballmannschaften verwaltet. Jede
Mannschaft hat einen eindeutigen Namen, ist in einem bestimmten Jahr gegründet
worden und ist an einer Adresse beheimatet. Zu jeder Fußballmannschaft gehören
Fußballspieler. Für jeden Spieler soll die SVNr gespeichert werden, welche ihn
identifiziert: Jeder Spieler hat einen Namen, eine Wohnadresse und ein Geburtsdatum,
sowie eine Position an der er spielt.

Fußballmannschaften beteiligen sich an Spielen. Diese werden durch die Adresse des
Stadions, Tag und Uhrzeit eindeutig festgelegt. Für sie werden die beiden beteiligten
Mannschaften und der Schiedsrichter gespeichert. Das Ergebnis soll ermittelt werden
können.

Falls das Spiel zu einem Turnier gehört, so ist diese Tatsache ebenfalls zu speichern.
Falls ein Spieler in einem Spiel Tore geschossen hat, soll die Anzahl der Tore gespeichert
werden. Für jeden Schiedsrichter werden dieselben Daten gespeichert wie für die
Spieler, außer die Position. Zusätzlich wird noch das Datum der Schiedsrichterprüfung gespeichert 
und verwaltet. Für jedes Turnier werden eine von der FIFA
vergebene eindeutige Nummer, der Name, Beginn- und Enddatum, sowie die beteiligten
Mannschaften in der Datenbank gespeichert.
