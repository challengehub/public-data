---
affiliated_institute:
  en_name: Kyushu University
  name: "\u4E5D\u5DDE\u5927\u5B66"
  url: https://www.kyushu-u.ac.jp
editor_id: github.NanoScaleDesign
extra_resources:
  3072c5c2-0214-4d77-83d9-ba170d844833:
    content_type: image/png
    description: Kyudai logo
  42fb107e-f863-4d2b-8d44-548509a33cc7:
    content_type: image/png
    description: Kyudai logo edges-only
  ab1e9a8a-9abb-4fb8-afba-bfcc478afa57:
    content_type: image/png
    description: Kyudai logo blurred
id: f6b7e2ab-628d-4fda-a53d-50cd6aaba1dd
language: en
modified: '2019-11-15T00:59:41.608131Z'
title: Edge detection and blurring with Fourier analysis and python
title_id: edge-detection-and-blurring-with-fourier-analysis-and-python
topics: []
translations: {}
version: '1.0'
---

## Comments
In the 1D case, after performing DFT, low frequencies are considered to be on the left and high frequencies on the right. In 2D, the low frequencies are considered to be in the top-left corner. Due to symmetry however, modification of frequencies typically requires both altering the intended frequency as well as its symmetrical counterpart. As a consequence, the spectrum in 2D is usually shifted so that the lowest frequencies are in the centre of the image. This is done using the *fftshift* function of *numpy*.



## Challenge
Here you are going to use your Fourier analysis knowledge and python skills to do image-processing.

1. Convert the original image of the Kyudai logo so that only the edges of the image are shown.
2. Convert the original image of the Kyudai logo so that the image becomes blurred.
3. Write a paragraph summarising the reasoning of your approaches in each case.
4. (optional) Try with another image (requirements for pre-processing the image can be found in the python file in the resources).

You may use the outline python code in the resources to help you, or you may use your own code from scratch. The supplied code relies on the following libraries:
- numpy
- PIL

Generally, to install new libraries you can use *pip3 install numpy* etc.

The code above will output the shifted DFT of the image to *kyudai.fft.png* and the inverse DFT of the image to *kyudai.fft.ifft.png*.

The original image and examples of edge-detection and blurring are shown below.

**Original image:** 
![Kyudai logo](/api/v0/teachers/github.NanoScaleDesign/resources/public/3072c5c2-0214-4d77-83d9-ba170d844833.png/3072c5c2-0214-4d77-83d9-ba170d844833.png)

**Edge-detected image:**
![Kyudai logo edges-only](/api/v0/teachers/github.NanoScaleDesign/resources/public/42fb107e-f863-4d2b-8d44-548509a33cc7.png/42fb107e-f863-4d2b-8d44-548509a33cc7.png)

**Blurred image**
![Kyudai logo blurred](/api/v0/teachers/github.NanoScaleDesign/resources/public/ab1e9a8a-9abb-4fb8-afba-bfcc478afa57.png/ab1e9a8a-9abb-4fb8-afba-bfcc478afa57.png)

## Resources
- Python outline code: http://raw.githubusercontent.com/NanoScaleDesign/FourierAnalysis/master/Image_processing/image_processing.py
- Kyudai image: http://raw.githubusercontent.com/NanoScaleDesign/FourierAnalysis/master/Image_processing/kyudai.png


## Solution Form
To mark this challenge as attempted, please rate the difficulty.
Please compare your solution with the images above and others in class.
