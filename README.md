
# Translink Data - Public Transport Database

This repository contains SQL scripts to create and manage a public transport database using data from [Queensland Government's General Transit Feed Specification (GTFS) - Translink](https://www.data.qld.gov.au/dataset/general-transit-feed-specification-gtfs-translink/resource/e43b6b9f-fc2b-4630-a7c9-86dd5483552b)

## Overview

This project provides a simple SQL-based database structure for storing and managing public transport data. The database consists of tables that store information on routes, trips, stops, schedules, and other transport-related data.

## Tables in the Database

- **routes**: Stores details about public transport routes.
- **calendar**: Contains service availability by day of the week.
- **trips**: Stores data about trips on the routes.
- **stops**: Information about various transport stops.
- **calendar_dates**: Contains exceptions like public holidays affecting services.
- **stop_times**: Arrival and departure times for stops within a trip.

## SQL Scripts

### Scripts Provided:
- **create_table.sql**: Defines the schema and structure of the database.
- **import_table.sql**: Used to import GTFS data into the database.

### Operations in the Scripts:
- Drop existing tables if they exist.
- Create new tables for routes, calendar, trips, stops, etc.
- Establish relationships between the tables (e.g., foreign keys).

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/AbishekThapa/Translink_Data.git
   ```

2. Run the SQL scripts in your SQL environment (e.g., MySQL, PostgreSQL):
   - **create_table.sql** to create the database schema.
   - **import_table.sql** to load data into the tables.

3. Modify or extend the database as needed for your project.

## Data Source

The data used in this project comes from [Queensland's General Transit Feed Specification (GTFS) - Translink dataset](https://www.data.qld.gov.au/dataset/general-transit-feed-specification-gtfs-translink/resource/e43b6b9f-fc2b-4630-a7c9-86dd5483552b).



