# Database Design

This section covers how to structure relational data so it is consistent, understandable, and reliable.

## Topics

- Relational database concepts: tables, rows, columns, and relationships.
- Primary keys and foreign keys.
- Unique, NOT NULL, CHECK, and DEFAULT constraints.
- Data types and choosing appropriate column definitions.
- Normalization: first, second, and third normal forms.
- Entity-relationship diagrams and cardinality.
- Index fundamentals and query considerations.
- Table partitioning and its use cases.

## Practice Ideas

- Design a small ecommerce schema with customers, products, orders, and order items.
- Identify primary and foreign keys.
- Add constraints to prevent invalid prices and missing identifiers.
- Normalize a flat order spreadsheet into related tables.
- Partition a table by a suitable date or category field and explain the decision.

## Free Learning & Practice

- [PostgreSQL Official Tutorial](https://www.postgresql.org/docs/current/tutorial.html) — relational database and SQL foundations.
- [PostgreSQL Documentation: Constraints](https://www.postgresql.org/docs/current/ddl-constraints.html) — keys and integrity rules.
- [PostgreSQL Documentation: Table Partitioning](https://www.postgresql.org/docs/current/ddl-partitioning.html) — partition concepts and syntax.
- [Khan Academy: Intro to SQL](https://www.khanacademy.org/computing/computer-programming/sql) — beginner-friendly database concepts.
- [DataCamp Database Design](https://www.datacamp.com/courses/database-design) — guided course content; availability may be limited by plan.

## Suggested Deliverables

- `ecommerce-erd.png`
- `create-tables.sql`
- `constraints.sql`
- `normalization-notes.md`
- `partitioning-example.sql`

## Completion Checklist

- [ ] Draw a simple entity-relationship diagram.
- [ ] Define primary and foreign keys.
- [ ] Apply constraints to protect data integrity.
- [ ] Explain why normalization is useful.
- [ ] Describe when partitioning can help.
