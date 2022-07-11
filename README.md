# About

This repository is the R markdown source for the article [Code Examples for DBI and RPostgres](https://shena4746.github.io/code-examples-dbi-rpostgres/).
Assuming you are using DBI with Postgres, it provides a brief overview of each DBI function and various code examples that illustrates how it is typically used and how it behaves.

It is also intended to document minor tips that are not as well-documented as DBI official references. One important example is the actual behaviour of DBI functions.
As implied in [DBI specification](https://dbi.r-dbi.org/articles/spec), the behaviour of DBI functions, which depends on the R/DBMS implementation, may sometimes be slightly different from the behaviour expected from the DBI documentation.
In such cases, the user is required to learn where the gaps exist and how they are different, typically through ad-hoc experimentation. This is exactly where this article grows out of. Consequently, the content tends to focus on tricky aspects at times. If you would like a more balanced explanation, then the official DBI references should still be your first choice.

## TOC

- About DBI and RPostgres
  - List of functions
  - Basic usage
- Functions in DBI and RPostgres
  - Connecting and disconnecting
  - Manipulating tables
  - Queries and statements
  - SQL
- References

## References

Overview

- [巨大なデータがSQLサーバーにあるときに、Rでどう立ち向かうかマニュアル：dbplyrパッケージを中心として](https://yutatoyama.github.io/note/intro_R_for_SQL.html)
- [Introduction to dbplyr](https://dbplyr.tidyverse.org/articles/dbplyr.html)
- [R: Working with Databases](https://nuitrcs.github.io/databases_workshop/r/r_databases.html)
- [Introduction to DBI](https://dbi.r-dbi.org/articles/dbi)

DBI

- [RSQLite & DBIの使い方](http://delta0726.web.fc2.com/packages/database/00_RSQLite.html)
- [DBI Reference](https://dbi.r-dbi.org/reference/)
- [DBI specification](https://dbi.r-dbi.org/articles/spec)
- [User-defined functions that DBI + RPostgres users should have](https://shena4746.github.io/r-functions-on-dbi/)
- [DBI: R Database Interface .pdf](https://cran.r-project.org/web/packages/DBI/DBI.pdf)

RPostgres

- [RPostgres - Reference](https://rpostgres.r-dbi.org/reference/index.html)
