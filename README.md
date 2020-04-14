# COVID19-xray-classifier
A classifier that takes X-RAY or CT-SCAN to classify it COVID19 or OTHERS (normal or other pneumonia cases).

## Data Preparation
The data for training the model was gathered from two sources:
1. COVID19 X-RAY images repository: https://github.com/ieee8023/covid-chestxray-dataset
2. Chest X-Ray Images (Pneumonia) on Kaggle: https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia

The preprocessing and cleaning of images/labels was done to ensure data in correct form. For further reference of the process please check this notebook https://www.kaggle.com/rgaltro/covid19-data-preprocessing.

## Training of model
Different models were trained like VGG16, Autoencoder classifier and InceptionV3. In the end InceptionV3 produced the best results.
### Note
To tackle the high imblance of data, different class weights were used.
