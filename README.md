# Supervised Learning: Mushroom categorisation

Dataset: This dataset includes descriptions of hypothetical samples corresponding to 23 species of gilled mushrooms in the Agaricus and Lepiota Family Mushroom drawn from The Audubon Society Field Guide to North American Mushrooms (1981). Each species is identified as definitely edible, definitely poisonous, or of unknown edibility and not recommended. This latter class was combined with the poisonous one. The Guide clearly states that there is no simple rule for determining the edibility of a mushroom; no rule like "leaflets three, let it be'' for Poisonous Oak and Ivy.

Objective: Can an supervised machine learning (ML) model predict edible from poisonous/unknown? 

Approach and Summary: Conducted an exploratory data analysis and cleaned data. Label encoded text variables and ran logistic regression (LR) and SVM alone. Compared results to a GridSearchCV ranking output with LR and SVM models encoded as a pipeline, with new voting classifier pipeline, to increase understanding of pipelines and GridSearchCV. Supervised ML gave strong predictions of training and test dataset. 

Tools used: Python, pandas, numpy, matplotlib, seaborn, scikitlearn, regularisation (scaling), Logistic Regression, SVM, Pipeline, Voting Classifier, GridSearchCV, KNN, Decision Tree

Files:

label_encoder ...x.. .joblib and color_ordinal_encoder.joblib - Exported encoder fits to be used for new data
scaler.pkl - Exported scaling model fits to be used for new data

stripplot . . .x. ..png, Mushroom image genaration.pptx - Used to build and display images in ipynb files

supervisedML_mushroom_DBoland_Feb25 - main code

mushrooms.csv - data input.
