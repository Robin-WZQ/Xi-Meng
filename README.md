<div align=center>
    <img src=https://github.com/Robin-WZQ/Xi-Meng/blob/main/assets/logo.png width="600"/>
</div>

# Xi Meng
[![license](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
![Love](https://img.shields.io/badge/Made%20with-love-ff69b4)
![Version](https://img.shields.io/badge/version-1.0-red)

> A system for Chinese Landscape generation.

[中文](https://github.com/Robin-WZQ/Xi-Meng) | [English](https://github.com/Robin-WZQ/Xi-Meng/tree/English)

## Datasets

To advance our experiment, a new dataset of traditional Chinese landscape paintings is released, with 485 clear contours and 105 contour-color matching pairs drawing by writing brush

For dataset acquisition and more detailed description, please refer to [HERE](https://github.com/Robin-WZQ/Xi-Meng-Dataset/tree/english)。

## Model
<div align=center>
    <img src=https://github.com/Robin-WZQ/Xi-Meng/blob/English/assets/model.png width="600"/>
</div>

we introduce a novel generative model to generate paintings with high-precision contours and any given style of landscape painting. Specifically, the model includes three stages, generating the Contour, Base Color, and Style Color based on GANs in turn.

The model does not need to rely on any conditional input given by the user (i.e. photos and user-defined contours), and can generate a landscape painting with high-precision contours and any target style.

## Results
<div align=center>
    <img src=https://github.com/Robin-WZQ/Xi-Meng/blob/main/assets/picall.png width="800"/>
</div>
