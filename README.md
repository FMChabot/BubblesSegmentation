# X-Ray Radiography - Oxygen bubbles counts
## Image filtering and bubbles segmentation 

Count and measure bubbles in a dual phase flow (oxygen/water)
## Process:
- Create and subtract background
- Non linear filtering, median filtering, down sampling
- Select thresholding method and threshold image
- Segment bubbles

## Experiment
X-ray radiography from channels of an opearating PEM water electrolyzer 
Measurements performed at Beamline 8.3.2 at the Advanced Light Source
Pixel size: 0.635 um ; Exposure time: 5 ms ; 



# Requirements: 
  - Install Tomopy Library (https://github.com/tomopy/tomopy?tab=readme-ov-file)
    - Using Conda: conda install -c conda-forge tomopy
