# Salary Benchmark Dashboard.

Interactive salary benchmarking dashboard for technology roles across multiple countries and anonymized clients.

This project visualizes estimated salary expectations for bilingual candidates with at least 4 years of relevant experience, using international remote contractor assumptions.

## Overview.

The dashboard includes:

- Salary benchmarks by position.
- Average salary comparison by employee country.
- Average vacancy cost by anonymized client.
- World heat map of average salary expectations.
- Boxplot by position with salary distribution.
- Interactive filters by:
  - Client.
  - Position.
  - Employee country.
  - Employer country.
  - Seniority.
  - Work modality.
  - Currency.
  - Confidence level.
- CSV export functionality.

## Data assumptions.

The benchmark assumes:

- Candidates are bilingual.
- Candidates have at least 4 years of relevant experience.
- Salaries are expressed in gross monthly USD.
- Work modality is international remote contractor.
- Employer country is the United States.
- Client names are anonymized as `client_1`, `client_2`, etc.

## Countries included.

The dashboard includes benchmark estimates for:

- Argentina.
- Brazil.
- Chile.
- Colombia.
- Costa Rica.
- Guatemala.
- Honduras.
- India.
- Mexico.
- Pakistan.
- Peru.

## Technologies used.

- HTML.
- CSS.
- JavaScript.
- Chart.js.
- Chart.js Boxplot plugin.
- Chart.js Data Labels plugin.
- Plotly.js.

## How to use.

1. Clone or download this repository.
2. Open the `.html` file directly in your browser.
3. Use the filters to explore salary benchmarks by role, country, client, and confidence level.
4. Use the CSV download button to export filtered results.

No backend, database, or server setup is required.

## File structure.

```text
.
├── salary_benchmark_dashboard_english_anonymized.html
├── README.md
├── .gitignore
└── LICENSE
