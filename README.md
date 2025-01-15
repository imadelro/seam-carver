# SeamCarver
## Overview
The Seam Carver is a Python class for performing seam carving on images. Seam carving is an image resizing technique that reduces the image size while preserving important content by removing low-energy seams.

This seam carver leverages dynamic programming to identify the seam with the lowest energy, ensuring minimal impact on the image's content.

## Features
**Energy Calculation**: Computes the energy of a pixel based on its neighbors using the gradient magnitude.

**Vertical Seam Removal**: Finds and removes the lowest-energy vertical seam.

**Horizontal Seam Removal**: Finds and removes the lowest-energy horizontal seam.

**Image Transposition**: Allows switching between horizontal and vertical seams.

## Demo
https://github.com/user-attachments/assets/4fc46acf-552a-42d3-a0b1-8cea61a34d38

