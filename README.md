# Machine Learning Practice

Jupyter notebooks covering core supervised and unsupervised learning techniques with scikit-learn.

| Notebook | Topics | Data |
| --- | --- | --- |
| `01_linear_regression_height_weight.ipynb` | Exploratory analysis, correlation, train/test split, feature scaling, simple linear regression | `height_weight_data.xlsx` |
| `02_regression_decision_trees_clustering.ipynb` | Good vs bad fit and R², multiple regression, polynomial regression, decision trees, confusion matrix, hierarchical clustering | `cars.csv`, `comedy.csv` |
| `03_logistic_regression_breast_cancer.ipynb` | Logistic regression and confusion-matrix evaluation | scikit-learn breast cancer dataset |

## Run locally

```bash
python -m venv venv
source venv/bin/activate        # Windows: venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```
