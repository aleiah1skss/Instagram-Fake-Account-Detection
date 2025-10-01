# Instagram-Fake-Account-Detection
This project classifies Instagram accounts as genuine or fake using machine learning. It uses Python to analyze profile data like profile pictures and follower counts. A Random Forest model was built and achieved high accuracy, providing a successful method to detect spammers.
# Instagram Fake Account Classification

## Project Overview

This project focuses on building a machine learning model to classify Instagram accounts as either genuine or fake (spammers). The goal is to identify fraudulent accounts by analyzing various profile characteristics and activities.

## Dataset

The dataset used in this project was collected from Instagram and contains a variety of features related to user profiles. It is comprised of both genuine and fake accounts, which are used to train and test our classification model.

## Tools and Technologies

* **Language:** Python
* **Libraries:**
    * `pandas` for data manipulation and analysis.
    * `numpy` for numerical operations.
    * `matplotlib` and `seaborn` for data visualization.
    * `scikit-learn` for machine learning model building and evaluation.

## How to Run the Code

1.  **Clone the Repository:** Clone this repository to your local machine using `git clone [repository-url]`.
2.  **Navigate to the Directory:** Open a terminal or command prompt and change the directory to the cloned repository.
3.  **Launch Jupyter Notebook:** Run `jupyter notebook` to open the project in your browser.
4.  **Run the Notebook:** Open the `[Your-Notebook-Name].ipynb` file and run all the cells.

## Key Findings & Results

The final model successfully classified Instagram accounts with high accuracy. The analysis highlighted that several key features are strong indicators of a fake account.

**Model Performance:**

* **Accuracy:** [Your accuracy score, e.g., 94.17%]

<br>

**Confusion Matrix:**
![Confusion Matrix](link-to-your-confusion-matrix-image)

<br>

**Feature Importances:**
![Feature Importances](link-to-your-feature-importances-image)

<br>

## Future Improvements

* **Model Optimization:** Explore hyperparameter tuning to further optimize the model's performance.
* **Advanced Models:** Test more complex machine learning models like XGBoost to see if a higher accuracy can be achieved.
* **Updated Dataset:** Acquire a more recent and larger dataset to make the model more robust against new spamming techniques.
