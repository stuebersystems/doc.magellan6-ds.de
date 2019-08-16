# tblLehrerLehraemter


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle Mandanten
2|ID|I|-|P|-
3|Lehrer|I|-|V|Verweis auf Ansicht Lehrer
4|Lehramt|A|8|V|Verweis auf Tabelle Lehraemter
5|Typ|S|-|-|Mögliche Werte:<br/>0 = Standard<br/>1 = Lehrbefähigung<br/>2 = Unterrichtserlaubnisg<br/>3 = Unterrichtsauftrag<br/>4 =<br/>Unterrichtsbefugnis<br/>5 = Lehrbefähigung kleine Fakultas<br/>6 = Lehrbefähigung große Fakultas
6|Pruefungsbezug|A|8|PV|Verweis auf Tabelle LehrerPruefungsbezug
7|JahrgangVon|S|-|-|-
8|JahrgangBis|S|-|-|-
9|Bemerkung|A|300|-|-
	
