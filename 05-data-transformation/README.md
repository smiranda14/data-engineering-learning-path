# Data Transformation

This section explores how raw data is cleaned, standardized, combined, and prepared for reliable downstream use.

## Topics

- ETL (Extract, Transform, Load) and ELT (Extract, Load, Transform).
- Data cleaning and standardization.
- Type casting and date/time handling.
- Handling missing, duplicate, and inconsistent values.
- Business rules and derived fields.
- Incremental versus full-refresh transformations.
- Reusable transformations and staging layers.
- Introduction to dbt models and tests.

## Practice Ideas

- Clean a raw ecommerce product file.
- Standardize product categories and brand names.
- Convert text prices into numeric values and validate them.
- Build staging and transformed tables.
- Compare an ETL workflow with an ELT workflow.

## Free Learning & Practice

- [dbt Learn](https://learn.getdbt.com/) — free courses and hands-on analytics engineering lessons.
- [dbt Documentation](https://docs.getdbt.com/docs/introduction) — models, tests, sources, and transformations.
- [Kaggle Learn](https://www.kaggle.com/learn) — practise data preparation with real datasets.
- [freeCodeCamp](https://www.freecodecamp.org/learn/) — free programming and data learning paths.
- [DataCamp tutorials](https://www.datacamp.com/tutorial) — free written learning resources; interactive courses are freemium.

## Suggested Deliverables

- `raw-to-staging.sql`
- `staging-to-mart.sql`
- `transformation-rules.md`
- `dbt-models/`

## Completion Checklist

- [ ] Explain the difference between ETL and ELT.
- [ ] Build a repeatable transformation.
- [ ] Document assumptions and business rules.
- [ ] Validate transformed output.
- [ ] Separate raw, staging, and analytical data layers.
