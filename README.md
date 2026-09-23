# Audible Data Cleaning — Power Query

A data cleaning case study using **Microsoft Excel Power Query** to transform a raw Audible audiobook dataset into a clean, structured, analysis ready dataset.

## Project Overview

The raw Audible dataset contained several data quality issues, including inconsistent title casing, combined author and narrator fields, text based durations and ratings, non numeric price values and inconsistent date formats.

Using Power Query, the dataset was cleaned and restructured through a series of transformations to make the fields consistent and suitable for further analysis and reporting.

## Tools Used

- Microsoft Excel
- Power Query
- Power Query M
- Data Cleaning & Transformation

## Data Cleaning & Transformation

The project covered the following transformations:

- Standardized book titles using consistent title casing
- Removed prefixes and separated multiple authors into individual columns
- Converted release dates into a proper Date data type
- Converted text based listening times into true Duration values
- Converted price values into numeric format and handled non-numeric entries
- Extracted numeric star ratings from text
- Split multiple narrator names into separate columns
- Created a `releaseinfo` field combining release date and language
- Standardized price values to two decimal places

## Outcome

The raw Audible export was transformed into a clean and structured dataset with standardized text, native date and duration types, reliable numeric fields, separated multi value columns and consistent currency formatting.

The resulting dataset is suitable for downstream analysis and visualization.

## Project Files

- `audible_cleaned.csv` — cleaned dataset produced after the Power Query transformations
- `Audible_Data_Cleaning_Case_Study.pdf` — project documentation showing the cleaning workflow and transformations

## Author

**Samarth Pathak**

[LinkedIn](https://linkedin.com/in/samarth-pathak-5680692b9) · [GitHub](https://github.com/sam-arth17)
