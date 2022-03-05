# pns 2photon longitudinal 3Ddata analysis
Peripheral nervous system (PNS) in two-photon longitudinal 3D data analysis


These codes are written in matlab, users can test single images or large-scale 4D datasets in a single PC or in High Performance Computing (HPC) clusters.


Steps of 2-photon data processing and quantitative analysis

I. Step 1: Automated stitching of four 16-bit raw image stacks into a superstack

II. Step 2: Segmentation and removal of epidermal autofluorescence via weakly-supervised learning and label propagation 

III. Step 3: 16-bit to 8-bit conversion of superstacks by nonlinear adaptive depth-dependent adjustment on global and local scales

IV. Step 4: Automated rigid and non-rigid 4D registration of stacks acquired at different time points

V. Step 5: Automated neuronal segmentation, tracing and statistical neural network analysis

VI. Step 6: Quantitative analysis of structural plasticity in SNS-mGFP and Thy1-YFP mice.

How to use:

1. Users can first download the file by click the menu "code", download the zip file.
2. Since these codes are written in matlab, you can run the code step by step in matlab.
3. Users can use your own two-photon image stacks for testing or can use our datasets for testing.


When you have any questions, please write to us.

hongwei.zheng AT uni-heidelberg.de

http://www.ana.uni-heidelberg.de/index.php?id=179
