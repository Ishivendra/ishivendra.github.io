# SQOOP Session 1

SQOOP is used to import data from
  1.  RDBMS to HDFS, and
  2.  HDFS to RDBMS

@startuml
left to right direction

database RDBMS
node HDFS

RDBMS --> HDFS:Import
HDFS --> RDBMS:Export
@enduml

![Example UML](http://yuml.me/a3dcfa98.png)
