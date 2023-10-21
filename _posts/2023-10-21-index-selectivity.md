---
layout: post
title:  "Index Selectivity"
date: 2023-10-21
categories: mssql
---
# What selectivity is really means ?
- It's not about how unique each row is by itself.
- It's about your query, and how small a percentage of the table you're searching for.
- When evaluating column order for indexes, don't think about how unique each column is. Think about what percentage you're searching for.  
(from Brent Ozar - Fundamental Index Tuning)
