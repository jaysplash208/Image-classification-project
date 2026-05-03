# Image-classification-project
# AI Image Classification Project

## Overview
This project demonstrates an image classification pipeline built with Deep Learning using TensorFlow and Keras in Google Colab.  

The system analyzes an input image and predicts the most likely category while also displaying the model’s confidence score. The purpose of the project was not only to generate predictions, but also to observe how AI handles real-world images with uncertainty.

## Project Objective
To build and test a machine learning model capable of classifying visual content and returning prediction probabilities.

This project also explores an important concept in Artificial Intelligence: models are not always perfect, and confidence scores help measure certainty.

## Dataset Used
The dataset included image samples from publicly available visual categories.  

For testing, one example used was an image of an actress receiving an award at an event, allowing the model to classify clothing/object patterns within the image.

## Technologies Used
- Python
- TensorFlow
- Keras
- NumPy
- Matplotlib
- Google Colab

## Features
- Image upload and preprocessing
- AI-based image classification
- Confidence score output
- Visual display of test image
- Prediction analysis

## Example Output
Prediction: sarong  
Confidence: 18.58%

This result shows that the model identified a possible category but with low certainty, highlighting the limitations of smaller datasets and the importance of continuous model improvement.

## Key Learning Outcomes
Through this project, I learned:

- How to preprocess images for neural networks
- How classification models generate probabilities
- How to interpret low-confidence predictions
- Why dataset quality strongly affects model performance
- How AI systems improve through iteration

## Challenges Encountered
- Limited dataset size
- Similar-looking image classes
- Low confidence predictions on complex real-world images

## Future Improvements
- Expand training dataset
- Improve image labeling quality
- Use transfer learning models such as MobileNet or ResNet
- Increase model accuracy and confidence
- Deploy as a web application

## Why This Project Matters
This project reflects practical understanding of Computer Vision workflows and demonstrates that building AI systems includes testing, evaluation, and improving imperfect models.
