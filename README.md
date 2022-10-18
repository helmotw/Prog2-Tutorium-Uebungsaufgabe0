# Prog2-Tutorium-Uebungsaufgabe0

## 1) Schreibe ein Programm, was einen bestimmten Wert im Array entfernt.

## 2) Schreibe ein Programm, was den Index eibes Bestimmten Wertes zurückgibt.

## 3) Schreibe ein Programm, was auf der Konsole dieses Raster erzeugt:
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           
- - - - - - - - - -                                                                                           

## 4) Schreibe ein Programm, was numerische Werte in einem Array  aufsteigend ordnet.

## 5) Schreibe ein Programm, was Duplikate von Werten in einem Array entfernt.

## 6) Alte Aufgabe von Prof. Dabrowski, schreibe ein Programm, was die babylonische Wurzel berechnet.
  /**
     * Berechne Wurzel X eines Werte S durch den babylonischen Algorithmus, angefangen
     * mit der Schätzung X(Anfangswert):
     * <ol>
     *     <li>Geschätzter Fehler e(n): e(n)=(S-X(n-1)²)/(2*X(n-1))</li>
     *     <li>Berechne X(n): X(n)=X(n-1)+e(n)</li>
     * </ol>
     * Continue until the estimated error reaches the desired maximum error
     * @param value Wert der zu ziehenden Quadratwurzel
     * @param initial Erste Wert zur Berechnung
     * @param maxError Maximal erlaubter Fehler (Rundung)
     * @return Array mit allen zwischen Ergebnissen und dem finalen Ergebnis am ende.
     */
    public static double[] calculateBabylonianRoot(double value, double initial, double maxError)
