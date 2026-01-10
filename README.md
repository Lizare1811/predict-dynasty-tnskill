Predict Dynasty – TNSkill Project

1)This project predicts the historical dynasty of Indian monuments based on architectural and historical features using a Random Forest Classifier. 
2)It demonstrates machine learning concepts such as categorical feature encoding, model training, and prediction with real-world historical data.

Project Files`predict_dynasty.py` – Python script to make predictions based on user input  
`monuments.csv` – Dataset containing monuments and their features  
`README.md` – This file  

Dataset Features

The dataset includes the following columns:

   Feature                  Description

Monument_Type         Type of the monument (Temple, Fort, etc.) 
Year_Built            Year when the monument was built
Patron_Ruler          Ruler or dynasty that commissioned the monument 
State                 Indian state where the monument is located 
Architectural_Style   Style of architecture of the monument 
Mterial               Primary construction material 
Religion              Religion associated with the monument 
Dynasty               Target variable: Dynasty the monument belongs to 

Categorical features are label-encoded for training the ML model.

How to Run

1. Ensure `predict_dynasty.py` and `monuments.csv` are in the same folder.  
2. Open a idle and choose the file
3. Run the Python script: python predict_dynasty.py
4. Enter the requested inputs:
Enter Monument_Type_Label: 2
Enter Year_Built: 1570
Enter Patron_Ruler_Label: 1
Enter State_Label: 3
Enter Architectural_Style_Label: 2
Enter Material_Label: 0
Enter Religion_Label: 1

Predicted Dynasty: Vijayanagar

Notes:
The example above shows one possible input; the output will vary depending on the values entered.
All categorical features (Monument Type, Patron Ruler, State, Architectural Style, Material, Religion) are label-encoded for the model.
The target variable, Dynasty, is also encoded and decoded back to its original name using LabelEncoder.inverse_transform.
Ensure predict_dynasty.py and monuments.csv are in the same folder when running the script.
This project was completed as part of the TNSkill-Vetri Nichayan Machine Learning program.
