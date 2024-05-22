The objective of this project is to develop a reliable object detection system using the Faster R-CNN architecture. Special attention is given to preprocessing and preparing data to ensure that the model trains on high-quality and accurately annotated images.

Key Features:
Data Preprocessing: Robust methods to preprocess and validate bounding boxes in image annotations.
Custom DataLoader: Implementation of a PyTorch DataLoader with a specialized collate_fn to handle images with no bounding boxes.
Model Training: Training a Faster R-CNN model using PyTorch, with detailed debugging and validation steps to ensure model accuracy and reliability.

The datasets used for this project consists of images annotated with object bounding boxes. The annotations are provided in XML format, which are parsed and processed into a suitable format for training the model.
LINKS TO DATASETS:
https://www.kaggle.com/datasets/cici118/swimming-pool-detection-algarves-landscape
https://www.kaggle.com/datasets/cici118/swimming-pool-detection-in-satellite-images

Data Preparation
Annotation Parsing: Extract bounding box coordinates from XML files.
Validation: Exclude images with incorrect or missing annotations.
Transformation: Apply transformations such as resizing, cropping, and normalizing to prepare images for training.
Model
The project utilizes the Faster R-CNN architecture, a widely-used model for object detection tasks. The model is trained to recognize objects defined in the dataset's annotations.
