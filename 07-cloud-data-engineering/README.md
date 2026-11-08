# Cloud Data Engineering

This section introduces cloud concepts and managed data services, with an initial focus on Amazon Web Services (AWS).

## Topics

- Cloud computing concepts: scalability, availability, and shared responsibility.
- Object storage and Amazon S3.
- Querying data in S3 with Amazon Athena.
- Data catalogs and AWS Glue.
- File formats: CSV, JSON, Parquet.
- Partitioned datasets and query cost considerations.
- IAM basics and least-privilege access.
- Introductory cloud data architecture.

## Practice Ideas

- Create a small sample dataset and organize it by year and month.
- Explore how object storage differs from a relational database.
- Query sample data with Athena when an AWS account and suitable access are available.
- Compare CSV and Parquet for analytical workloads.
- Document a simple S3-to-Athena data flow.

## Free Learning & Practice

- [AWS Skill Builder](https://skillbuilder.aws/) — AWS digital courses and learning plans; includes free content and optional paid offerings.
- [AWS Getting Started with Amazon S3](https://docs.aws.amazon.com/AmazonS3/latest/userguide/GetStartedWithS3.html) — official hands-on documentation.
- [Amazon Athena User Guide](https://docs.aws.amazon.com/athena/latest/ug/what-is.html) — official Athena concepts and tutorials.
- [AWS Glue Documentation](https://docs.aws.amazon.com/glue/) — official service documentation.
- [AWS Workshops](https://workshops.aws/) — guided technical workshops; check each workshop's prerequisites and potential cloud costs.

## Important Cost Note

AWS services may incur charges depending on usage, region, and configuration. Review pricing, free-tier eligibility, and budgets before creating resources. Delete test resources when finished.

## Suggested Deliverables

- `aws-data-architecture.md`
- `s3-layout-example.md`
- `athena-queries.sql`
- `parquet-vs-csv.md`

## Completion Checklist

- [ ] Explain object storage and its use cases.
- [ ] Describe how Athena queries data in S3.
- [ ] Explain the role of Glue Data Catalog.
- [ ] Understand basic partitioning and file formats.
- [ ] Identify potential cloud costs before running a lab.
