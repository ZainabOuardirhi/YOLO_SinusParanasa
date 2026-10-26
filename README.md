# Paranasal Sinus Localization — YOLO Experiments

Research experiments exploring localization of frontal, maxillary and ethmoid sinus regions on CT image slices with YOLOv5, YOLOv6 and YOLOv7 implementations.

> **Data restrictions:** The medical imagery used in this work is confidential. The repository remains private, and no example patient images or outputs should be made public without confirming that they are approved, anonymized and authorized for release.

## Project scope

- Explore object-detection approaches to localizing sinus regions in CT slices.
- Compare development workflows using YOLOv5, YOLOv6 and YOLOv7.
- Preserve reproducible experiment configuration and selected **approved** output figures where available.

*Detection/localization and pixel-level segmentation are different tasks.* This project documents detection experiments; no segmentation-quality claim or numerical benchmark is made without validated results.

## Available sources and experiments

The original source workspace is preserved in [the project Google Drive folder](https://drive.google.com/drive/folders/1kcM66S38GljGHzblcQcAC0WBlHghWO4B). It includes:

| Workspace | Material identified |
| --- | --- |
| [YOLOv5](https://drive.google.com/drive/folders/111yprRxfnWULKks9k4uGckOSgbz5zNdH) | Training, detection, testing and validation scripts; tutorial notebook; configurations |
| [YOLOv6](https://drive.google.com/drive/folders/1jE3ek4Wx3zQDcPMFfZHqqPpWbPhfi4kP) | Tutorial and inference notebooks, configs and supporting framework code |
| [YOLOv7](https://drive.google.com/drive/folders/1E3rFb9b49Y55L4u_6uy4Rdbb75OCBrec) | Training, testing, detection and export scripts; configs |
| [Detection runs](https://drive.google.com/drive/folders/10F_qtJqAVz7In8dVJTXhUY7GjLrlqBSm) | Saved inference runs and candidate result images, subject to privacy review |

Much of the framework source is upstream YOLO code. The presence of these files is **not** evidence that all framework code is original work, and it should not be copied into this repository without preserving authorship and relevant licenses.

## Repository state

The existing [Test_Dataset](Test_Dataset) folder is retained. Before any public release, its contents must be reviewed for confidential medical images or identifying metadata.

This repository is being organized as a project overview, not a distribution of medical datasets or pretrained weights. A future curated code release should include project-specific configurations, small original wrapper scripts, software versions, and properly authorized example outputs.

## Acknowledgments

YOLOv5, YOLOv6 and YOLOv7 are separately developed open-source object-detection frameworks. This project uses those research implementations as experimental baselines; framework source and pretrained models remain attributable to their respective maintainers.
