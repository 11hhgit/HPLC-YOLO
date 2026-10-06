 HPLC-YOLO
a infrared weak and small target detection method
 HPLC-YOLO

Official implementation of:

HPLC-YOLO: High-Resolution Prediction and Local Contrast-Guided YOLO for Infrared Small Target Detection

IEEE Access


 Overview

HPLC-YOLO is an infrared small target detection framework based on YOLOv8n.

The proposed method introduces three key components:

- High-resolution Small Target Detection Head (HSD-Head)
- Infrared Local Contrast Enhancement Module (ILCEM)
- Infrared Contrast-Semantic Adaptive Fusion Module (ICSAF)

The framework improves small target representation by preserving high-resolution details, enhancing local contrast information, and adaptively fusing detailed and semantic features.


 Environment

The experiments were conducted with:

- Python 3.8.0
- PyTorch 1.10.1
- CUDA 11.3
- Ultralytics 8.0.180


 Installation

Create environment:

```bash
conda create -n hplcyolo python=3.8
conda activate hplcyolo
