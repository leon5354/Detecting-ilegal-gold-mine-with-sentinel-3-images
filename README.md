# Detecting-ilegal-mining-with-sentinel-2-images
Disseration Object Dectection

This is my disseration about detecting illegal mining from certian area.
Follow through the steps in the notebook to train the model.

You may also need to download the TF object dectection API to make the training work.

Software Requirement
Python 3.7.13
Opencv-python-headless 4.1.2.30
TensorFlow 2.9
CuDNN  8.1.0.77
Cuda 11.2
Pycocotools 2.0.4

It is to examine the possibility of using the imagery data from Earth observation mission “Sentinel-2” to detect illegal mining activities with transfer learning in deep neural networks. The idea is to transfer the learning result from a pre-trained model with more extensive database and hardware support and adapt and train the pre-trained model with the input of the satellite imagery dataset as supervised learning material about legal and illegal mining in hands and expect to output a model that can automatically recognise illegal mines. 

Preparation for the dataset included two stages. First, two bandings of illegal and legal mining activities are collected from Sentinel-2, and imagery data are annotated with bounding boxes.

Faster R-CNN ResNet 50 model pre-trained with the COCO dataset is chosen for research due to the time-efficient nature of the architecture from the model, which is considered a suitable model to begin the research. During the training section, the models conducted showed a certain level of performance, and the performance of the models was successfully improved by increasing the scale of the imagery input to the models during the training. 

In order to justify the trained model, new data has been introduced to the models in order to simulate the actual world situation, at this stage, the model performance showed significant regression, which shows the models are not ready for practical use and further research has to be conducted in the future to examine the possibility for the application satellite imagery data to identify illegal mining activities.

