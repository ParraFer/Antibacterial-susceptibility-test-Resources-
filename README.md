# Antibacterial-susceptibility-test-Resources-
This repository contains the resources used for developing and validating a deep learning–based methodology for antibacterial susceptibility testing from microscopic images. The materials are organized as follows:

   *Code/
   Contains the implementation of the algorithm developed for the automatic measurement of inhibition halos using deep learning and image processing techniques.

   *Dataset/
   Includes the microscopic images used for training and testing, as well as the augmented images incorporated into the training set to enhance model robustness.

   *Saved_Weights/
   Provides the trained YOLOv8 network weights used for foreground extraction and for the segmentation of bacterial growth regions and bactericide zones in the visible microscopic area.

   *Results/
   Contains the complete outcomes of the antibacterial susceptibility tests, including detailed analyses, quantitative metrics, and visual representations of inhibition halo measurements.

   *Ecoli_test/
   This folder contains exploratory results obtained when testing the YOLOv8-based model on microscopic images of Escherichia coli. Since the model was trained exclusively on Staphylococcus aureus, the segmentation quality was not sufficiently precise. These results highlight the need to retrain the model with species-specific datasets or to develop dedicated models for each bacterium.
