# FinalProjectDS
 Final Data Science Project


The notebook consists of 7 parts:

Getting packages
- Here we define the packages we use for the whole notebook.

Getting CSV's
- Here we get the csv files. Note that the extracting of the big corpus csv-file is commented out, because we only needed it to get the cleaned version, and then we saved the cleaned version to file, so we would not have to clean again, because this takes a while.

The functions
- Here we define the function we use multiple times, such as clean and the vectorizing functions.

Processing the big dataset and visualizing
- Here we call the clean function on chunks of the big corpus, and gets some barplots about unique words and total words and the number of articles for each category. Not that the cleaning of the big dataset is inside a function that is commented out seeing as we only needed to do it once and then save the cleaned df.

Processing the Liar dataset
- Here we process the liar dataset, we dont save any of this data because it is quick to do.
-Note that below this section there is a code-box with the text #Run everything above this. Running everything above this will prepare everything for the models.

The models with confusion matrices for evaluation.
- Here we train, save and load the all the models. As such only loading and evauating was neccesary

The final tests for the models using test datasets.
- Confusion matrices for all the models using test datasets.