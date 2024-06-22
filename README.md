# Innovators
This repository contains Jupyter Notebooks containing the codes to predict sea surface temperatures due to the El Niño-Southern Oscillation (ENSO). This model is trained using the train.csv file.
## Authors
Shreya S Bhat </br>
Bhavesh Mali </br>
Aaditya Jadhav </br>
## File Descriptions
Here is a list of files in the repository along with their descriptions:
- **training_model.ipynb**: Contains the code used for training our model. </br>
- **predicting_values.ipynb**: Contains the code to predict the SST for evaluation.csv and data_1997_1998.csv using the trained model. </br>
- **trained_model.joblib**: The trained Random Forest Regressor model. </br>
- **evaluation_with_predictions.csv**: The predicted SST for evaluation.csv is saved here. </br>
- **data_1997_1998_with_predictions.csv**: The predicted SST for data_1997_1998.csv is saved here. </br>
## Libraries used:
- pandas </br>
- numpy </br>
- scikit-learn (sklearn) </br>
- tensorflow </br>
## Instructions
### 1. Clone the repository
bash git clone
### 2. Install required packages: Following command can be used:
```bash
pip install -r requirements.txt
```
### 3. Run the notebooks
## Notes
Ensure that the train.csv, evaluation.csv and data_1997_1998.csv files are in the same directory as the Jupyter Notebooks. 
