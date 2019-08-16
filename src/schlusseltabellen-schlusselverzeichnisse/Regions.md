#       Tabelle Regions


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|ID|I+|-|P|-
2|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
3|Kuerzel|A|10|-|-
4|Schluessel|A|10|-|-
5|Bezeichnung|A|100|-|-
6|StatistikID|A|16|-|-
7|Land|I|-|V|Verweis auf Tabelle **Staaten**
8|RegionTyp|I|-|V|Verweis auf Tabelle **RegionTypes**
9|InternalCode|A|3|-|Interner Code<br/><br/>Mögliche Werte:<br/>werden zukünftig noch festgelegt
10|GueltigVon|D|-|-|-
11|GueltigBis|D|-|-|-
