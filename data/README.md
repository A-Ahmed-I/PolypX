# CVC-ClinicDB Dataset

## Introduction

CVC-ClinicDB is a database of frames extracted from colonoscopy videos containing polyp examples. In addition to the original frames, the dataset provides ground truth annotations in the form of binary masks indicating the region covered by polyps in each image.

The dataset was generated from 25 different video studies, with at least one sequence containing a polyp extracted from each study. In total, CVC-ClinicDB comprises frames from 29 different sequences, carefully selected to showcase multiple viewpoints of polyps.

## Dataset Structure

The database consists of two types of images for each frame:

- **Original images**: `Original/frame_number.tiff` - Raw colonoscopy frames
- **Polyp masks**: `Ground Truth/frame_number.tiff` - Binary segmentation masks

## Frame-Sequence Correspondence

The mapping between frame numbers and video sequences is as follows:

| Frame Range | Sequence |
|-------------|----------|
| 1-25 | 1 |
| 26-50 | 2 |
| 51-67 | 3 |
| 68-78 | 4 |
| 79-103 | 5 |
| 104-126 | 6 |
| 127-151 | 7 |
| 152-177 | 8 |
| 178-199 | 9 |
| 200-205 | 10 |
| 206-227 | 11 |
| 228-252 | 12 |
| 253-277 | 13 |
| 278-297 | 14 |
| 298-317 | 15 |
| 318-342 | 16 |
| 343-363 | 17 |
| 364-383 | 18 |
| 384-408 | 19 |
| 409-428 | 20 |
| 429-447 | 21 |
| 448-466 | 22 |
| 467-478 | 23 |
| 479-503 | 24 |
| 504-528 | 25 |
| 529-546 | 26 |
| 547-571 | 27 |
| 572-591 | 28 |
| 592-612 | 29 |

## Usage

CVC-ClinicDB is designed for training and evaluation of polyp detection and segmentation models in colonoscopy videos, including participation in the ISBI 2015 Challenge on Automatic Polyp Detection.

## Copyright & Attribution

- Images in the `Original` folder are the property of Hospital Clinic, Barcelona, Spain.
- Images in the `Ground Truth` folder are the property of Computer Vision Center, Barcelona, Spain.

## Citation

When using this dataset, please cite:

```bibtex
@dataset{bernal2015cvc,
title={CVC-ClinicDB: A Database of Frames from Colonoscopy Videos},
author={Bernal, Jorge and Sanchez, F. J. and Fernandez-Esparrach, Gloria and Rodriguez, Cristina},
year={2015}
}
```

## License

**Important**: This dataset is restricted to research and educational purposes only. Commercial use of this dataset is strictly forbidden.
