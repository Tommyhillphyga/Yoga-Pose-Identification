# A Yoga Pose Identification Application
### About 
This app uses a YOLOV7 Pose Egit adstimation model and a lightweight weight TENSORFLOW LSTM model to detect human pose key points and classify six different yoga poses.
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

#download YOLOv7 Pose weight

![Poseestimation](https://user-images.githubusercontent.com/62513924/184828485-ec0dbb52-6e20-47f1-94ec-03fd1c6cb5fb.png)

#### References
- https://github.com/WongKinYiu/yolov7
- https://learnopencv.com/yolov7-object-detection-paper-explanation-and-inference/
- https://github.com/ultralytics/yolov5





