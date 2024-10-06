# Gothenburg Congestion Tax Documentation

## Overview
This documentation provides an overview of the Gothenburg Congestion Tax application, detailing its functionality, usage, and setup.

## Tax Calculation
The application calculates congestion tax based on specific rules:
- **Maximum Daily Fee:** 60 SEK
- **Applicable Hours:** Fees are charged only during certain hours.

## Tax Exemptions
Vehicles that are exempt from congestion tax include:
- Emergency vehicles
- Buses
- Diplomat vehicles
- Motorcycles
- Military vehicles
- Foreign vehicles

## How to Run the Application
1. Clone the repository.
2. Install the required .NET framework.
3. Set up the database connection (SQLite/SQL Server).
4. Run the application and input vehicle entry/exit times.

## Sample Input
| Entry Time             | Exit Time              |
|------------------------|------------------------|
| 2013-02-08 06:27:00    | 2013-02-08 07:15:00    |
| 2013-03-26 14:25:00    | 2013-03-26 15:05:00    |

## Contact
For questions or support, please reach out to Mansour Jouya at jouya.m@gmail.com.
