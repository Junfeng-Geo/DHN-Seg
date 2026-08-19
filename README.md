# DHN-Seg

**Expert-Guided Difficulty-Aware Neural Tissue Segmentation in Endoscopic Spine Surgery**

This repository hosts the public, patient-safe project page for an ongoing study of high-precision neural tissue segmentation in static endoscopic spine surgery frames. The current implementation uses DINOv3-L with UPerNet and explicitly learns from expert-defined clear and difficult positive and negative examples.

## Project page

The public static page is located in [`docs/`](docs/) and is ready for GitHub Pages. It contains no patient-derived images, videos, annotations, or model weights. A separate team-only preview is excluded from version control.

## Current status

- Pixel-level, two-center dataset construction is ongoing.
- Case-level train, validation, and test separation is used.
- DINOv3-L + UPerNet is the current implementation.
- Difficulty-balanced sampling, hard-pixel learning, prototype separation, and boundary supervision are under evaluation.
- Results are preliminary and have not been clinically validated.

## Data and model release

Patient-level images, videos, annotations, and model weights are not included. Any future release is subject to ethics approval, institutional authorization, participant consent where applicable, and publication review.

## Contact

Jiang Junfeng, Hohai University: `jiangjf@hhu.edu.cn`
