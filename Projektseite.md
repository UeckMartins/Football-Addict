# „Football Addict“ – Das Fußballspiel mit Suchtpotenzial

![Football Addict Logo](https://user-images.githubusercontent.com/111355009/230416728-d17c5746-4363-4d63-9df9-005884021c70.jpg)

## Inhaltsverzeichnis:

* Einleitung
* Programm
* Aufbau
  * Der Spieler
  * Der Ball
  * Die oberen Wände
  * Die Tore
  * Der Counter
  * Die Defenders
* Anleitung

## Einleitung:
Dies ist die Projektseite zum Fußballspiel „Football Addict“, programmiert von Philip Martins und Robert Ueck.
Was ist „Football Addict“?
Football Addict ist ein klassisches Computerspiel, wo man einen Spieler von Seite zu Seite steuert, um Tore zu erzielen und Gegentore zu verhindern. Addict heißt es, weil es ein offenes Ende hat und dadurch ein großes Verlangen daran besteht, so viele Tore wie möglich zu machen.
## Programm:
Verwendet wurde das Programm Greenfoot, einer mithilfe von Java geschriebenen Entwicklungsumgebung für das Programmieren.
![R](https://user-images.githubusercontent.com/111355009/230406629-f8635308-9b0a-4eb4-9f00-1231978922f7.png)

## Aufbau:
### Der Spieler: <a name="Der Spieler"></a>                                  ![signal-2023-02-08-085605_002r](https://user-images.githubusercontent.com/111355009/230417063-019a1ea5-0efc-4405-a7a2-5c87c8b5ee03.png)
Der Spieler (auch Player genannt) ist der einzige direkt kontrollierbare Teil dieses Spiels, diesen bewegt man mithilfe von den „Links“- und „Rechts“-Tasten. Dementsprechend ist dessen Code ziemlich simpel:

![Player Code](https://user-images.githubusercontent.com/111355009/230404658-cef5ebc3-7ec9-4266-a628-19a2ca766872.png)

Bewegen muss man den Spieler, um den Ball vom eigenen Tor wegzuhalten und in das gegnerische Tor zu „schießen“.
### Der Ball: <a name="Der Ball"></a> ![R214](https://user-images.githubusercontent.com/111355009/230417860-aa6ecdab-63ba-4479-a5af-8bdc40098d2e.png)

Der Ball ist der Weg, wie man in diesem Spiel Tore machen kann, lenken kann man diesen nur indirekt mithilfe des Spielers. Abprallen tut der Ball nur von den Wänden und dem Spieler, dies nach dem Prinzip Einfallswinkel = Ausfallswinkel, weshalb hierfür verhältnismäßig viel Code verwendet werden musste.

![Ball Code1](https://user-images.githubusercontent.com/111355009/230424481-66417066-ba51-4e14-92fb-734132f6d430.png)

![Ball Code2](https://user-images.githubusercontent.com/111355009/230424781-37f686fe-0fa0-4931-aebe-c481287d048c.png)

### Die oberen Wände: <a name="Die oberen Wände"></a>
Die oberen Wände haben das Ziel, den Ball wie bei den Seitenwänden abzulenken, nötig waren diese, damit das Tor oben abgedeckt ist, damit an den Seiten des Tores keine Tore erzielt werden können. Eigenen Code haben diese Wände aber nicht.
### Die Tore: <a name="Die Tore"></a>
Sobald der Ball das Tor des Spielers oder des Gegners berührt, verschwindet dieser und ein neuer Ball erscheint auf dem Spielfeld.
Das Tor hat auch eine weitere wichtige Funktion, es führt dazu, dass die Counter die Anzahl der „geschossenen“ Tore mitzählen kann.
### Der Counter: <a name="Der Counter"></a>
Die beiden Counters sind die Anzeigen für die geschossenen Tore, der Linke ist für den Spieler, der Rechte für den Gegner. Mithilfe von Variablen, welche beim Torerfolg addiert werden, kann dies visualisiert werden.

![image](https://user-images.githubusercontent.com/111355009/230634353-73de1bcf-a690-427d-b5c3-f2b0366c14b3.png)
![image](https://user-images.githubusercontent.com/111355009/230634466-c8f2dae8-2886-4241-ab39-7247e920c879.png)

### Die Defenders: <a name="Die Defenders"></a>
Die Defenders sind, wie der Name es schon sagt, Verteidiger. Diese können als Alternative in das Spiel hinzugefügt werden, um es schwieriger zu machen ein Tor zu erzielen und bewegen sich von Seite zu Seite. Der Ball prallt auch an ihnen ab.
## Anleitung:
Das Spiel ist sehr simpel, einfach starten und spielen! Das einzig steuerbare Element ist der Spieler, welcher sich mit der „Links“-Taste nach links und der „Rechts“-Taste nach rechts bewegt. Ansonsten heißt es noch: Auf den abprallenden Ball achten und viel Spaß haben!

![Picture Gameplay](https://user-images.githubusercontent.com/111355009/230419537-140ffe64-1676-4625-9055-5bfff4dc3137.png)

[Hier](https://github.com/UeckMartins/Football-Addict/blob/main/Protokoll.md) der Link zu unserem Protokoll
