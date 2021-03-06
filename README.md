# Face-detection-with-landmarks
This is a human face detection project, which can detect human faces and mark key points at the same time

这是一个人脸与人脸关键点检测的 demo。

源代码来自于[libfacedetection.train](https://github.com/ShiqiYu/libfacedetection.train)，拥有很快的检测速度（FPS：~60）。

我在原先的基础上做了轻量与优化，使之能够批量处理图片并能处理视频。


## 用法<br>
运行 task 文件夹中的 ```detect.py``` 实现人脸检测。

在此之前，请保证待检测的文件目录与数据是正确的。

## 注意<br>
处理不同分辨率的图像，检测速度将出现波动。

处理视频中的模糊帧易出现误检与漏检。

目前暂不支持模型训练，仅支持推理。


## 效果<br>
<p align="center">
	<img src="https://github.com/LeeWise9/Face-detection-with-key-point/blob/master/sample1.jpg" alt="Sample"  width="600">
</p>


<p align="center">
	<img src="https://github.com/LeeWise9/Face-detection-with-key-point/blob/master/sample0.jpg" alt="Sample"  width="600">
</p>
