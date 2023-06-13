*Intro:*
In this repository I implemented an Android application with fine-tuned YOLOv5 algorithm. The dataset YOLO algorithm was trained on is a KITTI dataset. The KITTI dataset is a widely used benchmark dataset for 2D object detection, particularly in the field of autonomous driving. It was created by the Karlsruhe Institute of Technology and the Toyota Technological Institute at Chicago (hence the name KITTI) to support research and development in the areas of computer vision and robotics.

The KITTI dataset focuses on various aspects of autonomous driving, including object detection, tracking, and scene understanding. For 2D object detection specifically, the dataset provides labeled images along with bounding box annotations for different object classes. The objects of interest include pedestrians, cars, cyclists, and others commonly encountered in urban driving scenarios. 

Hyperparameters that I chose were batch_size=16, epochs=155 and pre-trained on COCO dataset YOLOv5n (nano) model.

Meanwhile I linked Tensorboard for monitoring of a training process of the model.
Here is the training process of yolov5 model on KITTI dataset for 2-d object detection:
![](https://github.com/trybushenko/Android_YOLO/blob/master/media/desktop_recording.ogv.gif)

