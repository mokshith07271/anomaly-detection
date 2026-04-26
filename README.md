**Overview**
This project focuses on detecting anomalies (defects) in industrial images using a deep learning approach. Instead of relying on labeled defect data, the model is trained only on normal images and learns their patterns. When a defective image is given, the model fails to reconstruct it properly, which helps in identifying anomalies.

**Features**
Trained using only normal (non-defective) data
Uses a CNN-based Autoencoder for feature learning
Detects anomalies based on reconstruction error
Includes threshold tuning for better performance
Visualizes results using:
Confusion Matrix
Reconstruction Comparison
Anomaly Heatmaps

**How It Works**
The Autoencoder is trained on normal images from the dataset
It learns to reconstruct these images accurately
When a new image is passed:
If reconstruction is good → Normal
If reconstruction is poor → Anomaly
A threshold is applied on reconstruction error to classify results


