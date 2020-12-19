<!--
 * @Description: 
 * @Author: shaonianruntu
 * @Github: https://github.com/shaonianruntu
 * @Date: 2020-12-19 20:17:01
 * @LastEditTime: 2020-12-19 20:44:55
-->

# FID indicator (Pytorch Version)

Given two image datasets, calculate the FID indicator between the two datasets.

## Usage

run 
```
python fid_score.py
```

## Input

`pathA`, `pathB`: 
Path of two image datasets that need to be calculated, you need to modify them according to your real situation.

> It is best not to modify other input parameters.

## Output

Image size of two calculation datasets and FID indicator results.

Example:
```
imgs shape:  (2340, 250, 200, 3)
imgs shape:  (188, 250, 200, 3)
FID:  44.50189680413844
```