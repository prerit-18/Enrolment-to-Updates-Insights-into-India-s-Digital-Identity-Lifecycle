📊 Unlocking Societal Trends in Aadhaar Enrolment and Updates

📌 Project Overview

This project analyzes Aadhaar enrolment, demographic update, and biometric update datasets to identify meaningful patterns and trends related to population coverage, identity updates, and regional behavior.

The analysis focuses on data cleaning, aggregation, and exploratory analysis to transform raw UIDAI administrative data into insight-driven observations that can support informed decision-making and system-level understanding.

⸻

🎯 Problem Statement

Unlocking Societal Trends in Aadhaar Enrolment and Updates

The objective is to identify meaningful patterns, trends, or indicators from Aadhaar enrolment and update data and translate them into clear insights that can support informed decision-making and system improvements.

⸻

📂 Datasets Used

This project uses publicly available, aggregated Aadhaar datasets.

1️⃣ Aadhaar Enrolment Dataset
	•	Age-wise enrolment counts:
	•	0–5 years
	•	5–17 years
	•	18 years and above
	•	Geographic granularity:
	•	State
	•	District
	•	PIN code
	•	Temporal attribute:
	•	Date

Purpose:
Provides baseline population coverage and age-wise enrolment distribution.

⸻

2️⃣ Aadhaar Demographic Update Dataset
	•	Aggregated demographic update counts
	•	Age-segmented updates (5–17 and 18+)
	•	Geographic and temporal breakdown

Purpose:
Reflects identity updates driven by mobility, life events, and data corrections.

⸻

3️⃣ Aadhaar Biometric Update Dataset
	•	Aggregated biometric update counts
	•	Age-segmented updates (5–17 and 18+)
	•	Geographic and temporal breakdown

Purpose:
Captures biometric refresh behavior and age-related biometric changes.

⸻

⚠️ Data Availability

Due to GitHub file size limitations, the raw CSV datasets are not included in this repository.

The datasets can be downloaded from the official UIDAI data source and placed in the project directory before running the notebook.

⸻

🛠 Data Preprocessing

The notebook performs the following preprocessing steps:
	•	Combined multiple API chunks for each dataset
	•	Removed exact duplicate records caused by overlapping extraction ranges
	•	Standardized geographic identifiers (case normalization and semantic mapping)
	•	Identified logical duplicates at (date, state, district, PIN code) level
	•	Consolidated logical duplicates by aggregating numeric counts
	•	Validated that no duplicate records remain after cleaning

These steps ensure data integrity and prevent double counting.

⸻

📊 Exploratory Data Analysis (EDA)

The notebook explores:
	•	Age-wise enrolment distribution
	•	Geographic variation in enrolment and updates
	•	Comparative patterns between enrolment, demographic updates, and biometric updates
	•	State, district, and PIN-code level aggregation readiness

The analysis focuses on understanding what the data represents rather than applying unnecessary predictive models.

⸻

🔍 Key Insights
	•	Aadhaar enrolment varies significantly across age groups and regions, reflecting life-stage and population distribution.
	•	Demographic updates indicate identity changes linked to mobility and personal circumstances.
	•	Biometric updates show clear age-related patterns, emphasizing the importance of periodic biometric refresh.
	•	Proper preprocessing and aggregation are critical for extracting valid insights from large administrative datasets.

⸻

📈 Tools & Technologies
	•	Python
	•	pandas, numpy
	•	Jupyter Notebook

⸻

🏁 Conclusion

This project demonstrates how Aadhaar enrolment and update data can be systematically cleaned and analyzed to uncover meaningful societal trends. The insights derived from the notebook highlight the value of administrative data in supporting data-driven understanding and system-level improvements.

⸻

👤 Contributors
	•	Prerit
	•	Alisha Chaudhary
	•	Harmanpreet Kaur
⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻⸻
