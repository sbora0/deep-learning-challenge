# deep-learning-challenge
Deep Learning Challenge Assignment 21

For this assignment below are the requirements:

1. Preprocess the data.

    * Read in the charity_data.csv to a Pandas DataFrame, and be sure to identify the following in your dataset:
        * What variable(s) are the target(s) for your model?
        * What variable(s) are the feature(s) for your model?
        * Drop the EIN and NAME columns.
        * Determine the number of unique values for each column.
        * For columns that have more than 10 unique values, determine the number of data points for each unique value.
        * Use the number of data points for each unique value to pick a cutoff point to bin "rare" categorical variables together in a new value, Other, and then check if the binning was successful.
        * Use pd.get_dummies() to encode categorical variables.
        * Split the preprocessed data into a features array, X, and a target array, y. Use these arrays and the train_test_split function to split the data into training and testing datasets.
        * Scale the training and testing features datasets by creating a StandardScaler instance, fitting it to the training data, then using the transform function.

2. Complie, Train and Evaluate the model.

    * Continue using the Jupyter Notebook in which you performed the preprocessing steps from Step 1.
    * Create a neural network model by assigning the number of input features and nodes for each layer using TensorFlow and Keras.
    * Create the first hidden layer and choose an appropriate activation function.
    * If necessary, add a second hidden layer with an appropriate activation function.
    * Create an output layer with an appropriate activation function.
    * Check the structure of the model.
    * Compile and train the model.
    * Create a callback that saves the model's weights every five epochs.
    * Evaluate the model using the test data to determine the loss and accuracy.
    * Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity.h5.

3. Optimise the Model.

    * Create a new Jupyter Notebook file and name it AlphabetSoupCharity_Optimisation.ipynb.
    * Import your dependencies and read in the charity_data.csv to a Pandas DataFrame.
    * Preprocess the dataset as you did in Step 1. Be sure to adjust for any modifications that came out of optimising the model.
    * Design a neural network model, and be sure to adjust for modifications that will optimise the model to achieve higher than 75% accuracy.
    * Save and export your results to an HDF5 file. Name the file AlphabetSoupCharity_Optimisation.h5.

4. Write a Report on the Neural Network Model.


* Files Information:

    * The file "AlphabetSoupCharity.ipynb” is used to create the first model.
    * The file "AlphabetSoupCharity_Optimisation1.ipynb” is used to create the first optimisation model.
    * The file "AlphabetSoupCharity_Optimisation2.ipynb” is used to create the second optimisation model.
    * The file "AlphabetSoupCharity_Optimisation3.ipynb” is used to create the third optimisation model.
    * All the saved h5 files reside in "h5_files" folder.
    * The file "Neural Network Model Report.md" is used to write the report.

