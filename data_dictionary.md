# Data Dictionary

## Core Variables

| Column Name       | Description |
|------------------|-------------|
| length_of_stay   | Total number of days a patient remained hospitalized |
| total_cost       | Estimated hospitalization cost based on LOS benchmarks |
| admission_type   | Type of admission (e.g., Emergency, Elective) |
| diagnosis        | Primary diagnosis for the admission |
| died_in_hosp     | Indicator of in-hospital mortality |

---

## Engineered Risk Indicators

| Column Name     | Description |
|----------------|-------------|
| is_abnormal    | Binary flag indicating abnormal laboratory results |
| is_long_stay   | Flag identifying admissions above the high-risk LOS threshold |
| lab_value      | Numerical laboratory result used for abnormality assessment |

---

## Risk Thresholds

- High-risk admissions are defined using percentile-based LOS thresholds
- Thresholds are chosen to capture extreme outcomes rather than typical cases
