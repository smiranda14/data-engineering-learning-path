# Advanced SQL

This section explores SQL techniques for complex analysis, readable queries, and reusable database logic. The focus is on understanding not only how a query works, but why one approach may be clearer or more efficient than another.

## Topics

- Common Table Expressions (CTEs) and recursive CTE concepts.
- Views and materialized views.
- Window functions: ROW_NUMBER, RANK, DENSE_RANK, LAG, LEAD.
- PARTITION BY and window frames.
- Set operations: UNION, UNION ALL, INTERSECT, EXCEPT.
- CASE expressions and conditional aggregation.
- Query readability, modularity, and execution plans (introductory).

## Practice Ideas

- Rank products by revenue within each category.
- Calculate month-over-month sales changes with LAG.
- Identify each customer's first and most recent order.
- Compare CTEs with nested subqueries.
- Create a view for high-value orders and query it.

## Free Learning & Practice

- [PostgreSQL Exercises](https://pgexercises.com/) — practice from basic queries through joins, aggregations, and window functions.
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/) — analytical SQL concepts and examples.
- [SQLZoo](https://sqlzoo.net/) — additional query challenges.
- [DataCamp SQL tutorials](https://www.datacamp.com/tutorial/category/sql) — free topic guides; interactive courses are freemium.
- [HackerRank SQL](https://www.hackerrank.com/domains/sql) — structured challenges.

## Suggested Deliverables

- `ctes.sql`
- `views.sql`
- `window-functions.sql`
- `set-operations.sql`
- `advanced-sql-challenges.md`

## Completion Checklist

- [ ] Build and explain a multi-step CTE.
- [ ] Create and query a view.
- [ ] Use ranking and offset window functions.
- [ ] Explain the difference between UNION and UNION ALL.
- [ ] Solve a business question using at least one window function.
