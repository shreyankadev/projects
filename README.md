Project README

Introduction
This project aims to read and process data from CSV files (Artikel.csv, Kunden.csv, Auftraege.csv) and store it in a data storage system. Additionally, it generates reports at specified times and saves them to specified directories.

Features
- Reads data from CSV files (Artikel.csv, Kunden.csv, Auftraege.csv).
- Stores data in a data storage system.
- Generates reports at specified times.
- Saves reports to specified directories.
- Supports both single

Setup Instructions
1. Copy the repository to your local machine.
2. Ensure you have Java and Maven installed.
3. Configure the project properties and settings in the application.properties file.
4. Run the application using Maven in cmd
mvn spring-boot:run
5.You can also import the file as Maven project in eclipse and run

Configuration
- Data Files: Place the data files (Artikel.csv, Kunden.csv, Auftraege.csv) in the specified directory.
- Report Generation: Configure the time and directory for report generation in the application.properties file.
- Data Storage: Configure the data storage file directory in the application.properties file.

Usage
- Ensure that the data files (Artikel.csv, Kunden.csv, Auftraege.csv) are present in the specified directory.
- (csv.file.item = full path to item file
  csv.file.customer = path to customer file
  csv.file.order= full path to order)
- The application will automatically read the data files, process them, and generate reports at the specified times.
  (#Time of report generation
  scheduled.time.cron=0 50 11 * * *)
  if you want to process files at 12.30 please specify as =0 30 12 * * *

Contributors
Shreyanka Ramesh Hirandagi
