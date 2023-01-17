# amazon-from-space
Deep Learning: CNN Model
## Planet: Understanding-the-Amazon-from-Space
[Kaggle Competition](https://www.kaggle.com/c/planet-understanding-the-amazon-from-space) consisting in using satellite data to track the human footprint in the Amazon rainforest.

* Follow either of the steps to use the Dataset
  1. Download the DataSet:
    (https://www.kaggle.com/datasets/nikitarom/planets-dataset)

  2. Use Kaggle API to fetch the dataset onto colab

      * Get the API TOKEN

      * Set the Kaggle Environment and configure the directory

      * Run the command:

            !kaggle datasets download -d nikitarom/planets-dataset

* Use any of the IDEs to create a Notebook
  1. Google Colab (Preferably)
  2. Kaggle Notebook
  3. Jupyter Notebook
  
## Steps to Develop a CNN model:
1. Import the necessary libraries
2. Load the Dataset
    1. Working on Dataset Paths
3. Data Preprocessing
    1. One Hot Encoding
    2. Functions to create Performance Measures
4. Model Building
    1. Train the model
5. Optimization
6. Submission
    1. Loading the predicted values to CSV file
    
My [Notebook] has yielded Mean FScore Beta: 0.90592
