#	Tabelle Klassen


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandanten|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I|-|P|-
3|GUID|A|32|-|-
4      |IDIntern|I|-|-|-
5      |IDExtern|I|-|-|-
6      |GUIDExtern|A|36|-|-
6      |Kuerzel|A|15|-|-
7      |KuerzelAlpha|A|8|-|-
8      |KuerzelStatistik|A|20|-|-
9      |Langname1|A|100|-|-
10    |Langname2|A|100|-|-
11|Klassenart|S|-|-|Mögliche Werte:<br/>0 = Standardklasse<br/>1 = Ganztagsklasse<br/>2 = Oberstufenjahrgang (Nur Kurse)<br/>3 = Oberstufenjahrgang (Leistungs- u. Grundkurse)<br/>4 = Abschlussklasse<br/>5 = Kombinationsklasse<br/><br/>6 = Schulkindergarten<br/>7 = Standardklasse mit Oberstufensynchronisation
12| Notenart|S|-|-|Mögliche Werte:<br/>0 = Notenwerte<br/>1 = Punktwerte<br/>2 = Beurteilungen
13|Abteilung|A|10|V|Verweis auf Tabelle **Abteilungen**
14|Schulform|A|10|V|Verweis auf Tabelle **Schulformen**
15|Schulart|A|10|V|Verweis auf Tabelle *Schularten*
16|Organisation|A|10|V|Verweis auf Tabelle **Organisationen**
17|Behinderung|A|10|V|Verweis auf Tabelle **Behinderungsarten**
18|Foerderschwerpunkt1|A|10|V|Verweis auf Tabelle **FoerderSchwerpunkte**
19|Foerderschwerpunkt2|A|10|V|Verweis auf Tabelle **FoerderSchwerpunkte**
20|Beruf|A|10|V|Verweis auf Tabelle **Berufe**
21|Bildungsgang|A|10|V|Verweis auf Tabelle **Bildungsgaenge**
22|Berufsfeld|A|10|V|Verweis auf Tabelle **Berufsfelder**
23|Integration|A|10|V|Verweis auf Tabelle **Integrationsmerkmale**
24|Einzelintegration|L|-|-|-
25|Laenderuebergreifend|L|-|-|-
26|Schulartuebergreifend|L|-|-|-
27|Schulstelle|A|10|V|Verweis auf Tabelle **Schulstellen**
28|Foerderung|A|10|V|Verweis auf Tabelle **Foerderungen**
29|Regelbeitrag|N|-|-|Regelbeitrag für **Lernmittel**
30|Bemerkung|M|-|-|-
31|MerkmalA1|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
32|MerkmalA2|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
33|MerkmalA3|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
34|MerkmalA4|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
35|MerkmalA5|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
36|MerkmalA6|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
37|MerkmalS1|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
38|MerkmalS2|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
39|MerkmalS3|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
40|MerkmalS4|A|10|V|Verweis auf Tabelle **Klassenmerkmale**
41|MerkmalB1|A|15|-|-
42|MerkmalB2|A|15|-|-
43|MerkmalB3|A|15|-|-
44|MerkmalB4|A|15|-|-
45|KBGueltigVon|D|-|-|Klassenbuch gültig von
46|KBGueltigBis|D|-|-|Klassenbuch gültig bis
47|KBFuehrer|I|-|V|Klassenbuchführer, Verweis auf Ansicht **Lehrer**
48|KBBemerkung|M|-|-|Klassenbuch Bemerkung
49|Klassenorganisation|A|10|-|Verweis auf Tabelle **Klassenorganisationen**
50|Maske|S|-|-|Standardmaske der Klasse
51|Schuelerplan|L|-|-|Soll bei der Anzeige der Stundenplans der Schüler der Klasse der individuelle Schülerplan anstelle des Klassenplan angezeigt werden
52|NaechsteKlasse|I|-|V|Verweis auf Tabelle **Klassen**
53|NaechsteKlasseZeitraum|I|-|V|Verweis auf Tabelle **Zeitraeume**
54|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
