# 2025-Y2-S1-MLB-WE3G1-06
Crop Pest and Disease Detection - Data Preprocessing Pipeline
Project Overview
This project develops a machine learning solution for detecting crop pests and diseases in maize plants using image classification techniques.
Dataset Details

Dataset: Maize Crop Pest and Disease Detection
Classes: 7 categories (Maize fall armyworm, Maize grasshopper, Maize healthy, Maize leaf beetle, Maize leaf blight, Maize leaf spot, Maize streak virus)
Format: RGB images
Total Images: ~3000+ images

Group Member Roles
IT Number                  Preprocessing Technique
IT24103011                 Handling Missing/Corrupt Images
IT24103426                 Image   Resizing
IT24103358                 Normalization/Scaling
IT24103044                 Outlier Removal
IT24103179                 Feature Engineering (PCA)
IT24103024                 Noise Reduction/Denoising


How to Run Code
Prerequisites
bashpip install opencv-python pillow matplotlib scikit-learn numpy
Setup

Update file paths in the notebook:

pythoninput_path = "path/to/original/dataset"
output_path = "path/to/processed/dataset"

Run the integrated pipeline:

bashjupyter notebook group_pipeline.ipynb
Expected Output

Processed images saved to output directory
Visualization plots showing preprocessing results
Summary statistics for each preprocessing step
