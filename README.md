# 🍷 Wine Quality Analysis — Power BI

An interactive Power BI dashboard designed to analyze wine quality and explore the relationship between quality scores and different chemical characteristics.

The project combines data cleaning, transformation, DAX calculations, data visualization, and dashboard design to turn raw wine-quality data into an interactive analytical report.

---

## Dashboard Preview

![Wine_modelling_Dashboard](https://github.com/anu78600/Wine_modelling_Dashboard/blob/main/wine-quality-dashboard.png)

---

## Project Objective

The objective of this project is to analyze wine-quality data and identify patterns across different chemical characteristics.

The dashboard was designed to answer questions such as:

- How are wine quality scores distributed?
- How does alcohol level vary across quality scores?
- How does total sulfur dioxide change with wine quality?
- How does residual sugar vary across quality levels?
- What are the average chemical characteristics for each quality score?
- How does alcohol relate to wine quality?

---

## Key Metrics

| KPI | Value |
|---|---:|
| Total Wines | 4,898 |
| Average Quality | 5.88 |
| High Quality Wines | 1,060 |
| High Quality % | 21.64% |
| Average Alcohol | 10.50 |

> High-quality wines are defined as wines with a quality score of **7 or higher**.

---

## 📈 Dashboard Features

### 1. Wine Quality Distribution

Shows the distribution of wines across different quality scores.

### 2. Average Alcohol by Quality

Compares average alcohol levels across different wine-quality scores.

### 3. Alcohol vs Quality

A scatter visualization showing the relationship between alcohol level and wine quality.

### 4. Average Total Sulfur Dioxide by Quality

Shows how average total sulfur dioxide varies across quality levels.

### 5. Average Residual Sugar by Quality

Visualizes the average residual sugar associated with each quality score.

### 6. Chemical Characteristics

A summary table containing average chemical characteristics by quality score, including:

- Alcohol
- Sugar
- pH
- Chlorides

### 7. Interactive Filters

The dashboard includes interactive filters for:

- Wine Quality
- Alcohol Range

These allow users to explore specific segments of the dataset.

---

## Tools & Technologies

- **Power BI** — Dashboard development and visualization
- **Power Query** — Data cleaning and transformation
- **DAX** — KPI and analytical calculations
- **Excel** — Source data preparation
- **Figma** — Dashboard visual design and supporting visual elements

---

## Data Preparation

The dataset was prepared before visualization to make it suitable for analysis.

The workflow included:

1. Importing the wine-quality dataset
2. Reviewing data types
3. Cleaning and transforming the data
4. Preparing fields for analysis
5. Creating calculated measures using DAX
6. Building relationships between analytical components
7. Designing interactive Power BI visuals
8. Applying a consistent wine-inspired visual theme

---

## Key DAX Measures

### Total Wines

```DAX
Total Quantity =
COUNTROWS('winequality-white new')
