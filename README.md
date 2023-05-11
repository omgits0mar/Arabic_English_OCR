# OCR Text Extraction and Voice Output using Pytesseract and textract

This project aims to extract text from images in both Arabic and English languages using OCR (Optical Character Recognition) techniques, and then output the voice reading the text in both English and Arabic using GTTS (Google Text-to-Speech).

## Overview

1. The user first choose between Arabic or English OCR.
2. A user moves the mobile camera (Real-time) to the book or text he wanted to read.
3. The Model then will extract to text into an input string then convert this text to speech and read it out load.

## Installation
- Install Python 3 and pip.
- Install Pytesseract: `pip install pytesseract`
- Install Textract: `pip install textract`
- Install OpenCV: `pip install opencv-python`
- Install NumPy: `pip install numpy`
- Install Matplotlib: `pip install matplotlib`
- Install GTTS: `pip install gtts`

## Image Preprocessing
The script applies several preprocessing techniques on the input image to improve the accuracy of the OCR:

1. Binarization: Convert the image to binary form using thresholding.
2. Skewing Correction: Correct the skewing of the image if it exists using OpenCV functions.
3. Image Sharpening: Enhance the edges in the image using Gaussian and Laplacian filters.

## Limitations
- The accuracy of the OCR is affected by the quality and complexity of the input image.
- The script may not work well with handwritten text or unusual fonts.
- The GTTS may have limitations in reading some Arabic texts accurately.

## Note :

This repo and code feature is an open source python notebook part of the graduation project App `Smart Vision for Visually impaired` which aims to help visually impaired people sense and know what is going around by using AI, Computer Vision and Deeplearning to create powerfull features in a mobile app that could help those everyone in needs
This App is currently in developing of some features as :
1. **Optical characater recognition (OCR) for reading text in many languages.**
2. Friends face recognition using Siamese one-shot learn
3. Currency detection (Egyptian banknotes ✅) using YOLO object detection and EGYPT-IRIS dataset.
4. Image Caption and Scene Recognition of surroundings usind Pre-trained large models.
5. Voice commands (Trigger words detection) for choosing which feature the patiant wants by voice in the application
6. Object detection filtered by text and depth estimating the distance of this object using OpenAi's ClipSeg and Intel's DPT models.
Though in this notebook doesnot feature the real-time extraction as these are used in the app only.

## References
- Pytesseract: https://github.com/madmaze/pytesseract
- Textract: https://textract.readthedocs.io/en/stable/
- OpenCV: https://opencv.org/
- GTTS: https://gtts.readthedocs.io/en/latest/

