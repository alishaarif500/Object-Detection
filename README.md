# Object-Detection
This repository showcases an end-to-end, academic-grade Machine Learning pipeline designed for high-performance localized object detection. By leveraging transfer learning with **YOLOv8**, the system is capable of detecting and bounding multiple object classes with microsecond-latency inference (~7.4ms on commercial accelerators).

### Key Features
* **GPU-Accelerated Setup & Verification:** Automated PyTorch, CUDA, and Ultralytics integration diagnostics.
* **Automated Data Pipeline:** Auto-download, extraction, structure exploration, and pixel-space coordinate mapping of raw annotation formats (COCO8).
* **Transfer Learning & Fine-Tuning:** Pretrained YOLOv8 Nano model specialized on custom detection data with detailed loss tracking (Box Loss, Class Loss, DFL Loss).
* **Robust Evaluation Analytics:** Automatic generation of training metric curves (`results.png`) and inter-class classification analysis (`confusion_matrix.png`).
* **Interactive Deployment:** A lightweight Streamlit-powered dashboard allowing users to upload custom images, dynamically adjust confidence thresholds, and inspect structural metadata on demand.
