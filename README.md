# Spielplangenerator
## To-Do-Liste

- [ ] Schließen-Alert wieder aktivieren
- [ ] Bei Endpunktetabelle das Verschieben von Spielern in die andere Kategorie möglich machen
- [ ] Im Ladekreis einen Countdown machen, damit der User weiß, wie viel Zeit fürs Generieren noch maximal benötigt wird
- [ ] Verschieben von einzelnen Spielern in der Mixed-Ergebnistabelle per Button möglich machen
- [ ] Möglichkeit der Speicherung und Abrufung eines generierten Spielplans einbauen mittels localStorage
- [ ] Die Generation nach Runden duch Generation nach gewünschter Spiele pro Spieler ersetzen
- [ ] "Jeden generierten Spielplan als "best_so_far" speichern. Wenn der darauffolgende besser ist, dadurch ersetzen. Zum Schluss den besten ausgeben.
- [ ] Die Auto-Neugenerierung verbessern: Wenn nach gewisser Zeit keine Spiele ohne doppelten Paarungen gefunden werden konnten, die Bedingungen erleichtern, z.B. 2 Spieler dürfen doppelte Partner haben oder jeder darf 1 doppelten Partner haben o.Ä. etc. (für die Gegner das gleiche)
- [ ] Gegner-Generierung verbessern (doppelt und dreifach 1 Person)
- [ ] Performance optimieren: https://www.w3schools.com/js/js_performance.asp
- [ ] ChatGPT nach alternativen Generationsmöglichkeiten fragen
- [ ] Verschönern mittels Bootstrap o.Ä.?
- [ ] Umbau zu Desktop Application mittels Electron?



**Erledigt:**
- [x] Auswertung nach Herren/Damen trennen
- [x] Auswertung ausdrucken per Button
- [x] Anzahl der Runden / Anzahl der Spiele pro Spieler besser deklarieren (für Rene)
- [x] var zu let & const austauschen bzw. generell ALLE Variablen nach heutigem Standard deklarieren
- [x] for- & while-loops überprüfen auf "let" und if-conditions auf Leerzeichen überprüfen
- [x] Nicht pro Versuch alle Spielerkominationen neu berechnen, sondern ganz am Anfang ein "Ur-Array" machen und daraus in das "Arbeits-Array" kopieren --> Performance/ Zeitaufwand
- [x] Von globalen Variablen auf Funktions-Parameter umsteigen --> Major Rewrite!
- [x] Reset default Input Values 
- [x] Vergleich 1.8.2 mit 1.9.0: Wie viele Generationen innerhalb von 120 sek möglich



**Nicht möglich oder notwendig:**
- "Schließen?"-Alerts vervielfachen (nicht möglich)
- Anordnung der Inputs ändern (was tragt man zuerst ein?) (nicht notwendig)
- Das "Spieler Spiele Anzahl Array" mit dem "Spieler Punkte Games Array" verknüpfen (nicht notwendig?)