# Netflix_Dashboard
PowerBI Dashboard for Netflix Dataset 

### Sticky note
Connecting to MYSQL Workbench in some systems would require a separate Connector 
- Verify specs of PowerBI app in File<<About section
- For 64bit , download connector from following url : https://dev.mysql.com/downloads/connector/odbc/5.0.html
- Finish installation and ensure you select Complete instead of typical in configuration steps of Connector
- If connection still fails with MYSQL database, open ODBC Data Source (64-bit)
- Go to the System DSN tab and click Add....
- From the list, select MySQL ODBC X.XX Unicode Driver and click Finish

Configure the Connection
- In the setup window, fill in the following with your own details:
- Data Source Name (DSN): MySQL_Local (or any name you prefer).
- TCP/IP Server: localhost (or 127.0.0.1).
- User / Password: Your MySQL username and password.
- Database: Select your database from the dropdown.
- Click Test to ensure everything works, then click OK to save the DSN.

Connect in Power BI
- In Power BI Desktop, go to Get Data -> Other -> ODBC and select Connect.
- From the Data source name (DSN) dropdown, choose the DSN you just created (e.g., MySQL_Local).
- A dialog may appear—leave it as is and click Connect. Power BI will prompt you for credentials. Since they're stored in the DSN, you can often just click Connect again.
- The Navigator should now display your database and tables, ready for you to load your data.
