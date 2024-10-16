
# Video-Object-Detection 


This project implements a video object detection system that utilizes deep learning techniques to detect and track objects (specifically people and cars) in real-time. The system processes video streams and applies state-of-the-art object detection models to identify and visualize various objects in the scene.


## Acknowledgements

I extend my sincere gratitude to the developers and contributors of YOLOv5, the OpenCV library, and the LabelImg tool for providing essential resources for this project. I also appreciate the support and guidance from the online communities that assisted throughout the development process.

## Table of Contents

1. [Overview](#overview)
2. [Acknowledgements](#acknowledgements)
3. [Data Preparation](#data-preparation)
4. [Requirements](#requirements)
5. [Model Training](#model-training)
7. [Results](#results)
9. [Contributing](#contributing)
10. [License](#license)
11. [Authors](#authors)

## Data Preparation

--> Collected a dataset of 100 images each of cars and people from various online platforms.

--> Annotated the images using the LabelImg tool, adding bounding boxes around the objects of interest.

-->This annotated dataset is essential for training and evaluating the object detection model
## Requirements
Python: 3.7

Tensorflow: 2.16.1

Numpy: 1.26.4

Pandas: 2.0.3

Matplotlib: 3.9.0

Opencv-python: 4.8.0

Jupyter: 1.0.0

LabelImg: (latest version from the GitHub repository)




## Model Training 
This section details the training process for the YOLOv5 model using the annotated dataset. The model was trained to recognize the specified classes, optimizing for accuracy and performance.




## Results

![val_batch1_labels](https://github.com/user-attachments/assets/e984bdf5-2fd0-444b-add0-e0d4a9f596ed)





## Contributing

Contributions are welcome! Please feel free to submit a pull request or open an issue to discuss potential improvements.

## License 
This project is licensed under the MIT License.


## Authors
Melina Singh: Developed the video object detection project, including data collection, annotation, model training, and evaluation. I am responsible for implementing the YOLOv5 model and optimizing it for detecting cars and people in video frames.




