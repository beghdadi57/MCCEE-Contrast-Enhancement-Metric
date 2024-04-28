# Multi-Criteria Contrast Enhancement Evaluation (MCCEE) Metric 

This is the code for MCCEE metric accepted for publication at MMSP conference 2020. MCCEE metric combines four different criteria of image enhancement in 
assessing the quality of an enhanced image. These criteria are contrast improvement, brightness preservation, structure preservation and lightness order preservation.
For each of these criteria, we have selected and used one specific metric. These metrics are:

1. EMEE 

EMEE or Measure of Enhancement by Entropy is used to measure the improvement in contrast.

2. AMBE

Absolute Mean Brightness Error (AMBE) measures the difference in mean brightness between the original and the enhanced image.

3. SMO

Structure Measure Operator (SMO) is an over-enhancement metric which tries to capture the structural change. 

4. LOM 

Lightness Order Measure (LOM) is an over-enhancement measure that is based on local inversion of lightness order.

## Requirements

Following software needs to be in the same folder as this code or in the system path.

1. LibSVM library (https://www.csie.ntu.edu.tw/~cjlin/libsvm/#matlab)

2. Code for EMEE metric (https://github.com/samame92/EMEE)

3. Wavelet toolbox for MATLAB (https://www.mathworks.com/matlabcentral/fileexchange/5104-toolbox-wavelets) to be extracted in the folder toolbox_wavelets.

## Usage

If you intend to use this metric in your work, please cite the following paper:

Khan, Z.A., Beghdadi A., Cheikh, F.A., Kaaniche, M. and Qureshi, M.A. **A Multi-Criteria Contrast Enhancement Evaluation Measure using Wavelet Decomposition**. *IEEE MMSP* (2020)

## License

[![License](http://img.shields.io/:license-mit-blue.svg?style=flat-square)](http://badges.mit-license.org)

- **[MIT license](http://opensource.org/licenses/mit-license.php)**
