# VisualCryptoGraphy-Receiver's-Code-MajorProject (ONGOING)

## Introduction

This project demonstrates how to receive four image quadrants, sort and combine them to reconstruct the original image, and then extract a hidden message embedded using LSB (Least Significant Bit) steganography. The hidden message can only be extracted if all four quadrants are combined correctly.

To render the above code: visit the website [nbviewer](https://nbviewer.org/) and paste the link of this repository here to get rendered.

## Working of the Code

### 1. Upload Quadrants
- The user is prompted to upload the four quadrants.
- The quadrants are read and stored.

### 2. Sort Quadrants
- The quadrants are sorted to ensure they are in the correct order to form the original image.

### 3. Combine Quadrants
- The sorted quadrants are combined to reconstruct the original image.
- The reconstructed image is displayed.

### 4. Extract Secret Text
- The hidden message is extracted from the reconstructed image using the reverse LSB steganography method.
- The extracted message is displayed.

## Requirements
- Python 3.x
- OpenCV
- NumPy
- Matplotlib
- Google Colab (for file uploads)

## Usage
1. Clone the repository.
2. Open the notebook in Google Colab or Jupyter Notebook.
3. Run the notebook and follow the prompts to upload the four quadrants.
4. The combined image will be displayed and the hidden message will be extracted and shown.
