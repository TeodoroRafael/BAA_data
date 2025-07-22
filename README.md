# BAA_data
Dataset for Bone Age Assessment using Greulich and Pyle Metrics

# Using the dataset
1. Download X_data_256.pickle and y_data.pickle files
2. Load it with Python using pickle lib
3. X_data_256 is divided into 5 folds; Each fold contains several objects, where positions 0 and 1 represent the image and the sex of the patient, respectively.
4. y_data contains 5 folds; each object in position n corresponds to an object of the same fold and position in X_data_256.
    
