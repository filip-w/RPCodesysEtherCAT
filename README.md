# EtherCAT IO on **CODESYS** with Raspberry Pi
Getting started with learning EtherCAT and **CODESYS** on an affordable hardware platform.

## 📌 Project Overview
EtherCAT is a popular industrial Ethernet technology for real-time automation control, offering high speed and reliability. Using **CODESYS** on a Raspberry Pi to manage EtherCAT I/O is a cost-effective and scalable solution for industrial automation projects.

This guide walks you through the steps to set up EtherCAT I/O with **CODESYS** and a Raspberry Pi, creating a functional Industrial PC (**IPC**) environment.
![Media (41)](https://github.com/user-attachments/assets/fa828baf-724a-4cf0-8217-640971950797)

## 🛠 Hardware Requirements
| Component | Description | Link |
| --------- | ----------- | ----------- |
| Raspberry Pi 3 Model B+  |The main controller (**SBC**) |
|EtherCAT Bus IO Card | AliExpress-style IO module | [Link to Module](https://s.click.aliexpress.com/e/_c3qKftV1)|
| DIN Rail Power Supply | 5VDC (for Pi) and **24VDC** (for IO/Relays) | [Link to Module](https://s.click.aliexpress.com/e/_c3Z5U4oT)|
| **DIN** Rail Mount | Bracket for Raspberry PiRelay Module | [Link to Module](https://s.click.aliexpress.com/e/_c4EomqBD)|
| DIN Rail Relay | Slim Relay Module |  [Link to Module](https://s.click.aliexpress.com/e/_c4VS9TMJ)|
| Enclosure | IP67 Waterproof **ABS** Box (210x210x130mm) | [Link to Enclosure](https://s.click.aliexpress.com/e/_c4LSlr8B)|

## 🚀 Build Instructions. 
<img width="1396" height="865" alt="Communication_overview" src="https://github.com/user-attachments/assets/57f0e614-d689-4032-94f1-6accea99ca5b" />

1. Install Raspberry Pi OS
    1. Download the Raspberry Pi Imager tool.
    2.  Install the OS image to your microSD card. **Important**: Use the *Edit Settings* (cog icon) in the Imager to enter your WiFi credentials and enable **SSH** before flashing.
2. Prepare **CODESYS** Development System
    1. Download and install the **CODESYS** Development System V3 on your Windows PC.
    2.  It is available for free at the **CODESYS** Store.
    4. Deploy **CODESYS** Runtime
1. Open **CODESYS** on your PC.
    1. Use the **CODESYS** Control for Raspberry Pi package to deploy the runtime to your Pi's IP address.
    2. Ensure the license is activated (or use the 2-hour trial mode for testing).
  
<img width="1922" height="1153" alt="codesysProject" src="https://github.com/user-attachments/assets/874c3ecb-ac1d-4d1e-be5c-56c21a608670" />

## 📂 Project Files
**rpi_codesys_ethercat_tutorial.project**
The complete **CODESYS** project file containing the EtherCAT master configuration and IO mapping.
<img width="910" height="1021" alt="IO_Sketch" src="https://github.com/user-attachments/assets/2420f77e-9a0e-44ba-ad29-858a0ea466a8" />


## 📝 Conclusion
Setting up EtherCAT I/O on a Raspberry Pi with **CODESYS** opens up endless possibilities for industrial automation projects. 

The combination of affordable hardware and powerful software provides a robust platform for developing custom automation solutions.
![Media (2)](https://github.com/user-attachments/assets/5770dd40-04b9-4275-ac23-86e1867e6771)

## 🔗 Links & Resources
* [Original Hackaday Project](https://hackaday.io/project/201834-ethercat-io-on-codesys-with-a-raspberry-pi)
* [CODESYS Official Website](https://www.codesys.com/)
