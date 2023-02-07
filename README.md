# Safety_Glasses_detection
This code implemented using OpenCV and yolov5 custom model to detect safety glasses in video.

#how to riun this code
firstly, git clone yolov5 repo from ultralytics
https://github.com/ultralytics/yolov5.git

After that, change yolov5/detect.py with out detect.py file

Then run,
python detect.py --source glasses.mp4 --weights safety_glasses.pt --device 0 --view-img
