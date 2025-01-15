# SeamCarver
The Seam Carver is a Python class for performing seam carving on images. Seam carving is an image resizing technique that reduces the image size while preserving important content by removing low-energy seams.

## Features
Energy Calculation: Computes the energy of a pixel based on its neighbors using the gradient magnitude.
Vertical Seam Removal: Finds and removes the lowest-energy vertical seam.
Horizontal Seam Removal: Finds and removes the lowest-energy horizontal seam.
Image Transposition: Allows switching between horizontal and vertical seams.
