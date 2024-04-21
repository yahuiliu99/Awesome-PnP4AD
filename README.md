# Awesome Integrated Perception and Prediction for Autonomous Driving

This is a collection of research papers about **Integrated Perception and Prediction for Autonomous Driving (PnP4AD)**, and the repository will be continuously updated to track the frontier of this field. 

:clap:Welcome to follow and star! If you find any related papers or reports could be helpful, feel free to submit an issue or PR.

## Overview

**PnP4AD** refers to jointly handle perception (understanding the environment) and prediction (forecasting the future states of the environment) tasks within a unified framework or model with the input of multi-frame raw sensor data, instead of modularized and cascaded perception-then-prediction pipeline.  We categorize existing works based on the perspective of prediction representations: objects/agents,  instances/occupancy grids, and motions.

## Papers

### Object/Agent-Level 

#### Camera Input

- [arXiv 2022] Perceive, Interact, Predict: Learning Dynamic and Static Clues for End-to-End Motion Prediction [[paper](https://arxiv.org/pdf/2212.02181.pdf)]
- [CVPR 2023] ViP3D: End-to-End Visual Trajectory Prediction via 3D Agent Queries [[paper](https://arxiv.org/pdf/2208.01582.pdf)] [[Github](https://github.com/Tsinghua-MARS-Lab/ViP3D)]
- [ICCV 2023] VAD: Vectorized Scene Representation for Efficient Autonomous Driving [[paper](https://arxiv.org/pdf/2303.12077.pdf)] [[Github](https://github.com/hustvl/VAD)]

#### LiDAR Input

- [CVPR 2018] Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting with a Single Convolutional Net [[paper](https://arxiv.org/pdf/2012.12395.pdf)] 
- [CoRL 2018] IntentNet: Learning to Predict Intention from Raw Sensor Data [[paper](https://arxiv.org/pdf/2101.07907.pdf)]
- [CVPR 2019] End-to-End Interpretable Neural Motion Planner [[paper](https://arxiv.org/pdf/2101.06679.pdf)]
- [ICRA 2020] SpAGNN: Spatially-Aware Graph Neural Networks for Relational Behavior Forecasting from Sensor Data [[paper](https://arxiv.org/pdf/1910.08233.pdf)]
- [CVPR 2020] PnPNet: End-to-End Perception and Prediction with Tracking in the Loop [[paper](https://arxiv.org/pdf/2005.14711.pdf)]
- [CVPR 2020] STINet: Spatio-Temporal-Interactive Network for Pedestrian Detection and Trajectory Prediction [[paper](https://arxiv.org/pdf/2005.04255.pdf)]
- [ECCV 2020] Implicit Latent Variable Model for Scene-Consistent Motion Forecasting [[paper](https://arxiv.org/pdf/2007.12036.pdf)]
- [CoRL 2020] Inverting the Pose Forecasting Pipeline with SPF2: Sequential Pointcloud Forecasting for Sequential Pose Forecasting [[paper](https://arxiv.org/pdf/2003.08376.pdf)] [[Github](https://github.com/xinshuoweng/SPF2) :ghost:]
- [CVPR 2021] Deep Multi-Task Learning for Joint Localization, Perception, and Prediction [[paper](https://arxiv.org/pdf/2101.06720.pdf)]
- [ICCV 2021] LookOut: Diverse Multi-Future Prediction and Planning for Self-Driving [[paper](https://arxiv.org/pdf/2101.06547.pdf)]
- [CVPR 2022] Forecasting from LiDAR via Future Object Detection [[paper](https://arxiv.org/pdf/2203.16297.pdf)] [[Github](https://github.com/neeharperi/FutureDet)]

#### Multi-Modal

- [IROS 2020] End-to-end Contextual Perception and Prediction with Interaction Transformer [[paper](https://arxiv.org/pdf/2008.05927.pdf)]

### Instance/Occupancy-Level 

#### Camera Input

- [ICCV 2021] FIERY: Future Instance Prediction in Bird's-Eye View from Surround Monocular Cameras [[paper](https://arxiv.org/pdf/2104.10490.pdf)] [[Github](https://github.com/wayveai/fiery)]
- [ECCV 2022] StretchBEV: Stretching Future Instance Prediction Spatially and Temporally [[paper](https://arxiv.org/pdf/2203.13641.pdf)] [[Github](https://github.com/kaanakan/stretchbev)] 
- [arXiv 2022] BEVerse: Unified Perception and Prediction in Birds- Eye-View for Vision-Centric Autonomous Driving [[paper](https://arxiv.org/pdf/2205.09743.pdf)] [[Github](https://github.com/zhangyp15/BEVerse)]
- [ECCV 2022] ST-P3: End-to-end Vision-based Autonomous Driving via Spatial-Temporal Feature Learning [[paper](https://arxiv.org/pdf/2207.07601.pdf)] [[Github]( https://github.com/OpenPerceptionX/ST-P3)]
- [IJCAI 2023] PowerBEV: A Powerful Yet Lightweight Framework for Instance Prediction in Bird's-Eye View [[paper](https://arxiv.org/pdf/2306.10761.pdf)] [[Github](https://github.com/edwardleelpz/powerbev)]
- [CVPR 2023] TBP-Former: Learning Temporal Bird's-Eye-View Pyramid for Joint Perception and Prediction in Vision-Centric Autonomous Driving [[paper](https://arxiv.org/pdf/2303.09998.pdf)] [[Github](https://github.com/MediaBrain-SJTU/TBP-Former)​ :ghost:] 
- [arXiv 2023] Cam4DOcc: Benchmark for Camera-Only 4D Occupancy Forecasting in Autonomous Driving Applications [[paper](https://arxiv.org/pdf/2311.17663.pdf)] [[Github](https://github.com/haomo-ai/Cam4DOcc) :ghost:]

#### LiDAR Input

- [ECCV 2020] Perceive, Predict, and Plan: Safe Motion Planning Through Interpretable Semantic Representations [[paper](https://arxiv.org/pdf/2008.05930.pdf)]
- [CVPR 2021] MP3: A Unified Model to Map, Perceive, Predict and Plan [[paper](https://arxiv.org/pdf/2101.06806.pdf)] 
- [ECCV 2022] Differentiable Raycasting for Self-Supervised Occupancy Forecasting [[paper](https://arxiv.org/pdf/2210.01917.pdf)] [[Github](https://github.com/tarashakhurana/emergent-occ-forecasting)]
- [CVPR 2023] Point Cloud Forecasting as a Proxy for 4D Occupancy Forecasting [[paper](https://arxiv.org/pdf/2302.13130.pdf)] [[Github](https://github.com/tarashakhurana/4d-occ-forecasting)]
- [CVPR 2023] Implicit Occupancy Flow Fields for Perception and Prediction in Self-Driving [[paper](https://arxiv.org/pdf/2308.01471.pdf)] [[website](https://waabi.ai/implicito/)]
- [arXiv 2023] LiDAR-based 4D Occupancy Completion and Forecasting [[paper](https://arxiv.org/pdf/2310.11239.pdf)] [[Github](https://github.com/ai4ce/Occ4cast/)]

#### Multi-Modal 

- [CVPRW 2020] FISHING Net: Future Inference of Semantic Heatmaps in Grids [[paper](https://arxiv.org/pdf/2006.09917.pdf)] [[talk](https://www.youtube.com/watch?v=WRH7N_GxgjE&t=1004s)]

### Motion-Level 

#### LiDAR Input

- [CVPR 2020] MotionNet: Joint Perception and Motion Prediction for Autonomous Driving based on BEV Maps [[paper](https://arxiv.org/pdf/2003.06754.pdf)] [[Github](https://github.com/pxiangwu/MotionNet)]
- [CVPR 2022] BE-STI: Spatial-Temporal Integrated Network for Class-Agnostic Motion Prediction with Bidirectional Enhancement [[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Wang_BE-STI_Spatial-Temporal_Integrated_Network_for_Class-Agnostic_Motion_Prediction_With_Bidirectional_CVPR_2022_paper.pdf)] 
- [CVPR 2023] Weakly Supervised Class-Agnostic Motion Prediction for Autonomous Driving [[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Li_Weakly_Supervised_Class-Agnostic_Motion_Prediction_for_Autonomous_Driving_CVPR_2023_paper.pdf)] [[Github](https://github.com/L1bra1/WeakMotion)]
- [IJCAI 2023] ContrastMotion: Self-supervised Scene Motion Learning for Large-Scale LiDAR Point Clouds [[paper](https://arxiv.org/pdf/2304.12589v1.pdf)]
- [AAAI 2024] Semi-Supervised Class-Agnostic Motion Prediction with Pseudo Label Regeneration and BEVMix [[paper](https://arxiv.org/pdf/2312.08009.pdf)] [[Github](https://github.com/kwwcv/SSMP)]
- [CVPR 2024] Self-Supervised Class-Agnostic Motion Prediction with Spatial and Temporal Consistency Regularizations [[paper](https://arxiv.org/pdf/2403.13261.pdf)] [[Github](https://github.com/kwwcv/SelfMotion)]

#### Multi-Modal

- [CVPR 2021] Self-Supervised Pillar Motion Learning for Autonomous Driving [[paper](https://arxiv.org/pdf/2104.08683.pdf)] [[Github](https://github.com/qcraftai/pillar-motion)]
- [AAAI 2024] Self-Supervised Bird's Eye View Motion Prediction with Cross-Modality Signals [[paper](https://arxiv.org/pdf/2401.11499v1.pdf)] [[Github](https://github.com/bshfang/self-supervised-motion)]

### Others (agent-level + occupancy-level)

- [IROS 2021] Safety-Oriented Pedestrian Motion and Scene Occupancy Forecasting [[paper](https://arxiv.org/pdf/2101.02385.pdf)]
- [CVPR 2023] UniAD: Planning-oriented Autonomous Driving [[paper](https://arxiv.org/pdf/2212.10156.pdf)] [[Github](https://github.com/OpenDriveLab/UniAD)]
- [arXiv 2023] FusionAD: Multi-modality Fusion for Prediction and Planning Tasks of Autonomous Driving [[paper](https://arxiv.org/pdf/2308.01006.pdf)] [[Github](https://github.com/westlake-autolab/FusionAD)​]

## Talks

- [Joint Perception and Prediction for Self-driving](https://www.youtube.com/watch?v=Ce0vI_9SwNU) 
- [Joint Perception & Prediction for Autonomous Driving](https://www.youtube.com/watch?v=A-B5f9gLDh0)


