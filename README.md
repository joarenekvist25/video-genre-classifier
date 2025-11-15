# video-genre-classifier
**Project Goal**


The purpose of this project is to develop a machine learning model capable of classifying the genre of short video clips.
For the initial version, the project focuses on three genres:
-Sports
-News
-Cartoon


**Project Overview**


This project explores video classification using a practical, frame-based approach.
Instead of training a full video model, I extract frames from each video and train an image classification model on those frames.

The workflow is:

Extract frames from each video (1 frame per second).

Train an image classifier on the labeled frames.

Apply the classifier to frames from new videos.

Combine the frame-level predictions to produce a genre prediction for the entire video.


**Motivation**


work with video data and preprocessing

build an end-to-end machine learning pipeline

apply transfer learning and modern image classification methods

practice evaluation and interpretation of model results



**Technologies Used**


Python

PyTorch

Google Colab (for training with GPU support)

FFmpeg (for frame extraction)

Gradio (for building a simple demo interface)

