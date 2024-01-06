# React Native | Firebase | Python | ML Financial Recommendation App

Welcome to the repository for our innovative mobile application that combines React Native, Firebase, Python, and Machine Learning to provide personalized financial recommendations and effortless daily spending tracking.

## Project Overview

Our goal is to deliver a user-friendly mobile application that simplifies daily spending tracking. The key features of the app include:

1. **Receipt Classification:**
   - Utilizing deep learning models such as VGG16, VGG19, and ResNet50 to classify receipts into three categories: good quality, receipts with shadows, and receipts with wrinkles.
   - Applying appropriate pre-processing techniques for each identified category, recognizing their distinct characteristics.

2. **Text Extraction:**
   - Using Tesseract OCR to extract text from receipts.
   - Employing regular expressions to filter and extract item names along with their amounts from the extracted text.

3. **Generative AI for Post Processing:**
   - Employing generative AI techniques for post-processing to enhance the accuracy and completeness of the extracted information.

4. **SVM Model for Item Categorization:**
   - Implementing a Support Vector Machine (SVM) model to classify items into categories.
   - Saving the categorized items to Firebase for efficient storage and retrieval.

5. **Anomaly Detection and Financial Recommendations:**
   - Analyzing previous spending patterns using machine learning algorithms.
   - Detecting anomalies in individual spending patterns to provide personalized financial recommendations.
   - Helping users plan their future spending to achieve their financial goals.
