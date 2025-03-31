### Project Title
Predicting Likelihood of Developing Cardio vascular disease.

**Author**
Saianitha Badrinath

#### Executive summary
Coronary heart disease (CHD) is the most prevalent cardiovascular condition, caused by reduced blood flow to the heart due to arterial plaque buildup. While invasive coronary angiography is the gold standard for diagnosis, it is costly and carries procedural risks. A non-invasive, computer-aided diagnostic tool that integrates results from existing tests—such as exercise electrocardiograms, thallium scintigraphy, and coronary calcification imaging—could enhance diagnostic accuracy. With further refinement, this approach has the potential to surpass angiography in effectiveness, improving patient outcomes while lowering healthcare costs. Currently, the accuracy of individual non-invasive tests ranges from 35% to 75%, but a machine-learning model combining multiple modalities could offer superior diagnostic performance without the risks of invasive procedures.

The dataset consists of 303 observations, with 13 features representing results from various non-invasive tests and patient characteristics. The target variable reflects the outcome of an invasive coronary angiogram, where 0 indicates no coronary artery disease, and 1-4 indicate increasing severity. Most studies using this dataset have focused on distinguishing between the presence (1-4) and absence (0) of CHD.


#### Rationale
Cardiovascular diseases are a leading cause of death globally. This study analyzes risk factors  to identify individuals susceptible to heart disease, enabling early intervention and lifestyle changes to reduce mortality rates.

#### Research Question
Predicting Likelihood of Developing Cardio vascular disease.

#### Data Sources
https://www.kaggle.com/datasets/cherngs/heart-disease-cleveland-uci

#### Methodology
Classfication

#### Results
Findings:
Trained the data on the models = ['Decision Tree', 'Random Forest', 'Tuned Decision Tree', 'Tuned Random Forest', 'Decision Tree (Over)', 'Random Forest (Over)', 'KNN', 'SVM']

Random Forest, SVM and Decision tree performed relatively good and almost the same.

Factors that contributed majorly to the prediction class are :
1. age: age in years
2. cp: chest pain type
3. chol: serum cholestoral in mg/dl
4. thalach: maximum heart rate achieved
5. number of major vessels (0-3) colored by flourosopy
6. hal: 0 = normal; 1 = fixed defect; 2 = reversable defectand the label

Plots avaliable for reference:
1. Model Performnce comparison.
2. Data distribution and analysis
3. Feature Importance from various models.