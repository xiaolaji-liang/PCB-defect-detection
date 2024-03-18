说明：本项目是基于YOLOv7网络改进的PCB表观缺陷检测方法，实验环境为：python3.8.15+torch1.13.1+cuda11.6。
1、cfg/training/yolov7.yaml是网络结构配置文件
2、data/pcb-data.yaml是数据配置文件
3、models文件中包含改进BiFormer、EVCBlock、P-ELAN的配置文件
4、utils里general.py包括MPDIoU损失函数的配置文件，loss.py中的bbox_iou改为MPDIoU损失函数
5、权重文件使用yolov7.pt,由于文件过大无法上传
6、数据集无法上传，有需要可以联系我
7、训练模型从train.py开始，参数根据硬件环境自己调整
