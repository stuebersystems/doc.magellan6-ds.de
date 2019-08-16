# View LehrerFehlzeiten

Grundlage ist die Tabelle [tblLehrer](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblLehrerFehlzeiten.html).


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Lehrer|I|-|V|Verweis auf Ansicht **Lehrer**
4|Von|D|-|-|-
5|Bis|D|-|-|-
6|Stunden|N|-|-|-
7|Unterrichtstage|N|-|-|-
8|Fehltage|N|-|-|-
9|Grund|A|10|V|Verweis auf Tabelle **LehrerFehlgruende**
10|Voranfrage|A|1|-|-
11|Bemerkung|M|-|-|-
