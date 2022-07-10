# About

This repository is the R markdown source for the article [Code Examples for DBI and RPostgres](https://shena4746.github.io/code-examples-dbi-rpostgres/).
Assuming you are using DBI with Postgres, it provides a brief overview of each DBI function and various code examples that illustrates how it is typically used and how it behaves.

It is also intended to document minor tips that are not as well-documented as DBI official references. One important example is the actual behaviour of DBI functions.
As implied in [DBI: R Database Interface](https://cran.r-project.org/web/packages/DBI/index.html), the behaviour of DBI functions, which depends on the R/DBMS implementation, may sometimes be slightly different from the behaviour expected from the DBI documentation.
In such cases, the user is required to learn where the gaps exist and how they are different, typically through ad-hoc experimentation. This is exactly where this article grows out of. Consequently, the content tends to focus on tricky aspects at times. If you would like a more balanced explanation, then the official DBI references should still be your first choice.
