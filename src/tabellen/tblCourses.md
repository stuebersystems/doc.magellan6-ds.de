#       Tabelle tblCourses


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|Term|I|-|V|Zeitraum<br/>Verweis auf Tabelle **Zeitraeume**
5|Subject|I|-|V|Fach<br/>Verweis auf Tabelle **Faecher**
6|SubjectStatus|A|10|V|Fachstatus<br/>Verweis auf Tabelle **Fachstati**
7|SubjectType|A|10|V|Unterrichtsart<br/>Verweis auf Tabelle **Unterrichtsarten**
8|SubjectTeacher|I|-|V|Lehrer<br/> Verweis auf Ansicht **Lehrer**
9|Focus|A|10|V|Fachschwerpunkt<br/>Verweis auf Tabelle **Fachschwerpunkte**
10|Level|A|10|V|Fachniveau<br/> Verweis auf Tabelle **FachNiveaus**
11|CourseNo|S|-|-|KursNr
12|Bilingual|A|10|V|Verweis auf Tabelle **Kurssprachen**
13|Attribute|A|8|-|Merkmal
