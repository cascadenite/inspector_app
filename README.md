# iOS APP for Housing damage detection.

A mobile app that uses ssd mobilenet model trained in Tensorflow Objection Detection API to detect cracks and peeling paint in houses.

## Training

The model used was a ssd_mobilenet_v3 pre-trained on COCO dataset.  Fine-tuning was then done on a bespoke dataset of images taken around my house and crawled from google image search.  For example:

![img1](paintCrackIMG_1490.png) 

![img1](toSortIMG_1585.png) 
