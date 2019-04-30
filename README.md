# CellSegmentation_Kaggle
Its Python notebook for Kaggle's DataScience Bowl 2018 competition

I started with kernel shared by Minggang Chen as UNet Starter.

The python notebooks shared here are modified to use Data Generator function. also the Activation function used in UNet is different.
Also, the python notebook provided for submission is using Stage2_Final Test set.

You can use this notebooks as sample code for cell segmentation. 
you can also use it to predict the segmentation and plot some random predictions.

There are two python notebooks and one model shared here.
the model that gave me good accuracy is shared here.

there are two python note books
1. UNet-CNN-CellSegmentation.ipynb: 
-Load Data
-Create DataGenerator
-Build Model
-Train Model
-Predict
2. GenerateSubmission.ipynb
-Load Test Data
-Predict cell segmentation for Test Data
-Generate csv file for submission
