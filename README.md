# Pneumonia_detection_using_CNN
I have used the kaggle datasets (https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia) to train a CNN model to detect the pneumonia x-ray or normal x-ray. In this model, I used AlexNet CNN to train a model. Before training, all the datasets were preprocessed and resized to (227,227,3) because the input to AlexNet CNN is always (227,227,3). After training the model with various parameters, At last, i got a optimum result using batch size 32 and 12 epoch. The accuracy of the model is 88.62%. The confusion matrix of the model is shown as below\
![image](https://github.com/sanjoggaihre/Pneumonia_detection_using_CNN/assets/43695490/44207089-e8ff-4a32-8d53-5f010f662bec)\
Also the accuracy and loss metric is shown below.\
![image](https://github.com/sanjoggaihre/Pneumonia_detection_using_CNN/assets/43695490/bab70507-e018-470e-ac22-a749829ecd04)
