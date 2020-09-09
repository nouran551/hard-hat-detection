# fastai  Object Detection - HelmetDetection

This repository is one of my projects during my internship in instadeep, And it is a challenge in Zindi; Link to Competition: [Hard hat detection challenge by Instadeep](https://zindi.africa/hackathons/dsc-academy-hard-hat-detection-challenge/data)

It shows how to deploy Object Detection API - fast ai and give specific tutorials. It is based on [Object Detection](https://github.com/tensorflow/models/tree/master/research/object_detection). A specific example is to detect helmet, it could also explore to any other object detection tasks.

This is how to build an object detector for a custom dataset. You can find the custom dataset in [My drive Folder](https://drive.google.com/drive/folders/1jO1PA_J6-0P_-OpgKHJhRzymHqsWdbsO?usp=sharing). The goal is to detect the helmet, head, and bbox in the images.

<p float="left">
<img src=images/111.png />
<img src=images/222.png/>
</p>

## Dataset
#### This dataset, contains 5269 images with bounding box annotations as a test set in the PASCAL VOC format for these 3 classes:

* Helmet
* Person.
* Head.

#### And 1766 images as a test set, of total 7035 images.

## Annotations
Annotations in the PASCAL VOC format, saved as [CSV File](https://drive.google.com/file/d/1RRNWCmzuGeaaF3xfQyEUjVP0abc3RO2M/view?usp=sharing), After some processing on the CSV file and loading it to a Pandas df

<p float="center">
<img src=images/333.png/>
</p>
