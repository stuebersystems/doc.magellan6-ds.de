#       Tabelle MedienAusleiher



Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1      |Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2      |ID|I+|-|P|-
3      |SVID|I|-|V|Verweis auf Tabelle **Schueler**, **Lehrer** oder **Personen**
4      |SVTyp|S|-|-|Mögliche Werte:<br/>0 = Person<br/>1 = Lehrer<br/>2 = Schüler
5      |Barcode|A|20|-|-
6      |BarcodePrint|A|20|-|-
7      |Vorname|A|30|-|-
8      |Nachname|A|50|-|-
9      |Anrede|A|1|-|Mögliche Werte:<br/>0 = Frau<br/>1 = Herr<br/>2 = Frau Dr.<br/>3 = Herr Dr.<br/>4 = Frau Prof.<br/>5 = Herr Prof.<br/>6 = Frau Prof. Dr.<br/>7 = HerrProf. Dr.<br/>:  = Ms.<br/>; = Mrs.<br/> < = Mr.
10    |Geschlecht|A|1|-|Mögliche Werte:<br/>W = Weiblich<br/>M  = Männlich
11    |Geburtsdatum|D|-|-|-
12    |Strasse|A|100|-|-
13    |Land|A|3|-|-
14    |PLZ|A|5|-|-
15    |Ort|A|100|-|-
16    |Telefon|A|30|-|-
17    |Telefax|A|30|-|-
18    |Mobil|A|30|-|-
19    |Email|A|100|-|-
20    |Passfoto|A|30|-|-
21    |Status|S|-|-|Mögliche Werte:<br/>0 = Nicht Aktiv<br/>1 = Aktiv
22    |GueltigVon|D|-|-|-
23    |GueltigBis|D|-|-|-