# View ClassCourses

Grundlage sind:
* [KlassenZeitraeume](https://doc.magellan6-datenstruktur.stueber.de/tabellen/KlassenZeitraeume.html)
* [tblClassCourses](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblClassCourses.html)
* [tblCourses](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblCourses.html)

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|Verweis auf Tabelle **tblClassCourses**
3|ClassTerm|I|-|-|Verweis auf Tabelle **tblClassCourses**
4|Class|I|-|-|Verweis auf Tabelle **KlassenZeitraeume**
5|Term|I|-|-|Verweis auf Tabelle **tblCourses**
6|Course|I|-|-|Verweis auf Tabelle **tblClassCourses**
7|EnbreaID|I|-|-|EnbreaID
8|Subject|I|-|-|Verweis auf Tabelle **tblCourses**
9|SubjectStatus|-|-|-|Verweis auf Tabelle **tblCourses**
10|SubjectType|A|10|-|Verweis auf Tabelle **tblCourses**
11|SubjectTeacher|A|10|-|Verweis auf Tabelle **tblCourses**
12|Focus|A|10|-|Verweis auf Tabelle **tblCourses**
13|Level|A|10|-|Verweis auf Tabelle **tblCourses**
14|CourseNo|S|-|-|Verweis auf Tabelle **tblCourses**
15|Bilingual|A|10|-|Verweis auf Tabelle **tblCourses**
16|Attribute|A|8|-|Verweis auf Tabelle **tblCourses**