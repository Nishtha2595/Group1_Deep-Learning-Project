# Group1_Deep Learning-Project
**Project Name: Smart Traffic Signals using Object Detection**


**Group Members:**

Pranoy Peas-B2020038

Antony Chris Sam- B2020068

Clarion Chako- B2020077

Diwakar Bhardwaj- B2020078

Nishtha Garg- B2020093


**Problem Statement:**

The purpose of transportation research is to improve the flow of people and goods across the country. As the world's population grows, so does the number of people who travel, and the resources offered by current infrastructures are insufficient to meet this demand. As a result, intelligent traffic control has become a critical concern. The majority of traffic in metropolitan areas is controlled by fixed cycle traffic signal lights, which are frequently misconfigured, resulting in unnecessary vehicle delays.

In recent years, the use of image processing methods in automated traffic monitoring and control systems has been examined in order to improve traffic control procedures. There's also the ever-growing issue of traffic violations. As a result, we've deployed cameras with more automation potential to reduce our reliance on traffic cops and increase productivity.

The goal of this project is to present an intelligent synchronised traffic signal monitoring system to improve traffic monitoring and the way we deal with various transportation-related issues and circumstances. It will be part of a smart traffic system.


**Introduction:**

The challenge of locating and classifying a variable number of items on a picture is known as object detection. The "variable" component is the key distinction. Unlike tasks like classification, object detection produces a variable length output because the number of items spotted can vary from image to image.

**Image classification vs Image localization vs Object Detection**

Image Classification helps us to classify what is contained in an image. Image Localization will specify the location of single object in an image whereas Object Detection specifies the location of multiple objects in the image. Finally, Image Segmentation will create a pixel wise mask of each object in the images.

**Challenges in object detection**

Object detection is traditionally thought to be significantly more difficult than image classification, owing to the following five difficulties: dual priority, speed, various scales, limited data, and class imbalance.


**Algorithm Used**

**Faster RCNN-** Faster R-CNN is an object detection framework based on deep convolutional networks, which includes a Region Proposal Network (RPN) and an Object Detection Network. Both networks are trained for sharing convolutional layers for fast testing. Instead of using selective search algorithm on the feature map to identify the region proposals, a separate network is used to predict the region proposals. The predicted region proposals are then reshaped using a RoI pooling layer which is then used to classify the image within the proposed region and predict the offset values for the bounding boxes.


**Conclusion:**

We have successfully created a system for real-time video processing-based intelligent traffic monitoring that detects, counts, and identifies cars, as well as making decisions to control traffic jams. We demonstrated the benefits of combining OpenCV's computer vision approach with machine learning for an automated traffic control system. As a result, we can be confident that our proposed solution will be useful for traffic analysis and improvement.
