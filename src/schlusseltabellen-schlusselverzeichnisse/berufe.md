# Tabelle Berufe

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
---|---|---|---|---|---
1|ID|I+|-|P |-
2|Kuerzel|A|15|-|-
3|Schluessel|A|10|-|-
4|BezeichnungM|A|240|-|Männliche Bezeichnung
5|BezeichnungW|A|240|-|Weibliche Bezeichnung
6|Fachrichtung|A|10|V|Verweis auf Tabelle **Fachrichtungen**
7|Berufsfeld|A|10|V|Verweis auf Tabelle **Berufsfelder**
8|Kategorie|S|-|-|Mögliche Werte:  <br/>0 = Interne Schlüssel<br/>1 = Externe Schlüssel<br/>2 = Interne und Externe Schlüssel
9|StatistikID|A|16|-|-
10|GueltigVon|D|-|-|-
11|GueltigBis|D|-|-|-
