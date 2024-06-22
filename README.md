# Image Analysis of a Large-Scale Structure

<div align="center"><img src="https://raw.githubusercontent.com/QuentinPTT/vime-all4wall/main/results/selected%20MSER.jpg" align="center" width="400" /></div>

## Table of Contents

- [Context](#context)
- [Installation](#installation)
- [Features](#features)
- [Sources](#sources)
- [Contact](#contact)

## Context

Understanding the seismic behavior of U-shaped reinforced concrete core walls. This project uses computer vision techniques to detect targets and, subsequently, detect deformations in these structures.

## Installation

1. Clone the repository:
```sh
git clone https://github.com/quentinptt/vime-all4wall.git
```

## Features

1. Intrinsic calibration of the three cameras with ChArUco markers -> Correction of image distortion.
2. Detection of regions of interest and display of detected regions.
3. Selection among the detected regions based on circularity and intensity criteria.
4. Elimination of duplicates to retain one region per marker.
5. Calculation of the centroids coordinates of each region to sort the markers according to their position (from bottom to top).
6. Labeling of sorted markers.

## Sources

- [OpenCV ArUco Documentation](https://docs.opencv.org/3.4/d9/d6a/group__aruco.html)
- [OpenCV ArUco Detection Tutorial](https://docs.opencv.org/4.x/d5/dae/tutorial_aruco_detection.html)
- [Charuco Detection Tutorial](https://gregorkovalcik.github.io/opencv_contrib/tutorial_charuco_detection.html)
- Learning OpenCV - Adrian Kaehler and Gary Bradski

## Contact


Quentin PETIT - contact@quentinptt.fr
