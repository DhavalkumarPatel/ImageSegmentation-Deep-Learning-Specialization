# ImageSegmentation-Deep-Learning-Specialization
This repository is based on a project completed as part of the Deep Learning Specialization on Coursera by DeepLearning.AI. 

## Introduction

We will be building our own U-Net, a type of CNN designed for quick, precise image segmentation, and using it to predict a label for every single pixel in an image - in this case, an image from a self-driving car dataset. 

This type of image classification is called semantic image segmentation. It's similar to object detection in that both ask the question: "What objects are in this image and where in the image are those objects located?," but where object detection labels objects with bounding boxes that may include pixels that aren't part of the object, semantic image segmentation allows you to predict a precise mask for each object in the image by labeling each pixel in the image with its corresponding class.

As you might imagine, region-specific labeling is a pretty crucial consideration for self-driving cars, which require a pixel-perfect understanding of their environment so they can change lanes and avoid other cars, or any number of traffic obstacles that can put peoples' lives in danger. 

By the time you finish this notebook, you'll be able to: 

* Build your own U-Net
* Explain the difference between a regular CNN and a U-net
* Implement semantic image segmentation on the CARLA self-driving car dataset
* Apply sparse categorical crossentropy for pixelwise prediction

Onward, to this grand and glorious quest! 

## Credits and References
- [Deep Learning Specialization, Coursera](https://www.coursera.org/specializations/deep-learning?utm_medium=sem&utm_source=gg&utm_campaign=B2C_NAMER_deep-learning_deeplearning-ai_FTCOF_specializations_country-US-country-CA&campaignid=904733485&adgroupid=46370300620&device=c&keyword=coursera%20ai&matchtype=b&network=g&devicemodel=&adposition=&creativeid=415429098219&hide_mobile_promo&gclid=CjwKCAjw6eWnBhAKEiwADpnw9hljnzqyV-ElnDB_Tzr6cgek7YH6P3dWuoU2oR8EV71I6KW6XwS1PBoCokEQAvD_BwE)





