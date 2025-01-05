---
layout: page
title: Projects
permalink: /projects/
---

# Self-Balancing Segway [[Paper]][segway-paper-link]
**Skywalker Li***, Alex Tseng

<div class="slideshow-container">
    <div class="slides-wrapper-4">
        <div class="slide">
            <img src="/assets/segway/img1.jpeg" alt="Slide 1">
        </div>
        <div class="slide">
            <img src="/assets/segway/img2.png" alt="Slide 2">
        </div>
        <div class="slide">
            <img src="/assets/segway/img3.png" alt="Slide 3">
        </div>
        <div class="slide">
            <img src="/assets/segway/img4.png" alt="Slide 3">
        </div>
  </div>
</div>

- Engineered a segway design using Fusion 360 with distinct board locations for power, voltage regulation, motor drivers, gyroscope, etc.
- Implemented complementary filter on the accelerometer and gyroscope angle and incorporated high-level and low level PID control on said angle
- Utilized the DeepFashion training set to train a deep CNN model to generate bounding boxes around articles of clothing
- Trained on 30,000 images and achieved greater than 50% test accuracy in classifing images as one out of eight
emotions

[segway-paper-link]: https://docs.google.com/document/d/1xLCRtCav3NRidwRKPaouYSjtGcJM6hDeiP6yQk4c9x4/edit?usp=sharing

<br><br>

# Wind Aware Drone Controller [[Paper]][ladrone-paper-link]
**Skywalker Li**

<div class="img">
    <img class="regular-img" src="/assets/ladrone/poster.png" />
</div>
Scientists are interested in measuring particle dispersion trajectories in the atmosphere to model effects like pollutant spread. Current measurement techniques either give up size and track large tetroons over atmospheric length scales or track particles within the meter range. The LaDrone platform attempts to provide centimeter particle-level tracking over the kilometer scale. To do so, the LaDrone platform utilizes a gravity compensation control that lets the drone flow with the wind. This Independent Work improves upon this control by implementing a theoretically proven, fast-tracking controller experimentally for the first time. It then evaluates the fast-tracking controller and demonstrates significant improvements in its particle-tracking ability. 


[ladrone-paper-link]: https://docs.google.com/document/d/19j0C8M3VNqhm_rGdhuzjBBfjmeMsR9oNj-TNm82KGS0/edit?usp=sharing


<br><br>

# Visual Emotion Classifier [[Paper]][visual-paper-link]
**Skywalker Li***, Jack Zhang, Artha Abeysinghe (Equal Contribution)

<div class="slideshow-container">
    <div class="slides-wrapper-3">
        <div class="slide">
            <img src="/assets/visual-emotion/img1.png" alt="Slide 1">
        </div>
        <div class="slide">
            <img src="/assets/visual-emotion/img2.png" alt="Slide 2">
        </div>
        <div class="slide">
            <img src="/assets/visual-emotion/img3.png" alt="Slide 3">
        </div>
  </div>
</div>

- Developed novel pipeline for emotion sentiment recognition from human eyes using deep-CNN derived from a
winning ILSVRC paper, “Squeeze-and-Excitation Networks”
- Utilized YOLO v8 to extract eye regions from images and a modified SeResNet-50 architecture for emotion classification
- Trained on 30,000 images and achieved greater than 50% test accuracy in classifing images as one out of eight
emotions

[visual-paper-link]: https://docs.google.com/document/d/1x_1tO2GJ08z3Lz17qJXgIQUU8xGM2EZYdcLey7O5yJU/edit?tab=t.0#heading=h.uviz3msp9i7p






Independent Robotics Projects
June 2021 – June 2022
- Engineered a self-driving trash can and a voice-activated spice machine as technical projects.
- Implemented Deep Learning-based speech-to-text engine, OpenCV and CNN lane navigation, designed custom
smart speaker software in Python libraries, designed 3D models and circuitry, and pitched products to angel investors.