# Faster-RCNN-NEU-DET-dataset
Training a custom F-RCNN object detection model for surface detection dataset provided by NorthEastern Univesity.


This project was done for the automation of quality inspection of products in factories and manufacturing plants. As a bigger part of project, this is specifically done to detect scratch from the projects. As a proof of concept, the dataset was taken from NorthEastern university NEW-DET dataset. The dataset has several errors so the finetuned dataset is available in my google drive and the link is as follows:
	IMAGES : https://drive.google.com/drive/folders/1ab1LbNI8yCzzHiDrbrBawD8UJlmAQwxG
	ANNOTATIONS : https://drive.google.com/drive/folders/1wbkLQy47BwDSjk4XxwmkLrYV1paQiIlo
	
For the clarification, shout out to the dataset creaters, it is a good dataset but however the dataset has missing annotation, corrupted images and so on. 

The dataset was trained on Google TFOD API using a Faster RCNN Network as the inferece was suppposed to be conducted in real time. Tensorflow 1.15  was used for the training and tesing environemnt but however, its quite straightforward to use with tf2x version using TFOD 2 API. 


Steps to train Faster R-CNN:
Carefully follow the steps here:
https://tensorflow-object-detection-api-tutorial.readthedocs.io/en/latest/training.html

