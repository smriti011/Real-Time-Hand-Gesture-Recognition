# Real-Time-Hand-Gesture-Recognition
This project is used for the recognition of hand gesture in real time using sequences. 


WORKING:

**Install important dependencies**
1. CV2
2. Numpy
3. OS
4. Matplotlib
5. Time
6. Mediapipe


**Collect keypoints from Mediapipe Holistics**
Keypoints:  
1. Left Hand
2. Right Hand
3. Face
4. Pose

![S](https://github.com/user-attachments/assets/26697c4c-e0e5-4eef-ad67-279ca813641b)



**Start collecting data points through OpenCV window**

Labels : "Hello" , "Thank You" , "Bye"

![output3](https://github.com/user-attachments/assets/d3911eab-278a-453e-bfc5-c71a252fc6d9)


![Screenshot 2024-09-17 105555](https://github.com/user-attachments/assets/4cee7f78-0e9b-4d86-b45d-03929f89c5fb)



**Extract Keypoints Values**


Number of Sequence = 30

Create a NUMPY array for ['hello', 'thanks', 'Bye']


**Setup folder for collection**


**Collect Keypoints values for Training and Testing**

![Screenshot 2024-09-10 104546](https://github.com/user-attachments/assets/683d5a01-b1b3-42e2-8b86-aa7bc79c2004)


**Pre-processing Data and create Labels and Features**

Label_map = **{'hello': 0, 'thanks': 1, 'Bye': 2}**


**Train a Deep Neural Network with LSTM layers for sequences**

Frameworks : Tensorflow , Sklearn

Libraries  : Sequential, LSTM, Dense, TensorBoard

Number of EPOCHS = 200

Total params: 1,790,027 (6.83 MB)

Trainable params: 596,675 (2.28 MB)

Non-trainable params: 0 (0.00 B)

Optimizer params: 1,193,352 (4.55 MB)


**Perform Real time hand gesture detection using OpenCV**
![output1](https://github.com/user-attachments/assets/cb74cd5c-5720-4ca8-9228-658149154783)



**Evaluation using Confusion Matrix and Accuracy**


Framework : Sklearn

Libraries : multilabel_confusion_matrix, accuracy_score


**Test in Real Time**

Framework : Scipy

Libraries : stats

![Screenshot 2024-09-17 111409](https://github.com/user-attachments/assets/b360ee57-8bf0-41e8-bf9f-e9cd5f996469)

![Screenshot 2025-01-29 222525](https://github.com/user-attachments/assets/fe7fd435-13a2-4b6a-b621-f9ee7d940b30)


Continuous Hand Movements : 

![Screenshot 2024-09-17 111706](https://github.com/user-attachments/assets/ba9b0677-d80c-4557-ac7d-2f6e5867d8e4)

![Screenshot 2025-01-29 222549](https://github.com/user-attachments/assets/3b26ee14-3ee3-44c7-9094-9dd89b656dfc)



