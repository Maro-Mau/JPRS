# Zahlensysteme in der IT

###### _Eine Zusammenfassung von René Barthel._

### In der IT, werden die sogenannte Positionssysteme verwendet

### Das sind folgende Systeme `Binärsysteme`, `Dezimalsysteme`, `Hexdezimalsysteme`, `Oktalsysteme`.

## Binärsystem

Das Binärsystem basiert auf der Zahlbasis 2.  
 Es verwendet nur die Zahlen `0` und `1`, wobei jede Ziffer als Bit bezeichnet wird.  
Acht Bits ergeben ein Byte. Dieses Zahlensystem bildet die Grundlage aller digitalen Systeme.

Die Maschinensprache, auch bekannt als Maschinencode, verwendet das Binärsystem, um der CPU (Central Processing Unit)  
eines Computers Anweisungen zu geben.  
Im Binärsystem entspricht `0` dem Zustand "Strom aus", während `1` dem Zustand "Strom an" entspricht.  
Dies ist entscheidend für die Steuerung und Verarbeitung von Daten in digitalen Schaltkreisen.

1. Bit: Die kleinste Einheit im Binärsystem wird als "Bit" (Binary Digit) bezeichnet. Ein Bit kann entweder den Wert 0 oder 1 haben. Bitrepräsentationen werden verwendet, um Daten in Computern zu speichern und zu übertragen.

2. Byte: Ein Byte besteht aus 8 Bits. Dies ist eine gebräuchliche Einheit zur Messung von Speicher- und Datenkapazität. Ein Byte kann 256 verschiedene Kombinationen von 0en und 1en darstellen (2^8).

3. Umrechnung: Die Umrechnung zwischen dem Binärsystem und anderen Zahlensystemen wie dem Dezimalsystem (Basis 10) ist möglich. Zum Beispiel entspricht die Binärzahl "1101" der Dezimalzahl "13". Dies geschieht, indem man die Potenzen von 2 in Dezimalwerte umrechnet und sie addiert.

4. Arithmetik: Binärzahlen können in der gleichen Weise wie Dezimalzahlen addiert, subtrahiert, multipliziert und dividiert werden. Die Binärarithmetik ist jedoch einfacher, da es nur zwei Ziffern gibt: 0 und 1.

5. Darstellung von Informationen: In Computern werden Texte, Bilder, Videos und andere Informationen in binärer Form gespeichert. Jedes Zeichen oder Pixel wird durch eine spezielle binäre Abfolge dargestellt. Diese Abfolgen werden oft mit Hilfe von Zeichencodierungen wie ASCII oder Unicode interpretiert.

6. Logikgatter: Das Binärsystem bildet die Grundlage für die digitale Logik in Computern. Logikgatter, wie UND, ODER und NICHT, verarbeiten binäre Eingaben und erzeugen binäre Ausgaben. Dies ermöglicht komplexe Berechnungen und Datenverarbeitung.

7. Kommunikation: In der digitalen Kommunikation und Übertragung werden Daten in binärer Form übertragen. Diese Daten werden in Bits und Bytes aufgeteilt und durch verschiedene Protokolle übertragen, z. B. in Form von Binärdateien oder über Netzwerkverbindungen.

8. Speicherung: Speichermedien wie Festplatten, SSDs und RAM verwenden das Binärsystem, um Daten zu speichern. Jede Speicherzelle kann einen Zustand von 0 oder 1 repräsentieren, was es ermöglicht, Informationen in binärer Form zu speichern.

## Dezimalsystem

Das Dezimalsystem basiert auf der Zahlbasis 10.  
Es verwendet die Zahlen `0, 1, 2, 3, 4, 5, 6, 7, 8, 9` und  
wird auch als Basis-10-System bezeichnet.  
Das Dezimalsystem ist das am häufigsten verwendete Zahlensystem.  
Es wird von Menschen verwendet, um Zahlen zu zählen und zu messen.  
Die meisten Zahlensysteme sind als dezimale Zahlensysteme definiert.  
Einige Beispiele sind das US-Währungssystem, die Zeitmessung und die Gradmessung.

