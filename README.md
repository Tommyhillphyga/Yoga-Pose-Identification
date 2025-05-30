# A Yoga Pose Identification Application
### About 
This app uses a YOLOV7 Pose estimation model and a lightweight weight TENSORFLOW LSTM model to detect human pose key points and classify six different yoga poses.
### run Demo
- Clone repo
- install requirements
```
pip install -r requirements.txt
```
- Run the following command:
```
python pose-identification.py --poseweights yolov7-w6-pose.pt --source testvideo1.mp4
```

#download YOLOv7 Pose weight <a href="https://github.com/WongKinYiu/yolov7/releases/download/v0.1/yolov7-w6-pose.pt"> Here </a>


#### References
- https://github.com/WongKinYiu/yolov7
- https://learnopencv.com/yolov7-object-detection-paper-explanation-and-inference/
- https://github.com/ultralytics/yolov5





