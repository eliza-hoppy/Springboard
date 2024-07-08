## This is a README

### Problem Statement 
Food safety has become top of mind for many food establishments following the SARS-CoV-2 
outbreak in 2020. Despite food establishments’ current interest in improving this aspect of 
their operations, it remains a challenge area for them. 
Food service establishments are run by franchisees, corporate offices, or sole owners. The
myriads of ownerships in franchises and corporate establishments means management 
varies at the store level even within a single company; despite having knowledgeable food 
safety teams within the corporate company structure, this does not translate to successful 
implementation of hygiene procedures for food safety at the store level. For locations where 
there is a sole owner (one owner-one shop e.g. ‘mom-and-pop’ stores), sometimes there is a 
lack of food safety expertise. These factors contribute to establishments incurring health 
department violations and low inspection scores.
This analysis attempted to predict inspection scores based on health inspection comments 
and store information. Some questions which were explored were:
- Determine the most frequent health department violation in establishments
- Predict health department scores or the next violation based on establishment 
information and inspection comments
- Find opportunities for improvement for the 5 worst performing food service 
establishments.

### Data Sources
 - [Food-inspection-violations_1.json](https://data.world/durhamnc/violation-data)
 - [Restaurant-and-services_3.json](https://data.world/durhamnc/restaurants-data)
 - [Food-health-inspections_3.csv](https://www.kaggle.com/datasets/thedevastator/durham-county-food-inspections/?select=food-health-inspections_2.csv)
-  [Durham_County_Boundary.shp](https://live-durhamnc.opendata.arcgis.com/datasets/DurhamNC::durham-county-boundary/explore?location=36.050399%2C-78.857400%2C9.95)

### Models
Supervised machine learning approachers were used to predict inspection scores. Support vector regression, random forest regression, and xgboost regression were used for modeling. Both RandomizedSearchCV and Bayes Optimization were tested for hyperparameter tuning.

### Jupyter Notebooks
Notebooks for each step of the analysis process are below.
- [Data Wrangling](https://github.com/eliza-hoppy/-Capstone-Two-Github-Repo/blob/main/Capstone_Two_Data_Wrangling_Durham_County_Health_Inspection_ipynb_FINAL_11_29_23.ipynb)
- [Exploratory Data Analysis](https://github.com/eliza-hoppy/Springboard/blob/main/Capstone_2_Exploratory_Data_Analysis/Capstone_Two__Exploratory_Data_Analysis_Durham_County_Health_Inspection.ipynb)
- [Preprocessing and Training Data Development](https://github.com/eliza-hoppy/Springboard/blob/main/Capstone_2_Exploratory_Data_Analysis/Preprocessing_Training_Data_Development/Capstone_Two_Preprocessing_and_training_Data_Development-FINAL.ipynb)
- [Modeling](https://github.com/eliza-hoppy/Springboard/blob/main/Capstone_Two_Modelling/Capstone_2_Food_Inspection_Score_Modelling.ipynb)

### Documentation
- [Project Report](https://github.com/eliza-hoppy/Springboard/blob/main/Capstone_2_Report_Copy/Capstone_2_Durham_Inspection_Report.pdf)
- [Project Presentation](https://github.com/eliza-hoppy/Springboard/blob/main/Capstone_2_Report_Copy/Capstone_Two_Prediction_of_Durham_County_Department_of_Health_Inspection_Scores.pdf)
