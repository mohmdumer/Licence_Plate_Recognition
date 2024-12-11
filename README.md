# Licence_Plate_Recognition
# Real-Time License Plate Recognition

This project demonstrates real-time vehicle license plate recognition using YOLOv8 and EasyOCR. 
The pipeline includes detecting license plates in videos or images and extracting text from them. 
The solution leverages robust models for detection and optical character recognition to provide accurate results.

## Features
- **YOLOv8**: State-of-the-art object detection for identifying license plates.
- **EasyOCR**: Extracts text from detected license plates.
- **Video Processing**: Handles real-time video streams to detect and recognize license plates.
- **Image Processing**: Processes single or batch images for license plate recognition.
- **Text Extraction**: Outputs detected license plate text into a structured file.

## Dataset
The dataset was prepared and annotated using [Roboflow](https://roboflow.com).

## Workflow
1. **Dataset Preparation**: Annotate and preprocess the dataset using Roboflow.
2. **Model Training**: Train YOLOv8 on the annotated dataset.
3. **License Plate Detection**: Use YOLOv8 to detect license plates in images or videos.
4. **Text Recognition**: Use EasyOCR to extract license plate text.
5. **Results Storage**: Save annotated images/videos and extracted text to files.
