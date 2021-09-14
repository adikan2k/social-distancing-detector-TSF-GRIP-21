<h1> SOCIAL DISTANCING DETECTOR </h1>
This is a social distaning detector built using YOLO(COCO Model) along with OpenCV.

<h1>What is social distancing?</h1>

Social distancing is a method used to control the spread of contagious diseases.
As the name suggests, social distancing implies that people should physically distance themselves from one another, reducing close contact, and thereby reducing the spread of a contagious disease (such as coronavirus/COVID 19):

![social_distance_detector_spread](https://user-images.githubusercontent.com/90503792/133211471-7f59893c-ea5a-46d8-9351-5782e43984b5.gif)

<h1>Using OpenCV, computer vision and deep learning for social distancing</h1>

We can use OpenCV, computer vision, and deep learning to implement social distancing detectors.
The steps to build a social distancing detector include:

1. Apply object detection to detect all people (and only people) in a video stream (see this tutorial on building an OpenCV people counter)
2. Compute the pairwise distances between all detected people
3. Based on these distances, check to see if any two people are less than N pixels apart

* <h2>YOLO COCO weights</h2>
The weight file exceeds the github limits but can be download from https://pjreddie.com/media/files/yolov3.weights.
Add the weight file to the yolo-coco folder.

* <h2>GPU</h2>
Provided you already have OpenCV installed with NVIDIA GPU support, all you need to do is set USE_GPU=True in your config.py file.

<h1> OUPUT DEMO </h1>
![demo](https://user-images.githubusercontent.com/90503792/133215394-398f8047-f741-4e03-8b16-60438a834ca9.gif)


<h1>Contact me</h1>
Email - <a href = kanbargi.adi2k@gmail.com>kanbargi.adi2k@gmail.com<a> 
  
LinkedIn - <a href = https://www.linkedin.com/in/aditya-kanbargi-1b434b1aa/>my profile</a>
  
  <h1> Happy coding :) </h1>  
