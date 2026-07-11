# Rod–Disc Kinematic Modelling

<!-- HERO IMAGE
Insert: figures/fig_iczv_schematic_final.png
-->

## Overview

This project investigates the kinematics of a planar rod–disc mechanism by combining analytical modelling with experimental video tracking.

Using Python, marker positions were extracted from recorded footage to reconstruct the motion of the mechanism. The experimental results were then compared with predictions from rigid-body kinematics to evaluate the accuracy of the mathematical model.

The project was completed as coursework for the MEng Engineering Mathematics programme at the University of Bristol.

---

## Objectives

- Develop a mathematical model of a rod–disc mechanism
- Track the motion of the system from experimental video
- Reconstruct disc rotation, rod orientation and slider displacement
- Compare theoretical predictions with experimental measurements
- Verify the rolling no-slip condition
- Construct the Instantaneous Centre of Zero Velocity (ICZV)

---

## Methodology

The workflow consisted of the following stages:

1. Recording the mechanism during motion
2. Tracking coloured markers using Python
3. Converting image coordinates into physical measurements
4. Computing the kinematic variables
5. Comparing theoretical and experimental results
6. Verifying the no-slip condition
7. Constructing the ICZV

---

## Results

### Instantaneous Centre of Zero Velocity (ICZV)

<img width="1800" height="1500" alt="fig_iczv_schematic_final" src="https://github.com/user-attachments/assets/f8433a5c-71af-40af-8a89-4da99853ca16" />


The ICZV was reconstructed from the tracked motion to visualise the instantaneous centre of rotation of the rod throughout the experiment.

---

### Disc Rotation

<img width="640" height="480" alt="fig1_gamma" src="https://github.com/user-attachments/assets/016c51e1-9355-4fd8-b330-04b3a6d554db" />


The experimental disc rotation follows the theoretical prediction well, with small deviations caused by measurement uncertainty and minor slipping during motion.

---

### Slider Displacement

<img width="640" height="480" alt="fig2_slider" src="https://github.com/user-attachments/assets/2715f885-90b1-4a97-8bd2-fab7f7d9ac2b" />


The reconstructed slider displacement closely matches the analytical solution, with a small offset caused by the experimental setup and calibration.

---

### Rod Orientation

<img width="640" height="480" alt="fig3_alpha" src="https://github.com/user-attachments/assets/dce758d1-2aef-4dfb-ade9-d43345062194" />


The measured rod orientation agrees well with the theoretical model, demonstrating good agreement between the analytical solution and the tracked motion.

---

### No-Slip Verification

<img width="640" height="480" alt="fig4_noslip" src="https://github.com/user-attachments/assets/c0a647fe-d181-4c39-a435-a6c50833e32f" />


The measured translational velocity was compared with the theoretical rolling constraint. The agreement confirms that the no-slip assumption is satisfied for most of the experiment.

---

## Tools

- Python
- NumPy
- SciPy
- Matplotlib
- Jupyter Notebook

---

## Repository Structure

```text
rod-disc-kinematic-modelling/
│
├── notebooks/
│   ├── ...
│
├── figures/
│   ├── fig_iczv_schematic_final.png
│   ├── fig1_gamma.png
│   ├── fig2_slider.png
│   ├── fig3_alpha.png
│   └── fig4_noslip.png
│
├── README.md
│
└── report.pdf
```

---

## Skills Demonstrated

- Mathematical modelling
- Rigid-body kinematics
- Experimental data analysis
- Scientific programming with Python
- Numerical methods
- Data visualisation
- Model validation
