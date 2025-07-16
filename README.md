# IGCAR
Automated simulation of sodium leak detection in SS pipelines using a ferrite-core mutual inductance sensor. Frequency and thickness sweeps were conducted in FEMM via MATLAB to analyze eddy current effects on voltage and phase angle. Developed during IGCAR in-plant training.


## Sodium Leak Detection in SS Pipelines using Eddy Currents

This project models and simulates a non-invasive sodium leak detection system based on mutual inductance sensing for stainless steel-walled pipelines, inspired by safety requirements in sodium-cooled fast reactors. It was developed during an in-plant training at IGCAR.

##  Project Overview

A ferrite-core transformer is used as a mutual inductance sensor. The system detects the presence and thickness of leaked sodium by observing changes in the secondary voltage and phase angle. The electromagnetic behavior is simulated using FEMM and automated via MATLAB.

##  Tools and Technologies
- **FEMM**: Electromagnetic field simulation
- **MATLAB**: Simulation automation and data processing
- **Simulink / Origin**: Visualization and further analysis

##  Key Features
- Automated frequency sweep (1 kHz – 12 kHz)
- Sodium thickness variation (0 – 1.6 cm)
- Temperature dependence (120°C to 250°C)
- Voltage and phase angle sensitivity analysis

##  Folder Structure
/Sodium_Leak_Detection/
├── MATLAB_Code/ # All automation and analysis scripts
├── FEMM_Models/ # FEMM files for simulation
├── Plots/ # Exported plots (optional)
└── Report.pdf # Full technical report (IGCAR)



##  Output
- Secondary voltage vs frequency
- Phase angle vs frequency
- Sensitivity matrices for different conditions

##  Author
**Samiksha Biswas**  
Electrical Engineering Student @ IIT (ISM) Dhanbad  
[LinkedIn](https://www.linkedin.com/in/samiksha-biswas-819b55320/)

## 📄 License
This project is intended for educational and academic reference only.
