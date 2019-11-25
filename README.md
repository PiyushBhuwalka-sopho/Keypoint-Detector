# Keypoint-Detector

### Data

I am using the facial keypoints detection dataset from Kaggle. If you'd like to re-train the model, you'll need to first download the training/test sets and place them in the subdirectory `data`.


#### Step 1:  Face detection and Eye detection
Implement face and eye detection.

#### Step 2: De-noise an image for better face detection
De-noise an image for better face detection.

#### Step 3: Canny Edge Detection and Gaussian Blur
Blur and edge detect a test image.

#### Step 4: Automatically hide the identity of a person (blur a face)
Automatically detect the face of a person in a test image, then blur their face to mask their identity.

#### Step 5:  Build a Convolutional Neural Network (CNN)
Design a convolutional network architecture for learning correspondence between input faces and facial keypoints.
Compile and train the CNN on the dataset.
Visualize the loss function.

#### Step 6:  Complete a facial keypoints detector and complete the CV pipeline
Combine OpenCV face detection with trained convnet facial keypoint detector to detect facial keypoints on any image
that contains one or multiple human faces.
