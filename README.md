# SQL-CLAUSES-AGGREGATE-FUNCTIONS

SQL is followed by a unique set of rules and guidelines called Syntax. This tutorial gives you a quick start with SQL by listing all the basic SQL Syntax.

All the SQL statements start with any of the keywords like SELECT, INSERT, UPDATE, DELETE, ALTER, DROP, CREATE, USE, SHOW and all the statements end with a semicolon (;).

The most important point to be noted here is that SQL is case insensitive, which means SELECT and select have same meaning in SQL statements. Whereas, MySQL makes difference in table names. So, if you are working with MySQL, then you need to give table names as they exist in the database.

Various Syntax in SQL

1• SQL CREATE TABLE Statement

CREATE TABLE table_name(

column1 datatype,

column2 datatype,

column3 datatype,

.....
columnN datatype,

PRIMARY KEY( one or more columns )

);


2• SQL DROP TABLE Statement

DROP TABLE table_name;


3• SQL CREATE INDEX Statement

CREATE UNIQUE INDEX index_name

ON table_name ( column1, column2,...columnN);


4• SQL DROP INDEX Statement

ALTER TABLE table_name

DROP INDEX index_name;


5• SQL INSERT INTO Statement

INSERT INTO table_name( column1, column2....columnN)

VALUES ( value1, value2....valueN);


6• SQL UPDATE Statement

UPDATE table_name

SET column1 = value1, column2 = value2....columnN=valueN

[ WHERE  CONDITION ];


7• SQL DELETE Statement

DELETE FROM table_name

WHERE  {CONDITION};


8• SQL DESC Statement

DESC table_name;


9• SQL TRUNCATE TABLE Statement

TRUNCATE TABLE table_name;


10• SQL ALTER TABLE Statement

ALTER TABLE table_name {ADD|DROP|MODIFY} column_name {data_ype};


11• SQL ALTER TABLE Statement (Rename)

ALTER TABLE table_name RENAME TO new_table_name;


12• SQL SELECT Statement

SELECT column1, column2....columnN

FROM   table_name;


13• SQL DISTINCT Clause

SELECT DISTINCT column1, column2....columnN

FROM   table_name;


14• SQL WHERE Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  CONDITION;


15• SQL AND/OR Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  CONDITION-1 {AND|OR} CONDITION-2;


16• SQL IN Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  column_name IN (val-1, val-2,...val-N);


17• SQL BETWEEN Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  column_name BETWEEN val-1 AND val-2;


18• SQL LIKE Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  column_name LIKE { PATTERN };


19• SQL ORDER BY Clause

SELECT column1, column2....columnN

FROM   table_name

WHERE  CONDITION

ORDER BY column_name {ASC|DESC};


20• SQL GROUP BY Clause

SELECT SUM(column_name)

FROM   table_name

WHERE  CONDITION

GROUP BY column_name;


21• SQL COUNT Clause

SELECT COUNT(column_name)

FROM   table_name

WHERE  CONDITION;


22• SQL HAVING Clause

SELECT SUM(column_name)

FROM   table_name

WHERE  CONDITION

GROUP BY column_name

HAVING (arithematic function condition);


23• SQL USE Statement

USE database_name;


24• SQL COMMIT Statement

COMMIT;


25• SQL ROLLBACK Statement

ROLLBACK;

