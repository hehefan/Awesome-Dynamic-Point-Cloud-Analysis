# Dynamic Point Cloud / Point Cloud Video / Point Cloud Sequence

If you find any related paper, please kindly let me know. I will keep updating the page. Thanks for your valuable contribution. 

## Classification
### 1. MSR-Action3D
| Method                                                                   |      4      |      8      |      12     |      16     |    20       |      24     |
| ------------------------------------------------------------------------ | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| [MeteorNet](https://github.com/xingyul/meteornet)                        |    78.11    |    81.14    |    86.53    |    88.21    |      -      |    88.50    |
| [P4Transformer](https://github.com/hehefan/P4Transformer)                |    80.13    |    83.17    |    87.54    |    89.56    |    90.24    |    90.94    |
| [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)   |    81.14    |    83.50    |    87.88    |    89.90    |      -      |    91.20    |
| [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)   |    77.66    |    86.45    |    88.64    |    89.56    |    91.21    |    91.94    |
| [PSTNet++](https://github.com/hehefan/PSTNet2)                           |    81.53    |    83.50    |    88.15    |    90.24    |      -      |    92.68    |
| Anchor-Based Spatio-Temporal Attention                                   |    80.13    |    87.54    |    89.90    |    91.24    |      -      |    93.03    |


### 2. NTU RBG+D 60
| Method                                                                    | Cross Subject | Cross View  |
| ------------------------------------------------------------------------- | ----------- | ------------- |
| [3DV-PointNet++](https://github.com/3huo/3DV-Action)                      |      88.8   |     96.3    |
| [P4Transformer](https://github.com/hehefan/P4Transformer)                 |      90.2   |     96.4    |
| [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)    |      90.5   |     96.5    |
| [PSTNet++](https://github.com/hehefan/PSTNet2)                            |      91.4   |     96.7    |
| [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)    |      90.3   |     97.6    |



### 3. NTU RBG+D 120
| Method                                                                    | Cross Subject | Cross Setup |
| ------------------------------------------------------------------------- | ----------- | ------------- |
| [3DV-PointNet++](https://github.com/3huo/3DV-Action)                      |      82.4   |     93.5    |
| [P4Transformer](https://github.com/hehefan/P4Transformer)                 |      86.4   |     93.5    |
| [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)    |      87.0   |     93.8    |
| [PSTNet++](https://github.com/hehefan/PSTNet2)                            |      88.6   |     93.8    |
| [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)    |      83.5   |     95.4    |


## Segmentation
### 1. Synthia 4D
| Method                                                                        | mIoU (3 frames) |
| ----------------------------------------------------------------------------- | --------------- |
| [MinkNet14](https://github.com/chrischoy/SpatioTemporalSegmentation)          |      77.46      |
| [MeteorNet](https://github.com/xingyul/meteornet)                             |      81.80      |
| [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)        |      82.24      |
| [PSTNet++](https://github.com/hehefan/PSTNet2)                                |      82.60      |
| [ASAP-Net](https://github.com/intrepidChw/ASAP-Net)                           |      82.73      |
| [P4Transformer](https://github.com/hehefan/P4Transformer)                     |      83.16      |
| Anchor-Based Spatio-Temporal Attention                                        |      84.77      |
