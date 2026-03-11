# parking-lot-investigation-sql

This project is a SQL-based crime investigation scenario where a parking lot database is analyzed to detect suspicious activity. The database contains information about people, their vehicles, parking logs, payment records, and statements given during a police investigation.

Using SQL queries such as JOIN, filtering, and comparisons, the project identifies inconsistencies between the parked car plates, payment records, and claimed vehicle details. These inconsistencies help reveal potential suspects involved in a parking fraud or heist.

The project demonstrates how relational databases and SQL queries can be used for data analysis and investigation, similar to real-world forensic data analysis.

📂 Database Tables

persons – Stores personal information and license numbers.

parking_log – Records vehicle entry and exit times in the parking lot.

payments – Tracks parking payments made by each person.

statements – Contains statements given by individuals during the investigation.

🔍 Investigation Objective

The goal of this analysis is to:

Track parking activity of all vehicles.

Compare parking logs with payment records.

Verify statements provided by individuals.

Detect mismatched car plates and suspicious behavior.

These queries help identify individuals whose payment records or statements do not match their actual parking data, indicating possible fraud or involvement in the parking heist.

🛠 Technologies Used

MySQL

SQL Queries (JOIN, WHERE, Filtering)

Relational Database Design
