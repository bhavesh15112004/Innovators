# Innovators
This repository contains Jupyter Notebook containing the codes to predict sea surface temperatures due to the El Niño-Southern Oscillation (ENSO). This model is trained using the train.csv file.
## Authors
Shreya S Bhat </br>
Bhavesh Mali </br>
Aaditya Jadhav </br>
## File Descriptions
- **training_model_and_predicting.ipynb**: Contains the code used for training our model, and also to predict the SST for evaluation.csv and data_1997_1998.csv using the trained model. </br>
- **evaluation_with_predictions.csv**: The predicted SST for evaluation.csv is saved here. </br>
- **data_1997_1998_with_predictions.csv**: The predicted SST for data_1997_1998.csv is saved here. </br>
## Libraries used:
- pandas </br>
- numpy </br>
- scikit-learn (sklearn) </br>
- tensorflow </br>
## Instructions
### 1. Clone the repository
```bash
git clone https://github.com/bhavesh15112004/Innovators.git
```
### 2. Install required packages: Following command can be used:
```bash
pip install -r requirements.txt
```
### 3. Run the notebook
Run the notebook to generate predictions for evaluation.csv and data_1997_1998.csv
### 4. Check the outputs
The predicted SST for evaluation.csv will be available in evaluation_with_predictions.csv </br>
The predicted SST for data_1997_1998.csv will be available in data_1997_1998_with_predictions.csv </br> 
## Notes
Ensure that the train.csv, evaluation.csv and data_1997_1998.csv files are in the same directory as the Jupyter Notebooks. 
