=>Predicting Customer Purchase Using Decision Tree
This project uses a *Decision Tree Classifier* to predict whether a customer will buy a product or service based on their personal and contact data. The data comes from a real marketing campaign by a Portuguese bank.

-> Dataset Used
- File: bank-full.csv
- Source: [UCI Bank Marketing Dataset](https://archive.ics.uci.edu/ml/datasets/bank+marketing)
- Records: 45,211
- Target column: 'y'(whether the customer subscribed to a term deposit)
- Separator: ';' (semicolon)

-> What the Project Does
- Loads the full bank dataset
- Encodes the categorical columns into numbers
- Builds a Decision Tree model to predict customer behavior
- Evaluates the model using accuracy, confusion matrix, and classification report
- Shows clear visualizations like:
  - 📊 Confusion matrix heatmap
  - 🌲 Decision Tree diagram

-> Tools Used
- Python (Jupyter Notebook)
- Pandas & Seaborn (for data handling and visualization)
- Scikit-learn (for machine learning)

-> Output
Accuracy: ~89%
Classification Report:
  Precision, Recall & F1-score (higher for "No", lower for "Yes")
- ✅ Most "No" predictions are correct
- ⚠️ Some "Yes" predictions are missed due to imbalance in the dataset

->Visualizations
1. Confusion Matrix - Tells you how many predictions were right vs. wrong
2. Decision Tree Plot - Shows how the model makes decisions step-by-step

->How to Run This

1. Download the dataset: [bank-full.csv](https://archive.ics.uci.edu/ml/machine-learning-databases/00222/bank.zip)
2. Place it in the same folder as your notebook
3. Open the "Decision tree.ipynb" file using Jupyter Notebook
4. Run the cells one by one (Shift + Enter)

# SCT_DS_3
