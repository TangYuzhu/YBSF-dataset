# YBSF Sea Fog Dataset

## Overview
The YBSF dataset was released in 2022 and is built using Himawari-8 multispectral remote sensing images. It is a high spatial resolution, pixel-level annotated dataset specifically designed for sea fog detection research. The dataset employs multi-class annotations, labeling not only sea fog but also clouds and clear sky, which assists researchers in distinguishing various meteorological phenomena.

## Dataset Details
- **Data Source**: Himawari-8 AHI multispectral images.
- **Spatial Resolution**: All bands are processed to achieve a uniform resolution of 500 meters.
- **Annotation Information**: Pixel-level annotations covering multiple classes, including sea fog, clouds, and clear sky.
- **Sample Quantity**: The dataset contains only 24 sea fog observation events. This limited number is due to the strict criterion requiring the simultaneous presence of sea fog and clouds in the images.
- **Geographical Coverage**: Primarily covers the northern Yellow Sea and Bohai Sea regions (approximately 34°N-42°N, 117°E-127°E).

## Strengths and Limitations

### Strengths
- **High Spatial Resolution**: With a uniform 500-meter resolution, the dataset provides sufficient detail for in-depth analysis.
- **Pixel-Level Annotation**: Detailed annotations facilitate precise model training and evaluation, which is essential for developing high-accuracy sea fog detection algorithms.
- **Multi-Class Annotation**: Including labels for sea fog, clouds, and clear sky helps address the challenge of differentiating sea fog from clouds.

### Limitations
- **Limited Sample Size**: The dataset comprises only 24 sea fog events due to the strict selection criteria requiring both sea fog and clouds to be present simultaneously.
- **Class Imbalance**: The multi-class labeling might result in an uneven distribution of samples between sea fog and non-sea fog areas, requiring careful handling during model training.

## Usage Instructions
Researchers can use the YBSF dataset for:
- Developing and benchmarking sea fog detection algorithms.
- Conducting multi-class remote sensing image segmentation research, particularly in distinguishing sea fog from clouds.
- Environmental monitoring and meteorological forecasting applications.

## Data Access
The dataset is publicly available on GitHub. All data files and corresponding annotations can be accessed through this repository. Please refer to the repository contents for detailed data files and download instructions.

## Citation
If you use the YBSF dataset in your research, please cite it as follows:

> Tang, Y.; Yang, P.; Zhou, Z.; Zhao, X. Daytime Sea Fog Detection Based on a Two-Stage Neural Network. *Remote Sens.* **2022**, *14*, 5570. [https://doi.org/10.3390/rs14215570](https://doi.org/10.3390/rs14215570).


## Contact
For any questions or suggestions, please open an issue on GitHub or contact us via email: tanyuzhu5408@jit.edu.cn.

