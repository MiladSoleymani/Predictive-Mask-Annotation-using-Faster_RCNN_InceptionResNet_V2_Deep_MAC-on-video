# Predictive Mask Annotation using Faster RCNN_InceptionResNet_V2 + Deep_MAC on video

Suppose we are developing a new labeling tool to annotate masks in a video. Labeling all the frames of a video with great accuracy takes a lot of time and cost. In order to make the annotation process faster, we need to use semi-automated or automated labeling methods.

In this repository, I have tried to make a pipeline using the mask_rcnn_inception_resnet_v2 combined with DEEPMAC pretrained model to detect and mask vehicles on the highway.  

### Results

- main video

https://user-images.githubusercontent.com/78655282/125610848-b75e9593-9cb7-4408-aad1-27344bea044c.mp4

- output video

https://user-images.githubusercontent.com/78655282/125618476-a597ed29-b7bd-446c-9440-8600bbd9372d.mp4

### References 

- [Mask R-CNN](https://arxiv.org/pdf/1703.06870.pdf)
- [The surprising impact of mask-head architecture on novel class segmentation](https://arxiv.org/pdf/2104.00613.pdf)

### Open source repositories on this grand

- [TensorFlow Object Detection API](https://github.com/tensorflow/models/tree/master/research/object_detection)
