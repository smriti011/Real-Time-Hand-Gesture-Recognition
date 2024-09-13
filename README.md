# Real-Time-Hand-Gesture-Recognition
This project is used for the recognition of hand gesture in real time using sequences. 
   ![Screenshot (155)](https://github.com/user-attachments/assets/0db7432a-4bee-42eb-aa9a-62ff57f9484b)

Working:

1. **Collect keypoints from Mediapipe Holistics**
2. **Train a Deep Neural Network with LSTM layers for sequences**

![Screenshot (156)](https://github.com/user-attachments/assets/2c3c6be1-a309-408b-b8cc-cfa3086c452e)

3. **Perform Real time hand gesture detection using OpenCV**


Model: "sequential"
_________________________________________________________________
Layer (type)                 Output Shape              Param #   
_________________________________________________________________
lstm (LSTM)                  (None, 30, 64)            442112    
_________________________________________________________________
lstm_1 (LSTM)                (None, 30, 128)           98816     
_________________________________________________________________
lstm_2 (LSTM)                (None, 64)                49408     
_________________________________________________________________
dense (Dense)                (None, 64)                4160      
_________________________________________________________________
dense_1 (Dense)              (None, 32)                2080      
_________________________________________________________________
dense_2 (Dense)              (None, 3)                 99        

Total params    : 596,675
Trainable params: 596,675
Non-trainable params: 0
