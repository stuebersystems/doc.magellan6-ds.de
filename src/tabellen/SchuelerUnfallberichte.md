# Tabelle SchuelerUnfallberichte


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|Schueler|I|-|V|Verweis auf Tabelle **Schueler**
4|Empfaenger|I|-|V|Verweis auf Tabelle **Adressen**
5|Toedlich|A|1|-|Mögliche Werte:<br/>N = Nein<br/>J  = Ja
6|UnfallDatum|D|-|-|-
7|UnfallZeit|T|-|-|-
8|UnfallOrt|M|-|-|-
9|UnfallHergang|M|-|-|-
10|SchilderungVersicherter|A|1|-|Mögliche Werte:<br/>N = Nein, andere Person<br/>J  = Ja, Versicherter
11|VerletzteKoerperteile|M|-|-|-
12|Verletzungsart|M|-|-|-
13|UnterbrechungBesuch|A|1|-|Mögliche Werte:<br/>N = Nein<br/>J  = Sofort<br/>S = Später
14|UnterbrechungBesuchAm|D|-|-|Wenn Feld UnterbrechungBesuch=S, dann ist hier das Datum eingetragen
15|UnterbrechungBesuchStunde|S|-|-|Wenn Feld UnterbrechungBesuch=S, dann ist hier die Stunde eingetragen
16|WiederaufnahmeBesuch|A|1|-|Mögliche Werte:<br/>N = Nein<br/>J  = Ja
17|WiederaufnahmeBesuchAm|D|-|-|Wenn Feld WiederaufnahmeBesuch=J, dann ist hier das Datum eingetragen
18|Zeuge|M|-|-|-
19|Augenzeuge|A|1|-|Mögliche Werte:<br/>N = Nein<br/>J  = Ja
20|Behandlung|M|-|-|Name behandelnder Arzt/Krankenhaus
21|BehandlungUhrzeitVon|T|-|-|-
22|BehandlungUhrzeitBis|T|-|-|-
23|Datum|D|-|-|Datum des Unfallberichts
24|Leiter|A|300|-|Leiter (Beauftragter) der Einrichtung
25|Telefon|A|30|-|Rufnummer für Rückfragen
