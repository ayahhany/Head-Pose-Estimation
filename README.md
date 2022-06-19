# Head Pose Estimation
Dataset used is AFLW2000 contains training images to predict three angles of head motion (yaw, pitch, roll).

step1: extracting 468-points of face mesh using mediapipe

step2: plotting the 468 points on faces from the dataset

step3: plotting the 3 axis based on (yaw, pith, roll) values

step4: preprocessing and visualizing data distribution

step5: Model: SVR performed best on the dataset

step6: testing new images by predicting their (yaw, pith, roll) values using OpenCV

step7: plotting the 3 axis based on the predicted (yaw, pith, roll) values 

step8: testing videos (pre-recorded and realtime) using OpenCV


Dataset: https://drive.google.com/drive/folders/1kavxt9e3S67UYM9rw-2LRTotAEciVXpr?usp=sharing

Output video: https://drive.google.com/file/d/1rfmxZKIesfSj7zT2RPpcttPKqALgfxxo/view?usp=sharing
