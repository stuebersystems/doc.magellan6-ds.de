#       Tabelle Schueler

Nr.|Name|Typ|Größe|Funkt.|Bemerkung
---|--------|---|-----|--------|--
1|Mandant|I|-|PV|Verweis auf Tabelle<br/> **Mandanten**
2|ID|I+|-|P|-
3|GUID|A|32|-|-
4|IDIntern|I|-|-|-
5|IDExtern|I|-|-|-
6|GUIDExtern|A|36|-|-
7|Barcode|A|20|-|-
8|BarcodePrint|A|20|-|-
9|Nachname|A|50|-|-
10|Namenszusatz|A|30|-|z.B.: “von”, “zu”
11|Vorname|A|30|-|-
12|Vorname2|A|50|-|-
13|Anrede|A|1|-|Mögliche Werte:<br/>0 = Frau<br/>1 = Herr<br/>2 = Frau Dr.<br/>3 = Herr Dr.<br/>4 = Frau Prof.<br/>5 = Herr Prof.<br/>6 = Frau Prof. Dr.<br/>7 = HerrProf. Dr.<br/>: = Ms.<br/>; = Mrs.<br/>< = Mr.
14|Geschlecht|A|1|-|Mögliche Werte:<br/>W = Weiblich<br/>M = Männlich
15|Geburtsdatum|D|-|-|-
16|Geburtsort|A|100|-|-
17|Geburtskreis|A|100|-|-
18|Geburtsland|A|10|-|Verweis auf Tabelle **Staatsangehoerigkeiten**
19|Geburtsname|A|50|-|-
20|Strasse|A|100|-|-
21|Adresszusatz|A|200|-|-
22|Land|A|3|-|-
23|PLZ|A|5|-|-
24|Ort|A|100|-|-
25|Ortsteil|A|100|-|-
26|Adressgebiet|A|300|-|-
27|Gemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
28|Stadtbezirk|A|10|V|Verweis auf Tabelle **Stadtbezirke**
29|Telefon|A|30|-|-
30|Telefax|A|30|-|-
31|Mobil|A|30|-|-
32|EMail|A|100|-|-
33|Wohnform|A|10|V|Verweis auf Tabelle **Wohnformen**
34|Staatsangeh1|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
35|Staatsangeh2|A|10|V|Verweis auf Tabelle **Staatsangehoerigkeiten**
36|Muttersprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
37|Verkehrssprache|A|10|V|Verweis auf Tabelle **Muttersprachen**
38|Sprachgruppe|A|10|V|Verweis auf Tabelle **Sprachgruppen**
39|SopaedFoerderung|A|10|V|Verweis auf Tabelle **SopaedFoerderungen**
40|FoerderSchwerpunkt1|A|10|V|Verweis auf Tabelle **FoerderSchwerpunkte**
41|FoerderSchwerpunkt2|A|10|V|Verweis auf Tabelle **FoerderSchwerpunkte**
42|Konfession|A|10|V|Verweis auf Tabelle **Konfessionen**
43|RelWunsch|A|10|V|Verweis auf Tabelle **RelWuensche**
44|NichtDeutscheHerkunft|L|-|-|-
45|RelTeilnahme|A|10|V|Verweis auf Tabelle **RelTeilnahmen**
46|RelGrund|A|10|V|Verweis auf Tabelle **RelGruende**
47|RelAbmeldungVon|D|-|-|-
48|RelAbmeldungBis|D|-|-|-
49|Umschulung|A|10|V|Verweis auf Tabelle **Umschulungsmerkmale**
50|Funktion1|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
51|Funktion2|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
52|Funktion3|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
53|Funktion4|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
54|Funktion5|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
55|Funktion6|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
56|Funktion7|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
57|Funktion8|A|10|V|Verweis auf Tabelle **SchuelerFunktionen**
58|Personalnr|A|15|-|-
59|Beeintraechtigung|A|200|-|-
60|Behinderung|A|10|V|Verweis auf Tabelle **Behinderungsarten**
61|Krankenkasse|A|10|V|Verweis auf Tabelle **Krankenkassen**
62|Versicherungsart|A|10|V|Verweis auf Tabelle **Versicherungsarten**
63|NotfallPerson|A|50|-|-
64|NotfallTelefon|A|30|-|-
65|Fahrschueler|L|-|-|-
66|Fahrstrecke|A|50|-|-
67|FahrstreckeKM|N|-|-|-
68|Einstiegsstelle|A|50|-|-
69|Verkehrsmittel|A|10|V|Verweis auf Tabelle **Verkehrsmittel**
70|Fahrgeld|N|-|-|-
71|FahrgeldbewVon|D|-|-|-
72|FahrgeldbewBis|D|-|-|-
73|Fahrkarte|A|10|V|Verweis auf Tabelle **Fahrkarten**
74|FahrkarteGueltigVon|D|-|-|-
75|FahrkarteGueltigBis|D|-|-|-
76|KFZ|A|15|-|-
77|Status|S|-|-|Mögliche Werte:<br/>0 = Bewerber (unbestätigt)<br/>1 = Bewerber<br/>2 = Neu (Keine Klasse / Kein Zeitraum)<br/>3 = Eingeschult (aktiv in Klasse undZeitraum)<br/>4 = Abgänger (inaktiv in Klasse und Zeitraum)<br/>5 = Vorlage Bewerber<br/>6 = Vorlage Schüler
78|Anmeldestatus|S|-|-|Mögliche Werte:<br/>0 = LABO<br/>1 = Angemeldet ( und angenommen)<br/>2 = AAG (Antrag, Aufnahme an andere Grundschule)
79|Profil|A|10|V|Verweis auf Tabelle **SchuelerProfile**
80|Aussiedler|L|-|-|-
81|AussiedlerSeit|D|-|-|-
82|Auslaender|L|-|-|-
83|AuslaenderSeit|D|-|-|-
84|InDeutschlandSeit|D|-|-|-
85|AufenthaltserlaubnisBis|D|-|-|-
86|SchulpflichtErfuellt|L|-|-|-
87|Bafoeg|L|-|-|-
88|BafoegBis|D|-|-|-
89|Integrationsschueler|L|-|-|-
90|Gastschueler|L|-|-|-
91|GastschulgeldUeberwiesen|L|-|-|-
92|Bildungskarte|L|-|-|Mögliche Werte:<br/>0 = B1 (Berlin)<br/>1 = B2 (Berlin)<br/>2 = L (Berlin)
93|BildungskarteBis|D|-|-|-
94|Foerderung|A|10|V|Verweis auf Tabelle **Foerderungen**
95|Foerdernr|A|8|-|-
96|Foerderbetrag|N|-|-|-
97|Unterstuetzung|A|10|V|Verweis auf Tabelle **Unterstuetzungen**
98|Betreuung|S|-|-|Mögliche Werte:<br/>0 = Heim<br/>1 = Hort<br/>2 =Internat
99|BetreuungAdresse|I|-|V|Verweis auf Tabelle **Adressen**
100|MittagessenTeilnahme|L|-|-|-
101|GanztagbetriebGebunden|S|-|-|Mögliche Werte:<br/>0 = Früh mit Ferien<br/>1 = Früh und spät mit Ferien<br/>2 = Spät und Ferien<br/>3 = Nur Ferienbetreuung
102|GanztagbetriebOffen|S|-|-|Mögliche Werte:<br/>0 = Früh<br/>1 = Nachmittags<br/>2 = Früh und nachmittags<br/>3 = Nachmittags und spät<br/>4 = Früh, nachmittags und spät<br/>5 = Nur Ferienbetreuung
103|BewerbungAm|D|-|-|-
104|Bewerbungsziel1|A|10|V|Verweis auf Tabelle **Bewerbungsziele**
105|Bewerbungsziel2|A|10|V|Verweis auf Tabelle **Bewerbungsziele**
106|Bewerbungsziel3|A|10|V|Verweis auf Tabelle **Bewerbungsziele**
107|Bewerbungsziel4|A|10|V|Verweis auf Tabelle **Bewerbungsziele**
108|BewerberStatus|S|-|-|Mögliche Werte:<br/>0 = Auf Warteliste<br/>1 = Angenommen für Bildungsziel 1<br/>2 = Angenommen für Bildungsziel 2br/>3 = Angenommen für Bildungsziel 3<br/>4 = Nicht angenommen<br/>5 = Angenommen für Bildungsziel 4<br/>6 = Beratungstest<br/>7 = Beratungsgespräch<br/>8 = Nicht zum Gespräch/Testerschienen <br/>9 = Aufnahmebescheid<br/>10 = Zusage nicht zurück<br/>11 = Abgemeldet<br/>12 = Rückmeldung
101|BewerberStatusAm|D|-|-|-
102|BewerberNote|N|-|-|Gesamtdurchschnitt
103|BewerberHFNote|N|-|-|Hauptfächerdurchschnitt
104|BewerberPunkte|N|-|-|-
105|BewerberRangzahl|S|-|-|-
106|BewerberRangzahlZiel1|S|-|-|-
107|BewerberRangzahlZiel2|S|-|-|-
108|BewerberRangzahlZiel3|S|-|-|-
109|BewerberRangzahlZiel4|S|-|-|-
110|Fremdsprache1|I|-|V|Verweis auf Tabelle **Faecher**
111|Fremdsprache1Von|S|-|-|-
112|Fremdsprache1Bis|S|-|-|-
113|Fremdsprache1Note|N|-|-|-
114|Fremdsprache1Status|S|-|-|Mögliche Werte:<br/>0 = Unterricht an berichtender Schule<br/>1 = Unterricht an anderer Schule<br/>2 = Unterricht anerkannt<br/>3 =Unterricht abgewählt<br/>4 = Wahlunterricht<br/>5 = Fach<br/>6 = Hauptfach<br/>7 = Ergänzendes Fach
115|Fremdsprache1Status2|S|-|-|Mögliche Werte: <br/>0 = Pflichtfach/Wahlpflichtfach<br/>1 = Wahlfach (fakultative FS)<br/>2 = Arbeitsgemeinschaft<br/>3 = Förderunterricht<br/>4 = Pflichtfach<br/>5 = Wahlpflichtfach<br/>6 = Neigungsunterricht<br/>7 = Muttersprachl. Unterricht<br/>8 = Basiskurs<br/>9 = Erweiterungskurs<br/>10 = Gymnasialkurs
101|Fremdsprache1Referenz|I|-|V|Verweis auf Tabelle **Sprachreferenzen**
102|Fremdsprache2|I|-|V|Verweis auf Tabelle **Faecher**
103|Fremdsprache2Von|S|-|-|-
104|Fremdsprache2Bis|S|-|-|-
105|Fremdsprache2Note|N|-|-|-
106|Fremdsprache2Status|S|-|-|Mögliche Werte:<br/>0 = Unterricht an berichtender Schule<br/>1 = Unterricht an anderer Schule<br/>2 = Unterricht anerkannt<br/>3 = Unterricht abgewählt<br/>4 = Wahlunterricht<br/>5 = Fach<br/>6 = Hauptfach<br/>7 = Ergänzendes Fach
107|Fremdsprache2Status2|S|-|-|Mögliche Werte: <br/>0 = Pflichtfach/Wahlpflichtfach<br/>1 = Wahlfach (fakultative FS)<br/>2 = Arbeitsgemeinschaft<br/>3 = Förderunterricht<br/>4 = Pflichtfach<br/>5 = Wahlpflichtfach<br/>6 = Neigungsunterricht<br/>7 = Muttersprachl. Unterricht<br/>8 = Basiskurs<br/>9 = Erweiterungskurs<br/>10 = Gymnasialkurs
108|Fremdsprache2Referenz|I|-|V|Verweis auf Tabelle **Sprachreferenzen**
109|Fremdsprache3|I|-|V|Verweis auf Tabelle **Faecher**
110|Fremdsprache3Von|S|-|-|-
111|Fremdsprache3Bis|S|-|-|-
112|Fremdsprache3Note|N|-|-|-
113|Fremdsprache3Status|S|-|-|Mögliche Werte:<br/>0 = Unterricht an berichtender Schule<br/>1 = Unterricht an anderer Schule<br/>2 = Unterricht anerkannt<br/>3 = Unterricht abgewählt<br/>4 = Wahlunterricht<br/>5 = Fach<br/>6 = Hauptfach<br/>7 = Ergänzendes Fach
114|Fremdsprache3Status2|S|-|-|Mögliche Werte: <br/>0 = Pflichtfach/Wahlpflichtfach<br/>1 = Wahlfach (fakultative FS)<br/>2 = Arbeitsgemeinschaft<br/>3 = Förderunterricht<br/>4 = Pflichtfach<br/>5 = Wahlpflichtfach<br/>6 = Neigungsunterricht<br/>7 = Muttersprachl. Unterricht<br/>8 = Basiskurs<br/>9 = Erweiterungskurs<br/>10 = Gymnasialkurs
115|Fremdsprache3Referenz|I|-|V|Verweis auf Tabelle **Sprachreferenzen**
116|Fremdsprache4|I|-|V|Verweis auf Tabelle **Faecher**
117|Fremdsprache4Von|S|-|-|-
118|Fremdsprache4Bis|S|-|-|-
119|Fremdsprache4Note|N|-|-|-
120|Fremdsprache4Status|S|-|-|Mögliche Werte:<br/>0 = Unterricht an berichtender Schule<br/>1 = Unterricht an anderer Schule<br/>2 = Unterricht anerkannt<br/>3 = Unterricht abgewählt<br/>4 = Wahlunterricht<br/>5 = Fach<br/>6 = Hauptfach<br/>7 = Ergänzendes Fach
121|Fremdsprache4Status2|S|-|-|Mögliche Werte: <br/>0 = Pflichtfach/Wahlpflichtfach<br/>1 = Wahlfach (fakultative FS)<br/>2 = Arbeitsgemeinschaft<br/>3 = Förderunterricht<br/>4 = Pflichtfach<br/>5 = Wahlpflichtfach<br/>6 = Neigungsunterricht<br/>7 = Muttersprachl. Unterricht<br/>8 = Basiskurs<br/>9 = Erweiterungskurs<br/>10 = Gymnasialkurs
122|Fremdsprache4Referenz|I|-|V|Verweis auf Tabelle **Sprachreferenzen**
123|Grundschuleintritt|D|-|-|-
124|Latinum|L|-|-|-
125|Graecum|L|-|-|-
126|Einschulung|S|-|-|Mögliche Werte: <br/>0 = Vorzeitige Einschulung<br/>1 = Fristgerechte Einschulung<br/>2 = Verspätete Einschulung
127|HoechsterBildungsgangABS|A|10|V|Verweis auf Tabelle **Bildungsgaenge**
128|HoechsterAbschlussABS|A|10|V|Verweis auf Tabelle **AbschluesseExtern**
129|HoechsterAbschlussABSAm|D|-|-|-
130|HoechsterAbschlussABSNote|N|-|-|-
131|HoechsterAbschlussABSSchule|I|-|V|Verweis auf Tabelle **SchuelerSchulen**
132|HoechsterBildungsgangBBS|A|10|V|Verweis auf Tabelle **Bildungsgaenge**
133|HoechsterAbschlussBBS|A|10|V|Verweis auf Tabelle **AbschluesseExtern**
134|HoechsterAbschlussBBSAm|D|-|-|-
135|HoechsterAbschlussBBSBeruf|A|10|V|Verweis auf Tabelle **Berufe**
136|HoechsterAbschlussBBSNote|N|-|-|-
137|HoechsterAbschlussBBSSchule|I|-|V|Verweis auf Tabelle **SchuelerSchulen**
138|HoechsterAbschlussBBSAustritt|S|-|-|Mögliche Werte:<br/>0 = Abschluss<br/>1 = Abgang<br/>2 = Abbruch
139|Berufsjahre|N|-|-|-
140|Ausbildung|I|-|V|Verweis auf Tabelle **SchuelerAusbildung**
141|ZugangAm|D|-|-|1. Zugangsdatum
142|Zugang2Am|D|-|-|2. Zugangsdatum
143|HerkunftSchule|I|-|V|Verweis auf Tabelle **SchuelerSchulen**
144|EinschulungAntrag|L|-|-|-
145|EinschulungAbgebendeSchule|I|-|V|Verweis auf Tabelle **Schulen**
146|Einschulmerkmal|A|10|V|Verweis auf Tabelle **Einschulmerkmale**
147|Einschulmerkmal2|A|10|V|Verweis auf Tabelle **Einschulmerkmale**
148|Einschulmerkmal3|A|10|V|Verweis auf Tabelle **Einschulmerkmale**
149|EinschulungBemerkung|M|-|-|-
150|VoraussichtlichesEnde|D|-|-|-
151|Ueberweisung|L|-|-|-
152|UeberweisungAm|D|-|-|-
153|Abgang|A|10|V|Verweis auf Tabelle **Abgangsarten**
154|AbgangAm|D|-|-|-
155|Abgang2Am|D|-|-|-
156|Uebergang|A|10|V|Verweis auf Tabelle **Uebergangsarten**
157|UebergangAm|D|-|-|-
158|UebergangAnSchule|I|-|V|Verweis auf Tabelle **Schulen**
159|UebergangAnSchulform|A|10|V|Verweis auf Tabelle **SchulformenUebergang**
160|UebergangKlassenstufe|A|10|V|Verweis auf Tabelle **Klassenstufen**
161|UebergangUnterlagen|L|-|-|-
162|UebergangFoerderUnterlagen|L|-|-|-
163|UebergangZeugnis|L|-|-|-
164|UebergangGeaendertAm|DT|-|-|-
165|UebergangGeaendertVon|A|20|-|-
166|Bemerkung|M|-|-|-
167|Passfoto|B|-|-|-
168|MerkmalA1|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
169|MerkmalA2|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
170|MerkmalA3|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
171|MerkmalA4|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
172|MerkmalA5|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
173|MerkmalA6|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
174|MerkmalS1|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
175|MerkmalS2|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
176|MerkmalS3|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
177|MerkmalS4|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
178|MerkmalS5|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
179|MerkmalS6|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
180|MerkmalS7|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
181|MerkmalS8|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
182|MerkmalS9|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
183|MerkmalS10|A|10|V|Verweis auf Tabelle **Schuelermerkmale**
184|MerkmalB1|A|100|-|-
185|MerkmalB2|A|100|-|-
186|MerkmalB3|A|100|-|-
187|MerkmalB4|A|100|-|-
188|MerkmalT1|A|100|-|-
189|MerkmalT2|A|100|-|-
190|MerkmalT3|A|100|-|-
191|MerkmalT4|D|-|-|-
192|MerkmalD1|D|-|-|-
193|MerkmalD2|D|-|-|-
194|MerkmalD3|D|-|-|-
195|MerkmalD4|D|-|-|-
196|MerkmalU1|D|-|-|-
197|MerkmalU1|D|-|-|-
198|Auskunft|S|-|-|Mögliche Werte:<br/>0 = Keine Angabe<br/>1 = Geheim
199|AuswaertigerSchueler|A|10|V|Verweis auf Tabelle **SchuelerArten**
200|AusstellungBehoerde|A|100|-|-
201|AusstellungBehoerdeDatum|D|-|-|-
202|BetreuungInnerschulisch1|A|10|V|Verweis auf Tabelle **BetreuungenInnerschulisch**
203|BetreuungInnerschulisch2|A|10|V|Verweis auf Tabelle **BetreuungenInnerschulisch**
204|BetreuungInnerschulisch3|A|10|V|Verweis auf Tabelle **BetreuungenInnerschulisch**
205|BetreuungAusserschulisch1|A|10|V|Verweis auf Tabelle **BetreuungenAusserschulisch**
206|BetreuungAusserschulisch2|A|10|V|Verweis auf Tabelle **BetreuungenAusserschulisch**
207|BetreuungAusserschulisch3|A|10|V|Verweis auf Tabelle **BetreuungenAusserschulisch**
208|AkteAngefordert|L|-|-|-
209|LMAnteil|S|-|-|Lernmittelanteil in Prozent vom Regelbeitrag
210|LMZahlungsstand|S|-|-|Mögliche Werte:<br/>0 = Unbezahlt<br/>1 = Mahnung 1<br/>2 = Mahnung 2<br/>3 = Mahnung 3<br/>4 = Bezahlt<br/>5 = Teilbezahlt
211|LMZahlungsstandDatum|D|-|-|-
212|LMZusatzbeitrag|N|-|-|-
213|LMBefreit|L|-|-|-
214|LMBefreitBis|D|-|-|-
215|AusweisAusgestelltAm|D|-|-|-
216|AusweisBemerkung|M|-|-|-
217|Wahlfach1|I|-|V|Verweis auf Tabelle **Faecher**
218|Wahlfach2|I|-|V|Verweis auf Tabelle **Faecher**
219|Wahlfach3|I|-|V|Verweis auf Tabelle **Faecher**
220|Wahlfach4|I|-|V|Verweis auf Tabelle **Faecher**
221|Wahlfach5|I|-|V|Verweis auf Tabelle **Faecher**
222|Wahlfach6|I|-|V|Verweis auf Tabelle **Faecher**
223|HoechsterAbschlussBBSBerufAm|D|-|-|-
224|SchuelerausweisBis|D|-|-|-
225|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
226|BLZ|I|-|-|Bankleitzahl
227|Bank|I|-|V|Verweis auf Tabelle **Banken**
228|Bankkonto|A|20|-|Bankkonto 1
229|BankIBAN|A|28|-|-
230|BankInhaber|A|300|-|-
231|BankInfo|A|300|-|-
232|BankBemerkung|A|300|-|-
233|Bank2|I|-|V|Verweis auf Tabelle **Banken**
234|Bank2konto|A|20|-|Bankkonto 2
235|Bank2IBAN|A|28|-|-
236|Bank2Inhaber|A|300|-|-
237|Bank2Info|A|300|-|-
238|Bank2Bemerkung|A|300|-|-
239|Rechnung1Name1|A|100|-|Rechnungsadresse 1
240|Rechnung1Name2|A|100|-|-
241|Rechnung1Strasse|A|100|-|-
242|Rechnung1Adressgebiet|A|300|-|-
243|Rechnung1Land|A|3|-|-
244|Rechnung1PLZ|A|5|-|-
245|Rechnung1Ort|A|100|-|-
246|Rechnung1Ortsteil|A|100|-|-
247|Rechnung1Adresszusatz|A|200|-|-
248|Rechnung2Name1|A|100|-|Rechnungsadresse 2
249|Rechnung2Name2|A|100|-|-
250|Rechnung2Strasse|A|100|-|-
251|Rechnung2Adressgebiet|A|300|-|-
252|Rechnung2Land|A|3|-|-
253|Rechnung2PLZ|A|5|-|-
254|Rechnung2Ort|A|100|-|-
255|Rechnung2Ortsteil|A|100|-|-
256|Rechnung2Adresszusatz|A|200|-|-
257|HeimatName1|A|100|-|Heimatadresse
258|HeimatName2|A|100|-|-
259|HeimatStrasse|A|100|-|-
260|HeimatAdressgebiet|A|300|-|-
261|HeimatLand|A|3|-|-
262|HeimatPLZ|A|5|-|-
263|HeimatOrt|A|100|-|-
264|HeimatOrtsteil|A|100|-|-
265|HeimatAdresszusatz|A|200|-|-
266|HeimatGemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
267|PassNr|A|100|-|- 
268|PassGueltigBis|D|-|-|-
269|VisumNr|A|100|-|-
270|VisumAblaufAm|D|-|-|-
271|VisumAusstellungsort|A|300|-|- 
272|Sozialversicherungsnummer|A|100|-|-
273|Aufenthaltsbemerkung|A|300|-|-

