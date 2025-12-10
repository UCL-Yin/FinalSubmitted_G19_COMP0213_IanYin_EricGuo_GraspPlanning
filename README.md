# FinalSubmitted_G19_COMP0213_IanYin_EricGuo_GraspPlanning
OOP final coursework
This project simulates grasp attempts using PyBullet and trains a machine learning classifier
(e.g., Random Forest / Logistic Regression) to predict whether a grasp will succeed based on
RPY (roll–pitch–yaw) grasp pose parameters.

The project contains three main components:

Dataset generation
Simulate grasp attempts in PyBullet and save labeled (success/fail) grasp data.

Classifier training
Train a classifier using the collected data and save the model (.pkl).

Testing the classifier / grasp planner
Generate new test grasps and evaluate if the classifier can predict grasp success reliably.

urdf file
files for grippers and cubes' model

Please donwload the COMP0213_IanYin_EricGuo_GraspPlanning_submit.zip and uncompress

The project also utilises several additional packages to save code space and optimise runtime performance,
including PyBullet, NumPy, Pandas, joblib, and scikit-learn. To ensure the code runs correctly, please
ensure these packages are properly installed on your device.

You can use the command: pip install pybullet numpy pandas scikit-learn joblib

All tasks are executed through main.py using command-line arguments.

