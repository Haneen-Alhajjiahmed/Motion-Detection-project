# Motion-Detection-project
openCV + Python + flask for bulding a web page that stream out a live video. That detect any change in the frames of the vedio. For this project you will need an USB web camera or Raspberry Pi. The complete project attached.

## Project's architecture 

MotionDetectionProject
├── pyimagesearch
│   ├── motion_detection
│   │   ├── __init__.py
│   │   └── singlemotiondetector.py
│   └── __init__.py
├── templates
│   └── index.html
└── webstreaming.py

Note: you have to download the orginal module from the source. because pyimagesearch is not in PYPI.
https://www.pyimagesearch.com/2019/09/02/opencv-stream-video-to-web-browser-html-page/

## run the project
 - open the terminal 
 - run the installation commands (run them even if they exist because they may be an update):
 
       $ pip install flask
       $ pip install numpy
       $ pip install opencv-contrib-python
       $ pip install imutils
 - final command

       $ python webstreaming.py --ip 0.0.0.0 --port 8000
 then these information will be displayed:
 <img width="828" alt="Screen Shot 2021-07-17 at 12 56 25 AM" src="https://user-images.githubusercontent.com/85841915/126012560-37433738-b547-4432-ad43-bd58b6e762f2.png">
 The highlited part is taken to open the HTML page. everyone has a different URL based on his machine.
