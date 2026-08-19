# DHN-Seg

**Expert-Guided Difficulty-Aware Neural Tissue Segmentation in Endoscopic Spine Surgery**

This repository hosts the public, patient-safe project page for an ongoing study of neural tissue segmentation in endoscopic spine surgery. The current primary static teacher uses DINOv3-L with UPerNet. The project also investigates difficult positive and negative examples, continuous-video behavior, temporal boundary stability, and teacher-to-student distillation for real-time deployment.

## Project page

The public static page is located in [`docs/`](docs/) and is ready for GitHub Pages. It contains no patient-derived images, videos, annotations, or model weights. A separate team-only preview is excluded from version control.

## Current status

- Pixel-level, two-center dataset construction is ongoing.
- Case-level train, validation, and test separation is used.
- DINOv3-L + UPerNet is the current static teacher.
- Generic SAM2 propagation shows boundary instability and requires domain adaptation.
- Results are preliminary and have not been clinically validated.

## Data and model release

Patient-level images, videos, annotations, and model weights are not included. Any future release is subject to ethics approval, institutional authorization, participant consent where applicable, and publication review.

## Contact

Jiang Junfeng, Hohai University: `jiangjf@hhu.edu.cn`
