#     Tabelle SchuelerFehlzeiten

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Klassenbucheintrag|I|-|V|Verweis auf Tabelle **Klassenbuch**
4|EintragNrSchueler|I|-|-|-
5|Klasse|I|-|V|Verweis auf Tabelle **KlassenbuchKlassen**
6|Schueler|I|-|V|Verweis auf Tabelle **Schueler**
7|Von|DT|-|-|-
8|Bis|DT|-|-|-
9|Fehlgrund|A|10|V|Verweis auf Tabelle **SchuelerFehlgruende**
10|Fehltext|M|-|-|-
11|Bemerkung|M|-|-|-
12|Entschuldigungsgrund|A|10|V|Verweise auf Tabelle <br/>**Entschuldigungsgruende**
13|Entschuldigt|L|-|-|-
14|Versaeumt|L|-|-|-
15|AnzahlTage|I|-|-|-
16|AnzahlStunden|N|-|-|-
17|LogErsteintrag|DT|-|-|-
18|LogErsteintrag_Benutzer|A|20|-|-
19|LogLetzteAenderung|DT|-|-|-
20|LogLetzteAenderung_Benutzer|A|20|-|-
