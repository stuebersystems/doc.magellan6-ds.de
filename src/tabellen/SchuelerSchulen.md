#       Tabelle SchuelerSchulen


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle ** Mandanten**
2|ID|I+|-|P|-
3|Schueler|I|-|V|Verweis auf Tabelle ** Schueler**
4|Schule|I|-|V|Verweis auf Tabelle ** Schule**
5|Schulform|A|10|V|Verweis auf Tabelle ** SchulformenHerkunft**
6|Schulart|A|10|V|Verweis auf Tabelle ** SchulartenHerkunft**
7|Von|D|-|-|-
8|Bis|D|-|-|-
9|LetzteKlasse|A|15|-|-
10|Abschluss|A|10|-|Verweis auf Tabelle ** AbschluesseExtern**
11|Herkunft|A|10|-|Verweis auf Tabelle ** Herkunftsarten**
12|Unterlagen|A|10|-|Verweis auf Tabelle ** Herkunftsunterlagen**
13|Klassenstufe|A|10|-|Verweis auf Tabelle ** Klassenstufen**
14|Sprachfoerderung|L|-|-|-
15|Laufbahn|S|-|-|Mögliche Werte:<br/>0 = Einschulung in die Primarstufe<br/>1 = Übergang in die SEK I<br/>2 = Übergang in die SEK II<br/>3 = Übergang in BBS<br/>4 = Zuletzt besuchte Schule
