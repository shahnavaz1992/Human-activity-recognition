# Human-activity-recognition
This is a human activity recognition project in construction industry using IMU sensors.

In this project, six IMU sensors were connected to the arms, feet, head, and pelvis of workers to record their acceleration in three dimensions. While existing models were trained on human activities like walking and running, there were no datasets specifically for construction workers. To address this, I recorded eight different activities, including measuring, hammering, sawing, spraying, carrying materials, grinding, and adjusting frames. Given the limited data available from real construction job sites, I employed few-shot learning techniques to recognize activities that were not previously trained in the base model.

data.zip contains the input data used to train the model. The data is stored in four different groups called tasks, with each group windowed into 30-second intervals. x represents the acceleration data, and y represents the activity labels. The data is divided into training, validation, and test sets. base_model.h5 is the base model that was trained on other activities, and few_shot_learning.ipynb is the main script that uses CNN and LSTM layers to recognize activities related to the construction industry.



