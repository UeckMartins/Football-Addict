# „Football Addict“ – Das Fußballspiel mit Suchtpotenzial

## Inhaltsverzeichnis:

* [Einleitung](Einleitung)
* [Programm](Programm)
* [Aufbau](Aufbau)
  * [Der Spieler](Der-Spieler)

## Einleitung:
Dies ist die Projektseite zum Fußballspiel „Football Addict“, programmiert von Philip Martins und Robert Ueck.
Was ist „Football Addict“?
Football Addict ist ein klassisches Computerspiel, wo man einen Spieler von Seite zu Seite steuert, um Tore zu erzielen und Gegentore zu verhindern. Addict heißt es, weil es ein offenes Ende hat und dadurch ein großes Verlangen daran besteht, so viele Tore wie möglich zu machen.
## Programm:
Verwendet wurde das Programm Greenfoot, einer mithilfe von Java geschriebenen Entwicklungsumgebung für das Programmieren.
## Aufbau:
Der Spieler:
Der Spieler (auch Player genannt) ist der einzige direkt kontrollierbare Teil dieses Spiels, diesen bewegt man mithilfe von den „Links“- und „Rechts“-Tasten. Dementsprechend ist dessen Code ziemlich simpel:
Bewegen muss man den Spieler, um den Ball vom eigenen Tor wegzuhalten und in das gegnerische Tor zu „schießen“.
Der Ball:
Der Ball ist der Weg, wie man in diesem Spiel Tore machen kann, lenken kann man diesen nur indirekt mithilfe des Spielers. Abprallen tut der Ball nur von den Wänden und dem Spieler, dies nach dem Prinzip Einfallswinkel = Ausfallswinkel, weshalb hierfür verhältnismäßig viel Code verwendet werden musste.
Die oberen Wände:
Die oberen Wände haben das Ziel, den Ball wie bei den Seitenwänden abzulenken, nötig waren diese, damit das Tor oben abgedeckt ist, damit an den Seiten des Tores keine Tore erzielt werden können. Eigenen Code haben diese Wände aber nicht.
Die Tore:
Sobald der Ball das Tor des Spielers oder des Gegners berührt, verschwindet dieser und ein neuer Ball erscheint auf dem Spielfeld.
Das Tor hat auch eine weitere wichtige Funktion, es führt dazu, dass die Counter die Anzahl der „geschossenen“ Tore mitzählen kann.
Der Counter:
Die beiden Counters sind die Anzeigen für die geschossenen Tore, der Linke ist für den Spieler, der Rechte für den Gegner.
Die Defenders:
Die Defenders sind, wie der Name es schon sagt, Verteidiger. Diese können als Alternative in das Spiel hinzugefügt werden, um es schwieriger zu machen ein Tor zu erzielen und bewegen sich von Seite zu Seite. Der Ball prallt auch an ihnen ab.
Anleitung:
Das Spiel ist sehr simpel, einfach starten und spielen! Das einzig steuerbare Element ist der Spieler, welcher sich mit der „Links“-Taste nach links und der „Rechts“-Taste nach rechts bewegt. Ansonsten heißt es noch: Auf den abprallenden Ball achten und viel Spaß haben
