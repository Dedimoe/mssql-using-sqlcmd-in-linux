# mssql-using-sqlcmd-in-linux
Connect to SQL Server using sqlcmd on Linux

sqlcmd -S 192.168.0.78,1433 -U User -P pwd -d DatabaseName -Q "SELECT TOP 5 Id FROM dbo.MyTable;"

