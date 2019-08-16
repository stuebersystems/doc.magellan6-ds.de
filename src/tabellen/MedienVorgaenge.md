#        Tabelle MedienVorgaenge


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Exemplar|I|-|V|Verweis auf Tabelle **MedienExemplare**
4|Ausleiher|I|-|V|Verweis auf Tabelle **MedienAusleiher**
5|AusleiheVon|D|-|-|-
6|AusleiheBis|D|-|-|-
7|RueckgabeAm|D|-|-|-
8|Mahnstufe|S|-|-|-
9|Mahngebuehr|N|-|-|-
10|LetzteMahnungAm|D|-|-|-
11|MahnungBezahltAm|D|-|-|-
12|Verlaengern|S|-|-|-
13|Status|S|-|-|Mögliche Werte:<br/>0 = Offen<br/>1 = Gemahnt<br/>2 = Abgeschlossen
