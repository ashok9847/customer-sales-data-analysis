# Customer Sales Data Cleaning and EDA

## Project Overview 
This project focuses on cleaning and performing Exploratory Data Analysis (EDA) on a messy customer sales dataset. The goal is to transform raw, inconsistent data into a clean, structured format suitable for further analysis and to extract valuable insights into customer purchasing behavior and sales patterns.

## Table of Contents
- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Features and Objectives](#features-and-objectives)
- [Installation](#installation)
- [Usage](#usage)
- [Data Dictionary](#data-dictionary)
- [Key Findings](#key-findings)
- [Contributing](#contributing)
- [License](#license)

## Data Source
The primary data source for this project is `messy_customer_sales_data.csv`.

## Features and Objectives
- **Data Loading**: Load the raw customer sales data into a Pandas DataFrame.
- **Handling Missing Values**: Identify and appropriately handle missing values across various columns (e.g., `Customer_ID`, `Gender`, `Age`, `City`, `Last_Purchase_Date`, `Purchase_Amount`, `Feedback_Score`, `Country`).
- **Data Type Conversion**: Convert columns to their correct data types (e.g., `Age` to integer, `Last_Purchase_Date` to datetime).
- **Inconsistent Data Formatting**: Clean and standardize inconsistent entries (e.g., `Gender` (m/f/male/female), `City` (varied casing), `Country` (India/IND/india)).
- **Duplicate Removal**: Identify and remove duplicate entries to ensure data integrity.
- **Exploratory Data Analysis (EDA)**: Perform preliminary analysis to understand data distributions, identify outliers, and uncover initial patterns.
- **Summary Statistics**: Generate descriptive statistics to summarize the central tendency, dispersion, and shape of the dataset's distribution.

## Installation
To run this notebook, you will need Python and the following libraries. You can install them using `pip`:

```bash
pip install pandas matplotlib seaborn
```

## Usage
1.  Clone this repository:
    ```bash
    git clone https://github.com/yourusername/customer-sales-data-analysis.git
    cd customer-sales-data-analysis
    ```
2.  Place the `messy_customer_sales_data.csv` file in the project's root directory.
3.  Open and run the Jupyter Notebook (or Google Colab notebook):
    ```bash
    jupyter notebook Customer_Sales_Data_Cleaning_and_EDA.ipynb
    ```
    or simply open it in Google Colab.

Follow the cells sequentially to see the data cleaning steps and EDA in action.

## Data Dictionary
| Column Name        | Description                                     | Data Type (Cleaned) |
| :----------------- | :---------------------------------------------- | :------------------ |
| `Customer_ID`      | Unique identifier for each customer             | Object              |
| `Name`             | Customer's full name                            | Object              |
| `Gender`           | Customer's gender (Male/Female)                 | Object              |
| `Age`              | Customer's age                                  | Integer             |
| `City`             | City where the customer resides                 | Object              |
| `Signup_Date`      | Date when the customer signed up                | Object (Datetme anticipated)|
| `Last_Purchase_Date`| Date of the customer's last purchase          | Object (Datetme anticipated)|
| `Purchase_Amount`  | Total amount of the purchase                    | Integer             |
| `Feedback_Score`   | Customer's feedback score (1-10)                | Float               |
| `Email`            | Customer's email address                        | Object              |
| `Phone_Number`     | Customer's phone number                         | Integer             |
| `Country`          | Country where the customer resides (India)      | Object              |

## Key Findings
*(This section will be populated after the EDA is complete. Examples might include:)*
-   Average purchase amount by gender.
-   Distribution of customers across different cities.
-   Correlation between age and purchase amount.
-   Trends in purchase frequency.

## Contributing
Contributions are welcome! If you have suggestions for improvements, please open an issue or submit a pull request.

## License
This project is open-sourced under the MIT License.
