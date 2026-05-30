# Netflix_Dashboard
PowerBI Dashboard for Netflix Dataset 

###FYI
Connecting to MYSQL Workbench in some systems would require a separate Connector 
- Verify specs of PowerBI app in File<<About section
- For 64bit , download connector from following url : https://dev.mysql.com/downloads/connector/odbc/5.0.html
- Finish installation and ensure you select Complete instead of typical in configuration steps of Connector
- If connection still fails with MYSQL database, open ODBC Data Source (64-bit)
- Go to the System DSN tab and click Add....
- From the list, select MySQL ODBC X.XX Unicode Driver and click Finish

Configure the Connection
In the setup window, fill in the following with your own details:
Data Source Name (DSN): MySQL_Local (or any name you prefer).

TCP/IP Server: localhost (or 127.0.0.1).

Port: 3306 (unless you changed it).

User / Password: Your MySQL username and password.

Database: Select your database from the dropdown.

Click Test to ensure everything works, then click OK to save the DSN.
