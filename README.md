# ASE_PROJECT
Real Time-Employee Emotion Detection System
Application Working Process:
From the source code folder EmotionsDetection, run the Main.py then the following functionality will be performed.
Administrator:
Login: Here the admin will login with this system by entering the username admin and password admin.
Build Models: Here admin will train the ML and Deep learning models like SVM, NN, and CNN based on the facial expression dataset.
Models Evaluations: Here the admin will calculate the three models’ performance results based on accuracy with help of the trained model by taking the test data as input.
Employee Emotions:  Here the admin can view the list of employee emotion detection results in the table format.
Employee:
Register: Here the employee will be registered with this system by entering the name, employee id, password, email, and mobile number.
Login: Here the employee will login with this system by entering the valid employee id and password.
Employee emotion detection: Here the employee will run the webcam then this application will capture the frame from the webcam and give it to a trained CNN model then the model will predict the employee’s emotions and store it in the database.
