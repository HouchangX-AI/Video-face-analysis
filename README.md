# Video-face-analysis
开课吧&后厂理工学院 百度cv2期：人脸检测+人脸追踪+人脸识别+表情分类。

## 数据
适用于监控视频等摄像头移动较小的视频。

人脸检测与人脸识别数据集均为内部拍摄制作，人脸检测数据集基于faceboxes网络基础上获取人脸位置，共1944张图像；人脸识别数据集为裁剪后人脸，共7类每人约700张人脸图像；表情识别数据集为affectnet，训练集为287,542张8类表情图像，测试集为5000张，存在类别不平衡情况。

## 人脸检测
[FaceBoxes](https://github.com/zisianw/FaceBoxes.PyTorch)

## 人脸追踪
[Kernelized Correlation Filters](https://github.com/uoip/KCFpy)

## 人脸识别
[Light CNN ](https://github.com/AlfredXiangWu/LightCNN)

## 表情分类
mobilev3+attention+weight-loss 准确率达到60.6%




