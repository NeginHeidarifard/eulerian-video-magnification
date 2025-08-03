# Eulerian Video Magnification for Subtle Motion Detection

This repository provides an implementation of the **Eulerian Video Magnification (EVM)** algorithm, which enhances subtle motion and color variations in videos. The technique enables the visualization of physiological signals—such as heartbeats, breathing, and skin color changes—that are otherwise invisible to the human eye.

> 📄 Based on: [Eulerian Video Magnification for Revealing Subtle Changes in the World – MIT](https://people.csail.mit.edu/mrub/evm/)

---

##  Project Overview

This project focuses on building a computational pipeline for amplifying subtle temporal changes in videos using spatial decomposition and temporal bandpass filtering.

### Real-world Applications:
- Non-invasive physiological monitoring  
- Biomedical signal enhancement  
- Human-computer interaction  
- Behavioral and psychological analysis  
- Surveillance and anomaly detection  

---

##  Key Features

- Spatial decomposition using Laplacian pyramids  
- Temporal filtering using Butterworth filters  
- Motion and color signal amplification  
- Real-time rendering of enhanced videos  
- Tested on facial video datasets with visible physiological cues  

---

##  Folder Structure

```bash
project-root/
├── Eulerian video magnification.ipynb        # Main implementation in Jupyter Notebook
├── Eulerian video magnification_report.pdf   # Technical report documenting the methodology and results
└── README.md                                 # Project documentation


Technologies Used
Python (NumPy, SciPy, OpenCV)

Matplotlib, MoviePy

Jupyter Notebook

Report
Eulerian video magnification_report.pdf

Dataset Access
The dataset used in this project is not publicly uploaded due to storage limitations and privacy considerations.
If you are interested in reproducing the results or require the dataset for academic purposes, please contact the author.

Author
Negin Heidarifard
MSc Artificial Intelligence, Université Paris-Saclay
GitHub: github.com/NeginHeidarifard
Email: heidarifardnegin@gmail.com

This project was developed as part of the Computer Vision coursework at Université Paris-Saclay, demonstrating practical application of motion amplification techniques in real-world video data.
