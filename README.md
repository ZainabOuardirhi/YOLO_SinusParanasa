# Sinus Detection using YOLOv5, YOLOv6, and YOLOv7
This repository presents a comparative project on automated sinus cavity detection (Frontal, Maxillary, Ethmoid) using various versions of YOLO object detection models. The project was carried out in 2022 and uses **confidential CT scan images** that cannot be shared publicly.

## Objective
To evaluate and compare the detection performance of:
- YOLOv5 (s, m, l variants)
- YOLOv6
- YOLOv7

on sinus segmentation tasks from medical CT scan slices.

---
## Repository Structure
.
├── checkpoints/            # Trained model weights
├── data/                   # YAML configs (paths, classes)
├── test/                   # Inference & visualization scripts
├── traced_model.pt         # Exported PyTorch model
├── yolo_dataset/           # Main dataset folder
├── yolo_dataset_v1/        # Alternate dataset version (preprocessing variant)
├── yolo_dataset_v2/        # Alternate dataset version (preprocessing variant)
├── yolov5/                 # YOLOv5 source and training code
├── yolov5_v1/              # Alternate YOLOv5 experiment
├── YOLOv6/                 # YOLOv6 training and configs
├── yolov7/                 # YOLOv7 source code
├── yolov7_1/               # YOLOv7 trained model variant 1
├── yolov7_2/               # YOLOv7 trained model variant 2

---
## Disclaimer

- The dataset used is **confidential** and cannot be distributed.
- This project is for **research and academic demonstration only**.

---
## Acknowledgments

This project was developed as part of an internal research task in 2022. Special thanks to the colleagues and mentors who guided the experimental design and evaluation.

---
## Contact

For questions or collaboration opportunities, feel free to reach out via [your email].

