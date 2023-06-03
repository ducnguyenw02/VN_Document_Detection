## Results and models of Guided Anchoring Cascade RCNN on UIT-DODV dataset

|       Method       | Table  |  Figure  | Caption |  Formula | AP@.5 | AP@.75 | mAP |                                                                                 Config                                                                                  |                                                                                                                                                              Download                                                                                                                                                              |
| :----------------: | :-------: | :-----: | :-----: | :----------: | :-------: | :----: | :-----: | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|     Double-Head R-CNN    | 91.5 | 80.6 | 65.6 | 46.3 | 88.7 | 78.4 | 71.0 |             [config](https://github.com/ducnguyenw02/VN_Document_Detection/blob/main/dh_faster_rcnn_r50.py)              |                           [log]()                          |
|     Libra R-CNN    | 92.5 | 81.0 | 68.2 | 46.0 | 89.6 | 79.1 | 71.9 |       [config](https://github.com/ducnguyenw02/VN_Document_Detection/blob/main/libra_faster_rcnn_x101.py)        |               [log]()              |
|     Guided Anchoring Faster R-CNN     | 92.7 | 81.6 | 73.3 | 46.9 | 91.0 | 80.8 | 73.6   |                   [config](https://github.com/ducnguyenw02/VN_Document_Detection/blob/main/ga_faster_rcnn_x101.py)                   |                          [log]()                         |
|     CascadeTabNet + Fused Loss     | 94.3 | 83.0 | 73.3 | 47.5 | 89.1 | 81.6 | 74.5    |       [config]()       |             [log]()             |
|     Guided Anchoring Cascade R-CNN (Ours)     | 95.4 | 84.8 | 75.9 | 50.5 | 91.8 | 83.1 | 76.6 |           [config](https://github.com/ducnguyenw02/VN_Document_Detection/blob/main/ga_cascade_rcnn_x101.py)            |                       [log]()

## Installation
- Please setup [UIT-DODV dataset](https://github.com/nguyenvd-uit/uit-together-dataset/blob/main/UIT-DODV.md) for MMDetection.

- This repository builds upon [MMDetection](https://github.com/open-mmlab/mmdetection). 
See [The MMDetection documentation](https://github.com/open-mmlab/mmdetection/blob/master/docs/en/get_started.md) for installation instructions.
