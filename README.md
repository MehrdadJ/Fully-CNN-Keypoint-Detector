# Fully-Convolutional-Neural-Network-Keypoint-Detector
Keypoints detection is a critical element in object recognition. In order to train a model to predict keypoints, the groundtruth data, which usually is the position of keypoints on the train set, is needed. Common traditional approaches use the coordinates of the position of each keypoints and learn a model to detect keypoints. The deficiency of this approach is scale-dependency, which means the model is sensitive to scale of inputs, and does not guarantee to work on different scale inputs.

In order to overcome this issue, we use an approach that proposed by (Cao, Zhe et al. (2017)). In this method, a confidence map is created for each keypoints and is used as groundtruth in order to learn a fully convolutional neural network. By using this approach, the learned model would be scale-invariant.

This neural network has been implemented by Keras.
