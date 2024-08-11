## Kleine Einführung ##
Die Denkweise beschreibt ein logisches Aufbrechen der Aufgabe eines Algorithmus. Hierbei muss bedacht werden dass jeder Algorithmus entweder nur den mittleren, die ersten oder letzten beiden, oder alle Teile des EVA-Prinzips (Eingabe -> Verarbeitung -> Ausgabe) abdecken kann. Im Generellen kann gesagt werden, dass wir als Programmierer immer Daten von einem Input (**E** V A) in einen Output (E V **A**) manipulieren müssen. Diese Datenmanipulation kann ein einem oder mehreren Schritten erfolgen.

## Die Vorgehensweise ##
Als erstes muss sich Bild von der gegebenen Eingabe sowie dem gewünschten Output gemacht werden. Darauf hin kann ein generelles Statement über die Aufgabe des zu schreibenden Algorithmus gemacht werden. 

### Beispiel: ###
Eine zufällige Zahlenreihe soll nach der Größe der Zahlen geordnet werden. 

**Input:**
Zufällige Zahlenreihe im Stringvormat

**Output:**
Geordnete Zahlenreihe im Arrayformat.

**Generelle Aufgabe der Algorithmus:**
Die gegebene Zahlenreihe ordnen und im Arrayformat ausgeben.

---
Danach kann die Aufgabe unter Einbezug der gewollten Formate in kleine Unterschritte aufgebrochen werden. Hierbei muss darauf geachtet werden, dass die Schritte so jeweils so klein bzw. simpel sind wie möglich um sie nachher besser in Code umsetzten zu können.

### Beispiel: ###

1. Die Zahlen in ein Array umwandeln
2. Ein Loop schreiben, welches:
	1. Mit Position 0 anfängt
	2. Den Zähler des Loops erhöht
	3. Schaut, ob die jetzige Position (hier 1) größer oder kleiner ist
	4. Den Zähler um eins Erhöht
	5. Dies Durchführt, bis keine Änderung bei einem Durchlauf benötigt ist.
3. Das geordnete Array ausgibt, z.B. in ein Textfeld

