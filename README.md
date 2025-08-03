# Eulerian Video Magnification for Subtle Motion Detection

This repository presents an implementation of the Eulerian Video Magnification (EVM) algorithm, which enhances subtle motion and color variations in videos. The technique enables the visualization of physiological signals, such as heartbeats and breathing, that are otherwise imperceptible to the human eye.

## Project Overview

The objective of this project is to develop a pipeline for magnifying subtle temporal changes in videos using spatial decomposition and temporal filtering techniques. The application of such methods has significant implications for:

- Non-invasive physiological monitoring
- Human-computer interaction
- Surveillance and behavioral analysis
- Biomedical signal enhancement

## Key Features

- Spatial decomposition using Laplacian pyramids
- Temporal bandpass filtering using Butterworth filters
- Motion and color amplification
- Real-time video rendering for visualizing amplified signals
- Evaluation on facial video datasets with visible physiological changes

## Folder Structure

project-root/
│
├── Eulerian video magnification.ipynb # Main Jupyter notebook
├── Eulerian video magnification_report.pdf # Final report documenting the methodology
├── README.md # This file


## Technologies Used

- Python (NumPy, SciPy, OpenCV)
- Matplotlib, MoviePy
- Jupyter Notebook

## Report


- [`Eulerian video magnification_report.pdf`](./Eulerian%20video%20magnification_report.pdf)

## Dataset Access

The dataset used in this project is not publicly uploaded due to storage limitations and privacy considerations.  
**If you are interested in reproducing the results or require the dataset for academic purposes, please contact the author.**

## Author

**Negin Heidarifard**  
MSc Artificial Intelligence, Université Paris-Saclay  
GitHub: [github.com/NeginHeidarifard](https://github.com/NeginHeidarifard)  
Email: heidarifardnegin@gmail.com

---

This project was developed as part of the Computer Vision coursework at Université Paris-Saclay, demonstrating practical application of motion amplification techniques in real-world video data.
