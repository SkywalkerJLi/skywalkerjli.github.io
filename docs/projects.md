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
- Designed voltage regulation board to output 5V from 9.6V input and power distribution board
- Implemented complementary filter on the accelerometer and gyroscope angle and incorporated high-level and low level PID control on said angle
- Utilized the DeepFashion training set to train a deep CNN model to generate bounding boxes around articles of clothing in real time

[segway-paper-link]: https://docs.google.com/document/d/1xLCRtCav3NRidwRKPaouYSjtGcJM6hDeiP6yQk4c9x4/edit?usp=sharing

<br><br>

# LaDrone: Wind Aware Drone Controller [[Paper]][ladrone-paper-link]
**Skywalker Li**

<div class="img">
    <img class="regular-img" src="/assets/ladrone/poster.png" />
</div>

- Utilized PID control to adjust the drone's roll, pitch, and yaw angles in real time to mimic particle motion
- Wrote Python scripts to log the drone's state variables and visualize max velocity over time
- Built wind condition robot with Raspberry PI, Arduino, A989 stepper motor drivers, and NEMA 17 stepper motors

[ladrone-paper-link]: https://docs.google.com/document/d/19j0C8M3VNqhm_rGdhuzjBBfjmeMsR9oNj-TNm82KGS0/edit?usp=sharing


<br><br>

# Visual Emotion Classifier [[Paper]][visual-paper-link]
**Skywalker Li***, Jack Zhang, Artha Abeysinghe 

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
- Trained on 30,000 images and achieved greater than **50%** test accuracy in classifing images as one out of eight
emotions

[visual-paper-link]: https://docs.google.com/document/d/1x_1tO2GJ08z3Lz17qJXgIQUU8xGM2EZYdcLey7O5yJU/edit?tab=t.0#heading=h.uviz3msp9i7p