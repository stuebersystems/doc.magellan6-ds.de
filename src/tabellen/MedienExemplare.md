#       Tabelle MedienExemplare


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1      |Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2      |Katalog|I|-|PV|Verweis auf Tabelle **MedienKataloge**
3      |ID|I+|-|P|-
4      |Medium|I|-|V|Verweis auf Tabelle **Medien**
5      |Barcode|A|20|-|-
6      |BarcodePrint|A|20|-|-
7      |BarcodeExtern|A|20|-|Externer Barcode für importierte Mediendaten
8      |Signatur|A|50|-|-
9      |Zustand|I|-|V|Verweis auf Tabelle **MedienZustaende**
10    |Status|S|-|-|Mögliche Werte:<br/>0 = Frei<br/>1 = Vorgemerkt<br/>2 = Verliehen
11    |Bestandsstatus|S|-|-|Mögliche Werte:<br/>0 = Altbestand<br/>1 = Neukauf<br/>2  Spende<br/>3 = Schenkung<br/>4 = Dauerverleih<br/>5 = Dauerleihgabe
12    |Eingangsdatum|D|-|-|-
13    |Ausgangsdatum|D|-|-|-
14    |Betrag|N|-|-|-
15    |Waehrung|A|10|V|Verweis auf Tabelle **Waehrungen**
16    |Lieferant|I|-|V|Verweis auf Tabelle **Lieferanten**
17    |Standort|I|10|V|Verweis auf Tabelle **Standorte**
18    |Bemerkung|M|-|-|-
