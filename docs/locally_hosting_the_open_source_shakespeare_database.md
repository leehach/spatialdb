# Locally Hosting the Open Source Shakespeare Database

The tables in the `shakespeare` schema come from [Open Source Shakespeare](https://www.opensourceshakespeare.org/). I have created a SQL script which will duplicate this data in your locally hosted database. Download the file `shakespeare_insert.sql` from Canvas. This file will in one transaction create a schema names `shakespeare`, create tables to hold the data, and populated those new tables with data.

In order to upload the data:

1. Launch DBeaver.
2. Connect to the `universe` database on `localhost`.
3. Open a new SQL Editor.
4. From the SQL Editor menu, select Import SQL Script and open `shakepeare_insert.sql`.
5. Hit `Alt + X`, or from the SQL Editor menu select Execute SQL Script. You may get a warning message asking you to suppress display while the script runs. You can choose to do so. The entire script will run in 10-20 minutes.
