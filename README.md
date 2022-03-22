# A Real Time Vehicle Counting System using YOLO
**You only look once (YOLO)** is a state-of-the-art, real-time object detection system. YOLO algorithm employs convolutional neural networks (CNN) to detect objects in real-time.  </br>

**Object detection** is a phenomenon in computer vision that involves the detection of various objects in digital images or videos. Object detection consists of various approaches such as fast R-CNN, Retina-Net, and Single-Shot MultiBox Detector (SSD). </br>
Why the YOLO algorithm is important

YOLO algorithm is important because of the following reasons:-
* Speed: This algorithm improves the speed of detection because it can predict objects in real-time.
* High accuracy: YOLO is a predictive technique that provides accurate results with minimal background errors.
* Learning capabilities: The algorithm has excellent learning capabilities that enable it to learn the representations of objects and apply them in object detection.

##### How the YOLO algorithm works
YOLO algorithm works using the following three techniques:
1. Residual blocks
2. Bounding box regression
3. Intersection Over Union (IOU)

##### Residual blocks
First, the image is divided into various grids. Each grid has a dimension of S x S. The following image shows how an input image is divided into grids.</br>

![image](https://user-images.githubusercontent.com/23136710/141470657-8f222b38-9aeb-4f6d-8895-e45bde6a1572.png) </br>
In the image above, there are many grid cells of equal dimension. Every grid cell will detect objects that appear within them. For example, if an object center appears within a certain grid cell, then this cell will be responsible for detecting it.