1. Stellenwerte: Im Dezimalsystem nimmt jede Ziffer eine Stelle ein, die einen bestimmten Wert hat. Dies wird als "Stellenwert" bezeichnet. Der Stellenwert jeder Ziffer wird durch die Position der Ziffer im Dezimalwert bestimmt. Zum Beispiel hat die Zahl 123 den Wert 100 (1 Hundert), 20 (2 Zehner) und 3 (3 Einsen).

2. Basis: Das Dezimalsystem hat eine Basis von 10, da es 10 Ziffern gibt, die verwendet werden können, um Zahlen zu bilden. Der größte Nennwert im Dezimalsystem ist 9, da keine Ziffer größer als 9 ist. Der kleinste Nennwert ist 0, da Ziffern nicht negativ sein können.

3. Umrechnung: Die Umrechnung zwischen dem Dezimalsystem und anderen Zahlensystemen wie dem Binärsystem (Basis 2) ist möglich. Zum Beispiel entspricht die Dezimalzahl "13" der Binärzahl "1101". Dies geschieht

4. Arithmetik: Dezimalzahlen können in der gleichen Weise wie Binärzahlen addiert, subtrahiert, multipliziert und dividiert werden. Die Dezimalarithmetik ist jedoch komplexer, da es 10 Ziffern gibt: 0, 1, 2, 3, 4, 5, 6, 7, 8 und 9.

5. SQL und Datenbanken: In SQL-Datenbanken werden Dezimaldatentypen verwendet, um Dezimalzahlen mit einer festen Anzahl von Dezimalstellen darzustellen, was wichtig ist, wenn es um die Speicherung von Geldbeträgen oder präzisen Berechnungen geht.

6. Menschliche Kommunikation: Das Dezimalsystem ist das primäre Zahlensystem für die Kommunikation zwischen Menschen. Wenn IT-Profis Informationen oder Daten für nicht-technische Benutzer präsentieren oder erklären müssen, verwenden sie oft Dezimalzahlen, da sie am verständlichsten sind. Zum Beispiel können Datenübertragungsraten in Kilobit pro Sekunde (Kbps) oder Megabit pro Sekunde (Mbps) angegeben werden, was Dezimalzahlen sind.

7. Speichergrößen: Obwohl Speicher in Computern und IT-Systemen normalerweise in Binär- oder Hexadezimalnotation gemessen wird (z. B. Megabyte oder Gigabyte), kann es vorkommen, dass in der IT auch Dezimalzahlen zur Angabe von Speichergrößen verwendet werden, um eine benutzerfreundliche Darstellung zu ermöglichen

## Hexdezimalsysteme

Das Hexadezimalsystem basiert auf der Zahlbasis 16.  
Es verwendet die Zahlen `0, 1, 2, 3, 4, 5, 6, 7, 8, 9` und die Buchstaben `A, B, C, D, E, F` für die Zahlen `10, 11, 12, 13, 14, 15`.  
Das Hexadezimalsystem wird auch als Basis-16-System bezeichnet.

1. Stellenwerte: Im Hexadezimalsystem nimmt jede Ziffer eine Stelle ein, die einen bestimmten Wert hat. Dies wird als "Stellenwert" bezeichnet. Der Stellenwert jeder Ziffer wird durch die Position der Ziffer im Hexadezimalwert bestimmt. Zum Beispiel hat die Zahl 123 den Wert 100 (1 Hundert), 20 (2 Zehner) und 3 (3 Einsen).

2. Basis: Das Hexadezimalsystem hat eine Basis von 16, da es 16 Ziffern gibt, die verwendet werden können, um Zahlen zu bilden. Der größte Nennwert im Hexadezimalsystem ist F, da keine Ziffer größer als F ist. Der kleinste Nennwert ist 0, da Ziffern nicht negativ sein können.

3. Darstellung von Binärzahlen: Das Hexadezimalsystem bietet eine kompakte Möglichkeit, Binärzahlen darzustellen. Jede Ziffer im Hexadezimalsystem entspricht genau 4 Bits (einem Nibble) im Binärsystem. Zum Beispiel entspricht die Hexadezimalzahl "1A" der Binärzahl "00011010".

4. Speicheradressen: In der IT werden oft Speicheradressen und Daten in Hexadezimalnotation angegeben. Dies erleichtert die Lesbarkeit und die Umrechnung zwischen Hexadezimal und Binär.

