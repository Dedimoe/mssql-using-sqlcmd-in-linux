# mssql-using-sqlcmd-in-linux
Connect to SQL Server using sqlcmd on Linux

sqlcmd -S server_name,port -U User -P pwd -d DatabaseName -Q "query"

example :
```
sqlcmd -S 192.168.1.11,1433 -U User1 -P MyPassword -d MyDB -Q "SELECT TOP 5 Id FROM dbo.MyTable;"
```
