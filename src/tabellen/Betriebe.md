# Tabelle Betriebe

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|GUID|A|32|-|-
4|IDIntern|I|-|-|-
5|IDExtern|I|-|-|-
6|GUIDExtern|A|36|-|-
7|Kuerzel|A|15|-|-
8|Name1|A|50|-|-
9|Name2|A|50|-|-
10|Strasse|A|100|-|-
11|Land|A|3|-|-
12|PLZ|A|5|-|-
13|Ort|A|100|-|-
14|Ortsteil|A|100|-|-
15|Gemeinde|A|8|V|Verweis auf Tabelle **Gemeinden**
16|Telefon|A|30|-|-
17|Telefax|A|30|-|-
18|Internet|A|100|-|-
19|Email|A|100|-|-
20|Branche|A|10|V|Verweis auf Tabelle **Branchen**
21|Kammer|A|10|V|Verweis auf Tabelle **Kammern**
22|Arbeitsamt|A|10|V|Verweis auf Tabelle **Arbeitsaemter**
23|Sponsor|A|10|V|Verweis auf Tabelle **Sponsoren**
24|Status|S|-|-|Mögliche Werte:<br/>0 = Inaktiv<br/>1 = Aktiv
25|Bemerkung|M|-|-|-
26|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
