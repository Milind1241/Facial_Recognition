# Facial_Recognition
Steps to follow: In the command prompt, execute "pip install -r requirements.txt" to install the necessary packages for the project.
Within the project folder, establish a "TrainingImage" folder. Open the files "attendance.py" and "automaticAttendance.py" and adjust all path references to match your system configuration.
Finally, run the "attendance.py" file to initiate the process.

# Project Explanation
Upon initiating the project, the initial step involves registering your face to enable the system to recognize you. Begin by selecting "Register New Student." A small window will appear, prompting you to input your ID and name. Click on the "Take Image" button, triggering a camera window to open and capture up to 50 images of your face (modifiable based on your preference). These images are stored in a folder named "TrainingImage." Providing more images enhances the system's facial recognition capabilities.
Subsequently, click on the "Train Image" button. This action trains the model, converting all captured images into a numeric format comprehensible to the computer. The training process optimizes the system's ability to identify the registered face efficiently. Depending on your system, the training phase may take some time.
After completing the model training, select "Automatic Attendance." Enter the subject name, and the system will utilize the trained model to mark attendance based on facial recognition. The system generates a separate .csv file for each subject, organizing the attendance records accordingly.
To review attendance records, click on the "View Attendance" button and proceed to check the attendance sheet.
