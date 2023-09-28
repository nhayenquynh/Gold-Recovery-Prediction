## Sprint_10_Project

# Gold-Recovery-Prediction
<img width="613" alt="image" src="https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/ab417d56-7e20-4dcc-bc63-b7f7d8879ad0">

Stages of gold purification

# Task Description:

Prepare a prototype of a machine learning model for Zyfra. The company develops efficiency solutions for heavy industry.

The model should predict the amount of gold recovered from gold ore. You have the data on extraction and purification.

The model will help to optimize the production and eliminate unprofitable parameters.
You need to:

1. Prepare the data;
2. Perform data analysis;
3. Develop and train a model.
   
To complete the project, you may want to use documentation from pandas, matplotlib, and sklearn.

# Project Instructions & Questions to Answer:

1. Prepare the data
   
   1.1. Open the files and look into the data.

Path to files:

-/datasets/gold_recovery_train.csv

-/datasets/gold_recovery_test.csv

-/datasets/gold_recovery_full.csv

   1.2. Check that recovery is calculated correctly. Using the training set, calculate recovery for the rougher.output.recovery feature. Find       the MAE between your calculations and the feature values. Provide findings.
   
   1.3. Analyze the features not available in the test set. What are these parameters? What is their type?
   
   1.4. Perform data preprocessing.

2. Analyze the data
   
   2.1. Take note of how the concentrations of metals (Au, Ag, Pb) change depending on the purification stage.
   
   2.2. Compare the feed particle size distributions in the training set and in the test set. If the
   distributions vary significantly, the model evaluation will be incorrect.
   
   2.3. Consider the total concentrations of all substances at different stages: raw feed, rougher concentrate, and final concentrate. Do you       notice any abnormal values in the total distribution? If you do, is it worth removing such values from both samples? Describe the findings       and eliminate anomalies.

3. Build the model
   
   3.1. Write a function to calculate the final sMAPE value.
   
   3.2. Train different models. Evaluate them using cross-validation. Pick the best model and test it using the test sample. Provide findings.

Use these formulas for evaluation metrics:

![image](https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/53d418a8-53ec-4952-94a0-545f1eadcb6b)

![image](https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/bdd4e863-3185-44a5-99ee-8d26bc3b53ca)

![image](https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/bf53fb6f-67de-4e06-87ce-23cfde0d49cc)

# Project evaluation:

- Have you prepared and analyzed the data properly?
- What models have you developed?
- How did you check the model‘s quality?
- Have you followed all the steps of the instructions?
- Did you keep to the project structure and explain the steps performed?
- What are your findings?
- Have you kept the code neat and avoided code duplication?

# Generated Plots: 
<img width="969" alt="image" src="https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/a2691a0a-39e6-4254-9e14-119f0829f443">
<img width="986" alt="image" src="https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/9657e5d7-7cad-4e49-9c3b-fe0d69d9c356">
<img width="893" alt="image" src="https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/3ea78ddf-9f45-4503-a4dd-5b01bfc77e88">

# Result: 
<img width="912" alt="image" src="https://github.com/nhayenquynh/Gold-Recovery-Prediction/assets/125513684/6bbc9888-dfb3-4ef1-90e7-e80318106fa1">


