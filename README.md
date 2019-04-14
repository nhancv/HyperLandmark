#  Free Mobile Real-Time Face Landmark 106 points Localization

### Introduce
Conscience-level open source face calibration algorithm, face beauty, beauty, coordinated living detection, face calibration pre-processing steps. The project Windows project is based on the traditional SDM algorithm, by modifying the open source code, streamlining the test part of the code, Optimize the code structure. The Android code is based on deep learning. We designed an efficient network model. The model is robust and supports multi-face tracking. At present, the deep learning algorithm has achieved good results in the face calibration direction. Provide a more simple and easy to use implementation.


#### Related Resources
+ [HyperLandmark-iOS implementation based on SDM](https://github.com/elhoangvu/HyperLandmark-iOS) (2019.02.06)
+ [Related technology blog](https://blog.csdn.net/lsy17096535/article/details/81116221)
+ [Refer to the open source SDM algorithm](https://github.com/chengzhengxin/sdm)。
+ [Face calibration based on CNN](https://github.com/lsy17096535/face-landmark)。
+ [HyperLandmark 106 point number](https://github.com/zeusees/HyperLandmark/blob/master/images/landmark_order.png)

### Features

+ 106 points, the face contour description is more delicate
+ High accuracy, good calibration results in backlight and dark light conditions
+ The model is small, the tracking model is about 2MB, which is very suitable for mobile integration.
+ Fast, Android platform code in Qualcomm 820 (st) single face 7ms (2018.08.14)
+ Increase multi-face tracking

### APP

- Experience the Android app: [https://fir.im/HyperLandmark](https://fir.im/HyperLandmark)

### Latest Update

+ Add OpenGL based camera interface.

### TODO

+ Dense face landmark (800 points)
+ Facial action recognition
+ Euler angle , face pose estimation. 
+ Open source native tracking code.

### Notes

The Windows implementation is based on the free intraface implementation, which is not the same as android.

###  Rely

+ Windows demo relies on OpenCV
+ Android can be used directly


### Demo

![image](./resource/demo.gif)

![image](./resource/demo2.gif)

### Contact：

About face calibration We are conducting data collection and algorithm development, and technical exchanges and donation data can be added to the group.
+ Communication group 724142079

### Author
- [Jack Yu]( https://github.com/szad670401)(jack-yu-business@foxmail.com)






