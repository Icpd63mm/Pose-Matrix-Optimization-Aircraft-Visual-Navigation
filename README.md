# Pose-Matrix-Optimization-Aircraft-Visual-Navigation
MATLAB implementation of geometric-nonlinear global optimization algorithm for aircraft visual navigation pose matrix estimation.
Code for Paper: A Geometric-Nonlinear Global Optimization Algorithm for Solving Pose Matrices in Aircraft Visual Navigation
Overview
This package contains the MATLAB implementation of the proposed geometric-nonlinear global optimization algorithm for pose matrix estimation in aircraft visual navigation.
Platform
MATLAB R2020b or later
Files Description
Main1_GR_NGA_intersect.m: Main program entry 1, mainly used to test the computational performance of the RGA and NGA algorithms under normal intersection conditions.
Main2_GR_NGA_non_intersect.m: Main program entry 2, mainly used to test the computational performance of the RGA and NGA algorithms under extreme non-intersection conditions.
Main3_GR_NGA_DrawPic.m: Plotting program, which loads the algorithm performance data exported by the above two M-files in Excel table format and generates corresponding figures.
DATA_Bsm_intersect_7700.txt: Data source files for 7700 groups of intersection scenarios.
DATA_Bsm_non_intersect_135.txt: Data source files for 135 groups of non-intersection scenarios.
Usage
Open MATLAB and set the current directory to the code folder
Run the main script:
Main1_GR_NGA_intersect.m;Main2_GR_NGA_non_intersect.m;
All solution results will be automatically exported to the corresponding Excel files.
If you need to plot the output results for the two scenarios, please run Main3_GR_NGA_DrawPic.m.
Reproducibility
All algorithms and experimental settings are consistent with those described in the paper. This code supports full reproduction of the proposed method.
