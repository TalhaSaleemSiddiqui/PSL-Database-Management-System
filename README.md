# PSL-Database-Management-System
A relational database management system designed and implemented for the Pakistan Super League (PSL) using MySQL. The project models teams, players, matches, stadiums, umpires, sponsors, injuries, awards, ticket sales, rankings, and player match statistics.
The project includes a complete Entity Relationship Diagram (ERD) and realistic sample data to demonstrate relational database concepts and SQL operations.
📌 Project Overview
This DBMS captures the operational data of a PSL season, including:
•	Stadium and team information
•	Player and team management
•	Match scheduling and officials
•	Match results and performance
•	Playing XI information
•	Player batting and bowling statistics
•	Team rankings and points
•	Sponsorship information
•	Player injury records
•	Player awards
•	Match ticket sales
This project was built to practice and demonstrate:
•	Relational database design
•	Entity-Relationship modeling
•	Primary and foreign key relationships
•	Multiple-table relationships
•	Database normalization concepts
•	Realistic sample data population
•	SQL queries and data retrieval
🗂️ Database Schema
The database PSL_15 consists of 13 tables:
Table	Description
Stadium	Stadium details including name, location, and capacity
Team	PSL franchise team information
Player	Player details including team, role, nationality, age, and captaincy status
Umpire	Match official information
MatchSchedule	Match fixtures including date, stadium, teams, and umpires
MatchDetails	Match results including toss, winner, scores, win margin, and player of the match
Playing11	Playing XI for each match, including captain and wicketkeeper status
PlayerMatchStats	Per-match player batting and bowling statistics
TeamRanking	Team standings including matches played, won, lost, and points
Sponsor	Team sponsorship information
InjuryReport	Player injury records and injury dates
Award	Awards received by players
Ticket	Match ticket information including ticket type, price, area, and buyer name
🔗 Entity Relationship Diagram
The ERD represents the relationships between all 13 tables, including primary keys, foreign keys, and relationships between teams, players, matches, stadiums, umpires, and other entities.
⚙️ Tech Stack
•	Database: MySQL 8.0+
•	ER Diagram: MySQL Workbench
•	SQL: MySQL
🚀 Getting Started
Prerequisites
•	MySQL Server 8.0 or later
•	MySQL Workbench, DBeaver, or MySQL CLI

Installation
1. Clone the repository.
2. Open the `PSL.sql` file in MySQL Workbench or another MySQL client.
3. Execute the SQL script.
4. The `PSL_15` database, tables, and sample data will be created.
5. Run the included SQL queries to explore the database.
   
📊 Database Relationships
The main relationships include:
•	A Team has multiple Players
•	A MatchSchedule is associated with a Stadium
•	A MatchSchedule has two participating Teams
•	A MatchSchedule has two Umpires
•	A MatchDetails record belongs to a scheduled match
•	Playing11 connects matches, teams, and players
•	PlayerMatchStats stores player performance for each match
•	TeamRanking connects teams with match-wise rankings
•	A Sponsor is associated with a team
•	An InjuryReport belongs to a player
•	An Award is associated with a player
•	A Ticket belongs to a scheduled match
📁 Project Structure
PSL-Database-Management-System/
│
├── PSL.sql
├── ERD.png
└── README.md
🎯 Project Objectives
The main objectives of this project are to:
•	Design a relational database for a cricket league
•	Implement primary and foreign key constraints
•	Model real-world PSL entities and their relationships
•	Store and manage realistic cricket data
•	Demonstrate database querying and relational data management
•	Visualize the database structure through an ERD
👨‍💻 Academic Project Spring 2025
PSL Database Management System
Developed as a database management system project using MySQL.

