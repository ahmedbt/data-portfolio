## I. Introduction / Context

### Project goal
The goal of this project is to explore and analyze the hospital management data, understand cost distribution across departments and branches, identify trends over time, and uncover insights that can inform strategic decisions for hospital management optimization.


### Content of each column
![Column content](assets/table.png)

### Tools used
- **SQL**: For data cleaning, transformation, and preparation.
- **MS Excel**: For interactive dashboards, filtering, and visual exploration of the dataset.

## II. Data cleaning
To prepare the dataset for analysis, the following steps were performed:

1. **Column adjustments and renaming**
- Removed irrelevant columns like `description` and `appointment_date`.
- Renamed `specialization` to `department` and `status` to `appointment_status` for clarity.

2. **Type conversion**
- Converted `date_of_birth` and `treatment_date` to date, `cost` to numeric types.

3. **Standardization and formatting**
- Formatted `treatment_date` to short date, `cost` to integer without decimals.
- Trimmed unnecessary spaces.

4. **Feature engineering**
- Created column `age` from `date_of_birth` for clearer analysis.
- `years_experinence` put in three groups: 0-10, 11-20, 20+.
- Extracted only month from `treatment_date` for timeline chart.

5. **Resulting dataset**
- Cleaned, standardized, and structured data ready for exploratory analysis and visualization in Excel dashboard.


## III. Exploratory Data Analysis (EDA)

The cleaned hospital dataset allowed us to explore key questions about the hospital revenue, appointment distribution, and trends over time. 

Using MS Excel, interactive dashboards were created to visualize the findings.


































