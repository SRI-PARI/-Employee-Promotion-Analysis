# Employee Promotion Analysis

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Project Overview
This project aims to analyze HR data to understand the factors that influence employee promotions within a company. The analysis includes data visualization and exploration to identify trends and correlations between different variables such as departments, training scores, length of service, and more.

## Features
- Data loading and preprocessing
- Descriptive statistics and data exploration
- Visualization of:
  - Most popular departments
  - Promotion counts and percentages
  - Distribution of training scores, length of service, and age
  - Gender distribution
  - Regions and recruitment channels
- Analysis of factors influencing promotions:
  - Training scores
  - Awards won
  - Age
  - Department
  - Gender
  - Region

## Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - NumPy
  - Pandas
  - Matplotlib
  - Seaborn
  - WordCloud

## Installation
1. Clone the repository to your local machine:
    ```bash
    git clone https://github.com/your-username/hr-data-analysis.git
    cd hr-data-analysis
    ```

2. (Optional) Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

4. Place the `trainhr.csv` and `testhr.csv` files in the project directory.

## Usage
1. Run the script to perform the analysis:
    ```bash
    python hr_analysis.py
    ```

2. Follow the on-screen instructions to visualize and analyze the data.

## Project Structure
```plaintext
hr-data-analysis/
├── hr_analysis.py
├── trainhr.csv
├── testhr.csv
├── requirements.txt
└── README.md
