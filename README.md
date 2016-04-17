# PicOutPedestrian
Using opencv to detect people in images

### NMS
I used the non-maxima suppression algorithm (from imutils package) which takes multiple overlapping bounding boxes and reduces them to one. This should help reduce the number of false detections in the final detector.

###Images
The images used are samples from the INRIA person dataset

###Try it out
Along with opencv, you will need imutils.

`pip install imutils`

###Give it a goo!

`python detect.py --images images`

