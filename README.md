# mask_reminder
A fast mask detection app implemented using Keras, inspired by [allanzelener/YAD2K](https://github.com/allanzelener/YAD2K). It serves to remind people to wear masks correctly. 


## Usage

1. Download YOLOv3 weights from [YOLO website](http://pjreddie.com/darknet/yolo/).
2. Convert the Darknet YOLO model to a Keras model.
3. Run YOLO detection.

```
wget https://pjreddie.com/media/files/yolov3.weights
python convert.py yolov3.cfg yolov3.weights model_data/yolo.h5
python yolo_video.py [OPTIONS...] --image, for image detection mode, OR
python yolo_video.py [video_path] [output_path (optional)]
```

## Demo
<img src="https://github.com/PhoebeCheng9911/mask_reminder/assets/90079020/0f0d033d-1a2c-4bdc-b7d0-0ad978b957e9" width="420" height="370"> 
<img width="300" src="https://github.com/PhoebeCheng9911/mask_reminder/assets/90079020/09208303-a775-49da-8542-0a87eae5e6e0">
