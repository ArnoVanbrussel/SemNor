# 1 Computer Vision
 - Computer vision is a multidisciplinary field that enables computers to interpret and understand the visual world through digital images or videos. 
 - Its primary goal is to replicate the human visual system's ability to extract meaningful information from visual data. 
 - Computer vision aims to teach machines to "see" and comprehend the visual content of images and videos.

 - **Image Processing:** The manipulation and enhancement of images to improve their quality or extract useful information. 
 - **Feature Extraction:** Identifying and extracting relevant patterns, shapes, or objects from images. 
 - **Object Detection and Recognition:** Locating and classifying objects or specific features within images or video frames. 
 - **Image Segmentation:** Dividing an image into meaningful regions or segments based on shared characteristics. 
 - **Motion Analysis:** Analyzing the movement and changes in visual content over time, often used in video processing.
## 1.1 Every Image tells a story
- Goal of computer vision: perceive the “story” behind the picture. 
- Compute properties of the world 
	- 3D shape 
	- Color 
	- Names of people or objects 
	- What happened?
![[Pasted image 20241014123428.png]]
## 1.2 Challenges
![[Pasted image 20241014123455.png]]
## 1.3 Why Computer Vision?
- billions of images/day
- huge number of applications
## 1.4 Object Detection
- Waymo
- EasyMile
## 1.5 Object Tracking
- 6DoF head tracking
- Hand and body tracking
- 360 video capture
## 1.6 Object Identification
- Stargazing
- Mushroom identification
## 1.7 Evolution
- **Early Days (1960s-1970s):** 
	- Back then, people started making computer programs to work with pictures. But these early programs couldn't handle complicated images very well. 
- **Machine Learning (1980s-1990s):** 
	- Machine learning techniques began to be applied. This led to the development of algorithms for tasks such as object recognition and image classification. 
- **Deep Learning (2000s):** 
	- In the 2000s, deep learning techniques emerged, which use neural networks to learn patterns in images and videos. These algorithms have significantly improved the accuracy of computer vision tasks such as object detection and facial recognition. 
- **Real-Time (Recent Years):** 
	- Today, computers can do all of this in real-time. This means they can do it super fast, which is useful for things like self-driving cars, drones, and robots
# 2 Image Processing

- **Noise Reduction:** Images often contain noise, which is unwanted random variations in pixel values. Noise reduction techniques, such as filtering, are used to improve image quality. *Does not always mean clearer!
- **Image Enhancement:** Enhancement techniques can be applied to improve the visibility of certain features in an image, such as contrast stretching or histogram equalization. 
- **Image Scaling and Resizing:** Resizing images can be done to fit them into specific dimensions or reduce file size. Interpolation methods are used to resample pixel values when resizing.
## 2.1 Library
- OpenCV (OpenSource Computer Vision Library) is a versatile, open-source software library for computer vision and machine learning tasks. 
- OpenCV is used in diverse applications, including image and video analysis, object detection, feature extraction, 3D vision, augmented reality, facial recognition, and more. 
- Offers a rich set of functions and algorithms for image and video processing, enhancing tasks like filtering, resizing, and enhancement. 
- Pip install opencv-python
## 2.2 Mathematical basis
- Gaussian Blur and Fourier Transform
![[Pasted image 20241014124948.png]]
## 2.3 Noise Reduction
![[Pasted image 20241014125010.png]]
# 3 Image Feature Extraction
## 3.1 Feature Extraction
- Feature extraction is a critical step in computer vision, where the goal is to identify relevant and informative characteristics within an image. 
- These features serve as a basis for further analysis, such as object detection, image classification, or image segmentation. 
- Feature extraction methods can be broadly categorized into handcrafted feature extraction and learned feature extraction using deep learning techniques.
## 3.2 Features in Image
**High-level features**
- color features
- geometric features
- texture features
**Low-level features**
- pixels
![[Pasted image 20241014125246.png]]
## 3.3 Color Features
![[Pasted image 20241014125312.png]]
## 3.4 Geometric Features
- **Edge**: Represents abrupt changes in intensity in an image, often seen as lines or curves. Used for object detection and shape analysis.
- **Corner**: A point where intensity changes occur in multiple directions, making them good landmarks for tasks like feature matching and image stitching. 
- **Blob**: A region with similar intensity in an image, used for tasks like image segmentation and texture analysis
## 3.5 Pixel Features
- Pixel features refer to characteristics or attributes associated with individual pixels in an image. 
- Pixel features are typically represented as numerical values. 
- Pixel features are the result of image transformation, this process can be achieved by algorithms. 
- Each pixel in an image is associated with a set of numerical attributes or characteristics that describe various properties of that pixel, such as its color intensity, position, and so on. 
- For example, in grayscale images, the pixel's intensity is represented by a single numerical value ranging from 0 (black) to 255 (white).
![[Pasted image 20241014131125.png]]
## 3.6 Algorithms
- **SIFT (Scale-Invariant Feature Transform):** 
	- **Description:** SIFT is an algorithm that extracts key points and their descriptors from an image. It is known for its scale and rotation invariance, making it robust to changes in an object's size and orientation. 
	- **Key Points:** SIFT detects distinctive local features, such as corners and blobs, and computes descriptors that capture information about the surrounding region's texture and gradient. 
- **Frame Differencing:** 
	- **Description:** Frame differencing is an algorithm used for motion detection in video streams. It analyzes consecutive frames to identify areas of significant change, indicating movement. 
	- **Key Points:** Frame differencing works by calculating the absolute differences between successive frames. By comparing the current frame with the previous and next frames, it highlights regions where motion occurs. This method is effective for detecting simple movements but may struggle in scenarios with changing lighting conditions or camera shake. 
- **CAMShift (Continuously Adaptive Mean Shift):** 
	- **Description:** CAMShift is an algorithm used for object tracking in video streams. It adapts the mean shift algorithm to continuously update the position and size of the target object by analyzing its color histogram. 
	- **Key Points:** CAMShift tracks objects by using their color distribution and adjusts the search window size based on the object's dimensions, making it effective for objects that change in size and shape
# 4 Case Study
## 4.1 SIFT
