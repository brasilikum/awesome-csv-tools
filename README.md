# awesome-csv-tools
Awesome Tools for a Not-So-Awesome File Format

## Why?
Let's face it:

**CSV is not a great format**.
As [RFC 4180](https://tools.ietf.org/html/rfc4180#section-2) states:

> While there are various specifications and implementations for the
  CSV format (...), there is no formal
  specification in existence(...)
  
This leads to incompatibilities and many cases to handle in csv parsers.

**This list collects awesome tools to work with csv, if you still have to do so!**

## Tools

### X to CSV
- [in2csv](http://csvkit.readthedocs.io/en/1.0.2/scripts/in2csv.html) - Converts various tabular data formats into CSV

### Database export to CSV
- [pgclimb](https://github.com/lukasmartinelli/pgclimb) - Export data from PostgreSQL into different data formats
- [sql2csv](http://csvkit.readthedocs.io/en/1.0.2/scripts/sql2csv.html) - Executes arbitrary commands against a SQL database and outputs the results as a CSV

### Database import from CSV
- [pgfutter](https://github.com/lukasmartinelli/pgfutter) - Import CSV and JSON into PostgreSQL the easy way
- [pgloader](https://github.com/dimitri/pgloader) - Provides advanced options for importing files ([including CSV](http://pgloader.io/howto/quickstart.html)) into PostgresSQL

