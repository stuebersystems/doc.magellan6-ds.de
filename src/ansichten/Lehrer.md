# View Lehrer

Grundlage ist die Tabelle [tblLehrer](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblLehrer.html).

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
9|Kuerzel|A|6|-|-
10|Nachname|A|50|-|-
11|Namenszusatz|A|100|-|-
12|Vorname|A|100|-|-
13|Vorname2|A|100|-|-
14|Anrede|A|1|-|Mögliche Werte:<br/>0 = Frau<br/>1 = Herr<br/>2 = Frau Dr.<br/>3 = Herr Dr.<br/>4 = Frau Prof.<br/>5 = Herr Prof.<br/>6 = Frau Prof. Dr.<br/>7 = Herr<br/>Prof. Dr.<br/>:= Ms.<br/>;= Mrs.<br/>< = Mr.
15|Geschlecht|A|1|-|Mögliche Werte:<br/>W = Weiblich<br/>M = Männlich
16|Geburtsdatum|D|-|-|-
17|Geburtsname|A|50|-|-
18|Geburtsort|A|100|-|-
19|Ehestand|S|-|-|Mögliche Werte:<br/>0 = Verheiratet<br/>1 = Nicht Verheiratet<br/>2 = Ledig<br/>3 = Geschieden<br/>4 = Verwitwet
20|Kinderzahl|S|-|-|-
21|Strasse|A|100|-|-
22|Adresszusatz|A|200|-|-
23|Land|A|3|-|-
24|PLZ|A|5|-|-
25|Ort|A|100|-|-
26|Ortsteil|A|100|-|-
27|Adressgebiet|A|300|-|-
28|Gemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
29|Telefon|A|30|-|-
30|Telefax|A|30|-|-
31|Mobil|A|30|-|-
32|Email|A|100|-|-
33|KFZ1|A|15|-|-
34|KFZ2|A|15|-|-
35|TelefonDienst|A|30|-|-
36|TelefaxDienst|A|30|-|-
37|Kategorie|A|10|V|Verweis auf Tabelle **LehrerKategorien**
38|Staatsangeh|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
39|Staatsangeh2|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
40|Muttersprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
41|Verkehrssprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
42|Konfession|A|10|V|Verweis auf Tabelle **Konfessionen**
43|Bevollmaechtigung|A|10|V|Verweis auf Tabelle **Bevollmaechtigungen**
44|Abteilung1|A|10|V|Verweis auf Tabelle **Abteilungen**
45|Abteilung2|A|10|V|Verweis auf Tabelle **Abteilungen**
46|Abteilung3|A|10|V|Verweis auf Tabelle **Abteilungen**
47|Funktion1|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
48|Funktion1Von|D|-|-|-
49|Funktion1Bis|D|-|-|-
50|Funktion2|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
54|Funktion3Von|D|-|-|-
55|Funktion3Bis|D|-|-|-
56|Funktion4|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
57|Funktion4Von|D|-|-|-
58|Funktion4Bis|D|-|-|-
59|Funktion5|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
60|Funktion5Von|D|-|-|-
61|Funktion5Bis|D|-|-|-
62|Funktion6|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
63|Funktion6Von|D|-|-|-
64|Funktion6Bis|D|-|-|-
65|Funktion7|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
66|Funktion7Von|D|-|-|-
67|Funktion7Bis|D|-|-|-
68|Funktion8|A|10|V|Verweis auf Tabelle **LehrerFunktionen**
69|Funktion8Von|D|-|-|-
70|Funktion8Bis|D|-|-|-
71|Krankenkasse|A|10|V|Verweis auf Tabelle **Krankenkassen**
72|Versicherungsart|A|10|V|Verweis auf Tabelle **Versicherungsarten**
73|NotfallPerson|A|50|-|-
74|NotfallTelefon|A|30|-|-
75|Personalnr|A|15|-|-
76|Statistiknr|A|15|-|-
77|ZugangDatum|D|-|-|-
78|ZugangGrund|A|10|V|Verweis auf Tabelle **LehrerZugaenge**
79|AbgangDatum|D|-|-|-
80|AbgangGrund|A|10|V|Verweis auf Tabelle **LehrerAbgaenge**
81|Amtsbez|A|10|V|Verweis auf Tabelle **Amtsbez**
82|AmtsbezSeit|D|-|-|-
83|Dienstverh|A|10|V|Verweis auf Tabelle **Dienstverh**
84|Dienstbez|A|10|V|Verweis auf Tabelle **Dienstbez**
85|Dienstherr|A|10|V|Verweis auf Tabelle **Dienstherren**
86|Dienstalter|S|-|-|-
87|LetzteUeberpruefung|D|-|-|-
88|VertragVon|D|-|-|-
89|VertragBis|D|-|-|-
90|Beschaeftigungsart|A|10|V|Verweis auf Tabelle **Beschaeftigungsarten**
91|Beschaeftigungsverh|A|10|V|Verweis auf Tabelle **Beschaeftigungsverh**
92|BeschaeftigungSchulart|A|10|V|Verweis auf Tabelle **Schularten**
93|BeschaeftigungSchulzweig|A|10|V|Verweis auf Tabelle **Schulzweige**
94|Besoldung|A|10|V|Verweis auf Tabelle **Besoldungen**
95|Ausbildung|A|10|V|Verweis auf Tabelle **LehrerAusbildung**
96|Beruf|A|50|-|-
97|BerichtendeSchule|I|-|V|Verweis auf Tabelle **Schulen**
98|Abordnung1|I|-|V|Verweis auf Tabelle **Schulen**
99|Abordnung1Art|A|10|V|Verweis auf Tabelle **Abordnungsarten**
100|Abordnung2|I|-|V|Verweis auf Tabelle **Schulen**
101|Abordnung2Art|A|10|V|Verweis auf Tabelle **Abordnungsarten**
102|Status|S|-|-|Mögliche Werte:<br/>0 = Inaktiv<br/>1 = Aktiv
103|Bemerkung|M|-|-|-
104|Passfoto|B|-|-|-
105|MerkmalA1|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
106|MerkmalA2|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
107|MerkmalA3|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
108|MerkmalA4|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
109|MerkmalA5|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
110|MerkmalA6|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
111|MerkmalS1|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
112|MerkmalS2|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
113|MerkmalS3|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
114|MerkmalS4|A|10|-|Verweis auf Tabelle **LehrerMerkmale**
115|MerkmalB1|A|15|-|-
116|MerkmalB2|A|15|-|-
117|MerkmalB3|A|15|-|-
118|MerkmalB4|A|15|-|-
119|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
120|Bank1|I|-|V|Verweis auf Tabelle **Banken**
121|Bank1Konto|A|20|-|Bankkonto 1
122|Bank1IBAN|A|28|-|-
123|Bank1Inhaber|A|300|-|-
124|Bank1Info|A|300|-|-
125|Bank1Bemerkung|A|300|-|-
126|Bank2|I|-|V|Verweis auf Tabelle **Banken**
127|Bank2konto|A|20|-|Bankkonto 2
128|Bank2IBAN|A|28|-|-
129|Bank2Inhaber|A|300|-|-
130|Bank2Info|A|300|-|-
131|Bank2Bemerkung|A|300|-|-
132|Rechnung1Name1|A|100|-|Rechnungsadresse 1
133|Rechnung1Name2|A|100|-|-
134|Rechnung1Strasse|A|100|-|-
135|Rechnung1Adressgebiet|A|300|-|-
136|Rechnung1Land|A|3|-|-
137|Rechnung1PLZ|A|5|-|-
138|Rechnung1Ort|A|100|-|-
139|Rechnung1Ortsteil|A|100|-|-
140|Rechnung1Adresszusatz|A|200|-|-
141|Rechnung2Name1|A|100|-|Rechnungsadresse 2
142|Rechnung2Name2|A|100|-|-
143|Rechnung2Strasse|A|100|-|-
144|Rechnung2Adressgebiet|A|300|-|-
145|Rechnung2Land|A|3|-|-
146|Rechnung2PLZ|A|5|-|-
147|Rechnung2Ort|A|100|-|-
148|Rechnung2Ortsteil|A|100|-|-
149|Rechnung2Adresszusatz|A|200|-|-
150|HeimatName1|A|100|-|Heimatadresse
151|HeimatName2|A|100|-|-
152|HeimatStrasse|A|100|-|-
153|HeimatAdressgebiet|A|300|-|-
154|HeimatLand|A|3|-|-
155|HeimatPLZ|A|5|-|-
156|HeimatOrt|A|100|-|-
157|HeimatOrtsteil|A|100|-|-
158|HeimatAdresszusatz|A|200|-|-
159|HeimatGemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
160|PassNr|-|-|-|-
161|PassGueltigBis|-|-|-|-
162|VisumNr|-|-|-|-
163|VisumAblaufAm|-|-|-|-
164|VisumAusstellungsort|-|-|-|-
165|Sozialversicherungsnummer|-|-|-|-
166|Aufenthaltsbemerkung|-|-|-|-


