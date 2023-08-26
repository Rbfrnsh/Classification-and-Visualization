# Classification and Visualization Six Class Abnormalities of Heart Fetals Using Convolutional Neural Network and Saliency Map
This research is conducted to perform the classification of 6 classes of fetal heart image abnormalities using Convolutional Neural Network and Saliency Map. The proposed models for classification are CNN with custom layers, ResNet50V2, MobileNetV2, and DenseNet121. The hyperparameters used in this study include 50 and 100 epochs, batch sizes of 8, 16, and 32, and a learning rate of 0.0001.
This research is conducted to perform the classification of 6 classes of abnormalities in fetal heart images using Convolutional Neural Network and Saliency Map.
The proposed models for classification are CNN with custom layers, ResNet50V2, MobileNetV2, and DenseNet121. The hyperparameters utilized in this study include Epochs of 50 and 100, Batch sizes of 8, 16, and 32, and a Learning rate of 0.0001. After obtaining the best model, visualization testing will be conducted using the eXplainable Artificial Intelligence (XAI) method, specifically the Saliency Map, to determine the extent to which the model can represent the images and whether the model is proficient in classification.

Here are images of 6 abnormal fetal heart conditions and 1 NORMAL fetal heart image.

- EA
- AOS
- AVSD
- TOF
- AVSD
- NORMAL
- ASD
<img width="601" alt="image" src="https://github.com/Rbfrnsh/Classification-and-Visualization/assets/89909357/51dea426-3dbf-4de7-a4bb-9359a452ef03">

For the results presented on GitHub, only the CNN architecture with custom layers was utilized. Hyperparameter tuning was performed with Epochs 100, Batch Size 8, and Learning Rate 0.0001. Through training and evaluation, accuracy, sensitivity, and specificity results of 100% were achieved. These outcomes demonstrate that the model performs excellently in classifying image data.

