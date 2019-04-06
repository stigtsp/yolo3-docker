# yolo3-docker
Runs yolo3 in a docker container.

https://pjreddie.com/darknet/yolo/


```
$ docker build -t yolo3-docker .
$ xhosts + #This makes your X insecure!
$ docker run -it -e DISPLAY=$DISPLAY -v /tmp/.X11-unix:/tmp/.X11-unix yolo3-docker ./darknet detect cfg/yolov3.cfg yolov3.weights data/dog.jpg
```




OpenCV part copied from:
https://github.com/stempler/schickling-dockerfiles/tree/master/opencv
