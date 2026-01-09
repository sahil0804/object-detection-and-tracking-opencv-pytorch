
# Object Detection and Tracking using OpenCV and PyTorch
This project explores basic object detection and tracking techniques using computer vision and deep learning tools. The goal is to identify objects in video frames and track their movement over time using convolutional neural network concepts and traditional image processing methods.

**Project Context**

Object detection and tracking are widely used in applications such as surveillance, traffic monitoring, sports analytics, and autonomous systems.
This project demonstrates how video frames can be processed, analysed, and tracked using a combination of classical computer vision and deep learning-based techniques.

**Dataset and Input**

The project uses video files and extracted frames as input.
Frames are processed individually and across sequences to analyse object movement and tracking behaviour.
Data preparation and frame extraction are handled using OpenCV functions.

**Tools and Libraries**

- Python
  
- OpenCV (cv2) for video and image processing

- PyTorch and Torchvision for deep learning components

- NumPy for numerical operations

- Matplotlib for visualisation
  
**Approach**

The workflow of the project includes:

- Reading video files and extracting frames

- Preprocessing images (resizing, normalisation, transformations)

- Applying CNN-based models for object detection

- Identifying object regions and bounding boxes

- Tracking detected objects across consecutive frames
  
**Visualising detection and tracking results**

Both deep learning and traditional image processing steps are used to analyse object behaviour across time.
Results
The model is able to:

- Detect objects within video frames

- Track object movement across multiple frames

- Visualise bounding boxes and trajectories
   
Example outputs and tracking visualisations are available in the results folder.

**How to Run**
1. Install dependencies:

pip install -r requirements.txt

2. Open the notebook:

   jupyter notebook notebooks/object_detection_and_tracking.ipynb
   
4. Run all cells to reproduce the detection and tracking results.
