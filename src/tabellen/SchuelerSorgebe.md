# Tabelle SchuelerSorgebe


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Schueler|I|-|V|Verweis auf Tabelle **Schueler**
4|Sorgebe|I|-|V|Verweis auf Tabelle **Sorgeberechtigte**
5|Lehrer|I|-|V|Verweis auf Ansicht **Lehrer**
6|Person|I|-|V|Verweis auf Tabelle **Personen**
7|Geschwister|I|-|V|Verweis auf Tabelle **Schueler**
8|Familiennr|A|50|-|-
9|Verhaeltnis|S|-|-|Mögliche Werte:<br/>0   = Mutter<br/>1   = Vater<br/>2   = Eltern<br/>3   = Erziehungsberechtigte(r)<br/>4   = Sorgeberechtigte(r)<br/>5   =Ansprechpartner(in)<br/>6   = Vormund<br/>7   = Großmutter<br/>8   = Großvater<br/>9   = Pflegeelternbr/>10 = Eheleute<br/>11 = Verhältnis1<br/>12 = Verhältnis2<br/>13 =Verhältnis3<br/>14 = Verhältnis4<br/>15 = Verhältnis5<br/>16 = Verhältnis6<br/>17 = Verhältnis7<br/>18 = Verhältnis8<br/>19 = Verhältnis9<br/>20 = Verhältnis10<br/>"(Werte für die Verhältnis 11 … 20 können über „Bezeichnungen anpassen"" ersetzt werden)"
10|Sorgerecht|L|-|-|-
11|Benachrichtigung|S|-|-|Mögliche Werte:<br/>0 = Immer<br/>1 = Nur im Notfall<br/>2 = Nie
12|SeriendruckName1|A|300|-|-
13|SereindruckName2|A|300|-|-
14|Briefempfaenger|A|300|-|-
15|Briefanrede|A|300|-|-
16|TelefonPrioritaet|S|-|-|Mögliche Werte:<br/>0 = Telefon privat<br/>1 = Telefon beruf<br/>2 = Mobil
17|Position|S|-|-|-
18|Bemerkung|M|-|-|-
