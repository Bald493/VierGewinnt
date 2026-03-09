# VierGewinnt
Projektarbeit für SEM

## Beschreibung 
Dieses Projekt ist eine einfache Implementierung des Spiels **Vier Gewinnt** in Python.
Man Kann entweder gegen den Computer spielen, oder im Zwei-Spielermodus. Es gewinnt, wer als Erstes vier seiner Spielsteine in einer Reihe platziert hat - entweder **horizental, vertikal oder diagonal**. Wenn alle der 6x7-Felder mit Steinen gefüllt wurden und es keinen Gewinner gibt, gilt es als unentschieden.

Das Spiel wird in der Konsole ausgeführt und verwendet ein Spielfeld mit 7 Spalten, in die die Spieler abwechselnd ihre Spielsteine fallen lassen.

## Spiel starten
Um das Spiel zu starten, muss Python installiert sein.  
Das Spiel kann anschließend im Terminal mit folgendem Befehl gestartet werden:

<python -m vier_gewinnt.py>

## Spielablauf

1. Das Spielfeld wird zu Beginn jeder Runde angezeigt (`.` = leeres Feld, `O` = Steine Spieler1, `X` = Steine Spieler2)
2. Sie werden aufgefordert, eine Spalte zu wählen (0-6)
3. Ihr Stein wird in der gewählten Spalte nach unten fallen
4. Danach macht der Computer oder Spieler2 seinen Zug
5. Das Spiel endet, wenn ein Spieler vier Steine in einer Reihe hat oder das Spielfeld voll ist 

