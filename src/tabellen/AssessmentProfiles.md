# Tabelle AssessmentProfiles / Bewertungsprofile


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|Code|A|20|-|Kürzel für Bewertungsprofil
5|Name|A|100|-|Bezeichnung
6|Configuration|S|-|-|Mögliche Werte:<br/>0 = keine Bewertung<br/>1 = Grade (Note)<br/>2 = Report (Beurteilung)<br/>3 = Grade and Report (Note und Beurteilung)
7|GradeSystem|I|-|V|Verweis auf Tabelle **GradeSystems**
8|Description|A|300|-|Text
9|InternalCode|A|3|-|Interner Code<br/>Mögliche Werte:<br/>werden zukünftig noch festgelegt
