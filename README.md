# VHDL Low-Pass FIR Filter for ECG Denoising  

This repository contains the VHDL implementation of a Low-Pass FIR Filter designed for ECG denoising. The filter eliminates high-frequency noise, preserving essential signal characteristics for accurate biomedical signal analysis.

---

## Introduction  

ECG signals are susceptible to high-frequency noise, which can interfere with accurate diagnosis. A Finite Impulse Response (FIR) low-pass filter is implemented in VHDL to reduce noise and enhance signal fidelity. This project demonstrates a hardware-friendly design for FPGA-based systems. 

---

## Features  

- **Customizable Filter Coefficients**: Easily adaptable for various cutoff frequencies.  
- **Hardware Efficient**: Optimized for FPGA and ASIC implementations.  
- **High Precision**: Reduces noise without distorting the ECG signal.  

---

## Block Diagram  

![Block Diagram](https://drive.google.com/file/d/1RIgyKMswq4c7ORh3iwid12HYv6QYo6Av/view?usp=drive_link)  

The block diagram illustrates the data flow: input buffering, coefficient multiplication, and output summation.

---

## Simulation Results  

![Simulation Results](https://drive.google.com/uc?id=YOUR_SIMULATION_IMAGE_FILE_ID)  

The graph shows the performance of the filter in denoising a noisy ECG signal.

---

## Project Setup  

### Prerequisites  

- VHDL simulation tools: ModelSim, Vivado, Quartus, etc.  
- FPGA Development Board (optional).  


