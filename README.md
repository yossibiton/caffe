# Caffe for Object Detection
This fork is based on **Caffe for PVANET**, by Kye-Hyeon Kim, Yeongjae Cheon, Sanghoon Hong, Byungseok Roh, Minje Park (Intel Imaging and Camera Technology)

## Introduction

### Modifications made by Caffe for PVANET

- Implemented a new learning rate scheduling based on plateau detection.
- Implemented proposal layer for both CPU and GPU versions.
- Implemented NMS for both CPU and GPU versions.
- Copied RoI pooling layer and smoothed L1 loss layer from [py-faster-rcnn](https://github.com/rbgirshick/py-faster-rcnn)
- Applied a hotfix for 'average_loss'

### Additional modifications in this fork

- copied the Matlab interface from [Caffe for Faster R-CNN](https://github.com/ShaoqingRen/caffe) which is more advanced then the default matlab interface