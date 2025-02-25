# Olympic_history_sql_project

This repository contains SQL queries used to analyze historical Olympic data. The project involves querying two datasets: `athlete_events` and `athletes` to uncover interesting insights about Olympic performances, medals, and athletes.

# Project Overview

The goal of this project is to practice advanced SQL skills, including:
- Joins
- Common Table Expressions (CTEs)
- Temporary Tables
- Aggregate Functions
- Sub-queries
- Window Functions (`RANK()`, `LEAD()`, `LAG()`)

Each query answers a specific question related to Olympic history, providing valuable insights into athletes' achievements over the years.

# Dataset Description

- **athlete_events:** Contains information about athletes, events, and medals across different Olympic Games.
- **athletes:** Provides details about individual athletes, including their names, teams, and IDs.

# SQL Queries and Insights

Here are the key questions answered by the queries in this project:

1. **Which team has won the maximum gold medals over the years?**  
2. **For each team, what is the total number of silver medals and the year they won the most?**  
3. **Which player has won the most gold medals, provided they never won silver or bronze?**  
4. **In each year, which player won the most gold medals? In case of a tie, print all names.**  
5. **In which event and year did India win its first gold, silver, and bronze medal?**  
6. **Which players have won gold medals in both the Summer and Winter Olympics?**  
7. **Which players won gold, silver, and bronze medals in a single Olympics?**  
8. **Which players have won gold medals in three consecutive Summer Olympics (2000 onwards) for the same event?**

# Key Learnings

- Efficient use of `JOIN` operations to combine datasets.
- Using `CTEs` and `Window Functions` for complex aggregations.
- Applying conditional aggregations using `CASE` statements.
- Managing data ranking with `RANK()` and identifying trends with `LEAD()` and `LAG()`.

# Running the Queries

1. Ensure you have access to an SQL environment (e.g., SQL Server, MySQL).
2. Import the `athlete_events` and `athletes` datasets into your database.
3. Run the queries provided in `olympic_history.sql`.


