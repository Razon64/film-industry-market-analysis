# Da Best Flicks: Historical Movie Market Analysis

## Business Case
In 2017, the production startup "Da Best Flicks" required a data-driven strategy to enter the film industry. This project analyzes a dataset of 1,000 key movies (1937–2016) to identify high-potential genres and bankable talent for future productions.

## Objectives
*   Market Mapping: Link disparate datasets (Actors, Genres, and Sales) into a unified analysis engine.
*   Genre Profitability: Identify which categories yield the highest average box office returns.
*   Talent Benchmarking: Rank lead actors based on their international market appeal.
*   Operational Insights: Solve complex business queries regarding historical trends and outlier performance.

## Technical Implementation (Excel)
*   Data Relational Mapping: Employed `VLOOKUP` to normalize the data architecture.
*   Dynamic Pivot Tables:
    *   Implemented Calculated Fields to synthesize Domestic and International revenues.
    *   Applied Value Field Settings to analyze averages, providing a more accurate "Potential per Script" metric.
*   Statistical Analysis: Used `IFS` logical functions to answer multi-variable management questions.
*   Top-N Analysis: Filtered and ranked the Top 15 actors by International Box Office to guide casting recommendations.

## Key Findings
*   Genre Trends: (Insert a brief observation, e.g., "Sci-Fi consistently outperforms Drama in International markets by X%.")
*   Top Talent: The analysis identified the 15 most bankable leads for global distribution.

## How to Use
1. Open `reports/Movie_Analysis_Report.xlsx`.
2. Navigate to the Genre Analysis, Actor Analysis tab for investment insights.
3. Review the Answer Sheet for detailed statistical breakdowns.
