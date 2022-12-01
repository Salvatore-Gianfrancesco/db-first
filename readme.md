# Car dealer

## Table title: cars

### Table columns:
 - id | BIGINT | PK NOTNULL AUTO_INCREMENT
 - vin | CHAR(17) | NULL UNIQUE
 - auto_make | VARCHAR(100) | NOTNULL
 - auto_model | VARCHAR(100) | NULL
 - year | YEAR | NULL
 - color | CHAR(7) | NULL
 - price | SMALLINT | NULL
 - distance_travelled | MEDIUMINT | NULL
 - fuel_type | VARCHAR(100) | NULL
 - transmission | VARCHAR(100) | NULL
 - available | BOOL | NULL
 - home_delivery | BOOL | NULL
 - vote | FLOAT(2, 1) | DEFAULT(0)
 - reviews_number | MEDIUMINT | DEFAULT (0)