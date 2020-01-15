# Predict_Veh_Angle
https://www.kaggle.com/c/pku-autonomous-driving/data

Input: 60k labeled 3D car instances from 5k real-world images.

Input format :

The primary data is images of cars and related pose information. The pose information is formatted as strings, as follows:

`model_type, yaw, pitch, roll, x, y, z
`

Goal : develop an algorithm to estimate the absolute pose of vehicles (6 degrees of freedom) from a single image in a real-world traffic environment.

Scoring : Mean average precision

Prediction:

`ID_1d7bc9b31,0.5 0.25 0.5 0.0 0.5 0.0 1.0`

Each 7-value element in PredictionString corresponds to:

pitch, yaw, roll, x, y, z and confidence for each car in the scene.
