# Panorama Stitcher

This project demonstrates how to create a panorama image by stitching multiple images together. The repository contains two Jupyter notebooks: one uses a built-in stitcher, and the other implements the stitching process from scratch.

## Repository Structure

- **images/**: Contains input images and the resulting stitched output.
- **notebooks/**:
  - `Panorama Using Built-in Stitcher.ipynb`: Demonstrates how to use an existing library to stitch images.
  - `Panorama Stitcher From Scratch.ipynb`: Walks through the process of stitching images manually using image processing techniques.

## Example

Below are examples of input images and the resulting stitched panorama:

### Input Images
<p align="center">
  <img src="images/image1.png" alt="Image 1" width="45%" />
  <img src="images/image2.png" alt="Image 2" width="45%" />
</p>

### Output Image
<p align="center">
  <img src="images/Output.png" alt="Output" width="90%" />
</p>

## Dependencies

- Python 3.x
- OpenCV
- NumPy
- Matplotlib (for displaying images in notebooks)
