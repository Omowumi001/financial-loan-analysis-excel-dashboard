# India 2024 General Election – SQL Analysis

## Overview
This project applies SQL to analyse the 2024 Indian General Election dataset, with a focus on understanding seat distribution, party and alliance performance, and constituency-level outcomes. The analysis combines multiple tables to explore election results at national, state, and constituency levels.

The project demonstrates practical SQL skills applied to a real-world political dataset, emphasising structured querying, aggregation, and analytical reasoning.

---

## Dataset
The dataset consists of multiple relational tables covering:
- Constituency-wise election results
- State-wise election data
- Party-wise results
- Alliance affiliations
- Parliamentary constituencies

These tables were joined and analysed to derive insights into seat allocation and election outcomes across India.

---

## Skills Demonstrated
- Writing structured SQL queries
- INNER JOINs across multiple related tables
- Aggregations using COUNT and SUM
- Conditional logic using CASE statements
- Grouping and summarisation of election data
- Analytical interpretation of real-world datasets

---

## Key Questions Addressed
- What is the total number of parliamentary seats in the Indian General Election?
- How many seats are available for election in each state?
- How are parliamentary seats distributed across different states?
- Which party holds the highest number of seats in each state?
- How many seats were won by major political alliances such as the NDA and the I.N.D.I.A alliance?
- Who were the winning candidates and runner-up candidates in each constituency?

---

## Analysis Highlights
- Calculated the total number of parliamentary seats contested in the election.
- Determined state-wise seat allocation through joins between constituency and state datasets.
- Identified the leading party in each state based on seat counts.
- Aggregated alliance-level results to evaluate national performance of major political coalitions.
- Extracted constituency-level outcomes, including winning and runner-up candidates.

---

## Files
- `india_2024_general_election_analysis.sql` – SQL file containing all queries used in the analysis  
- `total_seats.csv` – Total number of parliamentary seats  
- `seats_available_by_state.csv` – Number of seats available for election in each state  
- `top_party_by_state.csv` – Party with the highest number of seats in each state  
- `nda_alliance_seats.csv` – Seats won by NDA alliance parties  
- `india_alliance_seats.csv` – Seats won by I.N.D.I.A alliance parties  
- `winner_runnerup_by_constituency.csv` – Winning candidate and runner-up per constituency  

*(CSV files represent selected query outputs used to illustrate key analytical findings.)*




