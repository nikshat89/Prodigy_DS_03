🧠 Decision Tree Classifier: Bank Marketing Campaign
📌 Overview
This project uses a Decision Tree Classifier to predict whether a customer will subscribe to a term deposit based on their demographic and behavioral data. The model is trained and tested on the Bank Marketing Dataset from the UCI Machine Learning Repository.

📂 Dataset
Source: Bank Marketing Data Set – UCI ML Repository

Format: CSV (semicolon-separated)

Description: Contains 45,211 records and 17 attributes related to customer data, call outcomes, and subscription status.

🔍 Objective
Preprocess and encode categorical data.

Train a Decision Tree Classifier on customer features.

Evaluate performance using accuracy, classification report, and confusion matrix.

Visualize the decision tree and results.

📊 Features
Demographic: age, job, marital status, education

Financial: default, housing loan, personal loan

Call Information: contact method, duration, campaign details

Outcome: previous marketing outcome, subscription (y)

🛠️ Tools & Libraries
pandas – data manipulation

numpy – numerical operations

seaborn & matplotlib – data visualization

scikit-learn – model training, encoding, evaluation

📈 Output-
✔️ Model Accuracy
📄 Classification Report (Precision, Recall, F1-score)
📉 Confusion Matrix Heatmap
🌳 Decision Tree Visualization

🔍 Sample Results
Accuracy: ~88% (varies depending on tree depth)

Top Features: duration, contact, month, poutcome

📌 Visualization Preview

🧠 Insights
Decision Trees offer interpretable results and visual flow of decision logic.

duration and contact type have significant impact on subscription decisions.

The model can be improved with pruning, ensemble methods, or cross-validation.

