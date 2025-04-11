# Project for ECE 633 Course

## Project Title
**Switching Transient Studies and Design of Neutral Grounding Reactor for Shunt-Compensated EHV Transmission Line**

## Introduction
This project investigates switching transient phenomena and neutral grounding reactor (NGR) design in shunt-compensated Extra High Voltage (EHV) transmission lines using an electromagnetic transient (EMT) simulation-based methodology. A key focus is the comparative evaluation of surge arresters (SAs) and pre-insertion resistors (PIRs) as mitigation techniques and the analytical and simulation-based determination of optimal NGR impedance to ensure effective arc suppression for safe single-pole auto-reclosing as well as suppresion of resonant overvoltages.

### Objectives
- Analyze switching transient overvoltages in a shunt-compensated EHV transmission line.
- Evaluate the mitigation performance of SAs and PIRs through EMT simulations.
- Design and validate an optimal NGR value through steady-state and transient studies.
- Ensure successful single-pole auto-reclosing and resonant overvoltage control using the designed NGR.

### Case Study
The Adani--Rahanpur 400\,kV double-circuit shunt-compensated transmission line is selected as the case study for switching transient overvoltage study and NGR design. This line is a cross-border AC high-voltage corridor developed for importing power from Adani Power's Godda thermal power plant in India into the transmission grid system in Bangladesh.All simulations are conducted in **PSCAD/EMTDC** 4.5 version. 

### Simulation Environment
All simulations are conducted in **PSCAD/EMTDC** 4.5 version. 

### Files and Organization
- `/PSCAD_Simulation_Files/`: Contains PSCAD simulation files
- `/Documents/`: Includes the final project report.

### Results Summary
- The switching transient studies demonstrated that PIRs provided superior performance compared to SAs in mitigating switching transients, especially in damping initial overvoltage peaks and oscillations.
- Comprehensive steady-state and transient analyses demonstrated that an optimally designed NGR can effectively balance secondary arc current suppression and resonant overvoltage control within acceptable neutral voltage limits.

## Dataset
Line data, system data, and SA data for the case study are provided by Power Grid Bangladesh, PLC, the sole transmission utility in Bangladesh.  

## Documents
- `ECE633_Project_Md_Touhidul_Haque.pdf`: Final course project report.

## References
1. M. Cervantes, I. Kocar, A. Montenegro, D. Goldsworthy, T. Tobin, J. Mahseredjian, R. Ramos, J. Marti, T. Noda, A. Ametani et al., “Simulation of switching overvoltages and validation with field tests,” IEEE Transactions on Power Delivery, vol. 33, no. 6, pp. 2884–2893, 2018.
2. M. R. Dadash Zadeh, M. Sanaye-Pasand, and A. Kadivar, “Investigation of neutral reactor performance in reducing secondary arc current,” IEEE Transactions on Power Delivery, vol. 23, no. 4, pp. 2472–2479, 2008.
3. “Ieee standard for requirements, terminology, and test procedures for neutral grounding devices,” IEEE Std C57.32-2015 (Revision of IEEE Std 32-1972), pp. 1–83, 2016.
4. “Ieee guide for the application of insulation coordination,” IEEE Std C62.82.2-2022, pp. 1–83, 2023.
5. V. Bathini, R. Nagaraja, and K. Parthasarathy, “Guidelines for selection of neutral reactors rating for shunt compensated ehv transmission lines,” International Journal of Engineering Research and Technology, NPSC, 2012.

## Acknowledgments
We extend our gratitude to our instructor and supervisor for their invaluable guidance and support throughout this course.

## Author
**Md Touhidul Haque**  
MSc Student, Electrical and Computer Engineering  
University of Alberta

