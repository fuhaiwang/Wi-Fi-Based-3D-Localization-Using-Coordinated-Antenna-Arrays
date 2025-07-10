# Wi-Fi-Based 3D Localization Using Coordinated Antenna Arrays

This repository provides Channel State Information (CSI) datasets collected using RF-switch-based multiplexing of multiple RF chains. The data were acquired for wireless sensing tasks using antenna array configurations and are categorized into two types:

Single-Array CSI for 3D AoA Estimation
CSI measurements collected from a single Uniform Rectangular Array (URA) using RF switching. These data are suitable for high-resolution 3D Angle-of-Arrival (AoA) estimation and beamforming research.

Dual-Array CSI for 3D Localization
CSI measurements jointly captured from two spatially separated URAs. These data enable 3D source localization via collaborative signal processing across arrays, supporting algorithm development in geometric or learning-based localization.

All data were collected under controlled settings with known ground truth positions and synchronized switching sequences. The dataset is structured to support easy parsing and integration with custom signal processing pipelines.

### Data preparation
#### WICAL Dataset
Download the dataset from [LINK]([https://drive.google.com/drive/folders/1JDdLGDruGNXWnM1eqY1FNL9PlStjaKWi?usp=drive_link](https://drive.google.com/file/d/1F0oEb3BHpQB7VV8JXqczlZU4rPlaC8pQ/view?usp=drive_link)).


#### Data Structure
We organize the datasets like this:
```
Relightable3DGaussian
├── datasets
    ├── data_URA_sharing
    |   ├── dataset
    |   ├── A_main_URA_dataloader.m
    |   ├── ...
    ├── data_2URA_sharing
    |   ├── data_dtu
    │   │── A_main_2URA_dataloader.m
    │   │── ...
```

### Running
We ran A_main_xURA_dataloader.m in MATLAB 2023a without any issues.






