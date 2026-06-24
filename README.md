# Medical Image Mask Viewer

A lightweight Python tool for visualizing DICOM and NIfTI medical images with optional segmentation mask overlay, designed for dataset inspection and segmentation quality control workflows.

## Features

- Read DICOM images
- Read NIfTI volumes
- Middle-slice visualization for 3D medical volumes
- Automatic windowing
- Adjustable image windowing using custom window center/width
- Segmentation mask overlay
- Save visualization output using the `--save` option

## Installation

```bash
git clone https://github.com/Sadafi88/medical-image-mask-viewer.git
cd medical-image-mask-viewer

pip install -r requirements.txt
```

## Supported Formats

### Medical Images

- DICOM (`.dcm`)
- NIfTI (`.nii`)
- NIfTI (`.nii.gz`)

### Segmentation Masks

- PNG (`.png`)
- JPEG (`.jpg`, `.jpeg`)
- Binary mask images

## Usage

### View a DICOM image

```bash
python dicom_viewer.py --dicom sample.dcm
```

### View a NIfTI image

```bash
python dicom_viewer.py --dicom sample.nii.gz
```

### View with segmentation mask overlay

```bash
python dicom_viewer.py --dicom sample.nii.gz --mask mask.png
```

### Save output visualization

```bash
python dicom_viewer.py --dicom sample.nii.gz --save output.png
```

## Example

Add a screenshot of the viewer output here:

![Viewer Example](viewer_example.png)

## Applications

- Medical image inspection
- Segmentation quality control
- Dataset verification
- DICOM visualization
- NIfTI visualization
- Medical imaging research workflows

## Dependencies

All required packages are listed in:

```text
requirements.txt
```

## License

MIT License
