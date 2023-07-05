# Spielplangenerator
## To-Do-Liste

**Normal:**


**Mixed:**


**Generell:**
- [ ] Schließen-Alert wieder aktivieren
- [x] Auf 32 Spieler / Runden aufstocken --> "...x, y, z, A, B, C, D, E, F"
- [ ] Die Namen nicht löschen, wenn die Spieleranzahl geändert wird
- [ ] Bei den Namen-Inputs gleich bei der Eingabe auf Strings prüfen, die zu Fehlern führen werden (z.B. " - ", "Marc" etc.)
- [ ] Eine Funktion, die automatisch durch die Plätze-Spieler-Rundenkombinationen durchiteriert, sodass die gewünschten Anzahl an Spielen pro Spielern erreicht wird --> Als Überbrückung zur Generation nach Spielen pro Spieler (siehe unten)
- [ ] var zu let & const austauschen bzw. generell ALLE Variablen nach heutigem Standard deklarieren
- [ ] "eval" zu arrays tauschen, sollte eigentlich keine großen Probleme auslösen
- [ ] "Jeden generierten Spielplan als "best_so_far" speichern. Wenn der darauffolgende besser ist, dadurch ersetzen. Zum Schluss den besten ausgeben.
- [ ] Die Generation nach Runden duch Generation nach gewünschter Spiele pro Spieler ersetzen
- [ ] Die Auto-Neugenerierung verbessern: Wenn nach gewisser Zeit keine Spiele ohne doppelten Paarungen gefunden werden konnten, die Bedingungen erleichtern, z.B. 2 Spieler dürfen doppelte Partner haben oder jeder darf 1 doppelten Partner haben o.Ä. etc. (für die Gegner das gleiche)
- [ ] Gegner-Generierung verbessern (doppelt und dreifach 1 Person)
- [ ] Performance optimieren: https://www.w3schools.com/js/js_performance.asp

In ferner Zukunft:
- [ ] ChatGPT nach alternativen Generationsmöglichkeiten fragen
- [ ] Auswertung der Siege inkl. Ranking auf Knopfdruck... dazu wird aber ein Major Rewrite benötigt, damit die Darstellung anders wird (Flashscore-ähnlich)


**Erledigt:**



**Nicht möglich oder notwendig:**
- "Schließen?"-Alerts vervielfachen (nicht möglich)
- Anordnung der Inputs ändern (was tragt man zuerst ein?) (nicht notwendig)
- Layout der Inputs ändern: Horizontal statt vertikal, damit unten Platz für die Ausgabe ist; oder: Partner-Gegner-Tabelle loslösen von Spielplan und weiter unten anzeigen (nicht notwendig)