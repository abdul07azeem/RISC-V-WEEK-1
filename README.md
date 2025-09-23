# RISC-V Tapeout Program WEEK-0

## 🗓Week 0 – Tool Installation  
This is a simple Overview of how I installed the required tools like Yosys,GTK wave and iverilog in Ubuntu using a Virtual Machine with the following Specifications 

### 🖥System Specifications  
- OS: Ubuntu 22.04
- Virtual Machine - VMWare Workstation
- RAM: 8 GB (minimum 6 GB recommended)  
- Processor: Intel i5 / AMD equivalent  

---

## 🧰Installed Tools  

### 1. Icarus Verilog (iverilog)  
**Command:**  
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
**Screenshot**:
![Screenshot](https://github.com/abdul07azeem/RISC-V-WEEK-1/blob/1159e40726fddaca64682e01fa31192e9106786c/Screenshot%20from%202025-09-20%2023-40-48.png)
---

## 2. GTKWave

**Command:**
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
gtkwave -version

**Screenshot:**
![Screenshot](https://github.com/abdul07azeem/RISC-V-WEEK-1/blob/abb2f8a19d3c8e18b456981f10e66841f7061d38/Screenshot%20from%202025-09-20%2023-44-53.png)
---

## 3. Yosys

**Command:**
```bash

$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install
```
**Screenshot:**
![Screenshot](https://github.com/abdul07azeem/RISC-V-WEEK-1/blob/4b4100c108899f006cd945fc8895110765913eb0/Screenshot%20from%202025-09-20%2023-21-55.png)
---

Learnings

Installed basic tools required for RISC-V program.

Learned how to check versions and take screenshots.
