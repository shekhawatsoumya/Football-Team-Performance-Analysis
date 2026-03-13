# Football-Team-Performance-Analysis

## Project Overview

This project analyzes global football match data to uncover historical trends in match volume, scoring patterns, and team performance across 269 countries. The analysis provides insights into football statistics from historical data spanning multiple decades.

## Data Source

- **Source**: Kaggle
- **Raw Data**: `Raw_data/Football data.xlsx`

## Data Cleaning

- **Tool**: Power BI / Power Query Editor
- **Cleaned Data**: `Clean_data/Football data.xlsx`
- **Process**: Data was cleaned and prepared using Power Query Editor within Power BI to ensure data quality and consistency for analysis.

## Analysis

- **Tool**: Power BI
- **Dashboard File**: `Result/Football Analysis.pbix`
- **Dashboard Preview**: `Result/Football Team Performance Analysis .png`

## Key Findings

### Key Performance Indicators (KPIs)

- **Total Matches**: 49,000 recorded matches
- **Total Goals Scored**: 144,000 goals
- **Scoring Efficiency**: An average of 2.94 goals per match
- **Home Field Advantage**: Home teams win approximately 49% of the time

### Historical Match Trends

- **Volume Growth**: Match frequency remained low and stable until roughly 1950. Since then, there has been an exponential increase, peaking at 1,229 matches in a single year during the early 21st century.
- **Scoring Evolution**: The "Average Goal by Year" chart shows significant volatility in the early years (with peaks above 7.0). However, scoring has stabilized significantly over the last century, trending toward a consistent average of 2.0 goals per match in modern times.

### Performance & Results Distribution

- **Win/Loss Breakdown**:
  - Home Wins: 49% (24.04K matches)
  - Away Wins: 28.27% (13.87K matches)
  - Draws: 22.73% (11.16K matches)
- **Top Performing Teams**: Zambia leads the dataset with the highest count of wins (358), followed by Yugoslavia (223) and Zimbabwe (188).

## Project Structure

Football-Team-Performance-Analysis/
├── README.md
├── LICENSE
├── Raw_data/
│   └── Football data.xlsx          # Original raw data from Kaggle
├── Clean_data/
│   └── Football data.xlsx          # Cleaned and processed data
├── Descriprtion/
│   └── Description.txt             # Detailed analysis summary
└── Result/
    ├── Football Analysis.pbix      # Power BI dashboard file
    └── Football Team Performance Analysis .png  # Dashboard screenshot

## Tools & Technologies

- **Data Cleaning**: Power BI Power Query Editor
- **Data Analysis & Visualization**: Power BI Desktop
- **Data Storage**: Excel (.xlsx format)
