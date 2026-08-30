# CMS Pharma Data Pipeline — Dissertation Practical Work

This repository contains the technical implementation supporting the dissertation
"[your dissertation title]" submitted to BSBI/UCA.

## Contents
- `01_notebooks/` — Databricks notebooks implementing the Bronze-Silver-Gold
  Medallion Architecture and the primary survey statistical analysis.
- `02_azure_architecture/` — Screenshots of the Azure resource group, credentials,
  external locations, and Unity Catalog configuration.
- `03_power_bi/` — Power BI file and visualisation screenshots built on the Gold layer.
- `04_primary_data/` — Raw primary survey data (anonymised).
- `05_findings_exports/` — Exported summary tables from the analysis.

## Technology Stack
Azure Data Factory, Azure Databricks (PySpark), Azure Data Lake Storage Gen2,
Delta Lake, Unity Catalog, Power BI (DirectQuery).

## Data Source
Centers for Medicare & Medicaid Services (CMS) — Medicare Part D Prescribers by
Provider and Drug dataset.
