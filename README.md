# Peach Farming Assistant

## Overview  
The **Peach Farming Assistant** is an intelligent tool designed to assist peach farmers in optimizing their farming practices. It uses advanced machine learning models to classify soil types, detect diseases in peach trees, and estimate the number of peaches through video analysis. This application leverages state-of-the-art models, including InceptionV3 for image classification and YOLOv8 for real-time object detection.

## Features  
- **Soil Classification**: Classifies soil into five distinct types and provides tailored recommendations to enhance peach cultivation.  
- **Disease Detection**: Detects common peach tree diseases from leaf and tree images, offering suggested treatments.  
- **Peach Counting**: Uses YOLOv8 to estimate the number of peaches in videos, helping farmers track yield.

## Model Details  
- **InceptionV3**: Used for soil classification and disease detection with high accuracy, trained on agricultural datasets.  
- **YOLOv8**: A cutting-edge object detection model used to count peaches in real-time video footage of orchards.  
- **Training Data**: The soil and disease models were trained on curated agricultural datasets, while the YOLOv8 model was trained on a custom dataset of orchard images for peach counting.

## How It Works  
1. **Capture Input**: Farmers can upload soil images, peach tree images, or orchard videos.  
2. **Soil and Disease Prediction**: The app processes the images, classifying soil types and detecting diseases based on the uploaded images.  
3. **Peach Counting**: For video uploads, YOLOv8 analyzes the footage and estimates the number of peaches on the trees.  
4. **Advice and Recommendations**: Based on the results, the app provides actionable advice to improve soil quality, treat diseases, and offers an estimated peach count.

## Use Cases  
- **Peach Farming Optimization**: Helps peach farmers make data-driven decisions to improve yield and tree health.  
- **Disease Prevention**: Provides early detection of diseases to prevent crop loss and promote healthier trees.  
- **Yield Monitoring**: Facilitates peach counting for orchard management and production forecasting.

## Future Improvements  
- **Weather-Based Recommendations**: Integrate weather data to provide dynamic recommendations based on local conditions.  
- **Irrigation and Fertilization Monitoring**: Expand functionality to include irrigation and fertilization recommendations tailored to soil and tree health conditions.
