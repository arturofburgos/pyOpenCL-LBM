# pyOpenCL-LBM
Implementation of incompressible 2D lid driven cavity in Python and pyOpenCL.  This jupyter notebook utilizes an OpenCL device to compute with Lattice Boltzmann method.  This includes CPUs and GPUs (Nvidia or AMD).

## Features implemented
* Single relaxation time (SRT) /  Bhatnagar-Gross-Krook (BGK)
* Two relaxation time (TRT)
* Halfway bounce-back boundary condition
* Any aspect ratio
* Comparison to Ghia et al. profiles

## Notes
* This is adapted and extended from the example CUDA code from Timm Kruger at https://github.com/lbm-principles-practice/code
* Depending on the devices on your computer, you might need to play with the device/platform selection.  If you just have one OpenCL device, this should work correctly out of the box.

## Dependencies
Install dependencies with `pip install requirements.txt`
* Python 3 and standard libraries
* pyopencl
* matplotlib
* Numpy
* Scipy
