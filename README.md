# Home Credit Default Risk

## Project Overview
This project aims to classify and predict the likelihood of clients successfully repaying loans. The primary objective is to assess and determine the reliability or creditworthiness of applicants for loan repayment, distinguishing between clients to whom loans can be safely granted and those who pose a financial risk to the business.

## Challenge Statement
The problem is particularly challenging due to the unique business model: granting loans to individuals with low or no credit scores—applicants whom traditional banks would typically reject. While this approach opens opportunities to underserved populations, it also exposes the business to higher financial risk. 

By leveraging advanced predictive modeling techniques, this project seeks to mitigate risk by identifying at-risk clients, enabling the business to maximize profits and optimize lending decisions.

## Data Preparation
To ensure robust and reliable predictions, the dataset underwent comprehensive cleaning and preprocessing, including:
- Handling missing values.
- Removing near-zero variance predictors.
- Addressing multicollinearity by eliminating highly correlated predictors.
- Feature engineering to extract meaningful insights from raw data.

Key variables include:
- Credit score.
- Family income.
- Credit card balances.
- Previous loan application history.

## Modeling Approach
A variety of classification models were developed and fine-tuned to achieve the best accuracy. These models include:

### Predictive Clustering Models
- **K-Means Clustering:** Grouped applicants based on similarities to uncover patterns in repayment behavior.

### Classification Models
- **Logistic Regression:** Employed to estimate probabilities of loan repayment.
- **Decision Trees:** Provided an interpretable model for identifying high-risk applicants.
- **Naïve Bayes (Gaussian NB):** Evaluated for its efficiency on categorical and numerical variables.

### Advanced Models
- **H2O Generalized Linear Estimator:** Utilized for optimizing prediction accuracy, offering scalable and high-performance results.

## Results
The models effectively categorized clients into low-risk and high-risk groups. Among the tested approaches, the H2O Generalized Linear Estimator delivered the highest accuracy, providing actionable insights for the lending strategy.

## Conclusion
This project demonstrates the power of predictive analytics in addressing real-world financial challenges. By employing machine learning techniques, the business can make informed decisions, reducing financial risk and improving profitability while supporting underserved communities.

---

### Repository Structure
- `data/`: Raw and processed data files.
- `notebooks/`: Jupyter notebooks detailing data exploration, preprocessing, and modeling.
- `scripts/`: Python scripts for data preparation and model training.
- `reports/`: Visualization and model performance reports.

### How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Home-Credit-Default-Risk.git
   ```
2. Navigate to the project directory:
   ```bash
   cd Home-Credit-Default-Risk
   ```
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Run the analysis notebook:
   ```bash
   jupyter notebook notebooks/analysis.ipynb
   ```

### Technologies Used
- Python (pandas, scikit-learn, H2O.ai)
- Jupyter Notebook
- H2O Generalized Linear Estimator
- Data visualization tools (Matplotlib, Seaborn)

---

### Acknowledgments
Special thanks to the open-source community and datasets that made this analysis possible.


