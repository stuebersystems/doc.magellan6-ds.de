# View SchuelerAnsicht

Grundlage sind die Tabellen:

* [Schueler](https://doc.magellan6-datenstruktur.stueber.de/tabellen/Schueler.html)
* [SchuelerZeitraeume](https://doc.magellan6-datenstruktur.stueber.de/tabellen/SchuelerZeitraeume.html)
* [KlassenZeitraeume](https://doc.magellan6-datenstruktur.stueber.de/tabellen/KlassenZeitraeume.html)


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|-|-
2|ID|I|-|-|-
3|GUID|A|32|-|-
4|IDIntern|I|-|-|-
5|IDExtern|I|-|-|-
6|GUIDExtern|A|36|-|-
7|KlassenZeitraumID|I|-|-|-
8|SchuelerZeitraumID|I|-|-|-
9|Klasse|I|-|-|-
10|Zeitraum|I|-|-|-
11|Gewechselt|L|1|-|-
12|Barcode|A|20|-|-
13|BarcodePrint|A|20|-|-
14|Nachname|A|50|-|-
15|Namenszusatz|A|100|-|-
16|Vorname|A|100|-|-
17|Vorname2|A|100|-|-
18|Anrede|A|1|-|-
19|Geschlecht|A|1|-|-
20|Geburtsdatum|D|-|-|-
21|Geburtsort|A|100|-|-
22|Geburtskreis|A|100|-|-
23|Geburtsland|A|10|-|-
24|Geburtsname|A|50|-|-
25|Strasse|A|100|-|-
26|Adresszusatz|A|200|-|-
27|Land|A|3|-|-
28|PLZ|A|10|-|-
29|Ort|A|100|-|-
30|Ortsteil|A|100|-|-
31|Adressgebiet|A|300|-|-
32|Gemeinde|A|8|-|-
33|Stadtbezirk|A|10|-|-
34|Telefon|A|30|-|-
35|Telefax|A|30|-|-
36|Mobil|A|30|-|-
37|EMail|A|100|-|-
38|Tutor|I|-|-|-
39|Wohnform|A|10|-|-
40|Staatsangeh1|A|10|-|-
41|Staatsangeh2|A|10|-|-
42|Muttersprache|A|10|-|-
43|Verkehrssprache|A|10|-|-
44|SopaedFoerderung|A|10|-|-
45|FoerderSchwerpunkt1|A|10|-|-
46|FoerderSchwerpunkt2|A|10|-|-
47|Sprachgruppe|A|10|-|-
48|Konfession|A|10|-|-
49|RelWunsch|A|10|-|-
50|RelTeilnahme|A|10|-|-
51|RelGrund|A|10|-|-
52|RelAbmeldungVon|D|-|-|-
53|RelAbmeldungBis|D|-|-|-
54|Umschulung|A|10|-|-
55|Funktion1|A|10|-|-
56|Funktion2|A|10|-|-
57|Funktion3|A|10|-|-
58|Funktion4|A|10|-|-
59|Funktion5|A|10|-|-
60|Funktion6|A|10|-|-
61|Funktion7|A|10|-|-
62|Funktion8|A|10|-|-
63|Personalnr|A|15|-|-
64|Beeintraechtigung|A|200|-|-
65|Behinderung|A|10|-|-
66|Krankenkasse|A|10|-|-
67|Versicherungsart|A|10|-|-
68|NotfallPerson|A|50|-|-
69|NotfallTelefon|A|30|-|-
70|Fahrschueler|L|-|-|-
71|Fahrstrecke|A|50|-|-
72|FahrstreckeKM|N|-|-|-
73|Einstiegsstelle|A|50|-|-
74|Verkehrsmittel|A|10|-|-
75|Fahrgeld|N|-|-|-
76|FahrgeldbewVon|D|-|-|-
77|FahrgeldbewBis|D|-|-|-
78|Fahrkarte|A|10|-|-
79|FahrkarteGueltigVon|D|-|-|-
80|FahrkarteGueltigBis|D|-|-|-
81|KFZ|A|15|-|-
82|Status|S|-|-|-
83|Profil|A|10|-|-
84|Aussiedler|L|-|-|-
85|AussiedlerSeit|D|-|-|-
86|Auslaender|L|-|-|-
87|AuslaenderSeit|D|-|-|-
88|InDeutschlandSeit|D|-|-|-
89|AufenthaltserlaubnisBis|D|-|-|-
90|SchulpflichtErfuellt|L|-|-|-
91|Bafoeg|L|-|-|-
92|BafoegBis|D|-|-|-
93|Integrationsschueler|L|-|-|-
94|Gastschueler|L|-|-|-
95|GastschulgeldUeberwiesen|L|-|-|-
96|Foerderung|A|10|-|-
97|Foerdernr|A|20|-|-
98|Foerderbetrag|N|-|-|-
99|Unterstuetzung|A|10|-|-
100|Betreuung|S|-|-|-
101|BetreuungAdresse|I|-|-|-
102|MittagessenTeilnahme|L|-|-|-
103|GanztagbetriebGebunden|S|-|-|-
104|GanztagbetriebOffen|S|-|-|-
105|BewerbungAm|D|-|-|-
106|Bewerbungsziel1|A|10|-|-
107|Bewerbungsziel2|A|10|-|-
108|Bewerbungsziel3|A|10|-|-
109|Bewerbungsziel4|A|10|-|-
110|BewerberStatus|S|-|-|-
111|BewerberStatusAm|D|-|-|-
112|BewerberHFNote|N|-|-|-
113|BewerberNote|N|-|-|-
114|BewerberPunkte|N|-|-|-
115|BewerberRangzahl|S|-|-|-
116|BewerberRangzahlZiel1|N|-|-|-
117|BewerberRangzahlZiel2|N|-|-|-
118|BewerberRangzahlZiel3|N|-|-|-
119|BewerberRangzahlZiel4|N|-|-|-
120|Fremdsprache1|A|10|-|-
121|Fremdsprache1Von|S|-|-|-
122|Fremdsprache1Bis|S|-|-|-
123|Fremdsprache1Status|S|-|-|-
124|Fremdsprache1Status2|S|-|-|-
125|Fremdsprache1Note|N|-|-|-
126|Fremdsprache1Referenz|A|10|-|-
127|Fremdsprache2|A|-|-|-
128|Fremdsprache2Von|S|-|-|-
129|Fremdsprache2Bis|S|-|-|-
130|Fremdsprache2Status|S|-|-|-
131|Fremdsprache2Status2|S|-|-|-
132|Fremdsprache2Note|N|-|-|-
133|Fremdsprache2Referenz|A|10|-|-
134|Fremdsprache3|A|-|-|-
135|Fremdsprache3Von|S|-|-|-
136|Fremdsprache3Bis|S|-|-|-
137|Fremdsprache3Status|S|-|-|-
138|Fremdsprache3Status2|S|-|-|-
139|Fremdsprache3Note|N|-|-|-
140|Fremdsprache3Referenz|A|10|-|-
141|Fremdsprache4|A|-|-|-
142|Fremdsprache4Von|S|-|-|-
143|Fremdsprache4Bis|S|-|-|-
144|Fremdsprache4Status|S|-|-|-
145|Fremdsprache4Status2|S|-|-|-
146|Fremdsprache4Note|N|-|-|-
147|Fremdsprache4Referenz|A|10|-|-
148|Wahlfach1|I|-|-|-
149|Wahlfach2|I|-|-|-
150|Wahlfach3|I|-|-|-
151|Wahlfach4|I|-|-|-
152|Wahlfach5|I|-|-|-
153|Wahlfach6|I|-|-|-
154|Ausbildung|I|-|-|-
155|Grundschuleintritt|D|-|-|-
156|Einschulung|S|-|-|-
157|HoechsterBildungsgangABS|A|10|-|-
158|HoechsterAbschlussABS|A|10|-|-
159|HoechsterAbschlussABSSchule|I|-|-|-
160|HoechsterAbschlussABSAm|D|-|-|-
161|HoechsterAbschlussABSNote|N|-|-|-
162|HoechsterBildungsgangBBS|A|10|-|-
163|HoechsterAbschlussBBS|A|10|-|-
164|HoechsterAbschlussBBSSchule|I|-|-|-
165|HoechsterAbschlussBBSAm|D|-|-|-
166|HoechsterAbschlussBBSNote|N|-|-|-
167|HoechsterAbschlussBBSAustritt|D|-|-|-
168|HoechsterAbschlussBBSBeruf|A|10|-|-
169|HoechsterAbschlussBBSBerufAm|D|-|-|-
170|Berufsjahre|N|-|-|-
171|Anmeldestatus|S|-|-|-
172|ZugangAm|D|-|-|-
173|Zugang2Am|D|-|-|-
174|HerkunftSchule|I|-|-|-
175|Einschulmerkmal|A|10|-|-
176|Einschulmerkmal2|A|10|-|-
177|Einschulmerkmal3|A|10|-|-
178|EinschulungAntrag|L|-|-|-
179|EinschulungAbgebendeSchule|I|-|-|-
180|EinschulungBemerkung|M|-|-|-
181|VoraussichtlichesEnde|D|-|-|-
182|Ueberweisung|L|-|-|-
183|UeberweisungAm|D|-|-|-
184|Abgang|A|10|-|-
185|AbgangAm|D|-|-|-
186|Abgang2Am|D|-|-|-
187|Uebergang|A|10|-|-
188|UebergangAnSchule|I|-|-|-
189|UebergangAnSchulform|A|10|-|-
190|UebergangAm|D|-|-|-
191|UebergangKlassenstufe|A|10|-|-
192|UebergangUnterlagen|L|-|-|-
193|UebergangFoerderUnterlagen|L|-|-|-
194|UebergangZeugnis|L|-|-|-
195|UebergangGeaendertAm|D|-|-|-
196|UebergangGeaendertVon|D|-|-|-
197|MerkmalA1|A|10|-|-
198|MerkmalA2|A|10|-|-
199|MerkmalA3|A|10|-|-
200|MerkmalA4|A|10|-|-
201|MerkmalA5|A|10|-|-
202|MerkmalA6|A|10|-|-
203|MerkmalS1|A|10|-|-
204|MerkmalS2|A|10|-|-
205|MerkmalS3|A|10|-|-
206|MerkmalS4|A|10|-|-
207|MerkmalS5|A|10|-|-
208|MerkmalS6|A|10|-|-
209|MerkmalS7|A|10|-|-
210|MerkmalS8|A|10|-|-
211|MerkmalS9|A|10|-|-
212|MerkmalS10|A|10|-|-
213|MerkmalB1|A|100|-|-
214|MerkmalB2|A|100|-|-
215|MerkmalB3|A|100|-|-
216|MerkmalB4|A|100|-|-
217|MerkmalT1|A|100|-|-
218|MerkmalT2|A|100|-|-
219|MerkmalT3|A|100|-|-
220|MerkmalT4|A|100|-|-
221|MerkmalD1|A|100|-|-
222|MerkmalD2|A|100|-|-
223|MerkmalD3|A|100|-|-
224|MerkmalD4|A|100|-|-
225|MerkmalU1|A|100|-|-
226|MerkmalU2|A|100|-|-
227|Auskunft|S|-|-|-
228|AuswaertigerSchueler|A|10|-|-
229|AusstellungBehoerde|A|100|-|-
230|AusstellungBehoerdeDatum|D|-|-|-
231|BetreuungInnerschulisch1|A|10|-|-
232|BetreuungInnerschulisch2|A|10|-|-
233|BetreuungInnerschulisch3|A|10|-|-
234|BetreuungAusserschulisch1|A|10|-|-
235|BetreuungAusserschulisch2|A|10|-|-
236|BetreuungAusserschulisch3|A|10|-|-
237|Schulbesuchsjahr|S|-|-|-
238|Ausbildungsjahr|S|-|-|-
239|Fachkombination|A|4|-|-
240|TeilnahmeZusatzangebot|L|-|-|-
241|SportBefreit|L|-|-|-
242|Unterrichtstage|S|-|-|-
243|Fehltage|S|-|-|-
244|FehltageU|S|-|-|-
245|Fehlstunden|S|-|-|-
246|FehlstundenU|S|-|-|-
247|Versaeumnisse|S|-|-|-
248|Verhalten|I|-|-|-
249|Mitarbeit|I|-|-|-
250|ZeugniskonferenzAm|D|-|-|-
251|ZeugnisausgabeAm|D|-|-|-
252|Anrechnungsdatum|D|-|-|-
253|Durchschnitt1|N|-|-|-
254|Durchschnitt2|N|-|-|-
255|Durchschnitt3|N|-|-|-
256|Pruefungsvorsitz|I|-|-|-
257|Jahrgang|S|-|-|-
258|AkteAngefordert|L|-|-|-
259|LMAnteil|S|-|-|-
260|LMZahlungsstand|S|-|-|-
261|LMZahlungsstandDatum|D|-|-|-
262|LMZusatzbeitrag|N|-|-|-
263|LMBefreit|L|-|-|-
264|LMBefreitBis|D|-|-|-
265|AusweisAusgestelltAm|D|-|-|-
266|AusweisBemerkung|A|150|-|-
267|Bildungskarte|S|-|-|-
268|BildungskarteBis|D|-|-|-
269|NichtDeutscheHerkunft|L|-|-|-
270|SchuelerausweisBis|D|-|-|-
271|BLZ|I|-|-|-
272|Bank|I|-|-|-
273|Bankkonto|A|20|-|-
274|BankIBAN|A|28|-|-
275|BankInhaber|A|300|-|-
276|BankInfo|A|300|-|-
277|BankBemerkung|A|300|-|-
278|Bank2|I|-|-|-
279|Bank2konto|A|20|-|-
280|Bank2IBAN|A|28|-|-
281|Bank2Inhaber|A|300|-|-
282|Bank2Info|A|300|-|-
283|Bank2Bemerkung|A|300|-|-
284|Rechnung1Name1|A|100|-|-
285|Rechnung1Name2|A|100|-|-
286|Rechnung1Strasse|A|100|-|-
287|Rechnung1Adresszusatz|A|200|-|-
288|Rechnung1Land|A|3|-|-
289|Rechnung1PLZ|A|10|-|-
290|Rechnung1Ort|A|100|-|-
291|Rechnung1Ortsteil|A|100|-|-
292|Rechnung1Adressgebiet|A|300|-|-
