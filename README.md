This repository contains a series of code snippets for analyzing confocal microscopy images of Arabidopsis roots. 
First, the nd2 files are converted to TIFF format using Fiji/ImageJ, separating the channels. 
Then, each channel is analyzed separately, applying a set of filters, and ranked using an automated pipeline. 
The filtered and highest-ranked images are used for segmentation with a convolutional neural network using the PanSeg environment.
