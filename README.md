![Darknet Logo](http://pjreddie.com/media/files/darknet-black-small.png)

#Darknet#
Darknet is an open source neural network framework written in C and CUDA. It is fast, easy to install, and supports CPU and GPU computation.


# run project
download repo
download weights

### FaceDectection Webcam

```
./darknet yolo demo models/yolo-face.cfg backup/yolo-face_final.weights
```

### FaceDetection Movie

```
./darknet yolo demo models/yolo-face.cfg backup/yolo-face_final.weights demo_movie.mp4
```

For more information see the [Darknet project website](http://pjreddie.com/darknet).

For questions or issues please use the [Google Group](https://groups.google.com/forum/#!forum/darknet).
