# Intelligent Autonomous UAS Inspection
## By Stanley Armstrong, Samuel Frazee, Angello Parrolivelli, Guneet Kohli, Jason Ngu, Avi Peltz

- A1 - Decoder Component.ipynb
  - QR Code decoder component that utilizes PyZBar and OpenCV.
- A2 - Detection Component.ipynb
  - Attempt at creating an object-detection regression model. Though we were able to train it, we were unable to use it to predict on new test images.
- Component Integration.ipynb
  - Combines our decoder component and multi-label classifier to run our decoder on images that our classifier was able to pick up QR Codes on.
- Multi-label Classification.ipynb
  - Contains our multi-label classifier model which was successfully trained and able to output results on new test images.
- ONNX Model Export.ipynb
  - Outputs our classifier model to an ONNX format for cross-platform support.

## Links
- [Report](https://drive.google.com/file/d/1PLG8Y0Vbf6052_fdSjbdKTrxFVvSBSRM/view?usp=sharing)
- [Presentation slides](https://docs.google.com/presentation/d/1w8ndVuESFwqNvVC0A68H8Q7QLeqUiIetR_mT7SJamHk/edit?usp=sharing)
