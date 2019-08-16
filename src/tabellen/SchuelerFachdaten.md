#        Tabelle SchuelerFachdaten


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Schueler|I|-|V|Verweis auf Tabelle **Schueler**
4|Klasse|I|-|V|Verweis auf Tabelle **Klassen**
5|Zeitraum|I|-|V|Verweis auf Tabelle **Zeitraeume**
6|Fach|I|-|V|Verweis auf Tabelle **Faecher**
7|Unterrichtsart|A|10|V|Verweis auf Tabelle **Unterrichtsarten**
8|Fachstatus|A|10|V|Verweis auf Tabelle **Fachstati**
9|Schwerpunkt|A|10|V|Verweis auf Tabelle **Fachschwerpunkte**
10|Niveau|A|10|V|Verweis auf Tabelle **Fachniveaus**
11|KursNr|S|-|-|-
12|Beurteilung|M|-|-|-
13|Note1|I|-|V|Verweis auf Tabelle **Noten**
14|Note2|I|-|V|Verweis auf Tabelle **Noten**
15|Note3|I|-|V|Verweis auf Tabelle **Noten**
16|Note4|I|-|V|Verweis auf Tabelle **Noten**
17|Note5|I|-|V|Verweis auf Tabelle **Noten**
18|Note6|I|-|V|Verweis auf Tabelle **Noten**
19|Note7|I|-|V|Verweis auf Tabelle **Noten**
20|Note8|I|-|V|Verweis auf Tabelle **Noten**
21|Note9|I|-|V|Verweis auf Tabelle **Noten**
22|Note10|I|-|V|Verweis auf Tabelle **Noten**
23|Note11|I|-|V|Verweis auf Tabelle **Noten**
24|Note12|I|-|V|Verweis auf Tabelle **Noten**
25|Note13|I|-|V|Verweis auf Tabelle **Noten**
26|Note14|I|-|V|Verweis auf Tabelle **Noten**
27|Vornote|I|-|V|Verweis auf Tabelle **Noten**
28|Endnote1|I|-|V|Verweis auf Tabelle **Noten**
29|Endnote2|I|-|V|Verweis auf Tabelle **Noten**
30|Faktor|N|-|-|-
31|Position|S|-|-|-
32|Merkmal|A|8|-|-
33|Lehrer|I|-|V|Verweis auf Ansicht **Lehrer**
34|ZusatzKlasse|I|-|V|Verweis auf Tabelle **Klassen**
35|IstStammkurs|A|1|-|-
36|Endnote1Fortschreiben|A|1|-|-
37|Mahnung|S|-|-|Mögliche Werte:<br/>0 = Mahnung<br/>1 = Nachmahnung<br/>2 = Nachprüfung 
38|Hauptfach|I|-|V|Verweis auf Tabelle **Faecher**<br/>Übergeordnetes Fach für das Feld „Fach“
39|Bilingual|A|10|V|Verweis auf Tabelle **Kurssprachen**
40|HausaufgabenVergessen|S|-|-|-
41|ArbeitsmittelVergessen|S|-|-|-
42|Muendlich|A|1|-|-
