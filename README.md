# Battery Management System — Simulation & Hardware Implementation

Major project (GNITS, 2024) — designed and implemented a BMS for a 6S, 22V lithium-ion battery pack.

## What it does

* MATLAB/Simulink model for active cell balancing and SOC estimation
* Overcharge protection at 4.25V ± 0.05V
* Over-discharge protection at 2.50V ± 0.08V
* Overcurrent protection at 50A, with surge handling up to 240A via parallel MOSFETs
* Hardware built using DW01-A (protection IC) and BB3A (cell balancing IC)

## Simulation

### Simulink Model


<img width="802" height="455" alt="image" src="https://github.com/user-attachments/assets/face9af8-1dc5-4312-88d6-d1e2869562fb" />


### MATLAB Function Block


<img width="811" height="462" alt="image" src="https://github.com/user-attachments/assets/89c1e377-80d6-4985-88b9-1ae33288b460" />


### Output Characteristics


<img width="812" height="447" alt="image" src="https://github.com/user-attachments/assets/0cab7dae-43aa-4c56-a02c-99e1e3de3b44" />


## Hardware

### BMS Module


<img width="728" height="501" alt="image" src="https://github.com/user-attachments/assets/5d088cb4-1a3b-4128-8d1a-147be482038e" />


### Hardware Connections


<img width="825" height="752" alt="image" src="https://github.com/user-attachments/assets/aa3f617d-58a1-45d1-8046-cf8d0a0befe8" />


### Protection Circuit


<img width="811" height="252" alt="image" src="https://github.com/user-attachments/assets/d3bef211-f775-412d-be65-fdf8289fee09" />


### N-Channel Balancing Circuit

<img width="847" height="285" alt="image" src="https://github.com/user-attachments/assets/92983bbb-d004-400d-a58f-4970a82fb379" />


## Components Used

* DW01-A Battery Protection IC
* HY2212 BB3A Cell Balancing IC
* AOD472 N-channel MOSFETs

## Specifications

| Parameter                 | Value          |
| ------------------------- | -------------- |
| Battery Pack              | 6S Lithium-Ion |
| Nominal Voltage           | 22V            |
| Overcharge Protection     | 4.25V ± 0.05V  |
| Over-discharge Protection | 2.50V ± 0.08V  |
| Overcurrent Protection    | 50A            |
| Surge Current Handling    | Up to 240A     |

## Team

Built as a 5-member team project under guidance of Mrs. K. Priyamvada, Assistant Professor, EEE, GNITS.

Team Members:

* Katkozu Sathwika Sindhu
* Farheen Fathima
* Rudrarapu Nehanjali
* Kotagiri Deekshitha
* Chitrala Hari Sahithi

## Full Report

See `/docs/project_report.pdf` for complete documentation.

