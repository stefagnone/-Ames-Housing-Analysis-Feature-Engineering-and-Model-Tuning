## Project Overview
This repository combines two related projects focusing on housing price predictions using the Ames Housing Dataset. The first project emphasizes innovative **feature engineering** to create new variables for enhanced predictive power. The second project applies a **Stochastic Gradient Descent Regression (SGD)** model with rigorous hyperparameter tuning to evaluate model performance and provide actionable insights.

### Objectives:
1. **Feature Engineering**:
   - Engineer three unique features that add predictive value to housing price models.
   - Explore the correlative impact of these features on the response variable (Sale Price).

2. **Model Tuning**:
   - Develop a Stochastic Gradient Descent Regression model.
   - Conduct hyperparameter tuning to optimize predictive accuracy.
   - Evaluate and interpret model metrics, including R-squared and residual error.

---

## Technologies Used
- **Python**:
  - Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`
- **Jupyter Notebook**: Analysis and modeling workflows
- **Excel**: Dataset preparation and visualization

---

## Repository Structure
- **/data**:
  - `AmesHousing.csv`: The original Ames Housing Dataset.
- **/notebooks**:
  - `Feature_Engineering_Ames.ipynb`: Notebook detailing the feature engineering process.
  - `Model_Discovery_and_Tuning.ipynb`: Notebook with model tuning and evaluation steps.
- **/documentation**:
 - `Model_Discovery_and_Tuning.html`: Html File with model tuning and evaluation steps.

---

## Key Insights
1. **Feature Engineering**:
   - Engineered features (e.g., Lot Frontage Ratio, Age of Home, and Neighborhood Premium Index) showed significant positive correlations with housing prices.
   - Practical real-world implications, such as identifying neighborhoods with higher premiums or properties with favorable characteristics.

2. **Model Performance**:
   - The SGD model achieved strong predictive performance with optimal hyperparameters.
   - Hyperparameter tuning minimized overfitting and balanced R-squared values between training and testing sets.

3. **Actionable Insights**:
   - High-performing neighborhoods can be targeted for investment or development.
   - Importance of engineered features in capturing nuanced patterns in real estate data.

---

## Instructions
### Requirements
- Python 3.8+
- Libraries: `pandas`, `numpy`, `scikit-learn`, `matplotlib`, `seaborn`

### Running the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/stefagnone/Ames-Housing-Feature-Engineering-and-Model-Tuning.git
   cd Ames-Housing-Feature-Engineering-and-Model-Tuning
