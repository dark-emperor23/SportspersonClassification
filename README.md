# Sportsperson Classifier

A machine learning project that identifies whether a given image belongs to a specific sportsperson. The model is trained using images collected automatically from the internet, and it selects the best algorithm based on cross-validation.


## Project Objective

This project aims to:
- Take the name of a sportsperson as input
- Download ~500 images of the sportsperson using Google Image Search
- Detect and extract faces from those images
- Train multiple classification models (Logistic Regression, SVM, KNN, etc.)
- Automatically select the best model using cross-validation
- Predict whether a test image contains the same sportsperson

---

## Workflow

1.User inputs a sportsperson's name

2.Images are scraped using icrawler from Google

3.Faces are detected using OpenCV Haar cascades

4.Features are extracted using Histogram of Oriented Gradients (HOG)

5.Multiple models are trained (SVM, Logistic Regression, KNN)

6.Best model is selected based on accuracy

7.A test image is passed to predict whether it belongs to the same person
