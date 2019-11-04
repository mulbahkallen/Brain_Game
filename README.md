# Brain_Game
Detection of acute intracranial hemorrhage and subtypes

RSNA Intracranial Hemorrhage Detection
Detection of Acute Intracranial Hemorrhage and it's Subtypes 

Modules 4 Project
The Project
Intracranial hemorrhage, bleeding that occurs inside the cranium, is a serious health problem requiring rapid and often intensive medical treatment. 
For example, intracranial hemorrhages account for approximately 10% of strokes in the U.S., where stroke is the fifth-leading cause of death. 
Identifying the location and type of any hemorrhage present is a critical step in treating the patient.

Diagnosis requires an urgent procedure. When a patient shows acute neurological symptoms such as severe headache or loss of consciousness, 
highly trained specialists review medical images of the patient’s cranium to look for the presence, location and type of hemorrhage. 
The process is complicated and often time consuming.


Mulbah Kallen

Methods & Techologies Used
Descriptive statistics
Python Pandas

DICOM Images
All provided images are in DICOM format. DICOM images contain associated metadata. 
This include PatientID, StudyInstanceUID, SeriesInstanceUID,....  

What am I predicting?
Predicting whether a hemorrhage exists in a given image, and what type it is.

File descriptions
stage_1_train.csv - the training set. Contains Ids and target information.
stage_1_sample_submission.csv - a sample submission file in the correct format. Contains Ids for the test set.

Data fields
Id - An image Id. Each Id corresponds to a unique image, and will contain an underscore .
Label - The probability of whether that sub-type of hemorrhage (or any hemorrhage in the case of any) exists in the indicated image.


Presentation Method
Canva presentation tool

Methodology & Basis for Project
Exploratory Project to gain a deeper understanding on Deep Learning 


Project Steps
1. Import/Load Data
2. Import relevant Libraries
3. Check images/Visualization
    Visualization of hemorrhage epidural
    Visualization of hemorrhage Intraparenchymal
    Visualization of hemorrhage Intraparenchymal
    Visualization of hemorrhage Subarachnoid
    Visualization of hemorrhage subdural
4. Create baseline model 
5. Evaluate model 
6. Make adjustments 
7. Summarize findings a) Finalize visualizations b) Create powerpoint

Deliverables
Kaggle/Juypter/Google CoLab Notebooks

0-TMDB API Collecting.ipynb This notebook contains the code for obtaining data from both the tmdb discover API and tmdb movie id API.
1-brain.ipynb base model/filtering(windowing) of dataset/visulizations.

Data
stage_1_train.csv - the training set. Contains Ids and target information.
stage_1_sample_submission.csv - a sample submission file in the correct format. Contains Ids for the test set.

Others
Canva Presentation link Summary of our finding in a presentation.
