# Awesome Dynamic Point Cloud / Point Cloud Video / Point Cloud Sequence / 4D Point Cloud Analysis

If you find any related paper, please kindly let me know. I will keep updating the page. Thanks for your valuable contribution. 

For two-frame sence flow estimation, please refer to [Awesome Point Cloud Scene Flow](https://github.com/MaxChanger/awesome-point-cloud-scene-flow).

## I. Video/Sqeuence-level Classification
### 1. MSR-Action3D
| No. | Method                                                                   |      4      |      8      |      12     |      16     |    20       |      24     |
| ----| ------------------------------------------------------------------------ | ----------- | ----------- | ----------- | ----------- | ----------- | ----------- |
| 1   | [MeteorNet](https://github.com/xingyul/meteornet)                        |    78.11    |    81.14    |    86.53    |    88.21    |      -      |    88.50    |
| 2   | [P4Transformer](https://github.com/hehefan/P4Transformer)                |    80.13    |    83.17    |    87.54    |    89.56    |    90.24    |    90.94    |
| 3   | [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)   |    81.14    |    83.50    |    87.88    |    89.90    |      -      |    91.20    |
| 4   | [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)   |    77.66    |    86.45    |    88.64    |    89.56    |    91.21    |    91.94    |
| 5   | [PSTNet++](https://github.com/hehefan/PSTNet2)                           |    81.53    |    83.50    |    88.15    |    90.24    |      -      |    92.68    |
| 6   | Anchor-Based Spatio-Temporal Attention                                   |    80.13    |    87.54    |    89.90    |    91.24    |      -      |    93.03    |
| 7   | [PST-Transformer](https://github.com/hehefan/PST-Transformer)            |    81.14   |     83.97    |    88.15    |    91.98    |      -      |93.73    |
| 8   | [Kinet](https://github.com/jx-zhong-for-academic-purpose/Kinet)          |    79.80    |    83.84    |    88.53    |    91.92    |      -      |    93.27    |
| 9   | PST<sup>2</sup> (MeteorNet + STSA)                                       |    81.14    |    86.53    |    88.55    |    89.22    |      -      | -  | 

### 2. NTU RBG+D 60
| No. | Method                                                                    | Cross Subject | Cross View  |
| ----| ------------------------------------------------------------------------- | ----------- | ------------- |
| 1   | [3DV-PointNet++](https://github.com/3huo/3DV-Action)                      |      88.8   |     96.3    |
| 2   | [P4Transformer](https://github.com/hehefan/P4Transformer)                 |      90.2   |     96.4    |
| 3   | [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)    |      90.5   |     96.5    |
| 4   | [PSTNet++](https://github.com/hehefan/PSTNet2)                            |      91.4   |     96.7    |
| 5   | [PST-Transformer](https://github.com/hehefan/PST-Transformer)             |      91.0   |     96.4    |
| 6   | [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)    |      90.3   |     97.6    |
| 7   | [Kinet](https://github.com/jx-zhong-for-academic-purpose/Kinet)           |      92.3   |     96.4    |



### 3. NTU RBG+D 120
| No. | Method                                                                    | Cross Subject | Cross Setup |
| ----| ------------------------------------------------------------------------- | ----------- | ------------- |
| 1   | [3DV-PointNet++](https://github.com/3huo/3DV-Action)                      |      82.4   |     93.5    |
| 2   | [P4Transformer](https://github.com/hehefan/P4Transformer)                 |      86.4   |     93.5    |
| 3   | [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)    |      87.0   |     93.8    |
| 4   | [PSTNet++](https://github.com/hehefan/PSTNet2)                            |      88.6   |     93.8    |
| 5   | [PST-Transformer](https://github.com/hehefan/PST-Transformer)             |      87.5   |     94.0    |
| 6   | [SequentialPointNet](https://github.com/XingLi1012/SequentialPointNet)    |      83.5   |     95.4    |


### 4. SHREC'17
| No. | Method                                                                    | Acc         |
| ----| ------------------------------------------------------------------------- | ----------- | 
| 1   | [PointLSTM (Min et al.)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch)  | 94.7    |
| 2   | [Kinet](https://github.com/jx-zhong-for-academic-purpose/Kinet)           |   95.2      |

### 5. NvGesture
| No. | Method                                                                    | Acc         |
| ----| ------------------------------------------------------------------------- | ----------- | 
| 1   | FlickerNet                                                                | 86.3        |
| 2   | [PointLSTM (Min et al.)](https://github.com/ycmin95/pointlstm-gesture-recognition-pytorch)  | 87.5    |
| 3   | [Kinet](https://github.com/jx-zhong-for-academic-purpose/Kinet)           |  89.1       |


## II. Point-level Segmentation
### 1. Synthia 4D
| No. | Method                                                                        | mIoU (3 frames) |
| ----| ----------------------------------------------------------------------------- | --------------- |
| 1   | [MinkNet14](https://github.com/chrischoy/SpatioTemporalSegmentation)          |      77.46      |
| 2   | [MeteorNet](https://github.com/xingyul/meteornet)                             |      81.80      |
| 3   | [PSTNet](https://github.com/hehefan/Point-Spatio-Temporal-Convolution)        |      82.24      |
| 4   | [PSTNet++](https://github.com/hehefan/PSTNet2)                                |      82.60      |
| 5   | [ASAP-Net](https://github.com/intrepidChw/ASAP-Net)                           |      82.73      |
| 6   | [P4Transformer](https://github.com/hehefan/P4Transformer)                     |      83.16      |
| 7   | [PST-Transformer](https://github.com/hehefan/PST-Transformer)                 |      83.95      |
| 8   | Anchor-Based Spatio-Temporal Attention                                        |      84.77      |
| 9   | PST<sup>2</sup>                                                               |      81.86      |


### 2. [SemanticKITTI](http://www.semantic-kitti.org/tasks.html#semseg)
| No. | Paper Title                                                                                                                  |      Venue      |
| ----|------------------------------------------------------------------------------------------------------------------------------| --------------- |
| 1   | SpSequenceNet: Semantic Segmentation Network on 4D Point Clouds                                                              |    CVPR'20      |
| 2   | LiDAR-based Recurrent 3D Semantic Segmentation with Temporal Memory Alignment                                                |    3DV'20       |
| 3   | [4D Panoptic LiDAR Segmentation](https://github.com/MehmetAygun/4D-PLS)                                                      |    CVPR'21      |
| 4   | Spatial-Temporal Transformer for 3D Point Cloud Sequences (PST<sup>2</sup>)                                                  |    WACV'22      |
| 5   | [LiDAR-based 4D Panoptic Segmentation via Dynamic Shifting Network](https://github.com/hongfz16/DS-Net)                      |    arXiv'22     |

## III. Other Task
| No. | Paper Title                                                                                                                  |      Venue      |
| ----|------------------------------------------------------------------------------------------------------------------------------| --------------- |
| 1   | Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting with a Single Convolutional Net         |    CVPR'18      |
| 2   | [PointRNN: Point Recurrent Neural Network for Moving Point Cloud Processing](https://github.com/hehefan/PointRNN)            |    arXiv'19     |
| 3   | [Occupancy Flow: 4D Reconstruction by Learning Particle Dynamics](https://github.com/autonomousvision/occupancy_flow)        |    ICCV'19      |
| 4   | [Tranquil Clouds: Neural Networks for Learning Temporally Coherent Features in Point Clouds](https://ge.in.tum.de/publications/2020-iclr-prantl/)  |ICLR'20| 
| 5   | [CaSPR: Learning Canonical Spatiotemporal Point Cloud Representations](https://geometry.stanford.edu/projects/caspr/)        |    NeurIPS'20   |
| 6   | [Learning Scene Dynamics from Point Cloud Sequences](https://github.com/BestSonny/SPCM)                                      |    IJCV'21      |
| 7   | [Moving Object Segmentation in 3D LiDAR Data: A Learning-based Approach Exploiting Sequential Data](https://github.com/PRBonn/LiDAR-MOS) | RAL'21 |
| 8   | [PointINet: Point Cloud Frame Interpolation Network](https://github.com/ispc-lab/PointINet)                                  |    AAAI'21      |
| 9   | [Self-supervised Point Cloud Prediction Using 3D Spatio-temporal Convolutional Networks](https://github.com/PRBonn/point-cloud-prediction) | CoRL'21 |
| 10   | TPU-GAN: Learning Temporal Coherence From Dynamic Point Cloud Sequences                                                     |    ICLR'22      |
| 11  | [HOI4D: A 4D Egocentric Dataset for Category-Level Human-Object Interaction](https://hoi4d.github.io)                        |    CVPR'22      |
| 12  | [IDEA-Net: Dynamic 3D Point Cloud Interpolation via Deep Embedding Alignment](https://github.com/ZENGYIMING-EAMON/IDEA-Net)  |    CVPR'22      |
