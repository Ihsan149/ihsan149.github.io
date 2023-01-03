---
title: "Synthesize and Segment: Towards Improved Catheter Segmentation via Adversarial Augmentation."
collection: publications
permalink: /publication/catheter_synthesis
excerpt: 'Automatic catheter and guidewire segmentation plays an important role in robot-assisted interventions that are guided by fluoroscopy. Existing learning based methods addressing the task of segmentation or tracking are often limited by the scarcity of annotated samples and difficulty in data collection. In the case of deep learning based methods, the demand for large amounts of labeled data further impedes successful application. We propose a synthesize and segment approach with plug in possibilities for segmentation to address this. We show that an adversarially learned image-to-image translation network can synthesize catheters in X-ray fluoroscopy enabling data augmentation in order to alleviate a low data regime. To make realistic synthesized images, we train the translation network via a perceptual loss coupled with similarity constraints. Then existing segmentation networks are used to learn accurate localization of catheters in a semi-supervised setting with the generated images. The empirical results on collected medical datasets show the value of our approach with significant improvements over existing translation baseline methods.'
date: 2009-10-01
venue: 'Applied Sciences'
paperurl: 'https://ihsan149.github.io/files/catheter_synthesis.pdf'
citation: 'Ihsan Ullah et al. (2021). Synthesize and Segment: Towards Improved Catheter Segmentation via Adversarial Augmentation; <i>Applied Sciences</i>. 1(1).'
---
Automatic catheter and guidewire segmentation plays an important role in robot-assisted interventions that are guided by fluoroscopy. Existing learning based methods addressing the task of segmentation or tracking are often limited by the scarcity of annotated samples and difficulty in data collection. In the case of deep learning based methods, the demand for large amounts of labeled data further impedes successful application. We propose a synthesize and segment approach with plug in possibilities for segmentation to address this. We show that an adversarially learned image-to-image translation network can synthesize catheters in X-ray fluoroscopy enabling data augmentation in order to alleviate a low data regime. To make realistic synthesized images, we train the translation network via a perceptual loss coupled with similarity constraints. Then existing segmentation networks are used to learn accurate localization of catheters in a semi-supervised setting with the generated images. The empirical results on collected medical datasets show the value of our approach with significant improvements over existing translation baseline methods.

---
Proposed Framework and Examples
<br/><img src='/images/catheter_synthesis.png'>

| Video Example  |
| ------------- | 
| <video src="https://ihsan149.github.io/images/catheter_synthesis.mp4" controls="controls" style="max-width: 930px;"></video> | 

[Download paper here](https://ihsan149.github.io/files/catheter_synthesis.pdf)
