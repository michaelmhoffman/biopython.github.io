---
title: BioSQL/Windows
permalink: wiki/BioSQL/Windows
layout: wiki
---

These are Windows specific notes on installing
[BioSQL](BioSQL "wikilink")

### MySQL

Download and install MySQL 5.1 from
<http://dev.mysql.com/downloads/mysql/5.1.html#win32>

Download and install MySQLdb (the python interface) from
<http://sourceforge.net/projects/mysql-python>

Get the schema from
<http://cvs.open-bio.org/cgi-bin/viewcvs/viewcvs.cgi/biosql-schema/sql/biosqldb-mysql.sql?cvsroot=biosql>

Create a new database, and load the schema etc as described on
[BioSQL](BioSQL "wikilink")

`mysqladmin -u root create bioseqdb`  
`mysql -p -u root bioseqdb < biosqldb-mysql.sql`