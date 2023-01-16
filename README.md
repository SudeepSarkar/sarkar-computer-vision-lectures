
## Computer Vision Course 

taught by Prof. Sudeep Sarkar, University of South Florida, Tampa, USA

A series of Colab (Jupyter) notebooks that walk you through the fundamentals of Computer Vision in python/opencv/pytorch/numpy/scipy. 

This is a graduate elective course in the general theme of artificial intelligence (AI) and will teach you about algorithms to extract information from images and video. We will learn about the problems of segmentation, tracking, extraction of geometric transforms in images, estimation of 3D information from a 2D image(s), and object detection and recognition using traditional and deep learning methods. 

### Installation

Clone this repository. See how to do it  -- https://www.geeksforgeeks.org/how-to-clone-github-repository-and-push-changes-in-colaboratory/

### Course Objectives

- Solve the core problems in computer vision, including segmentation, low-level features, tracking, 2D and 3D image geometry, structure from motion, stereo, and object recognition.

- Use traditional approaches and new deep learning-based solutions to solve computer vision problems.

- Apply the theoretical pinning of the major solution approaches

- Write computer vision code based on this understanding to solve real-life problems.

### Textbooks 

1. **Main: Richard Szeliski (2022) Computer Vision: Algorithms and Applications, ISBN 978-3030343712, Springer (second edition)**. The pdf of the book (Current draft, second edition) is available at http://szeliski.org/Book for free for personal use. 

2. Nalwa, Vishvjit (1993) A Guided Tour of Computer Vision, Addison-Wesley, Reading MA (ISBN 1-201-54853-4).

3. Jain, Ramesh, Rangachar Kasturi, and Brian G. Schunck (1995), Machine Vision, McGraw-Hill, New York (ISBN 0-07-032018-7).


### Course Structure 

The course is divided into 9 modules, each covering a topic area in computer vision. Each module is further divided into single class session notebooks. Two class sessions constitute a week. The entire set of modules is meant for a semester long course over 14 weeks. Each class session notebook include reading materials and assignments that involve running some variation of a code or solving some math problem, or providing explanations.


- Module 1: Image operations (Chapters 2 and 3)
  - Module 1.1: Digital camera (Section 2.3), Images and videos as arrays, image thresholding (text separation, text scanning apps) 
  - Module 1.2: Geometric primitives and transformations: 2D transformations (Section 2.1) 
  - Module 1.3: Pixel operations and histogram equalization (Section 3.1) 
- Module 2: Perspective Camera Model (Chapters 2)
  - Module 2.1: Perspective camera, intrinsic and extrinsic, 3D rigid (Section 2.1)
  - Module 2.2: Perspective camera, intrinsic and extrinsic, 3D rigid (Section 2.1)
- Module 3: Linear filtering (Chapters 3)
  - Module 3.1: Linear filtering, Gaussian convolutions, and its derivatives (Section 3.2)
  - Module 3.2: Linear filtering, Gaussian convolutions, and its derivatives (Section 3.2)
  - Module 3.3: Linear filtering, Gaussian convolutions, and its derivatives (Section 3.2) 
- Module 4: Point features and matching (Chapters 3)
  - Lecture 4.1: Multiresolution representations (image pyramids) (Section 3.5)
  - Lecture 4.2: SIFT feature detector and descriptor (Section 7.1)
  - Lecture 4.3: Feature matching, Hungarian, kinds of errors, ROC curves (Section 7.1.3)
  - Lecture 4.4: Estimating 2D to 2D matching
- Module 5: Object labeling using Deep Learning (Chapters 5 and 6)
  - Lecture 5.1: Deep Learning Networks basics – Single layer network with regression (Section 5.3)
  - Lecture 5.2: Multilayer Perceptron (MLP) (Section 5.3)
  - Lecture 5.3: Convolution Neural Networks: Le-Net (MLP)
  - Lecture 5.4: Convolution Neural Networks: Alex Net (Section 5.4)
  - Lecture 5.5: Convolution Neural Networks: VGG, ResNet (Section 5.4)
- Module 6: Object localization using Deep Learning (Chapters 5 and 6)
  - Lecture 6.1: Object Detection (SSD) (Section 6.3, 6.4)
  - Lecture 6.2: Region-based CNNs, R-CNN, Fast R-CNN, Faster R-CNN, Mask R-CNN (Section 6.4)
  - Lecture 6.3: Semantic Segmentation – Fully Convolutional Networks (FCN) (Section 6.4)
- Module 7: 2D to 3D pose alignment
  - Lecture 7.1: 2D to 3D pose alignment, camera calibration (Section 11.2.1)
  - Lecture 7.2: 2D to 3D pose alignment, camera calibration (Section 11.2.2)
- Module 8: 3D from 2D
  - Lecture 8:1: 3D from 2D – 2-camera, known geometry, stereo (Section 12.1, 12.3)
  - Lecture 8.2: 3D from 2D - multi-camera, known geometry, triangulation (Section 11.2.4)
  - Lecture 8.3: 3D from 2D - multi-camera, known geometry, triangulation (Section 11.2.4)
  - Lecture 8.4: 3D from 2D – 2-frame, unknown geometry (motion) (Section 11.3)
- Module 9: Video processing
  - Lecture 9.1: Object tracking (Kalman)
  - Lecture 9.2: Object tracking (Kalman)
