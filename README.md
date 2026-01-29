# Eulerian Video Magnification for Subtle Motion Detection

This repository presents an implementation of **Eulerian Video Magnification (EVM)**, a technique designed to amplify subtle temporal variations in video sequences. By operating directly on pixel intensity changes rather than explicit motion tracking, EVM makes it possible to visualize weak signals such as physiological color changes related to heartbeat or breathing that are otherwise imperceptible to the human eye.

> 📄 Inspired by: *Eulerian Video Magnification for Revealing Subtle Changes in the World*  
> MIT CSAIL – Wu et al.

---

## Project Overview

The goal of this project is to build and analyze a complete Eulerian Video Magnification pipeline based on spatial multiscale decomposition and temporal bandpass filtering. The implementation emphasizes clarity, interpretability, and qualitative analysis rather than strict physiological measurement.

The pipeline combines color space separation, Laplacian pyramids, temporal filtering, and scale-dependent amplification to enhance subtle signals while preserving visual realism.

---

## Potential Applications

- Non-invasive physiological signal visualization  
- Biomedical and health-related video analysis  
- Human–computer interaction  
- Behavioral and affective computing  
- Motion amplification for visual inspection  

---

## Key Features

- Multiscale spatial decomposition using **Laplacian pyramids**  
- Temporal **Butterworth bandpass filtering**  
- Scale-dependent amplification to reduce high-frequency noise  
- Face masking to localize amplification to relevant regions  
- Qualitative analysis of amplification artifacts and limitations  

---

## Repository Structure

```bash
project-root/
├── eulerian-video-magnification.ipynb     # Main implementation and analysis
├── Eulerian_video_magnification_report.pdf # Technical report (methods & results)
└── README.md                              # Project documentation
