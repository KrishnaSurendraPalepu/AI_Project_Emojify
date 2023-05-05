# AI_Project_Emojify
Our deep learning project aims to categorize human facial expressions to identify and match the appropriate emojis.
# 1. Motivation
This Project detects the human reaction by using the CNN model and create emoji Happy,Sad,Netural,Fearful,Disgust and Angry
 
# 2. Dataset Used:

https://www.kaggle.com/datasets/msambare/fer2013

Dataset from https://www.kaggle.com/datasets/msambare/fer2013 contains the data with data Image Properties: 48 x 48 pixels (2304 bytes) labels: 0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral The training set consists of 28,709 examples. The public test set consists of 3,589 examples. The training set consists of 28,709 examples and the public test set consists of 3,589 examples.

# 3. Why FER-2013 DataSet

Fer2013 is a challenging dataset. The images are not aligned and some of them are uncorrectly labeled as we can see from the following images. Moreover, some samples do not contain faces.

image

This makes the classification harder because the model have to generalize well and be robust to incorrect data. The best accuracy results obtained on this dataset, as far as I know, is 93.6% described in this paper: [Facial Expression Recognition using Convolutional Neural Networks: State of the Art, Pramerdorfer & al. 2016]

# 4. How to Use ?

#4.1 Install Dependencies:

Pandas
Numpy
CV2
datetime
Tensorflow
Tkinter
OS
Seaborn
Matplotlib
Anaconda and jupyter notebook is a better way to install dependencies

# 4.2 Download the data:

Download the Face Landmarks model with the Fer2013 dataset.
Kaggle FER-2013 Data for the facial datasets
Unzip the downloaded files

# 4.3 Train the model
Choose your parameters in 'parameters.py'
Launch training:

#4.4 Optimize Hyperparameters

optimize the dependednt parameters
Created sam.py and the developed Webapp using Tkinter.
When the program is executed it opens the webcam and detects the human face and gives the output as emoji

#4.5 Results
<img width="649" alt="image" src="https://user-images.githubusercontent.com/116232295/236355994-24858bf9-a1c3-484d-b8b7-ce34bebae735.png">

<img width="599" alt="image" src="https://user-images.githubusercontent.com/116232295/236356018-00199497-982e-4a4b-b8a8-2b7923b6d1ae.png">


# 5.Project Done by:

Krishna Surendra Palepu
Bharath Veer
Naveen Kumar Nettem
