<h3>Apache Sqoop</h3>
Commands and Code to move data from relational DBs into HDFS, Hive, HBase and similar Hadoop services.
<br>
<br><b>MySQL - Connect to MySQL and list all available tables</b>
<br>sqoop list-tables --connect jdbc:mysql://localhost:3306/database --username root --password pw
<br>
<br>sqoop import --connect jdbc:mysql://localhost:3306/database --username root --table mysql_table --hive-import --create-hive-table --hive-table hive_database.hive_table
<br>
<br>
<br><b>References:</b>
<br>
