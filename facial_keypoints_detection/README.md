### Objective

The objective of this task is to predict keypoint positions on face images. 

A detailed description of the project can be found here:
https://www.kaggle.com/c/facial-keypoints-detection/overview/description


### What I did

A large fraction of the training data have missing values. I trained a linear model to fit the missing features using existing features and then trained a regression CNN model to calculate the coordinates of the keypoints.

A sample result is as follows. The coordinates of the facial keypoints are denoted by the color dots.
![Sample result](https://github.com/ffrrpp/kaggle_projects/blob/master/facial_keypoints_detection/sample_result.png)
