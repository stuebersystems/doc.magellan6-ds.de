#		Die Datenbank

Dieses Dokument richtet sich hauptsächlich an Administratoren und erfahrene Benutzer, die einen Überblick über die Datenbankstruktur von Magellan bekommen möchten.
In folgenden Situationen können diese Informationen hilfreich sein:
*	Sie möchten Berichte mit Crystal Reports erstellen.
*	Sie möchten Abfragen, Berichte oder Formulare in Microsoft Access erstellen.
*	Sie möchten Daten aus einem anderen Verwaltungsprogramm importieren.
*	Sie möchten SQL-Abfragen über der Datenbank erstellen, vor allem im Zusammenhang mit der Magellan Scripting-Technologie.
*	Sie möchten einen detaillierten Überblick darüber haben, welche Daten wo und wie in Magellan gespeichert werden.
Bitte beachten Sie, dass die in diesen Unterlagen enthaltenen Angaben und Daten ohne vorherige Ankündigung geändert werden können.

Die Datengrundlage von MAGELLAN in der Version 6 ist eine Firebird-Datenbank. Firebird ist eine relationale Client/Server-Datenbank, auf die Sie unter anderem per ODBC direkt zugreifen können. Der standardmäßige Dateiname der Datenbank lautet Magellan6.fdb
Der einfachste Weg eine externe Verbindung zur Magellan-Datenbank aufzubauen, ist eine ODBC-Verbindung mit MS-Access einzurichten.
Gehen Sie dabei wie folgt vor:
1.	Starten Sie MS-Access und legen Sie eine neue, leere Datenbankdatei an.
2.	Klicken Sie im Menü „Datei“ auf „Externe Daten“ und dann auf „Tabellen verknüpfen“. Es erscheint das Dialogfenster „Verknüpfen“.
3.	Wählen Sie unter „Dateityp“ den Eintrag „ODBC“ aus. Es erscheint das Dialogfenster „Datenquelle auswählen“.
4.	Wählen Sie die Registerkarte „Computerdatenquelle“ und klicken Sie dort auf „Neu“.
5.	Wählen Sie die Option „Benutzerdatenquelle“ und klicken Sie auf „Weiter“ 
6.	Wählen Sie den Eintrag „Easysoft IB6 ODBC“ aus und klicken Sie auf „Weiter“. 
7.	Klicken Sie auf „Fertigstellen“.
8.	Tragen Sie nun die geforderten Parameter ein. Die wichtigsten Parameter sind „Database“ (=Dateipfad zur Datenbankdatei), „Dialect“ (=3) und „Character Set“ (=WIN1251). Je nach Anwendung sollten Sie auch „User Name“ und „Password“ definieren. Wenn Sie keine Änderungen an der Daten vornehmen wollen, können Sie auch die Option „Read Only“ ankreuzen.
9.	Bestätigen Sie mit OK.
10.	Wählen Sie nun die neu erzeugte Datenquelle aus und bestätigen Sie mit OK.
11.	Wenn alles richtig eingestellt wurde, bekommen Sie alle Tabellen und Ansichten der aktuellen Magellan-Datenbank angezeigt. Sie können jetzt alle oder auch nur einen Teil der angebotenen Objekte markieren und eine dauerhafte Verknüpfung einrichten.
Auch Crystal Reports greift über ODBC auf die MAGELLAN-Datenbank zu. Die dafür benötigte Datenquelle wird von Magellan automatisch eingerichtet.

