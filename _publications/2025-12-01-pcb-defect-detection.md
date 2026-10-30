---
title: "Efficient PCB Defect Detection via CURA-Based Lightweight Vision Models"
collection: publications
category: reports
permalink: /publication/2025-12-01-pcb-defect-detection
excerpt: 'A circuit-inspired residual architecture for real-time defect detection and spatial localization on edge hardware: 71% fewer parameters than deep-CNN baselines, 711 FPS sustained throughput, and 0.73 mean IoU via a context-aware ROI-crop pipeline for small-object regression.'
date: 2025-12-01
venue: 'Technical report'
citation: 'Shah, M. M. (2025). &quot;Efficient PCB Defect Detection via CURA-Based Lightweight Vision Models.&quot; <i>Technical report</i>.'
---

Printed-circuit-board inspection demands small-object detection at production-line speed on modest hardware. This report presents a hybrid MobileNetV2 detector with a circuit-inspired residual block (CURA):

* **84.81% accuracy at 711 FPS** for real-time spatial localization on edge-class hardware.
* **71% fewer trainable parameters** (1.96M) than deep-CNN baselines.
* **Context-aware ROI-crop pipeline** that raises effective object area from ~0.1% to ~11% of the input, enabling small-object bounding-box regression at **0.73 mean IoU** and an **89.6% detection rate**.

A companion experiment replaced a YOLO backbone with depthwise-separable MobileNetV2 plus post-training INT8 quantization, cutting CPU inference latency from 145 ms to 18 ms and model size by 92% (28.0 MB → 2.2 MB) for only a 4% precision drop.
