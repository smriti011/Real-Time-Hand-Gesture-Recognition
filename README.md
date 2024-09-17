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


**Start collecting data points through OpenCV window**

![output3](https://github.com/user-attachments/assets/d3911eab-278a-453e-bfc5-c71a252fc6d9)


**Extract Keypoints Values**


Number of Sequence = 30

Create a NUMPY array for ['hello', 'thanks', 'Bye']


**Setup folder for collection**


**Collect Keypoints values for Training and Testing**

![Screenshot 2024-09-10 104546](https://github.com/user-attachments/assets/683d5a01-b1b3-42e2-8b86-aa7bc79c2004)


**Pre-processing Data and create Labels and Features**


**Train a Deep Neural Network with LSTM layers for sequences**

Frameworks : Tensorflow , Sklearn

Libraries  : Sequential, LSTM, Dense, TensorBoard

Label_map = **{'hello': 0, 'thanks': 1, 'Bye': 2}**

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


