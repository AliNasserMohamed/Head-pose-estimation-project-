# Head-pose-Estimation-project-
This project tries to find the direction a person is looking using the orientation of the head.
Head orientation can be defined using pitch, yaw, and roll, so I used a machine learning model tries to estimate these values using facial landmarks.



https://github.com/AliNasserMohamed/Head-pose-estimation-project-/assets/67801762/b0ad896b-07da-44fa-9622-84f0a502d560




https://github.com/AliNasserMohamed/Head-pose-estimation-project-/assets/67801762/4357786e-a2f6-4972-aa94-7bffe7fa5041


# Dataset:
For this project, the dataset used is AFLW2000 Dataset, which consists of 2000 face images, with some information about them like the facial landmarks and the pitch, yaw, and roll values for each picture.
Solution:
Used the MediaPipe library to extract the face landmarks, then chose the most important facial features (like the nose, forehead, eyes and mouth positions) to be the input of the model.
Performed preprocessing step to make the model independent of the face position or scale.
Trained a regression model using the position of the most important facial landmarks to estimate the values of the pitch, yaw, and roll.
Used rotation, translation, and projection of the axes on the image to visualize the direction the person is looking at.
Used the values of pitch, yaw, and roll to define the direction.


Libraries used:

    MediaPipe
    Numpy
    OpenCV
    Matplotlib
    Pandas
    Scikit-Learn
