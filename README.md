# Custom-Instance-Segmentation
1. Objective
The goal of this project is to detect and segment objects in images using YOLOv8 (You Only Look Once, version 8). This means the model will not only find where objects are but also outline their exact shapes.

2. Procedure:
Step 1: Collect and Label Images
Images were collected.

Each object in the images was labeled by drawing polygons around them (this is called instance segmentation).

Step 2: Prepare the Dataset
The labeled images were organized into:

Training set: to teach the model.

Validation set: to test how well the model is learning.

Step 3: Set Up YOLOv8
A pre-trained YOLOv8 segmentation model was used.

A configuration file was created to tell the model:

How many types of objects it should detect.

Where the training and validation data are.

Step 4: Train the Model
The model was trained using a simple command.

During training, the model kept improving by comparing its guesses to the real labels.

Step 5: Test the Model
After training, the model was tested on new images.

The model was able to correctly find and outline the objects.

3. Results
The trained model could successfully detect and segment objects in both training and new images.

The outlines and labels were clearly visible on the output images.

4. Conclusion
This project is a great example of how to build an object detection and segmentation model easily using YOLOv8.
It is simple enough for beginners and useful for many real-world applications like:

Detecting products

Identifying animals

Outlining damaged areas, etc.



