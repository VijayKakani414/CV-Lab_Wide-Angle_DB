# Self-calibration of Larger FoV cameras for ADAS

This repository contains all my research project details pertaining to the self-calibration of larger FOV cameras used in Autonomous Vehicles

<img width="620" alt="Larger_FoV" src="https://github.com/VijayKakani414/Self-calibration-of-Larger-FoV-cameras-for-ADAS-tasks/assets/25151205/7a8ba03b-e323-45bf-9b0e-d42ac58e5514">

## Overview

This repository contains:

- **[Module-1] VPD**: Vanishing point detection module for determining sensor focal length.
- **[Module-2] Distortion Parameter Estimation**: Parameter estimation module using straight lines in the environment.
- **[Module-3] Undistortion & Compensation factor**: Using parameters to undistort the image scene.
- **Larger FoV samples**: Video files depicting the Larger FoV samples.
- **Default_demo.mp4**: Default mode uses parameter estimation alone.
- **Adaptive_demo.mp4**: Adaptive mode uses parameter estimation through empirical analysis.
- **manuscript.pdf**: Outlines the whole research and relevant results.
- **README.md**: README.md file.

## Repository Structure

The repository is structured as follows:
- Self-calibration-of-Larger-FoV-cameras-for-ADAS-tasks 
  - [Module-1] VPD
  - [Module-2] Distortion Parameter Estimation
  - [Module-3] Undistortion & Compensation factor
  - Larger FoV samples
  - Default_demo.mp4
  - Adaptive_demo.mp4
  - manuscript.pdf
  - README.md

## Getting Started

1. **Clone the Repository**: 
https://github.com/VijayKakani414/Self-calibration-of-Larger-FoV-cameras-for-ADAS-tasks.git

2. **Navigate to Specific Module**: 
cd Self-calibration-of-Larger-FoV-cameras-for-ADAS-tasks/[Module-1] VPD

3. **Modify relevant code-snippet**: Work on code-snippet provided in the `[Module-1] VPD` directory.

## Object detection & Semantic segmentation on the self-calibrated & undistorted samples 

![190_SOTA_YOLOv3_result](https://github.com/VijayKakani414/Self-calibration-of-Larger-FoV-cameras-for-ADAS/assets/25151205/e301a7c6-a1c8-447a-9a7a-78ed89820ff8)
![190_Undist_Seg_result](https://github.com/VijayKakani414/Self-calibration-of-Larger-FoV-cameras-for-ADAS/assets/25151205/0705101c-a5c5-47b8-8f6b-c193b9d0254a)

## Contribution Guidelines

Contributions to enhance this repository are welcome! If you have suggestions, improvements, or want to fix issues, please:

1. Fork the repository.
2. Create your feature branch (`git checkout -b feature/AmazingFeature`).
3. Commit your changes (`git commit -am 'Add some feature'`).
4. Push to the branch (`git push origin feature/AmazingFeature`).
5. Open a pull request.

## Support

For any questions or issues regarding this research/manuscript, feel free to contact [Vijay Kakani](mailto:vijaykakanivja@gmail.com).

Happy learning! 🚀
