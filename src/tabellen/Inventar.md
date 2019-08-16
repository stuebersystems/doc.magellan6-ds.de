# Tabelle Inventar


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Barcode|A|20|-|-
4|InventarNr|A|15|-|-
5|GeraeteNr|A|15|-|-
6|Bezeichnung|A|50|-|-
7|Kategorie|A|10|V|Verweis auf Tabelle **InventarKategorien**
8|Standort|A|10|V|Verweis auf Tabelle **Standorte**
9|Anfangsbestand|S|-|-|-
10|AnzGesamt|I|-|-|Über Trigger berechneter Wert
11|Bemerkung|M|-|-|-
