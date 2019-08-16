# Tabelle AssessmentEntries (Bewertungseinträge)

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|Profile|I|-|V|Verweis auf Tabelle **AssessmentProfiles**
5|Group|I|-|V|Verweis auf Tabelle **AssessmentGroups**
6|Code|A|20|-|Kürzel für Bewertungseinträgen
7|Name|A|100|-|Bezeichnung
8|GradeSystem|I|-|V|Verweis auf Tabelle **GradeSystems**
9|Position|I|-|-|-
10|Description|A|300|-|Text
11|InternalCode|A|3|-|Interner Code<br/>Mögliche Werte:<br/>werden zukünftig noch festgelegt
