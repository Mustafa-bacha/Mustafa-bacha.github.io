---
title: "Low-Latency Edge Perception via INT8 Quantization"
excerpt: "Replaced a YOLO backbone with depthwise-separable MobileNetV2 and post-training INT8 quantization: CPU latency 145 ms → 18 ms (55.5 FPS), model size −92% (28.0 → 2.2 MB), for only a 4% precision drop."
collection: portfolio
---

GPU-free, real-time object detection for embedded compute modules:

* Swapped a heavyweight YOLO backbone for **depthwise-separable MobileNetV2** and applied **post-training INT8 quantization**.
* **145 ms → 18 ms** CPU inference latency (55.5 FPS) and **92% smaller** model (28.0 MB → 2.2 MB), at only a 4% precision cost.
* Sustained 84.8% detection accuracy and 0.848 Macro-F1 on highly variable input streams — validating real-time remote monitoring on constrained hardware.

Related: [Efficient PCB Defect Detection technical report](/publication/2025-12-01-pcb-defect-detection).
