# Detection & Relocalization based on CenterPoint

3D Object Detection and Relocalization using CenterPoint in dataset [3RScan](https://github.com/WaldJohannaU/3RScan) and [Scannet](http://www.scan-net.org/).

<p align="center"> <img src='docs/CenterPoint.png' align="center" height="230px"> </p>

> [**3D Object Detection and Relocalization in Indoor Scenes**](https://github.com/xiongyiheng/xiongyiheng.github.io/blob/main/report/3D_Object_Detection_and_Relocalization_in_Indoor_Scenes.pdf),            
> Yiheng Xiong, Jingsong Liu        

We provide two configs, [rio_model.yaml](tools/cfgs/rio_configs/rio_model.yaml) for the centerpoint model on 3RScan and [scannet_model.yaml](tools/cfgs/scannet_configs/scannet_model.yaml) which executes centerpoint on ScanNet.

## Installation
1. download the dataset (3RScan and Scannet).
2. refer [readme](https://github.com/tianweiy/CenterPoint/blob/master/README.md) of original CenterPoint repo to install all dependencies.

## Acknowledgement

Our code is based on [OpenPCDet](https://github.com/open-mmlab/OpenPCDet) and [CenterPoint](https://github.com/tianweiy/CenterPoint). Some util files are copied from [mmdetection](https://github.com/open-mmlab/mmdetection) and [mmdetection3d](https://github.com/open-mmlab/mmdetection3d). Thanks OpenMMLab Development Team for their awesome codebases.
