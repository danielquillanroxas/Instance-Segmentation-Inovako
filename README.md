# Instance Segmentation with Fruits - Inovako

This project involves the development and evaluation of a YOLOv8 instance segmentation model for detecting mangoes, kiwis, and oranges. Below are the steps and key components of the project.

### 1. Creating the Dataset
- Compiled a dataset consisting of 20 images each for mangoes, kiwis, and oranges randomly from the internet.

### 2. Labeling the Dataset
- Used a labeling tool to segment the dataset.
- [Roboflow](https://roboflow.com/) was used for labeling.

### 3. Data Augmentation
- Applied data augmentation techniques using Roboflow to the labeled images to increase the variability and robustness of the dataset.
- Techniques include rotations, flips, noise addition, and brightness adjustments.

### 4. Training the YOLOv8 Model
- Trained the YOLOv8 instance segmentation model using the prepared dataset.
- Used Google Colab for training due to its GPU capabilities.


### 5. Model Performance
- Achieved a model performance that detects each of 5 untrained mango, kiwi, and orange images with at least 85% precision.
- Evaluated the model using precision, recall, and F1-Score metrics.
- Metrics:
    Overall Precision (Box): 0.833,
    Overall Recall (Box): 0.921,
    Overall mAP@0.5 (Box): 0.896,
    Overall mAP@0.5:0.95 (Box): 0.796,
    Overall F1-Score (Box): 0.876,


### 8. Video Demonstration
- Prepared a short desktop recording video with audio, demonstrating the model's predictions on the test images.
- The video link: https://www.loom.com/share/156bedc70d1d4121a668513e9909a2f2?sid=0d4b66ee-573b-4712-92cc-555e38ba1fee
   
