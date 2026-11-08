# Data Pipelines

This section covers how data moves from source systems to destinations through repeatable, observable, and reliable workflows.

## Topics

- Pipeline components: sources, extraction, transformations, and destinations.
- Batch processing and introductory streaming concepts.
- Scheduling and workflow orchestration.
- Dependencies, retries, and failure handling.
- Logging, monitoring, and alerting.
- Idempotency and data validation.
- Pipeline documentation and operational considerations.
- Introduction to Apache Airflow.

## Practice Ideas

- Design a simple pipeline that reads a CSV file, validates records, transforms fields, and writes an output file.
- Add logging and error handling.
- Make a pipeline safe to rerun without creating duplicate output.
- Draw a workflow showing dependencies between tasks.
- Document what should happen when a source file is missing or invalid.

## Free Learning & Practice

- [Apache Airflow Documentation](https://airflow.apache.org/docs/) — concepts, tutorials, and installation guidance.
- [Astronomer Academy](https://academy.astronomer.io/) — Airflow learning courses and tutorials.
- [Prefect Documentation](https://docs.prefect.io/) — workflow orchestration concepts and tutorials.
- [AWS Workshops](https://workshops.aws/) — practical cloud workflow labs; check costs and prerequisites.
- [DataTalksClub Data Engineering Zoomcamp](https://github.com/DataTalksClub/data-engineering-zoomcamp) — community-driven learning materials and hands-on projects.

## Suggested Deliverables

- `csv-validation-pipeline.py`
- `pipeline-design.md`
- `airflow-dag-example/`
- `monitoring-and-retries.md`

## Completion Checklist

- [ ] Draw a pipeline architecture.
- [ ] Separate extraction, transformation, and loading steps.
- [ ] Add validation and error handling.
- [ ] Explain retries and idempotency.
- [ ] Document how pipeline failures are detected.
