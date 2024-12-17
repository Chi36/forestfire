# forestfire project

**Problem Statement**: 
Wild forest fires are a major menace in many countries of the world. With each sudden fire incident, lives and property are adversely affected as well as the environment.
Accurately forecasting forest fires has become a crucial challenge as climate change worsens the conditions for wildfire occurrence and spread. Early warning systems, resource management, and successful firefighting efforts all depend on the ability to forecast the onset, spread, and magnitude of forest fires in real-time. While useful, existing forest fire prediction techniques have limitations with precision, scalability, and prompt deployment. Predicting the precise location, timing, and modes of forest fires is difficult because forest fire depends on a number of variables, notably geography, vegetation type, weather, and human activity. Therefore, a sophisticated, data-driven approach is required to accurately forecast forest fires. To address this challenge, openly sourced datasets were used to create a GUI that can predict possible forest fire occurrence. The data-driven insighhts from the project

**Input and Output Variables**: 
The inputs of the dataset include Temperature, Humidity, Wind Speed, Rainfall, Moisture, Vegetation Type and Region. The targets (output) are Fire Size, Suppression Cost, Fire Occurrence.

**Machine Learning Algorithm(s)**: 
Regression models such as Support Vector Regression (SVR), Random Forest, Linear Regression and KNN were applied. The classification models used are RandomForestClassifier, Logistic Regression, SVC and KNN Classifier.

**Ethics Considerations**: Include a link to your completed DataCards and Deon checklist to ensure ethical practices were followed.

**Graphical User Interface (GUI)**: (https://huggingface.co/spaces/Frankie89/forestfire1)

**Dataset**: Clearly specify the dataset used, including its source and any preprocessing steps applied.

**Project Details**: 
This predicts forest fires in a given region based on the available datasets.Load datasets, separate numerical and categorical variables. Next, handle missing values and perform One-Hot Encoding for categorical variables. Drop original columns and concatenate encoded ones. Now, split datasets into inputs (x) and targets (y). Perform one-Hot encoding on the output variables if categorical (ensure that features are numeric). Define the models used, train and select the best model. Define Gradio app and interface. Finally push to Hugging Face and move to GitHub. 


**The names of the author and the instructor**:                  Chimezie Frank Onwudinjo,  Dr. Jude A. Okolie                                                                                                                     
**Your department and university information**:                  Chemical Engineering Departmnent, Bucknell University

**Course Code**:                                                 CHEG 672 (Data Science in Chemical Engineering)
