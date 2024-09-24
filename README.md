## 简介

本人从yolov5源码上git下来，并且在train.py上加了一点注释。

主要的任务：

1. 搞清yolov5的网络结构图。
2. 熟悉 train.py detect.py coco128.yaml yolov5s.yaml源码。
3. 熟悉yolov5训练和推理过程。



## 训练和推理过程

### 1. 训练过程

（1）准备数据集，并且还要打上标签。

（2）在train.py中配置一些参数。

（3）在coco128.yaml中配置一些参数。

（3）执行命令行：python train.py。

（4）在runs/train下可以找到训练结果。

### 2. 推理过程

（1）在runs/train/exp/weights/下可以找到best.pt。

（2）在detect.py下配置一些参数。

（3）执行命令行：python detect.py。

（4）在runs/detect/下可以找到推理结果。
