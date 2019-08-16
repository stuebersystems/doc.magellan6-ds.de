#        Tabelle AchievementProfiles

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|ClassTerm|I|-|V|Verweis auf Tabelle **KlassenZeitraeume**
5|Course|I|-|V|Verweis auf Tabelle **tblCourses**
6|Code|A|20|-|Kürzel für Leistungsprofile
7|Name|A|100|-|Bezeichnung
8|Configuration|S|-|-|Mögliche Werte:<br/>0 = Grade<br/>1 = Report<br/>2 = Grade and Report<br/>3 = ComplexReport
9|GradeSystem|I|-|V|Verweis auf Tabelle **GradeSystems**
10|GradeType|I|-|V|Verweis auf Tabelle **GradeTypes**
11|AssessmentProfile|I|-|V|Verweis auf Tabelle **AssessmentProfiles**
12|Description|A|300|-|Text
13|InternalCode|A|3|-|Interner Code <br/>Mögliche Werte:<br/>werden zukünftig noch festgelegt
