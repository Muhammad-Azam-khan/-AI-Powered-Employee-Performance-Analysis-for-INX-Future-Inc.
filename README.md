
# Project Title

 AI-Powered Employee Performance Analysis for INX Future Inc.

---

# INX Future Inc. Employee Performance Analysis

## Project Overview

This project focuses on analyzing employee performance at INX Future Inc. with the aim of identifying key factors that influence performance and providing actionable recommendations to reduce employee attrition. The project involves the following key tasks:
- Data preprocessing and exploratory data analysis.
- Feature selection and engineering.
- Model training and evaluation.
- Insights generation and recommendations.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/employee-performance-analysis.git
   cd employee-performance-analysis
   ```

2. **Create and activate a virtual environment:**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. **Install the required libraries:**
   ```bash
   pip install -r requirements.txt
   ```

4. **Launch Jupyter Notebook:**
   ```bash
   jupyter notebook
   ```

## Dataset

The dataset contains employee data, including features such as age, gender, department, job role, satisfaction levels, and performance ratings. Below are the key features used in this analysis:

- `EmpNumber`, `Age`, `Gender`, `EducationBackground`, `MaritalStatus`, `EmpDepartment`, `EmpJobRole`
- `BusinessTravelFrequency`, `DistanceFromHome`, `EmpEducationLevel`, `EmpEnvironmentSatisfaction`
- `EmpHourlyRate`, `EmpJobInvolvement`, `EmpJobLevel`, `EmpJobSatisfaction`
- `NumCompaniesWorked`, `OverTime`, `EmpLastSalaryHikePercent`, `EmpRelationshipSatisfaction`
- `TotalWorkExperienceInYears`, `TrainingTimesLastYear`, `EmpWorkLifeBalance`, `ExperienceYearsAtThisCompany`
- `ExperienceYearsInCurrentRole`, `YearsSinceLastPromotion`, `YearsWithCurrManager`, `Attrition`, `PerformanceRating`

The dataset is processed and used for predictive modeling to determine the factors affecting employee performance and attrition.

## Project Structure

```plaintext
employee-performance-analysis/
│
├── data/               # Dataset files
├── notebooks/          # Jupyter notebooks for analysis
├── models/             # Trained models
├── reports/            # Generated analysis reports
├── src/                # Source code for data processing and modeling
│   ├── data_processing.py
│   ├── feature_engineering.py
│   └── model_training.py
├── README.md           # Project README file
├── requirements.txt    # Python libraries required
└── .gitignore          # Git ignore file
```

## Usage

1. **Data Preprocessing:**
   - Run `data_processing.py` to clean and preprocess the data.

2. **Feature Engineering:**
   - Run `feature_engineering.py` to perform feature selection and engineering.

3. **Model Training:**
   - Run `model_training.py` to train models and evaluate their performance.

4. **Analysis:**
   - Use the Jupyter notebooks in the `notebooks/` directory to explore data, perform analysis, and generate insights.

## Results

### Key Insights:
- **High positive correlation** between `Age` and `TotalWorkExperienceInYears` indicates that more experienced employees tend to be older.
- **Negative correlation** between `Attrition` and `TotalWorkExperienceInYears` suggests that employees with more experience are less likely to leave the company.

### Model Performance:
- **Gradient Boosting Classifier (GBClassifier)** achieved an `AUC` score of **0.96**, indicating outstanding discriminative ability.
- **Random Forest and XGBoost** models also demonstrated high accuracy and stability.

### Recommendations:
- Focus on improving job satisfaction and work-life balance to reduce attrition.
- Offer tailored retention strategies for high-risk groups based on education and experience.
- Minimize frequent business travel to reduce stress and turnover.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Contact

For any questions or inquiries, please contact:
- Muhammad Azam Khan: [mmakn5544@gmail.com](mailto:mmakn5544@gmail.com)
--github :[https://github.com/Muhammad-Azam-khan]

- LinkedIn: [Your LinkedIn Profile](https://www.linkedin.com/in/yourprofile)


