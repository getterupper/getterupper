---
title:          MonoOcc: Digging into Monocular Semantic Occupancy Prediction
date:           2024-03-13 17:59:04 +0800
selected:       true
pub:            "International Conference on Robotics and Automation (ICRA)"
pub_date:       "2024"
abstract: >-
  Monocular Semantic Occupancy Prediction aims to infer the complete 3D geometry and semantic information of scenes from only 2D images. It has garnered significant attention, particularly due to its potential to enhance the 3D perception of autonomous vehicles. However, existing methods rely on a complex cascaded framework with relatively limited information to restore 3D scenes, including a dependency on supervision solely on the whole network's output, single-frame input, and the utilization of a small backbone. These challenges, in turn, hinder the optimization of the framework and yield inferior prediction results, particularly concerning smaller and long-tailed objects. To address these issues, we propose MonoOcc. In particular, we (i) improve the monocular occupancy prediction framework by proposing an auxiliary semantic loss as supervision to the shallow layers of the framework and an image-conditioned cross-attention module to refine voxel features with visual clues, and (ii) employ a distillation module that transfers temporal information and richer knowledge from a larger image backbone to the monocular semantic occupancy prediction framework with low cost of hardware. With these advantages, our method yields state-of-the-art performance on the camera-based SemanticKITTI Scene Completion benchmark. Codes and models can be accessed at <a href="https://github.com/ucaszyp/MonoOcc">this https URL</a>.
cover:          assets/images/covers/monoocc.jpg
authors:
- Yupeng Zheng*
- Xiang Li*
- Pengfei Li
- Yuhang Zheng
- Bu Jin
- Chengliang Zhong
- Xiaoxiao Long
- Hao Zhao
- Qichao Zhang
links:
  Paper: https://arxiv.org/abs/2403.08766
---