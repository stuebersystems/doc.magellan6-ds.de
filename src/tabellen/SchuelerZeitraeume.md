#        Tabelle SchuelerZeitraeume

Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|-|Eindeutige ID
3|Schueler|I|-|PV|Verweis auf Tabelle **Schueler**
4|Klasse|I|-|PV|Verweis auf Tabelle **Klassen**
5|Zeitraum|I|-|PV|Verweis auf Tabelle **Zeitraeume**
6|Gewechselt|A|1|-|Mögliche Werte:<br/>N = Hat (noch) nicht gewechselt<br/>J = Hat innerhalb des Zeitraums gewechselt<br/>+ = Hat in den nächsten Zeitraum gewechselt
7|Ausbildungsjahr|S|-|-|-
8|Schulbesuchsjahr|S|-|-|-
9|Fachkombination|A|4|-|-
10|TeilnahmeZusatzangebot|L|-|-|-
11|SportBefreit|L|-|-|-
12|Unterrichtstage|S|-|-|-
13|Fehltage|S|-|-|-
14|FehltageU|S|-|-|-
15|Fehlstunden|N|-|-|-
16|FehlstundenU|N|-|-|-
17|Versaeumnisse|S|-|-|-
18|Verhalten|I|-|V|Verweis auf Tabelle **Noten**
19|Mitarbeit|I|-|V|Verweis auf Tabelle **Noten**
20|ZeugniskonferenzAm|D|-|-|-
21|ZeugnisausgabeAm|D|-|-|-
22|Zeugnisausgabe2Am|D|-|-|-
23|Tutor|I|-|V|Verweis auf Ansicht **Lehrer**
24|Pruefungsvorsitz|I|-|V|Verweis auf Ansicht **Lehrer**
25|Verordnung|A|10|V|Verweis auf Tabelle **Verordnungen**
26|Anrechnungsdatum|D|-|-|-
27|Status|S|-|-|Mögliche Werte:<br/>0 = Abschluss berechnen<br/>1 = Abschluss erreicht<br/>2 = Abschluss nicht erreicht
28|Meldungen|M|-|-|-
29|Log_Datum|D|-|-|-
30|Log_Uhrzeit|T|-|-|-
31|Log_Benutzer|A|20|-|-
32|Ausbildung|I|-|-|-
33|Zwischenzeugnis|L|-|-|-
34|Leistungsanforderungen|L|-|-|-
35|Jahrgang|I|-|-|-
