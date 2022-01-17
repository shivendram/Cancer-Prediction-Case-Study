Source: https://www.kaggle.com/c/msk-redefining-cancer-treatment/data
We have two data files: one conatins the information about the genetic mutations and the other contains the clinical evidence (text) that human experts/pathologists use to classify the genetic mutations.
Both these data files are have a common column called ID
Data file's information:
training_variants (ID , Gene, Variations, Class)
training_text (ID, Text)
There are nine different classes a genetic mutation can be classified into => Multi class classification problem
Objective: Predict the probability of each data-point belonging to each of the nine classes.
