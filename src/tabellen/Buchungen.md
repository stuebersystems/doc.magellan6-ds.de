# Tabelle Buchungen


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I|-|PV|-
3|Haushaltsstelle|I|-|V|Verweis auf Tabelle **Haushaltsstellen**
4|Buchungsart|S|-|-|Mögliche Werte:<br/>0 = Ausgabe<br/>1 = Einnahme<br/>2 = Ausgabe-Korrektur<br/>3 = Einnahme-Korrektur<br/>4 = Geplante Ausgabe
5|Bereich|A|10|V|Verweis auf Tabelle **Buchungsbereiche**
6|Datum|D|-|-|-
7|Betrag|N|-|-|-
8|Grund|M|-|-|-
9|BelegNr|A|15|-|-
10|Besteller|A|20|-|-
11|BestellNr|A|15|-|-
12|BestellDatum|D|-|-|-
13|RechnungNr|A|15|-|-
14|LieferscheinNr|A|15|-|-
15|Lieferant|I|-|V|Verweis auf Tabelle **Lieferanten**
16|Log_Datum|D|-|-|-
17|Log_Uhrzeit|T|-|-|-
18|Log_Benutzer|A|20|-|-
