# [DCFNet](https://link.springer.com/chapter/10.1007/978-981-97-4399-5_30)
This repository contains the segmentation results from [MFNet Dataset](https://github.com/haqishen/MFNet-pytorch) for the paper "[DCFNet: Dense Complementary Fusion for RGB-Thermal Urban Scene Perception](https://link.springer.com/chapter/10.1007/978-981-97-4399-5_30)".

## Table of Contents
- [DCFNet](#dcfnet)
  - [Table of Contents](#table-of-contents)
  - [Visualization](#visualization)
  - [IoU results of each class](#iou-results-of-each-class)
  - [Citation](#citation)

## Visualization

<img title="a title" src="./imgs/graph.jpg">

Results for test and val set can be found in the [results](DCFNet_results.zip).

## IoU results of each class
| Class      |  Car  | Person |  Bike  | Curve | Car Stop | Guardrail | Color Cone |  Bump  |
|:----------:|:-----:|:------:|:------:|:-----:|:--------:|:---------:|:----------:|:------:|
| IoU (%)    |  89.8 |  74.4  |  67.7  |  48.6 |   37.3   |    10.6    |    55.6    |  58.7  |


## Citation
If you find our work useful in your research, please consider citing:

```
@InProceedings{10.1007/978-981-97-4399-5_30,
author="Zhang, Yu-Wen Michael
and Zhang, Gang
and Hu, Xiaolin",
title="DCFNet: Dense Complementary Fusion for RGB-Thermal Urban Scene Perception",
booktitle="Advances in Neural Networks -- ISNN 2024",
year="2024",
publisher="Springer Nature Singapore"
}
```
