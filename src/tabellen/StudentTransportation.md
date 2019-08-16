#       Tabelle StudentTransportation



Nr.|Feldname|Typ|Größe|Funktion|Bemerkung
--|--|--|--|--|--
1|Mandant|I|-|PV|Verweis auf Tabelle **Mandanten**
2|ID|I+|-|P|-
3|EnbreaID|A|24|-|Externer Identifikator aus ENBREA
4|Student|I|-|V|Verweis auf Tabelle **Schueler**
5|InboundRoute|I|-|V|Verweis auf Tabelle **TransportationRoutes**
6|OutboundRoute|I|-|V|Verweis auf Tabelle **TransportationRoutes**
