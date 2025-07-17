# SQL Practice Project – Olympic Tokyo 2021 Dataset

This repository contains my practice exercises from a structured SQL learning path.  
The project includes both lesson-based query tasks and practical exercises using real-world data.

##  Lesson Topics Covered

- Insert data into tables
- Select and retrieve data
- Filter results with WHERE clauses
- Update existing data
- Delete records
- Use of aggregate functions (SUM, COUNT, AVG, etc.)
- Grouping data with `GROUP BY`


###  Dataset Description:
The dataset contains records of **11,000 athletes**, with the following table structure:

| Column Name | Type | Description |
|---------------|---------------|-----------------|
| `name` | VARCHAR(255) | Athlete's name |
| `nationality` | VARCHAR(255) | Country name |
| `discipline` | VARCHAR(255) | Sport discipline|


###  Query Objectives:

1. **List of Iranian athletes**, ordered by name (where `nationality` = `Islamic Republic of Iran`)
2. **List of disciplines per country**, with participant count per discipline and country.  
   Output: `discipline`, `nationality`, `count` — ordered by `count` descending
3. **Country ranking** based on number of athletes (predicted final ranking).  
   Output: `nationality`, `count` — ordered by `count` descending



