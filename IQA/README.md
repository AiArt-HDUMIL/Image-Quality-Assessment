<!--
 * @Description: 
 * @Author: shaonianruntu
 * @Github: https://github.com/shaonianruntu
 * @Date: 2020-12-19 20:23:52
 * @LastEditTime: 2020-12-19 20:46:34
-->

# Image Quality Assessment,IQA (Matlab Version)

Given two image datasets, calculate the IQA indicator (PSNR, FSIM, SSIM, MAE & FPM) between the two datasets.

## Usage

Use Matlab run
```
main.m
```

## Input

Replace `addpath(genpath('YOU_PATH'));` with the path of the current folder on your computer.

`refpath`: Path of reference image dataset.

`dispath`: Path of test image dataset. `method_folders` is the subdirectories of `dispath`.

## Output

IQA indicator (PSNR, FSIM, SSIM, MAE & FPM) results of two calculation datasets.

Example:

```
IQA Result:
PSNR: 28.4115
FSIM: 0.6612
SSIM: 0.36618
MAE: 0.040039
FPM: 0.23488
```