# Waggle Power BI Dashboard: Lapdog vs. Lapcat Analysis

This Power BI report analyzes user and pet data from Waggle, a pet-tech startup known for its smart devices. 
Following the success of the Lapdog fitness collar for dogs, Waggle launched a field test of its feline counterpart, the Lapcat. 
This dashboard helps stakeholders understand how the new device is performing and whether it justifies further development.

## Datasets Overview

The data used in this project was provided by Udacity as part of their Data Analyst Nanodegree Program. 
The datasets were already cleaned and curated to simulate real-world business scenarios, allowing me to focus on analysis, visualization, and stakeholder communication.

## Business Requirements

Waggle stakeholders are asking key questions to evaluate the impact and market potential of LapCat:

**From the CEO:**
- Did the average daily steps increase for cats wearing the device, as they did for dogs?
- Were owners of Lapcat devices as satisfied with the product as Lapdog owners?

**From the Product Team:** They are especially interested in demographic insights related to pets and families.

**Design & Usability Requirements:** The report also needed to meet Waggle’s design standards:

- A branded header on each page, showing the page title and Waggle logo
- Slicers positioned on the left or beneath the banner to filter visuals
- Navigation buttons placed consistently for ease of use
- Only Waggle-approved palette colors (plus black, white, and gray tones)
- One reset button per page to clear filters
- Buttons for page-to-page navigation

## Report Structure

***Key Features***

- Waggle-branded theme and layout for consistency
- Dynamic visual swapping for comparing trends
- Filter reset and drill-through functionality
- Built-in slicers for stakeholder exploration
- Used the same colors for dogs and cats across all pages to make comparisons easy and intuitive.

### Page 1: Lapdog vs Lapcat (Home)

This page directly addresses the CEO’s questions with side-by-side compareisons:

- Average daily step count and satisfaction ratings by device
- Step trends over time by species
- Activity minutes and daily steps by month/year

### Page 2: Pets Summary

- Demographics of Waggle pets: species, breed, age, weight.
- Activity breakdown: steps and active minutes by age group.

### Page 3: Family Summary

- Owner location, household size, and income demographics.
- Visuals show patterns in household types and pet ownership.

#### Page 4: Family Details

- This is a detailed view of individual households and their pets. This page is accessed by right-clicking entries from the table visual on Page 3.
- Supports deeper insights into user-level data.

## Project Files

- `Waggle Report.pbix` — Main Power BI report
- `sample-datasets-for-pbi.xlsx` — Cleaned datasets used for visualizations
- `marketing-collateral.zip` — Brand assets and presentation materials

