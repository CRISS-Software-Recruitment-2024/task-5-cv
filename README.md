# task-5-cv
This is the Computer Vision task for this recruitment.
Computer vision is very importatant for our subsystem as it helps us detect obstacles and identify tags and markers like arrows. In this task you will take your first step in training a cv model. 

TASK : ```Stop sign detection using Computer Vision```

1.Use a pre trained object detection model working like YOLO, or SSD
2.Use a pre-created dataset from the web (You can use something like RoboFlow or Kaggle for getting datasets). 
3.Make sure the dataset is small enough (having 200 images max, otherwise you’ll have 4-hour + training time (speaking from experience ;)) 
4.Preprocess the input image or video frame (e.g., resizing, normalization).
5.Perform stop-sign detection on the input data using the loaded model.
6.Extract bounding box coordinates, confidence scores, and class labels for detected objects and display the labels, confidence scores for each object (Your model should be able to detect multiple stop signs, if present in the frame)
7.Evaluate the trained model using the testing set to measure its accuracy and generalization performance.
8.Generate a confusion matrix and analyze the model's performance for each digit class. (You may use some frameworks like Matplotlib)

Additional Brownie task:
-Implement a real-time object detection feature using a webcam or live video feed.

SUBMISSION: Commit any file you use to write your code (python/c++/c etc)
