#        Tabelle Sorgeberechtigte

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|GUID|A|32|-|-
4|IDIntern|I|-|P|-
5|IDExtern|I|-|P|-
6|GUIDExtern|A|36|-|-
7|Nachname|A|50|-|-
8|Namenszusatz|A|100|-|-
9|Vorname|A|100|-|-
10|Vorname2|A|100|-|-
11|Geburtsland|A|10|-|Verweis auf Tabelle **Staatsangehoerigkeiten**
12|Anrede|A|1|-|Mögliche Werte:<br/>0 = Frau<br/>1 = Herr<br/>2 = Frau Dr.<br/>3 = Herr Dr.<br/>4 = Frau Prof.<br/>5 = Herr Prof.<br/>6 = Frau Prof. Dr.<br/>7 = HerrProf. Dr.<br/>8 = Familie<br/>9 = Herr und Frau<br/>:   = Ms.<br/>;   = Mrs."<br/>< = Mr.<br/>= = Mr. and Ms.<br/>> = Mr. and Mrs.<br/>?  = Eheleute
13|Strasse|A|100|-|-
14|Adresszusatz|A|200|-|-
15|Land|A|3|-|-
16|PLZ|A|5|-|-
17|Ort|A|100|-|-
18|Ortsteil|A|100|-|-
19|Adressgebiet|A|300|-|-
20|TelefonPrivat|A|30|-|-
21|TelefonBeruf|A|30|-|-
22|Mobil|A|30|-|-
23|Email|A|100|-|-
24|Beruf|A|50|-|-
25|Staatsangeh1|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
26|Staatsangeh2|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
27|Muttersprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
28|Verkehrssprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
29|Funktion1|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
30|Funktion2|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
31|Funktion3|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
32|Funktion4|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
33|Funktion5|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
34|Funktion6|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
35|Funktion7|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
36|Funktion8|A|10|V|Verweis auf Tabelle **SorgebeFunktionen**
37|Status|S|-|-|Mögliche Werte:<br/>1 = Erreichbar<br/>2 = Nicht erreichbar<br/>3 = Verstorben
38|Status2|S|-|-|Mögliche Werte:<br/>0 = Nicht Aktiv<br/>1 = Aktiv
39|Bemerkung|M|-|-|-
40|Auskunft|S|-|-|Mögliche Werte:<br/>0 = Keine Angabe<br/>1 = Geheim
41|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
42|Bank1|I|-|V|Verweis auf Tabelle **Banken**
43|Bank1Konto|A|20|-|Bankkonto 1
44|Bank1IBAN|A|28|-|-
45|Bank1Inhaber|A|300|-|-
46|Bank1Info|A|300|-|-
47|Bank1Bemerkung|A|300|-|-
48|Bank2|I|-|V|Verweis auf Tabelle **Banken**
49|Bank2konto|A|20|-|Bankkonto 2
50|Bank2IBAN|A|28|-|-
51|Bank2Inhaber|A|300|-|-
52|Bank2Info|A|300|-|-
53|Bank2Bemerkung|A|300|-|-
54|Rechnung1Name1|A|100|-|Rechnungsadresse 1
55|Rechnung1Name2|A|100|-|-
56|Rechnung1Strasse|A|100|-|-
57|Rechnung1Adressgebiet|A|300|-|-
58|Rechnung1Land|A|3|-|-
59|Rechnung1PLZ|A|5|-|-
60|Rechnung1Ort|A|100|-|-
61|Rechnung1Ortsteil|A|100|-|-
62|Rechnung1Adresszusatz|A|200|-|-
63|Rechnung2Name1|A|100|-|Rechnungsadresse 2
64|Rechnung2Name2|A|100|-|-
65|Rechnung2Strasse|A|100|-|-
66|Rechnung2Adressgebiet|A|300|-|-
67|Rechnung2Land|A|3|-|-
68|Rechnung2PLZ|A|5|-|-
69|Rechnung2Ort|A|100|-|-
70|Rechnung2Ortsteil|A|100|-|-
71|Rechnung2Adresszusatz|A|200|-|-
72|HeimatName1|A|100|-|Heimatadresse
73|HeimatName2|A|100|-|-
74|HeimatStrasse|A|100|-|-
75|HeimatAdressgebiet|A|300|-|-
76|HeimatLand|A|3|-|-
77|HeimatPLZ|A|5|-|-
78|HeimatOrt|A|100|-|-
79|HeimatOrtsteil|A|100|-|-
80|HeimatAdresszusatz|A|200|-|-
81|HeimatGemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
82|ArbeitgeberBetrieb|-|-|-|Verweis auf Tabelle **Betriebe**
83|ArbeitgeberKontakt|-|-|-|Verweis auf Tabelle **BetriebeKontakte**
84|ArbeitgeberAbteilung|A|300|-|-
85|ArbeitgeberPosition|A|300|-|-
