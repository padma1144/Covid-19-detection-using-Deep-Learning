# Covid-19-detection-using-Deep-Learning

COVID-19 Detection based on Chest X-rays and CT Scans using four Transfer Learning algorithms: VGG16, ResNet50, InceptionV3, Xception. The models were trained for 500 epochs on around 1000 Chest X-rays and around 750 CT Scan images on Google Colab GPU. After training, the accuracies acheived for the model are as follows:

                InceptionV3  VGG16   ResNet50   Xception
Chest X-rays    96%          94%      83%       92%

CT Scans        93%          93%      80%       95%

Dataset

The dataset for the project was gathered from two sources:

Chest X-ray images (1000 images) were obtained from: https://github.com/ieee8023/covid-chestxray-dataset
CT Scan images (750 images) were obtained from: https://github.com/UCSD-AI4H/COVID-CT/tree/master/Data-split 80% of the images were used for training the models and the remaining 20% for testing
