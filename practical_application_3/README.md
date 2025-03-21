Folder parctical_application_3 contains:
  1) Data folder that contains the bank-additional-full.csv file
  2) Images folder that contains the plotted graphs for the independent investigation.
  3) application jupyter notebook that contains the code. Link: https://github.com/saianithab/learn_ml/blob/main/practical_application_3/application.ipynb
 

 Business Problem:
 The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed. 
 
 Goal:
 The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

Findings:
Trained the data on the models = ['Decision Tree', 'Random Forest', 'Tuned Decision Tree', 'Tuned Random Forest', 'Decision Tree (Over)', 'Random Forest (Over)', 'KNN', 'SVM']

1) Accuracy of the 4 types of models were not drastically different with KNN , Random Forest and SVM peforming slightly better.
2) Recall of SVM model was largely better than the other models which means it was able to correctly predict positives.
3) F1 score of SVM model was largely better than the other models which means it performed the best amongst other models overall.

Overall, I think SVM outperformed other models.

