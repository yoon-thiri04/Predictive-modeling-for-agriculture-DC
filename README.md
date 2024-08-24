## Project Description 
A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for his field. They've provided you with a dataset called soil_measures.csv, which contains:

`N`: Nitrogen content ratio in the soil
`P`: Phosphorous content ratio in the soil
`K`: Potassium content ratio in the soil
`pH` value of the soil
`crop`: categorical values that contain various crops (target variable).

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.

### To-Do
☑️ Build multi-class classification models to predict the type of "crop" and identify the single most importance feature for predictive performance.
- 🏴the Logistic Regression model is having difficulty converging within the default number of iterations ==> `Scaling the features`
- 🏳️If the convergence issues persist==> consider using a different model like `RandomForestClassifier`, which might not have the same convergence issues as logistic regression.

### Repo Structure
```
│
├── LICENSE
├── README.md         
├── notebook.ipynb
├── soil_measures.csv
```
