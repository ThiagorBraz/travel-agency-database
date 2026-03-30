# Travel Agency Database

SQL Server database schema for a travel agency management system, 
developed as part of the 1st Semester Information Systems module 
at Atlantic Technological University (ATU), Sligo, Ireland.

## About the Project

Relational database designed to manage tour operations for a 
travel agency, including tours, tour instances, pricing and 
tour guides. The schema includes tables, views and relationships 
built following relational database design principles.

## Database Structure

### Tables
- **Tour** — tour name, description and duration
- **TourInstance** — specific tour occurrences with date and guide
- **TourPrice** — pricing by tour timing and age group
- **Guide** — tour guide name and contact details

### Views
- **vTourDetails** — tour summary with instance count
- **vUpcomingTours** — upcoming tours with price and guide details

## Technologies Used

- SQL Server Express
- T-SQL (Transact-SQL)

## How to Use

1. Open SQL Server Management Studio (SSMS)
2. Run the script `Script_Database_-_Thiago_Braz.sql`
3. The database `TravelAgency` will be created automatically 
   with all tables and views

## Academic Context

Developed at Atlantic Technological University (ATU), Sligo — 
Higher Diploma in Computer Science, 1st Semester, Information Systems 
Module.
