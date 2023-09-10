# Defect Detection using Image Comparison

By comparing photos with each other using the Structural Similarity Index (SSIM), this Python tool finds flaws in the images. It recognizes changes between two photos and outlines defect-ridden areas with bounding boxes..

## Prerequisites

- Python 3.x
- OpenCV
- imutils
- scikit-image

Install the required libraries:

```
pip install opencv-python imutils scikit-image
```
## Flowchart

![Flowchart](https://github.com/Bhuvaneshbhuvi93/Dhvani/assets/118096816/2c618463-4b58-4d6c-a296-e40fe675a473)

# Bee Dynamics Simulation
This Python program models the three-dimensional motion of a system over time. Based on a set of differential equations, it simulates how a "bee" might move. Plots are made of the obtained trajectories for analysis.

## Dependencies
Python 3.x
NumPy
SciPy
Matplotlib
## Usage
1.Install the required dependencies:
```
pip install numpy scipy matplotlib
```

## Code Explanation
**plot.ipynb:**
Contains the Python code for simulating and plotting the bee's motion. It defines the differential equations, sets up the time span and initial conditions, and uses solve_ivp from scipy.integrate for numerical integration.

**system(t, variables):**
Defines the system of ordinary differential equations (ODEs) governing the motion of the bee. Modify this function to change the behavior of the system.

**t_span:** 
Defines the time span for the integration. Adjust the range as needed.

**initial_conditions:** 
Specifies the initial values for x, y, and z at t = 0.

# Object Detection

## Prerequisites
Matplotlib
