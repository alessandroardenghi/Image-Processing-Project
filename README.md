# ⚙️ Image Processing Project

## 🌟 Highlights

- We performed Projective and Affine Rectification
- We perfomed Sequential RanSaC to find clusters of dominant lines
- We performed Feature Matching and computed Fundamental Matrix and Epipolar Lines


## ℹ️ Overview

In this project we were given two pictures of Villa Melzi d'Eril from two different perspectives. The project was divided into 5 tasks:
- **Task1**: We applied Sobel and Canny edge filters to detect edges in the image, and then we did corner detection using Harris Corner Detector. Finally, we obtained the lines present in the image using Hough Transform.
- **Task2**: We rectified the horizontal section of Villa Melzi d'Eril and estimated the true ratio between the length of the facades.
- **Task3**: We clustered dominant lines together using RanSaC on the lines obtained in Task1, and obtained 3 clusters corresponding to lines parallel to the x, y and z axis. We also obtained the points at infinity.
- **Task4**: We estimated the camera matrix given the points at infinity obtained in Task3
- **Task5**: We did manual and automatic feature matching between the two images, then estimated the fundamental matrix and epipolar lines.

### ✍️ Authors

Alessandro Ardenghi, Rocco Giampetruzzi, Rolf Minardi
