# astro100finalproject

M67 Hertzsprung–Russell Diagram

This repository contains the full data reduction code and analysis code used to recreate the Hertzsprung–Russell (H-R) diagram of the open cluster M67

Overview

I obtained B- and V-band photometric data using KeplerCam on the 1.2-m telescope at Mt. Hopkins. The project processes raw CCD images to generate a calibrated H-R diagram, showcasing main-sequence, turn-off, and red-giant branch stars in M67.

Contents
	• Ast100FinalProject: Main Python script performing: data reduction of raw fits files, aperture photometry with DAOStarFinder, source matching across filters, and final H-R Diagram plotting

How to Run
	1.	Clone the repository at this link: https://github.com/rbhargava03/astro100finalproject
 	2.	Download the "2025.0318" folder
 	2.	Change this line "dir = 'drive/MyDrive/Harvard/2025.0318" so that it navigates to your "2025.0318" folder
	3. 	Use Python 3 with astropy, photutils, numpy, and matplotlib is installed.
	4.	Run the main script
