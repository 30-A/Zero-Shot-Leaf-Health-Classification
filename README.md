# Automated Leaf Health Annotation for Greenhouse Images

This project implements an automated system for classifying plant health in greenhouse images using zero-shot learning models.

## Overview

The system processes greenhouse images, classifying each section as:
- Healthy (H)
- Unhealthy (U)
- Background (B)

It uses an ensemble of five zero-shot learning models and a majority voting mechanism for final classification.

## Repository Contents

- `zero_shot.ipynb`: Jupyter notebook containing the main implementation
- `hort-americas-growing-hydroponic-strawberries.jpeg`: Sample input image
- `output.png`: Example output image with annotations
- `requirements.txt`: List of required Python packages

## Requirements

Install dependencies:

```
pip install -r requirements.txt
```

## Usage

1. Open and run the `zero_shot.ipynb` notebook in a Jupyter environment.
2. The notebook will process the sample image and generate an annotated output.

## Models Used

- ViT-SO400M-14-SigLIP-384
- ViT-H-14-378-quickgelu
- ViTamin-XL-384
- ViT-bigG-14-CLIPA-336
- EVA02-E-14-plus

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
