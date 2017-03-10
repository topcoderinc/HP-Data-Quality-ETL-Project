
###Delimited File Input Component:
```
File Path (String)
Encoding (ISO-8859-15, | UTF-8)
Row Separator (LF(ì\nî) | CR (ì\rî) | CRLF (ì\r\nî))
Field Separator (String)
Is CSV? (checkbox)
Escape Character (visible if is CSV is chosen) (String)
Text Enclosure (visible if is CSV is chosen) (String)
Header (Integer)
Footer (Integer)
Limit(Integer)
Trim Input? (checkbox)
```

###Delimited File Output Component:
```
File Name (String)
Row Separator  (String)
Field Separator  (String)
Append (checkbox/bool)
Include Header (checkbox/bool)
Compress as Zip File (checkbox/bool)
IsCSV file? (checkbox/bool)
CSV Escape Character   (String)
CSV Text Enclosure   (String)
Encoding  (ISO-8859-15, | UTF-8)
```

###Excel Input:
```
Excel Version (2007 - xlsx)
File Name (String)
Sheet Name (String)
Header (Int)
Footer (Int)
Limit(Int)
First Column (Int)
Last Column (Int)
Encoding  (ISO-8859-15, | UTF-8)
```

###Excel Output:
```
Excel Version (2007 - xlsx)
File Name (String)
Sheet Name (String)
Include Header (bool)
```

###Database Input
```
JDBC URL  (String)
Database Version (enumeration from Settings - pairs JAR Files and Database Types/Versions)
Class Name  (String)
Username (String)
Password (String)
Table Name (String)
Query  (String - Text Area)
```

###Database Output
```
JDBC URL (String)
Database Version (enumeration from Settings - pairs JAR Files and Database Types/Versions)
Class Name (String)
Username (String)
Password (String)
Table Name (String)
Action on Data Insert | Update | Insert or Update | Update or Insert | Delete
Clear Data in Table?  (Boolean)
Query  (String - Text Area)
```

###Vertica Input:
```
Version: (Vertica 7.0.X)
Host:  (String)
Port:  (String)
Database:  (String)
Schema: (String)
Username: (String)
Password: (Masked String)
Table: (String)
Query (String)
```

###Vertica Output:
```
Version: (Vertica 7.0.X)
Host:  (String)
Port:  (String)
Database:  (String)
Schema: (String)
Username: (String)
Password: (Masked String)
Table: (String)
Action on Table:  (Create Table if does not exist | Create Table | Drop and Create Table | Drop Table if exists and Create Table | Clear Table
Action on Data: Insert | Update | Insert or Update | Update or Insert | Delete
```
