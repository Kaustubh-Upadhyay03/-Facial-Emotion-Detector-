# EmotionLens
A full-stack Python application built with Keras, Numpy, and deployed in Flask that recognizes facial expressions from a webcam or video using a trained neural network.

To use, <code>pip install</code> all the dependencies from <code>requirements.txt</code> and run <code>main.py</code> on your local environment.
The neural network is trained on almost 40,000 images, and has an accuracy of about 84%. 
The convolutional network tracks each frame individually and monitors changes in facial expression and updates the video live with a bounding box across the recognized face and the best available mood.

Download the repository for the best results, feel free to upload your own videos, and try it yourself by turning your wecam on!
