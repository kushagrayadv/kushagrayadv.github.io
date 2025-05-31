---
layout: page
title: "Computer Vision Projects"
---

<div class="project-card">
  <div class="project-card-content">
      <h3>A denoising approach towards reliable object detection</h3>
      <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" alt="TensorFlow">
      <ul>
        <li>Designed a two-stage deep learning pipeline combining image denoising and object detection to handle noisy input images.</li>
        <li>Used Residual Dense Network (RDN) to restore high-quality images from noisy inputs via hierarchical feature learning and residual connections.</li>
        <li>Applied Single Shot Multibox Detector (SSD) to perform efficient object detection on denoised images.</li>
        <li>Achieved 81.6% mAP on the Pascal VOC dataset, significantly outperforming baseline SSD models under varying noise levels.</li>
      </ul>
      <p><a href="https://github.com/kushagrayadv/ir-with-ssd">View Project</a></p>
  </div>
      <img src="/assets/projects/object-detection.jpg" alt="Object detection" class="project-card-img" />
</div>

<div class="project-card">
  <div class="project-card-content">
    <h3>Toward Safer Communities: Strategies to Mitigate Firearm Risks</h3>
    <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white" alt="TensorFlow">
    <ul>
        <li>Built a firearm classification system using transfer learning on ResNet-34 and ResNet-50 to detect and classify weapons (e.g., rifles, pistols, knives) from CCTV footage.</li>
        <li>Created and released a custom weapon dataset of 5,000+ images categorized into big guns, small guns, and other weapons.</li>
        <li>Achieved up to 95% classification accuracy using a dual-stage training strategy with adaptive learning rate selection.</li>
        <li>Integrated explainability using the GSInquire method to highlight critical regions driving classification decisions, improving transparency and interpretability.</li>
      </ul>
    <p><a href="https://github.com/kushagrayadv/gun-dataset">View Project</a></p>
  </div>
  <img src="/assets/projects/weapon-detection.jpg" alt="weapon detection" class="project-card-img" />
</div>
