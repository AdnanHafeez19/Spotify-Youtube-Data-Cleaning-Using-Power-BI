# 🎵 Spotify & YouTube Music Data Cleaning with Power BI

## 📌 Project Overview
This project focuses on cleaning and transforming a combined dataset from Spotify and YouTube Music using **Power BI's Power Query Editor**. The aim is to prepare raw, inconsistent data for high-quality analysis by resolving common data issues such as missing values, formatting inconsistencies, and invalid entries.

---

## 🎯 Objectives

- Identify and handle missing values in key metrics like `Views` and `Likes`.
- Split and clean merged data in columns like `Spotify_Info` and `Youtube_Info`.
- Standardize column names and case formats for consistency.
- Remove irrelevant columns and random data entries.
- Correct data types for numeric and categorical fields.
- Fix invalid values such as `"invalid_data"` in numeric columns.
- Eliminate duplicate rows and reorder columns for clarity.

---

## 🧰 Tools Used

- **Power BI Desktop**
  - **Power Query Editor** for all data cleaning operations
  - No external tools, scripts, or programming languages were used

---

## 📁 Dataset

- **Source:** [Google Drive](https://drive.google.com/file/d/1qanyuwEzkwEJ73vDJHk4ZlWE0JUG7udb/view)
- **Format:** CSV
- **Contents:** Artist info, track titles, albums, Spotify metrics (e.g., danceability, energy), YouTube metrics (e.g., views, likes)

---

## 🧹 Key Cleaning Tasks

| Step | Description |
|------|-------------|
| 1. Missing Values | Replaced or removed missing/null values in numerical fields |
| 2. Merged Columns | Split `Spotify_Info` and `Youtube_Info` using delimiters and cleaned the outputs |
| 3. Naming Consistency | Renamed columns using `snake_case` for uniformity |
| 4. Irrelevant Columns | Removed columns with random or unusable data |
| 5. Data Types | Converted text-based numeric fields to proper number format |
| 6. Invalid Entries | Replaced `"invalid_data"` and cleaned up inconsistent entries |
| 7. Duplicates | Identified and removed duplicate records |
| 8. Reordering | Reorganized columns for logical flow and readability |

---

## 📊 Final Output

- Cleaned dataset ready for use in Power BI reports and dashboards
- Well-structured column naming and ordering
- Reliable metrics for streaming data analysis

---

