# Veda Technology Internship — Task 31
## Features and Target Selection (Iris Dataset)

This beginner-friendly project demonstrates how to identify input features (`X`) and a target variable (`y`) for a supervised machine-learning task.

### Dataset
The Iris dataset is provided by scikit-learn, so no separate CSV download is required. It contains 150 flower observations, four numeric measurements, and three species classes.

### Selected columns
**Features (`X`)**
- `sepal length (cm)`
- `sepal width (cm)`
- `petal length (cm)`
- `petal width (cm)`

**Target (`y`)**
- `species` (the flower species label)

The measurements are model inputs. The species label is what the model would attempt to predict, so it must not be included among the input features.

### Files
- `Task_31_Features_and_Target_Selection.ipynb` — runnable Jupyter Notebook
- `project_report.pdf` — project report
- `requirements.txt` — Python dependencies

### Run the project
1. Install Python 3.9 or newer.
2. (Recommended) Create and activate a virtual environment.
3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
4. Launch Jupyter:
   ```bash
   jupyter notebook
   ```
5. Open `Task_31_Features_and_Target_Selection.ipynb` and run all cells from top to bottom.

### Expected outcome
The notebook prints the dataset shape, lists selected features and target, checks for missing values, and displays sample rows. It also includes a small optional train/test split demonstration to show how `X` and `y` are used.

### Interview questions
- **What is a feature?** An input variable used by a model to make predictions.
- **What is a target variable?** The output label/value the model is trained to predict.
- **What is the difference between X and y?** `X` contains input features; `y` contains the target.

### Notes
This task focuses on feature/target selection, not on claiming a trained model achieves any particular accuracy. The optional split is only a demonstration.
