## 📊 Analyzing Customer Churn in Telecommunications: Insights from Data Patterns and Trends

This project explores customer churn behavior in the telecommunications sector using data-driven insights.
By examining customer demographics, usage patterns, and regional differences, the analysis identifies key factors contributing to customer attrition and helps design better retention strategies.

## 🧠 Project Overview

Customer churn represents one of the biggest challenges in the telecom industry.
This study performs descriptive and pattern analysis to answer critical questions such as:

1. Which demographic and socioeconomic factors are most associated with churn?

2. How do communication behaviors (calls, SMS, data usage) differ between churned and active customers?

3. Which states and telecom partners show the highest churn trends over time?

## 🧾 Dataset Description

The dataset telecom_churn.csv contains customer-level information such as:

| Feature                               | Description                                             |
| ------------------------------------- | ------------------------------------------------------- |
| `customer_id`                         | Unique customer identifier                              |
| `age`                                 | Customer’s age                                          |
| `gender`                              | Gender of the customer                                  |
| `state`, `city`                       | Location information                                    |
| `telecom_partner`                     | Telecom provider                                        |
| `calls_made`, `sms_sent`, `data_used` | Usage metrics                                           |
| `date_of_registration`                | Registration date                                       |
| `churn`                               | Whether the customer left the service (1 = Yes, 0 = No) |


## ⚙️ Technologies Used

* Python 3.10+

* Libraries:

* `pandas` – data preprocessing

* `numpy` – numerical operations

* `matplotlib`, `seaborn` – data visualization

* `warnings`, `datetime` – date and warning handling

## 📈 Key Analyses & Insights
🔍 1. Churn Distribution & Overview

* Checked missing data, imbalance in churned vs. retained customers.

* Created distribution plots showing percentage of churn.

* Discovered majority customers are retained, but specific groups show higher churn.

👥 2. Demographic Analysis

* Grouped customers by age, gender, and state.

* Created heatmaps and bar plots to identify high-churn age segments and gender imbalances.

* Found that customers aged 30–39 and male users in certain states show higher churn.

📡 3. Usage Behavior Analysis

* Compared average calls, SMS, and data usage across tenure bins.

* Visualized with line charts showing customer behavior over tenure.

* Identified that low-usage customers tend to churn earlier.

🗺️ 4. Regional & Partner Trends

* Grouped churn data by state, telecom partner, and year.

* Observed regional churn spikes for certain partners in specific years.

* Helps telecoms focus on targeted retention campaigns.

## 🧩 Visualizations

* Countplots for churn distribution

* Heatmaps of churn by age & gender

* Line charts for tenure vs. usage

* Bar charts of churned customers per region and partner

* Year-wise trend lines for partner churn per state

## 🔬 Research Questions
| #     | Research Focus      | Description                                                    |
| ----- | ------------------- | -------------------------------------------------------------- |
| **1** | Demographic Factors | How age, gender, and state affect churn                        |
| **2** | Behavioral Patterns | Relationship between churn and service usage                   |
| **3** | Regional Trends     | How churn varies across states and telecom partners over years |

## 📊 Results Summary

* Certain states consistently exhibit higher churn rates.

* Lower tenure and lower engagement (usage) are strongly correlated with churn.

* Partner-specific churn spikes highlight operational or service-related issues.

* Insights provide a data-driven foundation for customer retention strategies.

## 🧩 How to Run

1. Clone this repository

```
git clone https://github.com/PriyanshuSamanta/Analyzing-Customer-Churn-in-Telecommunications-Insights-from-Data-Patterns-and-Trends.git
cd Analyzing-Customer-Churn-in-Telecommunications-Insights-from-Data-Patterns-and-Trends
```

2. Install required libraries

```
pip install pandas numpy matplotlib seaborn
```

3. Run the notebook in Jupyter or Google Colab
```
jupyter notebook "Analyzing Customer Churn in Telecommunications.ipynb"
```

4. Upload the dataset telecom_churn.csv in the same directory.

## 📘 Future Work

* Predict churn using Machine Learning models (Logistic Regression, Random Forest)

* Apply Feature Importance and SHAP explainability

* Build interactive dashboards for churn visualization

```
 👤 Author

Priyanshu Samanta

GitHub: https://github.com/PriyanshuSamanta

LinkedIn: www.linkedin.com/in/priyanshu-samanta-5542b923a

Email: priyanshusamanta101@gmail.com
```


## ⭐ If you found this helpful, give this repo a star!

“Turning data into insight is the first step to customer retention.”
