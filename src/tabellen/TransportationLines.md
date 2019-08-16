#        Tabelle TransportationLines


Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|InboundRoute|I|-|V|Verweis auf Tabelle **TransportationRoutes**
5|OutboundRoute|I|-|V|Verweis auf Tabelle **TransportationRoutes**
6|Operator|I|-|V|Verweis auf Tabelle **Adressen**
7|Code|A|20|-|-
8|Name|A|100|-|-
