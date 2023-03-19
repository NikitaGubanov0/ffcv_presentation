# FFCV Object Detection Example

This repository contains a simple example of using the FFCV library for object detection on an image. The example demonstrates how to use FFCV to load a pre-trained object detection model and apply it to an input image to detect objects.

## Prerequisites

1. Python 3.6 or higher
2. FFCV library
3. OpenCV library

## Installation

1. Install Python 3.6 or higher if not already installed.
2. Install FFCV and OpenCV using pip:

```
conda create -y -n ffcv python=3.9 cupy pkg-config compilers libjpeg-turbo opencv pytorch torchvision cudatoolkit=11.3 numba -c pytorch -c conda-forge
conda activate ffcv
pip install ffcv
```

## Running the example

1. Clone this repository:

  git clone https://github.com/NikitaGubanov0/ffcv_presentation.git

2. Change into the project directory:

  cd ffcv-object-detection-example

3. Run the object detection script:

  python object_detection.py


The script will display the input image with detected objects outlined by boundi
