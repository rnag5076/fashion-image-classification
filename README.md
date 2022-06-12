# Fashion-image-classification

MAIN FILE :- analysis.ipynb

This Project entails the techniques for the classification of fashion images on the basis of attributes like neck, sleeve length, pattern. For Classification, a Deep Learning Model is trained with an Accuracy of ~ 92%.

> Techniques
  * For Handling Null values - To begin, I created a cnn that was trained on the valid values (rows with no Nan Values). I predicted the Nan values using that model, then retrained my model to produce more efficient outputs. 
  * Introducing a new Attribute - To efficiently train the model, we created a new attribute by combining all of the attribute values and then training our model on that attribute. 
  * * A Data Augmentation strategy was also used in order to expand the amount of the data so that our model does not produce skewed findings.

> Project Flow

  * Generating Descriptive Statistics About the Dataset
  * Printing the Unique Categories Inside Each Attribute
  * Value Count for Each Sub-category of Each Attribute
  * Checking for Null Values
  * Check if There Are Rows Having All Values as Nan
  * Drop Nan Values
  * Balancing the Data by Data Augmentation Techniques
  * Creating a Simple CNN Model and Training it on Our Dataset
  * Reading the CSV File and Retrieving Nan Value Images
  * Predicting the Nan Images
  * Augmented Dataset [Link](https://drive.google.com/file/d/1VqUBOUGKCHAreXBlQBPVlnyzkVHNplfq/view?usp=sharing)
  * Creating New CNN Model After Including Nan Images
  * Making Output CSV File
