# create database studentdb
```SQL
CREATE DATABASE studentdb;
USE studentdb;
```
# create table tblstudent

## columns are
1.studentId  datatyepe integer , make it as primary key and it shiuld be auto incremented,
2.studentName datatyepe varchar, range 64
3.dob datatyp date,
4. address datatyp varchar range 64
```SQL
CREATE TABLE tblstudent
    ( studentId INTEGER PRIMARY KEY AUTO_INCREMENT,
      studentName VARCHAR(64),
      dob DATE,
      address VARCHAR(64));
```
## Add atlead three entries (3 rows) into the table
```SQL
INSERT INTO tblstudent (studentName, dob, address) VALUES
    ("John Doe", "1995-05-15", "New York str. xyz"),
    ("John Smith", "1990-04-23", "Los Angeles str. xyw"),
    ("Jane Dilan", "1991-06-07", "Mississipi str. zty");
```
