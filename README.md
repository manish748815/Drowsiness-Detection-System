# Drowsiness-Detection-System
Drowsiness while driving is a significant cause of accidents, leading to injuries and fatalities. A drowsiness detection system can prevent such incidents by monitoring the driver's eye movements and providing timely alerts.The goal is to develop a real-time system using computer vision to detect drowsiness through eye analysis. The system uses a webcam to capture video and alerts the driver if drowsiness is detected.
# Logic of Project
The project includes direct working with the 68 facial landmark detector and also the face detector of the Dlib library. The 68 facial landmark detector is a robustly trained efficient detector which detects the points on the human face using which we determine whether the eyes are open or they are closed.
# Working of the project
As the landmarks are detected using the detector. Now we are taking the ratio which is described as 'Sum of distances of vertical landmarks divided by twice the distance between horizontal landmarks'. Now this ratio is totally dependent on your system which you may configure accordingly for the thresholds of sleeping, drowsy, active.
