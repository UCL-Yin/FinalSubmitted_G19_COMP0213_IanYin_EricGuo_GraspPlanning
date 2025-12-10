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

All tasks are executed through main.py using command-line arguments.
