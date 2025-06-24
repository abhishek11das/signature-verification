# Signature Verification
A Python application to verify the similarity between two handwritten signatures by analyzing their structural similarity.


This application helps you mathematically evaluate how similar two signatures are. You can capture or upload images of two signatures, which will be displayed side-by-side. The app then calculates and shows the similarity percentage to help determine if the signatures match. The comparison uses the `structural_similarity` function from the `skimage.metrics` package, which compares the visual structure of the two images.

## Features
- Upload or capture two signature images.
- Display both signatures side-by-side for visual comparison.
- Show similarity percentage based on Structural Similarity Index Measure (SSIM).
- Simple and easy-to-use interface.


## Prerequisites
1. Python 3.6 or higher
2. OpenCV
3. Scipy
4. Scikit-image


## Run
1. `pip install requirements.txt`
2. `python main.py`


## Please open an issue if
* you have any suggestion to improve this project
* you noticed any problem or error
