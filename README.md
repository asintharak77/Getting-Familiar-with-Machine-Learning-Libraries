# Getting-Familiar-with-Machine-Learning-Libraries

This is a practice workbook to get familiar with basic Machine Learning.

### Questions

1. Download the 80-cereals dataset from https://www.kaggle.com/crawford/80-cereals
2. Load the dataset using pd.read_csv method
3. a. In the column "mfr", replace the column "K" as "Kellogg's", "G" as "Nestle" and all other values as "Other Brands"
   b. In the column "type", replace "C" with "Type 1" and "H" with "Type 2"
4. Visualise the count of above two features "mfr" and "type" with a bar-plot
5. Describe the five-number summary and boxplots of the features - protien, sugars, fat, carbo
6. Plot Histograms for the features - fat, carbo, sodium, fiber
7. Split the datasets into following ratios: 60:40, 70:30, 80:20. Write down what happens when you give "random_state" parameter with a constant value and what happens if you do not mention the parameter at all.
8. Apply MinMaxScaler() and StandardScaler() to the following features: calories, protien, fat, sodium, fiber, carbo, sugars.
9. Does the standard or min-max scaling make a difference in value distribution? Support your answers with some visualisations on the above dataset.
10. As an extension of 7th step, Generate a new Pandas DataFrame with the following columns based on the Training Dataset: Split Ratio | Random State | Total Number of Entries | Count of Kellogg's | Count of Nestle | Count of Other Brands
