# Machine Learning Analysis on Airlines Dataset

# NOTE For full analysis, please refer the jupyter notebook file in the repo, thank you
## Objective
The objective of this work is to implement classic machine learning algorithms for classification, clustering, regression, dimension reduction, and ensembles. The analysis will be performed on a dataset from the CORGIS collection project, specifically the airlines dataset.

## Dataset
The dataset chosen for this analysis is the airlines dataset from the Corgis project. It provides information about airline flights including various features such as departure and arrival times, carrier information, and delays.
Additional information regarding the dataset can be found here 

## Analysis Workflow
1. **Visual Analysis in Excel:**
   - The initial step involved performing visual analysis of the dataset using Excel. This allowed for a preliminary understanding of the data's structure, patterns, and potential insights.

2. **Data Preprocessing and Analysis in Python:**
   - Next, the dataset was loaded into Python for further analysis and preprocessing.
   - Various machine learning algorithms were implemented using Python libraries such as scikit-learn and TensorFlow.

## Repository Structure
- `data/`: Contains the airlines dataset in CSV format.
- `notebooks/`: Jupyter notebooks documenting the analysis process.
- `scripts/`: Python scripts for preprocessing and implementing machine learning algorithms.
- `README.md`: Detailed documentation providing an overview of the project, analysis workflow, and instructions for reproducing the results.

## Usage
To replicate the analysis or experiment with the code:
1. Clone the repository to your local machine.
2. Navigate to the repository directory.
3. Install the required dependencies specified in `requirements.txt`.
4. Explore the Jupyter notebooks in the `notebooks/` directory for detailed analysis.
5. Experiment with the provided Python scripts for preprocessing and implementing machine learning algorithms.

## Results
The findings of the analysis, including insights, model performances, and any conclusions drawn, will be documented within the Jupyter notebooks and summarized in the README.
## Data Preprocessing

To streamline the dataset for analysis, the following preprocessing steps were performed:

### Dropping Redundant Columns

1. **Time-related Columns:**
   - Since the `Time.label` column provides all necessary information about the time of the flight status, the following redundant columns were dropped:
     - `Time.Month`
     - `Time.Month Name`
     - `Time.Year`
   ```python
   df.drop(columns=['Time.Month', 'Time.Month Name', 'Time.Year'], inplace=True)
   
## Some analysis that were done through this project 

<img width="655" alt="Screenshot 2024-02-23 at 2 25 52 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/48fc0062-dc13-44dd-bf95-78e2e1f10212">

<img width="920" alt="Screenshot 2024-02-23 at 2 26 04 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/8fb56044-266f-4122-8478-3f5d5d6aa0c7">
<img width="954" alt="Screenshot 2024-02-23 at 2 26 14 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/d365f61c-1675-4cb4-8cac-c3238edc99ad">
<img width="916" alt="Screenshot 2024-02-23 at 2 26 27 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/5f2893e9-4f37-4431-bcdc-f4fcb36cfdcb">
<img width="934" alt="Screenshot 2024-02-23 at 2 26 37 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/2d61393b-17f9-4bcb-ac73-6b50b159f8b7">
<img width="910" alt="Screenshot 2024-02-23 at 2 26 49 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/a8d738be-4f8f-42ac-ae07-045d6130bf54">
<img width="780" alt="Screenshot 2024-02-23 at 2 26 57 PM" src="https://github.com/Sathyanarayanan-ops/FlightdataEDA/assets/57038667/6e93f07e-2d9b-4765-a2f1-8a0ad486970c">

