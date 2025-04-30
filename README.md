# astro100finalproject

M67 Hertzsprung–Russell Diagram

This repository contains the full data reduction code and analysis code used to recreate the Hertzsprung–Russell (H-R) diagram of the open cluster M67

Overview

I obtained B- and V-band photometric data using KeplerCam on the 1.2-m telescope at Mt. Hopkins. The project processes raw CCD images to generate a calibrated H-R diagram, showcasing main-sequence, turn-off, and red-giant branch stars in M67.

Contents
	•	Ast100FinalProject: Main Python script performing:
  	•	Aperture photometry with DAOStarFinder
  	•	Source matching across filters
  	• Final H-R Diagram plotting
  	•	make_figures.sh: Script to regenerate all plots and figures used in the final report.
	•	data/: Directory for raw B and V images and calibration frames
	•	report/: Final PDF report summarizing the methodology, results, and discussion.

How to Run
	1.	Clone the repository: git clone https://github.com/rajanbhargava/M67-HR-Diagram.git
cd M67-HR-Diagram
	2.	Use Python 3 with astropy, photutils, numpy, and matplotlib is installed.
	3.	Run the main script
