# R2DBC: datasources creation from Spring Boot config properties

Databases currently supported by Spring Data R2DBC:
* PostGres, 
* MSSQL, 
* MySQL, 
* MariaDB, 
* Oracle, 
* H2


Problems (see the `application.properties` file)

* if URL has the ending slash, database name is not used - [IDEA-333406](https://youtrack.jetbrains.com/issue/IDEA-333406)
*  URL part after "_" or "-" is truncated - [IDEA-333876](https://youtrack.jetbrains.com/issue/IDEA-333876)
* incorrect results for H2 database - [IDEA-333409](https://youtrack.jetbrains.com/issue/IDEA-333409)
* user/password in url are ignored - [IDEA-333877](https://youtrack.jetbrains.com/issue/IDEA-333877)
* no gutter for MSSQL - [IDEA-333879](https://youtrack.jetbrains.com/issue/IDEA-333879)
* incorrect results for Oracle - [IDEA-333881](https://youtrack.jetbrains.com/issue/IDEA-333881)