5. Farbendarstellung: In der Computergrafik werden Farben oft im Hexadezimalsystem dargestellt. Zum Beispiel wird die Farbe Weiß oft als "#FFFFFF" (RGB-Code) dargestellt, wobei jede der sechs Hexadezimalziffern einen Anteil der Farbkomponenten Rot, Grün und Blau darstellt.

6. Netzwerkkommunikation: In Netzwerkkommunikation und bei der Konfiguration von Netzwerkgeräten werden IP-Adressen und MAC-Adressen häufig in Hexadezimalnotation verwendet.

7. Fehlercodes und Debugging: In der Programmierung und im Debugging werden oft Speicheradressen, Fehlercodes und Daten im Hexadezimalsystem dargestellt, um Fehler leichter zu identifizieren und zu beheben.

8. Dateiformate: Hexadezimale Werte finden sich auch in Dateiformaten, insbesondere in Datei-Headern, um bestimmte Informationen zu codieren.

## Oktalsysteme

Das Oktalsystem, auch als Basis-8-System bekannt, ist ein Zahlensystem, das in der IT und der Computerwissenschaft weniger häufig verwendet wird als das Binärsystem und das Hexadezimalsystem. Es basiert auf acht verschiedenen Symbolen, den Ziffern 0 bis 7. Obwohl es nicht so verbreitet ist wie das Binär- oder Hexadezimalsystem, gibt es einige Bereiche in der IT, in denen das Oktalsystem eine Rolle spielt:

1. Unix-Berechtigungen: In Unix-ähnlichen Betriebssystemen werden Dateiberechtigungen häufig im Oktalsystem dargestellt. Dieses System verwendet drei Oktalzahlen, um die Berechtigungen für den Eigentümer, die Gruppe und andere Benutzer einer Datei darzustellen. Zum Beispiel entspricht die Oktalzahl "755" den Berechtigungen "rwxr-xr-x", wobei "r" für Lesen, "w" für Schreiben und "x" für Ausführen steht.

2. Computerarchitektur: In einigen älteren Computerarchitekturen wurde das Oktalsystem verwendet, um Speicheradressen und Befehlscodes darzustellen. Dies war besonders in den frühen Tagen der Computertechnologie üblich.

3. Umrechnungen: Das Oktalsystem kann in der IT als Zwischenschritt verwendet werden, um zwischen Binär- und Dezimalzahlen umzurechnen. Da 8 eine Potenz von 2 ist (2^3), kann jede Oktalziffer genau 3 Bits im Binärsystem darstellen. Dies erleichtert die Konvertierung zwischen diesen beiden Systemen.

4. Programmierung: Obwohl das Oktalsystem in moderner Softwareentwicklung nicht weit verbreitet ist, können Entwickler gelegentlich Oktalzahlen verwenden, um bestimmte Bitmuster oder Konfigurationen darzustellen.

5. Insgesamt ist das Oktalsystem in der IT weniger gebräuchlich geworden, da das Hexadezimalsystem aufgrund seiner einfacheren Umrechnung in das Binärsystem und seiner größeren Kapazität (16 Symbole gegenüber 8) in den meisten Fällen bevorzugt wird. Dennoch hat das Oktalsystem immer noch seine Nische, insbesondere in spezifischen Anwendungen, in denen es historisch verwendet wurde oder wo es aus bestimmten Gründen praktisch ist.


## Rechengesezte
Binär | Dezimal | Hexadezimal | Oktal
--- | --- | --- | ---
0 | 0 | 0 | 0
1 | 1 | 1 | 1
10 | 2 | 2 | 2
11 | 3 | 3 | 3
100 | 4 | 4 | 4
101 | 5 | 5 | 5
110 | 6 | 6 | 6
111 | 7 | 7 | 7
1000 | 8 | 8 | 10
1001 | 9 | 9 | 11
1010 | 10 | A | 12


#### Anwendung Duales system
```
1 0 1 1 0 1 0 1
| | | | | | | |
| | | | | | | 1 = 1
| | | | | | 0 = 2
| | | | | 1 = 4
| | | | 0 = 8
| | | 1 = 16
| | 0 = 32
| 1 = 64
0 = 128
----------------
= 181
```
##### Flip Flop
