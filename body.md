\pagebreak

# Installierte Versionen von MS-SQL-Server?

MS-SQL Server 2012

# Aktuelle Versionen von MS-SQL-Server?

- MS-SQL 2014
	- Express
	- Web
	- Developer
	- Standard
	- Business Intelligence
	- Enterprise
- MS-SQL 2016 (Prerelease)

# Komponenten von MS-SQL-Server

- Database-Core
- Analysis Service
- Reporting Service
- Integration Service
- Master Data Service

# Welche Hardwarevoraussetzungen benötigt man am Server und an den Clients?

## Server

- $\ge$ 6GB HDD Speicher
- DVD Laufwerk (bei DVD installation)
- Monitor
	- Super-VGA ($\ge$ 800x600)
- Internet
- RAM
	- Express: 512 MB
	- Andere: 1GB
- Prozessor
	- Geschwindigkeit
		- x86: 1.0 GHz
		- x86\_64: 1.4 GHz
	- Typ
		- x86: Pentium III-compatible processor or faster
		- x86\_64: AMD Opteron, AMD Athlon 64, Intel Xeon with Intel EM64T
			support, Intel Pentium IV with EM64T support


# Welche Softwarevoraussetzungen benötigt am Server und an den Clients?

## Server

- NTFS (empfohlen)
- read-write Datei system
- .NET 3.5 SP1
- Windows Powershell
- Network Software
- Internet Software ($\ge$ IE7)
- 

# Wie kann man den MS-SQL Server in der Cloud verwenden?

Je nachdem was Sie mit dieser äußerst ungenauen Fragestellung gemeint haben gibt
es hier andere Möglichkeiten.

## IaaS

Mieten Sie Server bei z.B. [Scaleway](http://scaleway.com) oder Amazon,
verwalten Sie diesen und setzen Sie MS-SQL darauf auf.

## PaaS

Bei PaaS müssen Sie sich nur mehr um den MS-SQL-Server kümmern.

## SaaS

Hierbei müssen Sie nur mehr auf den Service zugreifen und alles wird von den
freundlichen Leuten erledigt denen Sie Ihre Kreditkartendaten anvertraut haben.

## Server in der "echten" Cloud

Dazu müssen Sie einen sehr sehr hohen Turm bauen und dort einen Server
betreiben, dann haben Sie einen Server in der **echten** Cloud.

## Server "verwenden"

Ich empfehle TCP/IP um die Verbindung herzustellen und schon können Sie
loslegen.

# Wie hoch sind etwa die Kosten für ca. 1000 User?

## Webapp

Sollten Sie eine Webapplikation hosten bei der 1000 Nutzer gleichzeitig
zugreifen würde vielleicht sogar MySQL reichen.

Da Sie allerdings auf MS-SQL bestehen empfehle ich die "Web"-Edition von MS-SQL.
Für diese sollten Sie vermutlich Ihren Hoster kontaktieren.

Sollten Sie auf das Selfhosting bestehen könnten Sie auch die Standardedition
wählen (\$3,717/Prozessorkern).

## Datenbank-Logins

Soll es 1000 verschiedene Logins (z.B. aus Sicherheitsgründen für eigene
Applikationen) geben würden Sie vermutlich mit der Standardedition zurechtkommen
können.

Sollte es etwas mehr sein würden die nächst teureren Versionen auch reichen.

## Developer/Datenbank-Programmierer

Bei 1000 Entwicklern die direkt auf die Datenbank zugreifen müssen werden Sie
wohl oder übel Microsoft für die passende Lizenzierung kontaktieren müssen, was
bei einer Anschaffung von mindestens \$28,512 für die Enterprise Edition wohl
sinnvoll wäre.

# Welche Konkurrenzprodukte gibt es? Wie liegen diese preislich?

## MySQL

Relationale Datenbank die Wert auf Geschwindigkeit und Einfachheit legt: gratis

## MongoDB

NoSQL Datenbank die Wert auf Geschwindigkeit und Einfachheit legt: gratis

## Oracle DB

Liegt sowohl von der Funktionalität als auch dem Preis in etwa bei MS-SQL.

# Welche Konkurrenzprodukte am Cloudmarkt gibt es? Wie liegen diese preislich?

## Oracle

## Google

Eine managed MySQL Datenbank kostet zwischen mehreren tausend Euro und ein paar
wenigen Cent, laut [Pricing
Calculator](https://cloud.google.com/products/calculator/#).

# Welche Datenbanken sind zurzeit die schnellsten DBs am Markt?

- MySQL
- Andere

# Was wird in MS-SQL 2016 neu?

- mehr Cloud
- Geschwindigkeit
- Cloud

# Suche ein Einführungsvideo zu MS-SQL-Server-Admin "Install and Configure SQL Server"  laut mündlicher  Angabe und erstelle drei Kontrollfragen (inkl Referenz und Antwort) aus dem Inhalt!

"[How to Install SQL Server 2014 Express and SQL Server Management Studio 2014
Express](https://www.youtube.com/watch?v=E_zFM7mzFUg)"


1. Von welcher Website wurde der SQL-Server heruntergeladen?
	- von der Herstellerseite ("microsoft.com")
2. Welche zwei Dateien mussten heruntergeladen werden?
	- die Datenbank (für die richtige Architektur)
	- das Management Tool
3. Was ist das Hauptfeature der Datenbank?
	- "Database Engine Services"

