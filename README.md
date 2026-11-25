# Receivables Assignment Grader

Browser-based batch grader for the 2020–2025 Receivables Data Simulation.

1. Open the [grader](https://hunternbh.github.io/receivables-assignment-grader/).
2. Select saved Excel submissions. To try the workflow, download the sample workbook from the grader and select it. The sample uses synthetic data and should score **29/31**.
3. Expand a result to inspect individual checks or download the scores and cell results as CSV files.

The grader uses the protected yearly copies in each workbook to check the 2020–2024 receivables totals, sales write-off rates and aging-bucket write-off rates, plus the 2025 receivables total. Each of the 31 workbook cells earns one point. The default absolute tolerance is below $0.001 for amounts and below 0.10 percentage points for rates. Both tolerances are adjustable. The 2025 allowance estimate and the optional 30-point report rubric are for manual assessment.

The working-data check matches original customer inputs and ignores added calculations and fields left blank in the protected copy. A missing or changed original value produces a warning. The protected copy still supplies the grading values.

The page processes workbooks in your browser. You can also download and open the HTML file locally.
