#        Tabelle Personen


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|GUID|A|32|-|-
4|IDIntern|I|-|P|-
5|IDExtern|I|-|P|-
6|GUIDExtern|A|36|-|-
7|Barcode|A|20|-|-
8|BarcodePrint|A|20|-|-
9|Nachname|A|50|-|-
10|Namenszusatz|A|100|-|-
11|Vorname|A|100|-|-
12|Vorname2|A|100|-|-
13|Anrede|A|1|-|Mögliche Werte:<br/>0 = Frau<br/>1 = Herr<br/>2 = Frau Dr.<br/>3 = Herr Dr.<br/>4 = Frau Prof.<br/>5 = Herr Prof.<br/>6 = Frau Prof. Dr.<br/>7 = HerrProf. Dr.<br/>:  = Ms.<br/>; = Mrs.<br/> < = Mr.
14|Geschlecht|A|1|-|Mögliche Werte:<br/>W = Weiblich<br/>M  = Männlich
15|Geburtsdatum|D|-|-|-
16|Geburtsname|A|30|-|-
17|Ehestand|S|-|-|Mögliche Werte:<br/>0 = Verheiratet<br/>1 = Nicht Verheiratet<br/>2 = Ledig<br/>3 = Geschieden<br/>4 = Verwitwet
18|Kinderzahl|S|-|-|-
19|Strasse|A|100|-|-
20|Adresszusatz|A|200|-|-
21|Land|A|3|-|-
22|PLZ|A|5|-|-
23|Ort|A|100|-|-
24|Ortsteil|A|100|-|-
25|Adressergaenzung|A|300|-|-
26|Telefon|A|30|-|-
27|Telefax|A|30|-|-
28|Mobil|A|30|-|-
29|Email|A|100|-|-
30|TelefonDienst|A|30|-|-
31|TelefaxDienst|A|30|-|-
32|KFZ1|A|15|-|-
33|KFZ2|A|15|-|-
34|Beruf|A|50|-|-
35|Staatsangeh1|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
36|Staatsangeh2|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
37|Muttersprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
38|Verkehrssprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
39|Kategorie|A|10|V|Verweis auf Tabelle **Personenkategorien**
40|Personalnr|A|15|-|-
41|Status|S|-|-|Mögliche Werte:<br/>0 = Nicht Aktiv<br/>1 = Aktiv
42|Bemerkung|M|-|-|-
43|Passfoto|B|-|-|-
44|Bank1|I|-|V|Verweis auf Tabelle **Banken**
45|Bank1Konto|A|20|-|Bankkonto 1
46|Bank1IBAN|A|28|-|-
47|Bank1Inhaber|A|300|-|-
48|Bank1Info|A|300|-|-
49|Bank1Bemerkung|A|300|-|-
50|Bank2|I|-|V|Verweis auf Tabelle **Banken**
51|Bank2konto|A|20|-|Bankkonto 2
52|Bank2IBAN|A|28|-|-
53|Bank2Inhaber|A|300|-|-
54|Bank2Info|A|300|-|-
55|Bank2Bemerkung|A|300|-|-
56|Rechnung1Name1|A|100|-|Rechnungsadresse 1
57|Rechnung1Name2|A|100|-|-
58|Rechnung1Strasse|A|100|-|-
59|Rechnung1Adressgebiet|A|300|-|-
60|Rechnung1Land|A|3|-|-
61|Rechnung1PLZ|A|5|-|-
62|Rechnung1Ort|A|100|-|-
63|Rechnung1Ortsteil|A|100|-|-
64|Rechnung1Adresszusatz|A|200|-|-
65|Rechnung2Name1|A|100|-|Rechnungsadresse 2
66|Rechnung2Name2|A|100|-|-
67|Rechnung2Strasse|A|100|-|-
68|Rechnung2Adressgebiet|A|300|-|-
69|Rechnung2Land|A|3|-|-
70|Rechnung2PLZ|A|5|-|-
71|Rechnung2Ort|A|100|-|-
72|Rechnung2Ortsteil|A|100|-|-
73|Rechnung2Adresszusatz|A|200|-|-
74|HeimatName1|A|100|-|Heimatadresse
75|HeimatName2|A|100|-|-
76|HeimatStrasse|A|100|-|-
77|HeimatAdressgebiet|A|300|-|-
78|HeimatLand|A|3|-|-
79|HeimatPLZ|A|5|-|-
80|HeimatOrt|A|100|-|-
81|HeimatOrtsteil|A|100|-|-
82|HeimatAdresszusatz|A|200|-|-
83|HeimatGemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**

