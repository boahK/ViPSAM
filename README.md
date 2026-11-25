# ViPSAM : Visual Prompting Medical Image Segmentation Using Segment Anything Model

![Framework](./framework_rev.png)

The official source code for "ViPSAM: Visual Prompting Medical Image Segmentation Using Segment Anything Model", presented at MICCAI 2026.

# Implementation

A PyTorch implementation of a deep learning-based model.

- Requirements
  - OS : Ubuntu / Windows
  - Python 3.10.18
  - PyTorch 2.5.1

# Dataset

- In our experiments, we used a proton therapy planning dataset consisting of non-contrast CT and contrast-enhanced MRI scans collected at Samsung Medical center.

# Evaluation

- test.py is the implementation code if inference for liver lesion segmentation

# Citation
If you find our work useful in your research, please cite our paper:

```bibtex
@inproceedings{lee2026vipsam,
  title={ViPSAM: Visual Prompting Medical Image Segmentation Using Segment Anything Model},
  author={Lee, San and Kim, Nalee and Yu, Jeong Il and Park, Hee Chul and Kim, Boah},
  booktitle={International Conference on Medical Image Computing and Computer-Assisted Intervention},
  pages={668--677},
  year={2026},
  organization={Springer}
}
```
