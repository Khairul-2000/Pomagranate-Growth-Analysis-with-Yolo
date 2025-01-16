## Overview
We'll training some of the  object detection model to recognize the Pomagranate Growth: bud,flower, early-fruit, mid-growth, ripe.




### **Our Data**

The dataset consists of images capturing various growth stages of pomegranates. The images were collected from May to September in an orchard located within the Henan Institute of Science and Technology in China. There are a total of 5857 images in the dataset, and each image is labeled and classified into one of five periods: bud, flower, early-fruit, mid-growth, and ripe.
The dataset was curated and hosted by the School of Computer Science and Technology at Henan University of Science and Technology, in collaboration with researchers from the Artificial Light Plant Factory at the same university.
When adapting this example to your own data, create two datasets in Roboflow: `train` and `test`. Use Roboflow to generate TFRecords for each, replace their URLs in this notebook, and you're able to train on your own custom dataset.

### **Our Model**

We'll be training YOLOV8 AND YOLOV5. This specific model is a one-short learner, meaning each image only passes through the network once to make a prediction, which allows the architecture to be very performant for mobile hardware.



### **Training**

Google Colab provides free GPU resources. Click "Runtime" → "Change runtime type" → Hardware Accelerator dropdown to "GPU."

Colab does have memory limitations, and notebooks must be open in your browser to run. Sessions automatically clear themselves after 12 hours.



## Video Presentation 

https://github.com/user-attachments/assets/01c0b7ad-abd7-45e8-99d9-d624ed3d3ae0

