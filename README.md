# Plant Business Analysis

An online business report and analysis for plant products, showcasing data visualization, insights, and key metrics.

## Table of Contents

- [Introduction](#introduction)
- [Dataset / Inputs](#dataset--inputs)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Analysis & Business Questions](#analysis--business-questions)
- [Results & Insights](#results--insights)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction

This repository contains the materials for an online business report focused on plant products. The aim is to analyze sales, pricing, and customer-related data to provide actionable insights for business decisions. The project includes dashboards, visualizations, and data analysis workflows.

## Dataset / Inputs

The data used for this project is assumed to be a collection of plant product records, including attributes such as plant type, brand, price, age, size, and location. Placeholders should be replaced with actual dataset details when available.

## Tech Stack

- Microsoft Excel (primary tool for data analysis and dashboard creation)
- Built-in Excel features such as PivotTables, charts, and formulas
- Optional: Power BI or other BI tools if dashboards are exported or re-created outside Excel

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/username/plant-business-analysis.git
   cd plant-business-analysis
   ```
2. Open the Excel workbook located in the `dashboard/` folder using Microsoft Excel.
3. Ensure macros or data connections are enabled if used in the workbook.

## Usage

- The main analysis and dashboard are contained within an Excel workbook in the `dashboard/` directory.
- Place any raw data files (CSV, Excel) in the `data/` folder and update links or data sources in the workbook as needed.
- Use Excel’s PivotTables, filters, and charts to explore and modify the analysis.
- If desired, export data or visuals for use in other tools or presentations.


## Analysis & Business Questions

Typical questions addressed in the project include:
- Which plant types are most popular by sales volume?
- How do prices vary by brand, size, and location?
- What is the distribution of plant age across different categories?
- Are there any seasonal or geographical trends?

## Results & Insights

The visual dashboard provides several concrete metrics:

- **Total Plant Types:** 12 distinct types of plants are represented in the dataset.
- **ID Count:** 400 individual plant records were analyzed.
- **Average Price:** The mean original price across all items is 168 (currency units).
- **Location Age:** Age distribution shows 151 plants categorized as indoor, 2 as outdoor, and 476.1 total age units when combining both.
- **Brand Prices & Counts:** Charts display price distributions by brand, highlighting which brands contribute most significantly to total value.
- **Plant Size Pricing:** Small plants account for the highest total price (1605.93), followed by medium (470.43) and large (4.99) size categories.
- **Plant Age Distribution:** Age segments are visualized with counts such as 112, 86, 45, etc., indicating clusters around specific age ranges.

These insights guide business questions around pricing strategy, inventory focus by plant type and size, and age/location-based marketing.


## Project Structure

```
plant-business-analysis/
├── dashboard/        # Dashboard definitions and reports
├── data/             # Dataset files (CSV, Excel, etc.)
├── visualisation/    # Scripts or notebooks for charts and plots
├── README.md         # Project documentation
├── LICENSE           # License information
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request with any improvements, bug fixes, or new features.

## License

This project is open-source. Specify your license here (e.g., MIT License).

## Contact

For questions or feedback, please contact [kanchi sukheja](mailto: kanchisukheja20@gmial.com) or visit the project repository on GitHub.


