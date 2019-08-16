#     Tabelle StudentCourseAttendance

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|StudentTerm|I|-|V|SchülerZeitraum<br/>Verweis auf Tabelle<br/>**SchuelerZeitraeume**
5|Course|I|-|V|Kurs<br/>Verweis auf Tabelle **tblCourses**
6|ForgotHomework|S|-|-|HausaufgabenVergessen
7|ForgotMaterial|S|-|-|ArbeitsmittelVergessen
8|Position|I|-|-|-
