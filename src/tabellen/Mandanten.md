#     Tabelle Mandanten


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1      |ID|I+|-|P|-
2      |Kuerzel|A|15|-|-
3      |Name1|A|100|-|-
4      |Name2|A|100|-|-
5      |Name3|A|100|-|-
6      |Strasse|A|100|-|-
7      |Land|A|3|-|-
8      |PLZ|A|5|-|-
9      |Ort|A|100|-|-
10    |Ortsteil|A|100|-|-
11    |Gemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
12    |Telefon|A|30|-|-
13    |Telefax|A|30|-|-
14    |EMail|A|40|-|-
15    |Internet|A|40|-|-
16    |Hauptstelle|I|-|V|Verweis auf Tabelle **Mandanten**
17    |Aussenstelle|A|3|-|-
18    |Schulart|A|10|V|Verweis auf Tabelle **Schularten**
19    |Kategorie|A|10|V|Verweis auf Tabelle **Mandantenkategorien**
20    |Betreuungsform|A|10|V|Verweis auf Tabelle **Betreuungsformen**
21    |Schultraeger|A|10|V|Verweis auf Tabelle **Schultraeger**
22    |Schulstatus|A|10|V|Verweis auf Tabelle **Schulstati**
23    |Schulnummer|A|12|-|-
24    |Schulleiter|I|-|V|Verweis auf Ansicht **Lehrer**
25    |Stellvertreter|I|-|V|Verweis auf Ansicht **Lehrer**
26    |Adresse1|I|-|V|Verweis auf Tabelle **Adressen**
27    |Adresse1Art|S|-|-|Mögliche Werte:<br/>0 = Schulträger<br/>1 = Schulamt<br/>2 = Ministerium
28    |Adresse2|I|-|V|Verweis auf Tabelle **Adressen**
29    |Adresse2Art|S|-|-|Mögliche Werte:<br/>0 = Schulträger<br/>1 = Schulamt<br/>2 = Ministerium
30    |Adresse3|I|-|V|Verweis auf Tabelle **Adressen**
31    |Adresse3Art|S|-|-|Mögliche Werte:<br/>0 = Schulträger<br/>1 = Schulamt<br/>2 = Ministerium
32    |Bank|I|-|V|Verweis auf Tabelle **Banken**
33    |Bankkonto|A|-|20|-
34    |MinPersonalNr|I|-|-|-
35    |MaxPersonalNr|I|-|-|-
36    |Bemerkung|M|-|-|-
37    |MerkmalA1|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
38    |MerkmalA2|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
39    |MerkmalA3|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
40    |MerkmalA4|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
41    |MerkmalA5|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
42    |MerkmalA6|A|10|V|Verweis auf Tabelle **MandantenMerkmale**
43    |daVinciDatei|A|300|-|daVinci-Datei des Mandanten
44    |KBLetzteSynchronisation|DT|-|-|Letzte Synchronisation mit dem Klassenbuch
45    |Logo|M|-|-|-
46    |Logo2|M|-|-|-
47    |Rechtsstatus|S|-|-|Mögliche Werte:<br/>0 = öffentlich<br/>1 = Privat
48    |PruefungsNr|A|20|-|-
49    |EnbreaID|A|24|-|Externer Identifikator aus ENBREA
