# Human action recognition using Detectron2 and LSTM
This is an application built to show how human action classification can be done using 2D Pose Estimation and LSTM RNN machine learning models. 

2D pose estimation is done using Facebook AI Research's Detectron2. 
A LSTM model is used to classify actions from 2D pose estimation output from a sequence of consecutive frames on a video. 

Model classifies the action into 6 categories
- JUMPING
- JUMPING_JACKS
- BOXING
- WAVING_2HANDS
- WAVING_1HAND
- CLAPPING_HANDS
