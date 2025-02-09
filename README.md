### **Laptop Price Prediction Using Machine Learning**

This project uses regression techniques to predict laptop prices based on configurations, including Linear Regression, SVR, and Random Forest. The Random Forest model was the most effective, achieving an R-squared score of **88.24%**.


#### **Table of Contents**

1. Project Overview

2. Data Overview

3. Steps to Run

4. Results

5. Technologies Used

6. Key Insights

7. Contact

**Project Overview**

The aim of this project is to predict laptop prices based on specifications like processor, RAM, GPU, and screen type. It explores regularized regression techniques such as L1 (Lasso), L2 (Ridge), Elastic Net, Support Vector Regression (SVR), and Random Forest to identify the best predictive model.

This project was part of a college assessment for the module “Applied Statistics and Machine Learning” and adheres to rigorous data preprocessing, modeling, and evaluation standards.

**Data Overview**

- **Dataset:** Contains 1,721 rows and 23 columns, including input features like RAM, CPU, GPU, and an output feature: Price\_euros.

- **Source:** The dataset contains information on laptop specifications collected from various manufacturers.

- **Key Features:**

  - **Numerical Attributes:** RAM, Weight, CPU\_freq, etc.

  - **Binary Attributes:** Touchscreen, RetinaDisplay, etc.

  - **Categorical Attributes:** Company, TypeName, OS, GPU\_company, etc.

- **Processing Steps:**

1. **Encoding:** Target encoding, one-hot encoding, and ordinal encoding based on feature type.

2. **Scaling:** StandardScaler to normalize data for machine learning models.

3. **Dimensionality Reduction:** PCA (Principal Component Analysis) to reduce dimensionality and improve model performance.

**Steps to Run**

To replicate this project, follow these steps:

1. Clone the repository:

git clone https://github.com/shudhanshudesai/Laptop-Price-Prediction-Model.git

2. Navigate to the project directory:

cd Laptop-Price-Prediction-ML

3. Install the required Python libraries:

pip install -r requirements.txt

4. Open the Jupyter notebook:

jupyter notebook laptop\_price\_prediction.ipynb

5. Run the notebook to:

- Preprocess the dataset.

- Train regression models (Linear Regression, SVR, and Random Forest).

- Evaluate model performance.

- Predict laptop prices using new input data.

**Results**

- **Best Model:** Random Forest Regressor

- **R-squared Score:** 88.24%

- **Example Prediction:**

  - **Input:** \['Apple', 'Ultrabook', 16GB RAM, Intel Core i7, Retina Display, etc.]

  - **Predicted Price:** €3137.12

The Random Forest model outperformed Linear Regression (Elastic Net) and Support Vector Regression (SVR) by capturing non-linear relationships in the data.

**Technologies Used**

- **Programming Language:** Python

- **Libraries:**

  - Data Processing: Pandas, NumPy

  - Visualization: Matplotlib, Seaborn

  - Machine Learning: Scikit-learn

  - **Tools:** Jupyter Notebook, Google Colab

**Key Insights**

1. **Data Preprocessing Matters:** Encoding, scaling, and dimensionality reduction (PCA) significantly improved model performance.

2. **Random Forest is Superior:** Captured non-linear relationships better than other models, achieving the highest R-squared score.

3. **Elastic Net’s Balance:** Combined L1 (interpretability) and L2 (performance) regularizations effectively, making it a strong alternative for simpler models.

4. **SVR’s Trade-offs:** Although SVR captured non-linear patterns, its interpretability is limited compared to Random Forest and Elastic Net.

**Contact**

- **Name:** Shudhanshu Ashish Desai

- **LinkedIn:** https://www.linkedin.com/in/shudhanshu-ashish-desai/

- **Email:** shudhanshudesai10@gmail.com

**License**

This project is licensed under the MIT License - see the LICENSE file for details.

Copy this into a README.md file, and it will work perfectly as markdown.
