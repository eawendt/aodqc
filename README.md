# aodqc
Data and code accompanying "A cloud screening algorithm for ground-based sun photometry using all-sky images and deep transfer learning."

## DOI
[![DOI](https://zenodo.org/badge/472905349.svg)](https://zenodo.org/badge/latestdoi/472905349)

## What is contained in this repository
1. The full set of raw image files from the NCASI data set.
2. Partitioned images from three independent data sets.
3. Deep learning model and weight files in hdf5 format.
4. A python example notebook with how to use the model.

## How to use the example notebook
### Method 1 (recommended): Google Colab
1. Click this link: [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/eawendt/aodqc/blob/main/aodqc_example.ipynb)
2. Run the script. There is a command in the script that automatically creates a local clone of the repository in your Google Drive.

### Method 2: Run Locally
1. Clone the repository
2. Make sure you have the following packages installed on your machine:
    * cv2
    * glob
    * matplotlib
    * natsort
    * numpy
    * random
    * tensorflow
3. Comment out the following command: ```!git clone https://github.com/eawendt/aodqc.git```
