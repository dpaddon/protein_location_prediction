# Predicting the subcellular location of eukaryotic proteins

Subcellular localisation of proteins is an important task in bioinformatics, and one for which machine learning techniques are ideally suited to solving. 

In this project, open-source machine learning classification tools (BioPython and scikit-learn) are used in order to predict the location of 20 "blind" test proteins as either Nuclear, Secreted, Mytochondrial, or Cytosolic. Examples of proteins belonging to each of the four classes, and the 20 unkown proteins, can be found in the Data directory.

An accuracy of around 60% is achieved on a held-out validation set, with the results for the blind set shown at the bottom of the notebook.
