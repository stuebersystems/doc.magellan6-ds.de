#       Tabelle tblStudentComplexReports


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|StudentAchievement|I|-|V|Verweis auf Tabelle **tblStudentAchievements**
5|Profile|I|-|V|Verweis auf Tabelle **AssessmentProfiles**
6|Group|I|-|V|Verweis auf Tabelle **AssessmentGroups**
7|Entry|I|-|V|Verweis auf Tabelle **AssesmentEntries**
8|Grade|I|-|V|Verweis auf Tabelle **GradeEntries**
9|Report|M|-|-|Beurteilung
