# TALKIE
ASL TO TEXT CONVERTER

This Python project aims to convert American Sign Language (ASL) gestures captured through a video feed into corresponding text using computer vision techniques. The ASL to Text Converter utilizes OpenCV, TensorFlow, and other libraries to process the video frames, detect hand gestures, and classify them into the corresponding alphabets or words of the ASL.

# Description

In our project, we have explored two different methods for classifying American Sign Language (ASL) gestures captured through a camera feed. These methods aim to convert ASL gestures into corresponding textual representations.

* Method 1: Feature-based classification
In this approach, we extract specific features from each character of the ASL alphabet captured through the camera. These features include roundness, which measures the curvature of the hand gesture, and height-to-width ratio, which represents the proportions of the hand shape. These features serve as input to a neural network model, where the network learns to map the extracted features to the corresponding ASL characters. By training the neural network on a labeled dataset, it becomes capable of classifying unseen ASL gestures based on their extracted features.

* Method 2: Convolutional Neural Network (CNN) classification
Alternatively, we employ a CNN-based approach for classifying ASL gestures. In this method, we utilize a pre-trained CNN model, specifically designed to process and classify images. We capture images of the hand gestures using the camera feed and input them directly into the CNN. The CNN model, consisting of convolutional layers, pooling layers, and fully connected layers, learns the underlying patterns and features of the hand gestures required for accurate classification. By training the CNN on a large dataset of labeled ASL gesture images, it becomes proficient at recognizing and classifying different ASL characters.

By implementing these two methods, we aim to compare their performance in terms of accuracy and efficiency. The feature-based approach leverages hand-crafted features to describe the ASL gestures, while the CNN-based approach utilizes the power of deep learning to automatically extract relevant features from raw image data. By evaluating and comparing the results of both methods, we can determine the most effective approach for ASL gesture classification and proceed with the chosen method in our project.

