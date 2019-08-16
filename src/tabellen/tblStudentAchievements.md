#        Tabelle tblStudentAchievements


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|StudentTerm|I|-|V|Verweis auf Tabelle **SchuelerZeitraeume**
5|AchievementProfile|I|-|V|Verweis auf Tabelle **AchievementProfiles**
6|Grade|I|-|V|Verweis auf Tabelle **GradesEntry**
7|GradeFactor|N|-|-|-
8|Report|M|-|-|Text
9|Position|I|-|V|Verweis auf Tabelle **AssessmentProfiles**
