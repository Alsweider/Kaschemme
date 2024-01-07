# Kaschemme
Textbasiertes Würfelspiel

In Kaschemme tritt der Held im Würfelspiel gegen den Stammgast einer zweifelhaften Taverne an. Die Regeln sind die gleichen wie beim Würfelspiel aus dem Browserspiel "[Legend of the Green Dragon](https://de.wikipedia.org/wiki/Legend_of_the_Green_Dragon)":

Der Spieler hat 3 Würfe und darf sich bis zum letzten Wurf entscheiden, ob er die jeweilige Augenzahl behalten möchte. Danach würfelt der Computergegner. Wer am Ende die höhere Augenzahl behalten hat, gewinnt das eingesetzte Gold und die Runde.

Im Unterschied zum LotGD-Würfelspiel kennt der Computer die Augenzahl des Spielers beim Würfeln nicht. Das vermeidet einen unlauteren Vorteil und verbessert die Chancengleichheit. Zur Erläuterung ein Beispiel:

Der Spieler entscheidet sich im 2. Wurf dafür, seine erwürfelten 4 Augen zu behalten. Nun ist der Computer an der Reihe. Da der Computer in der LotGD-Version das Ergebnis des Spielers kennt, wird er nach dem Würfeln einer 5 nicht mehr das überflüssige Risiko eingehen, ein weiteres Mal zu würfeln, um womöglich eine 6 zu erreichen, da er mit 5 Augen bereits gewonnen hat. In Kaschemme hingegen kommt es vor, dass der Computer einen weiteren Wurf wagt, obwohl er mit der vorherigen Augenzahl den Spieler besiegt hätte. Spieler und Computer starten also mit gleichen Voraussetzungen.

Anstatt die Entscheidung des Computergegners vom Ergebnis des Spielers abhängig zu machen, basiert sie in Kaschemme auf einer zufälligen Schicksalszahl, die etwa dafür sorgt, dass der Computer eine im ersten Wurf erwürfelte 6 in seltenen Fällen auch mal verschenkt (ein Versehensfaktor). Im zweiten Wurf gibt sich der Computer ähnlich wie ein Mensch oft auch mit einer etwas schlechteren Zahl zufrieden. 

