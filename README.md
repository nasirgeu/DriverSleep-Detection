# DriverSleep-Detection
Made this model using Yolov5, PyTorch and OpenCV to detect whether a driver is sleeping or not.
# Outline
1. Installing Ultralytics YOLO (Extention of YoloV4)
2. Making Detections (Awake or Sleeping/Drowsy)
3. Training our Model
4. Real Time performance

# How it Works?
1. Installing YOLO V5.
2. Label Images using LabelImg with exports to YOLO Formats.
3. Real Time image rendering from scratch.

## A. Install and Import Dependencies
1. PyTorch : PyTorch is a machine learning framework based on the Torch library, used for applications such as computer vision and natural language processing, originally developed by Meta AI and now part of the Linux Foundation umbrella. It is free and open-source software released under the Modified BSD license.

2. Yolov5 : YOLOv5 🚀 is a family of compound-scaled object detection models trained on the COCO dataset, and includes simple functionality for Test Time Augmentation (TTA), model ensembling, hyperparameter evolution, and export to ONNX, CoreML and TFLite


(Import them listed below: ) <br>
3. Torch (used to load YOLO model and make detection) <br> 
4. matplotlib (for visualizing images) <br>
5. numpy (strong array transformation) <br>
6. Cv2 (webcam access)

## Load Model
=> Model can load using  "torch.hub.load('ultralytics/yolov5', 'yolo5s') <br>
=> Here s represent Small, (alternative => s, m, l, x)

## Make Model From Scratch
1. Create A dataset
2. Label it using LabelImg
3. Train the model
4. Render and display


# Reference
[Youtube](https://www.youtube.com/watch?v=tFNJGim3FXw) <br>
[UltraLytics YoloV5](https://pytorch.org/hub/ultralytics_yolov5/#:~:text=YOLOv5%20%F0%9F%9A%80%20is%20a%20family,to%20ONNX%2C%20CoreML%20and%20TFLite.) <br>
[LabelImg](https://github.com/heartexlabs/labelImg)
