# View StudentAchievements

Grundlage sind die Tabellen:

* [tblStudentAchievements](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblStudentAchievements.html)
* [AchievementsProfiles](https://doc.magellan6-datenstruktur.stueber.de/tabellen/AchievementProfiles.html)
* [GradeTypes](https://doc.magellan6-datenstruktur.stueber.de/schlusseltabellen-schlusselverzeichnisse/GradeTypes.html)
* [AssessmentProfiles](https://doc.magellan6-datenstruktur.stueber.de/tabellen/AssessmentProfiles.html)
* [tblCourses](https://doc.magellan6-datenstruktur.stueber.de/tabellen/tblCourses.html)
* [Faecher](https://doc.magellan6-datenstruktur.stueber.de/schlusseltabellen-schlusselverzeichnisse/faecher.html)

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|-|-
2|ID|I|-|-|-
3|EnbreaID|A|24|-|-
4|StudentTerm|I|-|-|-
5|AchievementProfile|I|-|-|-
6|ProfileCode|A|20|-|-
7|ProfileName|A|100|-|-
8|Course|I|-|-|-
9|CourseCode|A|10|-|-
10|CourseName|A|200|-|-
11|CourseDisplayName|A|-|-|-
12|Configuration|S|-|-|-
13|GradeType|I|-|-|-
14|GradeTypeCode|A|20|-|-
15|GradeTypeName|A|100|-|-
16|AssessmentProfile|I|-|-|-
17|ASPCode|A|20|-|-
18|ASPName|A|100|-|-
19|GradeSystem|I|-|-|-
20|Grade|I|-|-|-
21|GradeFactor|N|-|-|-
22|Report|M|-|-|-
23|Position|S|-|-|-
