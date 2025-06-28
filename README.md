# codealpha_tasks

Project Overview

The goal is to demonstrate the full life‑cycle of an applied data‑science project—data loading, preprocessing, model training, evaluation, and a simple user interface—while remaining accessible to first‑time machine‑learning practitioners.  
The project is implemented in a single Jupyter notebook so that the entire workflow can be executed and inspected cell by cell.
## Dataset

| File name                 | Purpose                                                         |
|---------------------------|-----------------------------------------------------------------|
| `dataset.csv`             | Primary training data: 17 symptom columns and one `Disease` label |
| `Symptom-severity.csv`    | Maps each symptom to an integer weight (severity)               |
| `symptom_Description.csv` | One‑sentence description for every disease                      |
| `symptom_precaution.csv`  | Up to four recommended precautions for every disease            |

All files are included in the repository and originate from publicly available medical‑symptom datasets on Kaggle.

## Key Features

* **Random Forest classifier** trained on 17 input symptoms  
* **Fuzzy symptom matching** (RapidFuzz) corrects typos and minor spelling errors  
* Command‑line interface accepting up to five symptoms per prediction  
* Outputs disease name, short description, and a numbered list of precautions  
* Fully reproducible Jupyter notebook (`Disease_Prediction_Model.ipynb`)

  ## Software Stack

* Python 3.8   
* pandas  
* scikit‑learn  
* RapidFuzz (for fuzzy matching)  
* Jupyter Notebook
