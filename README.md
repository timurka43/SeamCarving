

# Seam Carving: Content-Aware Image Resizing
Seam carving is a technique for content-aware image resizing that reduces the dimensions of an image by removing the least important seams—paths of connected pixels with the lowest cumulative energy. This approach allows for intelligent resizing without distorting the most important features of the image.

## Collaborators
* Peter Murphy
* Krishna Nayar

Both collaborators are classmates from the CSC-301 Analysis of Algorithms class, contributing to various aspects of algorithm design and implementation.

## Contributions
### My Contributions
* Designed and implemented the vertical seam-carving algorithm, focusing on reducing the image's width while preserving key visual elements.
* Implemented the dynamic programming approach to efficiently find and remove low-energy seams.
* Identified and corrected design bugs in the program to ensure proper functionality for the final submission.
* Converted the pixel data structure back into the finalized image format after seam removal.

### Collaborators' Contributions
* Peter Murphy: Assisted with algorithm validation and contributed to refining the dynamic programming approach.
* Krishna Nayar: Worked on converting the image into a data structure and calculating each pixel's energy for use in the seam-carving algorithm.

## Acknowledgment
We would like to express our gratitude to Professor William Rebelsky for providing the energy function used in our implementation, which served as a foundational component of our seam-carving algorithm.


## Current Implementation
The current implementation processes the InitialImage.png provided in the repository and reduces its dimensions as follows:

* Original Dimensions: 507x285 (width x height)
* Reduced Dimensions: 408x285 (width x height)

## Features:
* Vertical Seam Cutting: Reduces the width (number of columns) by repeatedly identifying and removing vertical seams with the lowest energy.
* Dynamic Programming: Ensures efficient calculation of the optimal seams for removal.

## Further Development
Future iterations of this project aim to extend functionality in the following ways:

1. Horizontal Seam Cutting: Implement seam carving to reduce the image height by identifying and removing horizontal seams.
2.  User-Defined Inputs:
    * Allow users to provide custom images for resizing.
    * Enable users to specify desired dimensions for both width and height.
3 Enhanced Visualization:
    * Provide visual representation of seams before removal.
    * Animate the resizing process for educational purposes.

4. Performance Optimization: Explore parallel processing or GPU acceleration for handling larger images more efficiently.


By implementing these features, the program will become more versatile and robust, capable of accommodating a broader range of use cases.

