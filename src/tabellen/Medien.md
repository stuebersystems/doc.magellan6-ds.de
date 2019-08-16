#        Tabelle Medien


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1      |Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2      |ID|I+|-|P|-
3      |Barcode|A|20|-|-
4      |BarcodePrint|A|20|-|-
5      |InventarNr|A|15|-|-
6      |Titel|A|100|-|-
7      |Untertitel|A|100|-|-
8      |Medienart|A|10|V|Verweis auf Tabelle **Medienarten**
9      |Medienkategorie|A|10|V|Verweis auf Tabelle **Medienkategorien**
10    |Standort|A|10|V|Verweis auf Tabelle **Standorte**
11    |Verlag|I|-|V|Verweis auf Tabelle **Verlage**
12    |Verlagsname|A|50|-|-
13    |Verlagsort|A|50|-|-
14    |Herausgeber|A|50|-|-
15    |Autor|A|50|-|-
16    |Signaturvorgabe|A|50|-|-
17    |Copyright|A|50|-|-
18    |ISBN|A|20|-|-
19    |ISSN|A|20|-|-
20    |Erscheinungsjahr|S|-|-|-
21    |Erscheinungsland|A|10|V|Verweis auf Tabelle **Staaten**
22    |Erscheinungsweise|A|10|V|Verweis auf Tabelle **Erscheinungsweisen**
23    |Sprache|A|10|V|Verweis auf Tabelle **Sprachen**
24    |Format|A|10|V|Verweis auf Tabelle **Medienformate**
25    |Umfang|A|100|-|-
26    |Serie|A|30|-|-
27    |Band|A|30|-|-
28    |Heft|A|30|-|-
29    |Ausgabe|A|30|-|-
30    |Jahrgang|S|-|-|-
31    |Zusammenfassung|M|-|-|-
32    |Bemerkung|M|-|-|-
33    |Status|S|-|-|Mögliche Werte:<br/>0 = Ausleihbar<br/>1 = Nicht ausleihbar<br/>2 = Nicht aktuell<br/>3 = Dauerverleih / Teilweise Dauerverleih<br/>4 = Dauerleihgabe / Teilweise Dauerleihgabe
34    |Mehrjahresband|L|-|-|-
35    |JahrgangVon|A|10|V|Verweis auf Tabelle **MedienJahrgaenge**
36    |JahrgangBis|A|10|V|Verweis auf Tabelle **MedienJahrgaenge**
