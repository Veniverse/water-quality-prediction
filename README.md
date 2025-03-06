# water-quality-prediction
📌 Project Overview
This project analyzes water quality based on various physicochemical parameters and predicts whether water is potable using machine learning models. The dataset is preprocessed, visualized, and evaluated with different classification algorithms to determine the best-performing model.

📂 Dataset
The dataset contains key water quality parameters, including:

pH (Acidity or Alkalinity of water)
Hardness (Dissolved calcium and magnesium in water)
Solids (Total dissolved solids in water)
Chloramines (Presence of chlorine compounds)
Sulfate (Sulfate concentration in water)
Conductivity (Ability of water to conduct electricity)
Organic Carbon (Organic matter present in water)
Trihalomethanes (Chemical by-products in chlorinated water)
Turbidity (Clarity of water)
Potability (Target variable: 0 = Not Potable, 1 = Potable)

🔍 Exploratory Data Analysis (EDA)
Handled missing values by filling them with the mean.
Visualized data distributions and relationships between variables.
Analyzed feature correlations using heatmaps, histograms, scatter plots, and pair plots.
Identified trends in potable vs. non-potable water samples.

📊 Data Preprocessing
Filled missing values with column mean.
Partitioned dataset into training (80%) and testing (20%) sets.
Standardized the data before applying machine learning models.

⚙️ Machine Learning Models
Two classification models were implemented:

Decision Tree Classifier

Criterion: gini
Min samples split: 10
Accuracy: 58.53%
K-Nearest Neighbors (KNN)

Metric: manhattan
Number of Neighbors: 22
Accuracy: 61.7%

🚀 Conclusion: The KNN model performed better, achieving a higher accuracy compared to the Decision Tree model.

📜 Key Results
KNN outperformed Decision Tree in water quality classification.
pH, hardness, and conductivity had strong correlations with potability.
Missing values had to be carefully handled to avoid biased predictions.

🤝 Contributing
Feel free to fork this repository, improve the model, and submit a pull request!

📌 Author: Veni R
