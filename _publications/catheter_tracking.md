---
title: "Real-Time Tracking of Guidewire Robot Tips Using Deep Convolutional Neural Networks on Successive Localized Frames."
collection: publications
permalink: /publication/catheter_tracking
excerpt: 'Studies are proceeded to stabilize cardiac surgery using thin micro-guidewires and catheter robots. To control the robot to a desired position and pose, it is necessary to accurately track the robot tip in real time but tracking and accurately delineating the thin and small tip is challenging. To address this problem, a novel image analysis-based tracking method using deep convolutional neural networks (CNN) has been proposed in this paper. The proposed tracker consists of two parts; (1) a detection network for rough detection of the tip position and (2) a segmentation network for accurate tip delineation near the tip position. To learn a robust real-time tracker, we extract small image patches, including the tip in successive frames and then learn the informative spatial and motion features for the segmentation network. During inference, the tip bounding box is first estimated in the initial frame via the detection network, thereafter tip delineation is consecutively performed through the segmentation network in the following frames. The proposed method enables accurate delineation of the tip in real time and automatically restarts tracking via the detection network when tracking fails in challenging frames. Experimental results show that the proposed method achieves better tracking accuracy than existing methods, with a considerable real-time speed of 19ms.'
date: 2019-10-01
venue: 'IEEE Access'
paperurl: 'https://ihsan149.github.io/files/catheter_tracking.pdf'
citation: 'Ihsan Ullah et al. (2019). Real-Time Tracking of Guidewire Robot Tips Using Deep Convolutional Neural Networks on Successive Localized Frames; <i>IEEE Access</i>. 1(1).'
---
Studies are proceeded to stabilize cardiac surgery using thin micro-guidewires and catheter robots. To control the robot to a desired position and pose, it is necessary to accurately track the robot tip in real time but tracking and accurately delineating the thin and small tip is challenging. To address this problem, a novel image analysis-based tracking method using deep convolutional neural networks (CNN) has been proposed in this paper. The proposed tracker consists of two parts; (1) a detection network for rough detection of the tip position and (2) a segmentation network for accurate tip delineation near the tip position. To learn a robust real-time tracker, we extract small image patches, including the tip in successive frames and then learn the informative spatial and motion features for the segmentation network. During inference, the tip bounding box is first estimated in the initial frame via the detection network, thereafter tip delineation is consecutively performed through the segmentation network in the following frames. The proposed method enables accurate delineation of the tip in real time and automatically restarts tracking via the detection network when tracking fails in challenging frames. Experimental results show that the proposed method achieves better tracking accuracy than existing methods, with a considerable real-time speed of 19ms.

---
Proposed Framework and Examples
<br/><img src='/images/500x300.png'>"

This is an item in your portfolio. 

[Download paper here](https://ihsan149.github.io/files/catheter_tracking.pdf)
