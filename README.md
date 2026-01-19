# A-B Testing & Regression Analysis

**A/B Testing and Regression Analysis Project** using Python in a Google Collab. The goal is to evaluate whether a change in a system (like a web page or marketing campaign) leads to a significant improvement in a key metric (like conversion rate), and then to apply regression techniques to model relationships between variables.

A/B testing is a statistical method used to compare two versions of something — often a control and a treatment — to determine which performs better. Regression analysis helps quantify the effect of one or more predictors on a target outcome. :contentReference[oaicite:0]{index=0}

## 🧠 Objectives

* Perform an A/B test to determine if there is a statistically significant difference between control and treatment groups.
* Use regression analysis to model the relationship between variables and understand their impacts.
* Visualize results and interpret statistical findings.
* Provide clear insights and recommendations based on the analysis.

## 🛠️ Tools & Technologies

* **Programming Language:** Python  
* **Environment:** Jupyter Notebook  
* **Libraries & Packages:**
  * pandas
  * numpy
  * matplotlib / seaborn
  * statsmodels
  * scipy

## 📌 Project Steps

### 1. **Data Loading & Cleaning**
* Load raw dataset containing user metrics, conversion flags, and group assignments.
* Handle missing values or duplicates.
* Ensure correct alignment of control/treatment groups with corresponding pages or variants.

### 2. **Exploratory Data Analysis (EDA)**
* Summarize dataset properties (counts, means, distributions).
* Visualize key variables and group differences.
* Check group sizes and conversion distributions.

### 3. **A/B Testing**
* Formulate the null and alternative hypotheses.
* Use statistical tests (like **z-test** or **chi-square**) to compare conversion rates between groups.
* Compute p-values and confidence intervals.
* Interpret results — determine if the difference is statistically significant.

### 4. **Regression Analysis**
* Fit a regression model (e.g., logistic or linear regression) to model the influence of features on outcomes.
* Analyze model coefficients to understand variable importance.
* Evaluate model performance.

### 5. **Results & Interpretation**
* Summarize whether the new variant outperformed the control.
* Provide practical recommendations based on statistical evidence.

## 🧪 Example Hypothesis

**Null Hypothesis (H0):** There is no difference in conversion rates between the control and treatment groups.  
**Alternative Hypothesis (H1):** The treatment group has a different (e.g., higher) conversion rate than the control group.

Interpretation is based on whether the p-value is less than a significance level (e.g., 0.05). :contentReference[oaicite:1]{index=1}

## 📈 Sample Output (What to Expect)

* Conversion rate comparison chart between control vs. treatment
* Statistical test result with z-score and p-value
* Regression model summary and interpretation
* Insights and business recommendations

## 🛠️ How to Run

1. Clone this repository:
   ```bash
   git clone https://github.com/Puja29D/A-B-Testing-Regression-Analysis.git


