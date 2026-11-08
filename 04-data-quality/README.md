# Data Quality

This section focuses on identifying, measuring, and improving the quality of data before it is used for reporting, analytics, or downstream data pipelines.

## Core Dimensions

- **Completeness:** required values are present.
- **Uniqueness:** duplicate records are identified and handled.
- **Validity:** values follow expected formats and allowed ranges.
- **Consistency:** related fields and tables do not contradict each other.
- **Accuracy:** values reflect the intended real-world information.
- **Timeliness:** data is available and updated when expected.

## Topics

- NULL and missing-value analysis.
- Duplicate detection with GROUP BY and window functions.
- Invalid formats, data types, and out-of-range values.
- Referential integrity checks.
- Standardization of text, dates, and categories.
- Data quality rules, scorecards, and monitoring metrics.

## Practice Ideas

Use a synthetic ecommerce catalog and create checks for:
- Duplicate product identifiers.
- Missing product names or categories.
- Zero, negative, or missing prices.
- Inconsistent category spelling.
- Products referencing unknown brands.
- Records that fail business validation rules.

## Free Learning & Practice

- [Great Expectations Documentation](https://docs.greatexpectations.io/) — learn data validation concepts and expectations.
- [dbt Learn](https://learn.getdbt.com/) — free learning content on analytics engineering and testing.
- [PostgreSQL Exercises](https://pgexercises.com/) — practise SQL patterns used in validation.
- [DataCamp SQL tutorials](https://www.datacamp.com/tutorial/category/sql) — reference material for NULLs, joins, and aggregations.
- [Kaggle Learn](https://www.kaggle.com/learn) — practise working with datasets.

## Suggested Deliverables

- `data-quality-checks.sql`
- `duplicate-detection.sql`
- `null-analysis.sql`
- `quality-rules.md`
- `quality-metrics.sql`

## Completion Checklist

- [ ] Define measurable quality rules.
- [ ] Detect duplicates and missing values.
- [ ] Validate relationships between tables.
- [ ] Produce a quality summary with counts and percentages.
- [ ] Explain the business impact of each issue.
