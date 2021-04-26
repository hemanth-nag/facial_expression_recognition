# facial_expression_recognition
Recognize 7 distinct facial expressions real-time using keras and openCV

## Procedure to Execute:

--Unzip the dataset.zip file to the root directory of this project. You can also download the dataset from here: '[fer2013](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data)'

--Run 'train_model.ipynb' file to build a CNN model and train it using the dataset. It also saves the model in model.json file and saves the weights in model_weights.h5 file.

--Run 'test_real_time.ipynb' file on your PC for real time expression recognition. The file uses my pre-trained weights by default saved in the saved_model directory. The pretrained weights give 70% accuracy on the training dataset and 60% accuracy on the test dataset(15 epochs). I recommend loading the saved weights and training the model further for improved accuracy. 


## Sample Output:
![alt text](saved_model/output.gif)

## Accuracy and Loss while training:
![alt text](saved_model/graph.png)


## Accuracy Obtained for each Expression(percentage):

{'angry': 63.05381727158949,

 'disgust': 67.66055045871559,
 
 'fear': 39.956065413717354,
 
 'happy': 89.64513446077072,
 
 'neutral': 69.66767371601208,
 
 'sad': 73.6024844720497,
 
 'surprise': 85.20971302428256}

