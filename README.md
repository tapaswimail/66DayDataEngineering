# \#66DayDataEngineering

A personal learning streak — 33 tasks, 66 days, one habit loop.

\---

## What this is

This repo documents my structured journey to strengthen **Python and SQL skills for data engineering** — built around a two-day habit loop that prioritises understanding first, then memory-based reproduction.

Each task takes two days:

|Day|What I do|
|-|-|
|Day 1|Read the scenario → set up data and run the solution in Google Colab → understand, annotate, write it down|
|Day 2|Reproduce the solution from memory in a fresh Colab → post the learning on LinkedIn|

\---

## Curriculum at a glance

33 tasks across 11 chunks, grouped into three phases:

**Phase 1 — Foundations** (Chunks 1–4 · Days 1–24)

* Advanced aggregation and window functions
* Data cleaning, type casting, deduplication
* Reshaping, pivoting, and complex CTEs
* Strings, datetime handling, and file formats

**Phase 2 — Engineering** (Chunks 5–8 · Days 25–48)

* DuckDB, JSON parsing, and large file streaming
* ETL patterns and error handling
* Data quality validation and pytest
* Performance tuning and memory optimisation

**Phase 3 — Pipelines** (Chunks 9–11 · Days 49–66)

* Advanced SQL — recursive CTEs, as-of joins, retention metrics
* Incremental loads, SCD Type 2, API ingestion
* End-to-end capstone pipeline

\---

## Tasks
**Chunk-01-Advanced aggregation and window functions**
 * **Task 1 — Python · Days 1–2** - Scenario: You receive a sales DataFrame with 500 rows and columns rep_name, region, product, units_sold, revenue. Your manager asks for a single summary table showing — per region — the total revenue, the average units sold, the number of distinct reps, and the name of the top-earning rep.

   **Solution-** Date - 30 and 31 March 2026 - [task-01-groupby-agg](https://colab.research.google.com/drive/1HtQqUaGwuwqrPF2IlhmnCRXaLu30ptr2?usp=sharing)

 * **Task 2 — SQL · Days 3–4** - Scenario: An `orders` table holds e-commerce transactions. For each customer, you need: their total spend, their rank by total spend across all customers, their spend as a percentage of the highest spender, and the running cumulative revenue share percentage.
   
   **Solution-** Date - 1 and 2 April 2026 - [task-02-sql-cte](https://colab.research.google.com/drive/1HtQqUaGwuwqrPF2IlhmnCRXaLu30ptr2?usp=sharing)

 * **Task 3 — Python · Days 5–6** - Scenario: A DataFrame records daily sales per store across 12 months. We need to compute — for each store — a 7-𝐝𝐚𝐲 𝐫𝐨𝐥𝐥𝐢𝐧𝐠 𝐚𝐯𝐞𝐫𝐚𝐠𝐞 𝐫𝐞𝐯𝐞𝐧𝐮𝐞, the 𝐦𝐨𝐧𝐭𝐡-𝐨𝐯𝐞𝐫-𝐦𝐨𝐧𝐭𝐡 𝐩𝐞𝐫𝐜𝐞𝐧𝐭𝐚𝐠𝐞 𝐜𝐡𝐚𝐧𝐠𝐞, and a 𝐟𝐥𝐚𝐠 𝐟𝐨𝐫 𝐰𝐡𝐞𝐭𝐡𝐞𝐫 𝐚𝐧𝐲 𝐫𝐨𝐥𝐥𝐢𝐧𝐠 𝐚𝐯𝐞𝐫𝐚𝐠𝐞 𝐞𝐱𝐜𝐞𝐞𝐝𝐞𝐝 ₹100,000.
   
   **Solution-** Date - 3 to 5 April 2026 - [task-03-python](https://colab.research.google.com/drive/1KJ5sLtJIGBBYL3xjlJ0DgdDjbkYSTLBz?usp=sharing)

## Tools used

* Python 3.x · pandas · NumPy · pyarrow
* DuckDB · SQL
* Google Colab
* pytest

\---

## Progress tracker

|Chunk|Theme|Tasks|Status|
|-|-|-|-|
|1|Aggregation \& window functions|1–3|✅|
|2|Cleaning \& deduplication|4–6|⬜|
|3|Reshaping \& CTEs|7–9|⬜|
|4|Strings, datetime, file formats|10–12|⬜|
|5|DuckDB, JSON, large files|13–15|⬜|
|6|ETL patterns \& error handling|16–18|⬜|
|7|Data quality \& validation|19–21|⬜|
|8|Performance \& memory|22–24|⬜|
|9|Advanced SQL patterns|25–27|⬜|
|10|Pipeline patterns \& incremental loads|28–30|⬜|
|11|End-to-end capstone|31–33|⬜|

`⬜ not started` · `🟡 in progress` · `✅ done`

\---

## Follow along

I post daily updates on LinkedIn with the key insight from each task.
Hashtag: **#66DayDataEngineering**

\---

*Started: 30/03/2026 · Target completion: 66 days later*

