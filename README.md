# Simple DICOM Mask Viewer

A lightweight Python tool for visualizing DICOM medical images with optional segmentation mask overlay.

## Features

- Read DICOM images
- Automatic windowing
- Custom window center/width
- Segmentation mask overlay
- Save visualization output

## Installation

```bash
pip install -r requirements.txt
```

## Usage

### View DICOM image

```bash
python dicom_viewer.py --dicom sample.dcm
```

### View with segmentation mask

```bash
python dicom_viewer.py --dicom sample.dcm --mask mask.png
```

## Requirements

- pydicom
- numpy
- matplotlib
- opencv-python
