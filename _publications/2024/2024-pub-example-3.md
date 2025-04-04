---
title:          "WIO-EKF: Extended Kalman Filtering-Based Wi-Fi and Inertial Odometry Fusion Method for Indoor Localization"
date:           2024-04-10
selected:       true
pub:            "IEEE Internet of Things Journal"
# pub_pre:        "Submitted to "
# pub_post:       'Under review.'
pub_last:       ' <span class="badge badge-pill badge-publication badge-success">Spotlight</span>'
pub_date:       "2024"

abstract: >-
  Indoor location and navigation technologies are crucial for healthcare, security and other location-based services. Wi-Fi and inertial sensors have become mainstream indoor localization technologies for wearable device platforms due to simple deployment and low cost. This study proposes an extended Kalman filtering (EKF)-based multimodal sensor fusion algorithm for indoor localization, combining Wi-Fi fingerprint and inertial measurement unit (IMU) data to provide accurate and continuous pedestrian localization. The main contributions of this work are threefold. First, a Wi-Fi fingerprint data augmentation method based on access point (AP) location sorting is proposed and a regression network model with a convolutional denoising autoencoder for WiFi-based indoor localization (CDAELoc) is designed to improve the robustness. Second, a dual-branch deep inertial odometry (DbDIO) network model for IMU-based indoor localization is introduced, consisting of two branches with various convolutional kernel sizes to extract features at different scales. Finally, an EKF-based Wi-Fi and inertial odometry (WIO-EKF) fusion localization system is presented, utilizing the predicted results from the proposed CDAELoc and DbDIO models as the system observations and mitigating the initial heading error of DbDIO. The proposed models are applied to the UJIIndoorLoc, RoNIN public data sets and self-collected data set. Experimental results prove that the proposed CDAELoc model outperforms other Wi-Fi localization models, reducing the average positioning error (APE) by 12.5\%. The proposed DbDIO model achieves higher accuracy and requires fewer model parameters than any other deep inertial odometry model. Finally, the APE of WIO-EKF is lower than those of CDAELoc and DbDIO by 34\% and 42\%.
cover:          /assets/images/covers/cover3.jpg
authors:
  - Pan Zhou
  - Hao Wang
  - Raffaele Gravina
  - Fangmin Sun
links:
  Paper: [https://github.com/luost26/academic-homepage](https://ieeexplore.ieee.org/abstract/document/10496456)
---
