# NAP Database Export
This is a simple project aimed to fulfil the requirements for regulation N-18 in Bulgaria.

This regulation requires every software that manages sales which are paid in cash to supply an open source tool to extract information from the database.

The exact text states:

_3. за софтуери, които се инсталират в среда на клиента, се представят: пълно описание на обектите в базата данни (БД), свързани с управлението на продажбите, вкл. таблици и предназначението им, връзки между тях, описание на полетата в таблиците, както и изпълним файл и source-кодът, от който е генериран изпълнимият файл, за достъп и извличане на данни от БД в структуриран четим вид с възможност за избор - от всички или от част от таблиците, с които работи софтуерът;_

## What this tool does

This tool consists of a single screen which allows you to:

1. Connect to a local database or a server.
2. List all databases (if you are connecting to a server).
3. List all tables in the database.
4. Select which tables to extract information from or select all.
5. Choose a file format for extraction. (CSV semicolumn delimited / CSV comma delimited)
6. Save all the data from each selected table in a separate file.

## Technologies used

C#, Windows Forms and .NET 4.0

Connects to SQLite, MySQL, Microsoft SQL Server, Microsoft Access databases and declared ODBC Data Source Name (DSN). 
Depending on the Build Platform choosed an compilation time, is will use the 32-bit or 64-bit System Data Sources
More Database Providers can be added in the future.

## Other information

This project is a fork of https://github.com/flipm0de/NapDatabaseExport.
Many thanks to Vladimir Dimitrov (flipm0de).




