# Patient-Flow Analysis
Healthcare operations teams often manage fragmented patient data from referrals, admissions, facility capacity, and discharge systems. This project consolidates those sources into a unified dataset and produces actionable operational insights.

Key objectives:

Clean and validate patient operations data.

Standardize tables across referrals, admissions, discharges, demographics, and capacity.

Build a relational schema for storage and querying.

Perform SQL-based trend and performance analysis.

Develop interactive dashboards for operational tracking.

Generate insights to support patient flow, placement efficiency, and resource usage.

 patient-operations-analytics/
│
├── data_raw/
│ ├── referrals.csv
│ ├── admissions.csv
│ ├── discharges.csv
│ ├── patient_demographics.csv
│ └── facility_capacity.csv
│
├── data_clean/
│ └── master_cleaned.csv
│
├── sql/
│ ├── schema.sql
│ └── queries.sql
│
├── documentation/
│ ├── ER_diagram.png
│ ├── insights_summary.md
│ ├── dashboard_instructions.md
│
│
└── README.md (this file)
