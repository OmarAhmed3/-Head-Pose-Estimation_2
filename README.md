# -Head-Pose-Estimation_2
Head Pose Estimation Project
# Description
# detecting a person if person look left or right or upper and down using mediapipe library by three Angles (pitch , yaw , roll) two angle vertical Nose and other angle change from position to postion.

# Steps
# 1. import mediapipe and cv2
# 2. looping to collect paths of dataset in list using glob.iglob and path of directory of dataset and append this paths in list(paths)
# 3. we prepare csv.file to read dataset in this csv file
# 4. we read matfile and we insert this reading in csvfile (Landmarks_data.csv)
# 5. we read a csvfile of data using pandas and drop labels of dataset(three Angle) and we get shape of dataset (1137, 939)
# 6. we divide dataset by train_test_split to test_data , validation_data and test_data
# 7. we train models using pipelines
# 8. we Normalize data using StandardScaler
# 9. we use PCA and SVR model to get predictions
# 10. we training pipeline and get error of points
# 11. we load this models using pickle.load() to ready to using webcam
# 12. X-Axis pointing to right. drawn in red
# 13. Y-Axis | drawn in green
# 14. Z-Axis (out of the screen) drawn in blue
# 15. we using function of vedio and load vedio into Function and get the results
