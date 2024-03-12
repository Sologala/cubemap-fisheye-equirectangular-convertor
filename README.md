# cubemap-fisheye-equirectangular-convertor

## TODO
- [ ] Implementing of fisheye to cubemap 
- [ ] Implementing of fisheye to equirectangle 

## Usage

With Python 3 and all requirements installed, just run the following command in the folder of the project:
```
python3 cubemap-converter.py
```
## Input files
Input image must be a cubemap with the following structure (see also cubemap.png image):

<img src="./cubemap.png" height = "350" style="display: inline-block; vertical-align: middle;">

## Output files

There can be two different outputs:
  - Fisheye image with a certain resolution specified by the user.

|  fisheye fov 60   | fisheye fov 120   | fisheye fov 180|
| --- | --- | --- |
| ![](./outputs/fisyeye_60_800_800.png)     |   ![](./outputs/fisyeye_120_800_800.png)  |  ![](./outputs/fisyeye_180_800_800.png)| 

  - Equirectangular image. Its dimensions are fixed and depend on the input image size.

|equirectangle|
|---|
|![](./outputs/equirectangle.png)|

# Ref
> https://github.com/michael-good/cubemap-to-projections-converter
