# Practical Projects

This folder contains end-to-end projects that apply data engineering concepts to realistic business scenarios. Each project should include its objective, dataset source, data model, implementation, validation, results, and lessons learned.

## Project Standards

Every project should aim to include:
1. **Business problem:** what question or process are we trying to improve?
2. **Dataset:** public or synthetic data, with its source and license documented.
3. **Data model:** tables, keys, relationships, and assumptions.
4. **Implementation:** SQL scripts, Python code, or pipeline configuration.
5. **Data quality:** validation rules and test results.
6. **Results:** meaningful metrics, sample outputs, and limitations.
7. **Documentation:** clear instructions to reproduce the work.

## Planned Projects

### 1. Ecommerce Data Quality Analysis

**Goal:** Analyze a sample ecommerce product catalog and identify data quality issues that could affect product discovery, reporting, and downstream processes.

**Potential checks:**
- Duplicate product identifiers or records.
- Missing product names, categories, or brands.
- Zero, negative, or missing prices.
- Inconsistent category and brand labels.
- Invalid product codes or formats.
- Products with unexpected or conflicting attributes.

**Planned deliverables:**
- Sample dataset (synthetic or public).
- Data dictionary and quality rules.
- SQL scripts for profiling and validation.
- Summary of issues and quality metrics.
- Recommendations for improving the catalog.

**Suggested technology:** PostgreSQL and SQL; Python may be added for data generation or automation.

**Privacy note:** This project will use only public or synthetic data. No confidential employer, supplier, or customer data will be included.

## Free Data Sources & Practice

- [Kaggle Datasets](https://www.kaggle.com/datasets) — discover public datasets; review each dataset's license and terms.
- [Google Dataset Search](https://datasetsearch.research.google.com/) — find datasets from public sources.
- [SQLBolt](https://sqlbolt.com/) and [PostgreSQL Exercises](https://pgexercises.com/) — practise SQL before applying it to projects.
- [DataTalksClub Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) — project-based data engineering curriculum.

## Project Folder Template

For each project, use a structure like:

```text
project-name/
├── README.md
├── data/
│   └── README.md
├── sql/
├── src/
├── docs/
└── results/
```

Do not commit passwords, API keys, access tokens, personal information, or confidential datasets.
