## Intro:
In this repository I implemented an Android application with fine-tuned YOLOv5 algorithm. The dataset YOLO algorithm was trained on is a KITTI dataset. The KITTI dataset is a widely used benchmark dataset for 2D object detection, particularly in the field of autonomous driving. It was created by the Karlsruhe Institute of Technology and the Toyota Technological Institute at Chicago (hence the name KITTI) to support research and development in the areas of computer vision and robotics.

The KITTI dataset focuses on various aspects of autonomous driving, including object detection, tracking, and scene understanding. For 2D object detection specifically, the dataset provides labeled images along with bounding box annotations for different object classes. The objects of interest include pedestrians, cars, cyclists, and others commonly encountered in urban driving scenarios. 

__Hyperparameters that I chose were__: 
1) batch_size=16; 
2) epochs=155; 
3) pre-trained on COCO dataset YOLOv5n (nano) model.

Meanwhile I linked Tensorboard for monitoring of a training process of the model.
Here is the training process of yolov5 model on KITTI dataset for 2-d object detection:
![](https://github.com/trybushenko/Android_YOLO/blob/master/media/desktop_recording.ogv.gif)

The whole preprocessing of KITTI images, its renaming, training, validation, exporting etc. are in [yolov5/YOLO_setup.ipynb](https://github.com/trybushenko/Android_YOLO/blob/master/yolov5/YOLO_setup.ipynb) jupyter notebook. First thing first, check it out before viewing android application.

After training, validation and exporting the fine-tuned model I moved it to [../android/app/src/main/assets](https://github.com/trybushenko/Android_YOLO/tree/master/android/app/src/main/assets) directory.