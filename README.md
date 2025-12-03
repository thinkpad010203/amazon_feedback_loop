# Fedback loop Simulation Framework

This repository contains a simple and modular simulation framework to model
the feedback loop of recommender systems in online retail environments and investigate its systemic effects.

Through the code you run experiments, generate results, and visualize output data.

## 🚀 Features

- Modular and extensible simulation framewok
- Automatic result saving
- Easy plotting of simulation outputs
- Ready-to-use example configuration

## 📁 Repository Structure

project_root/

- │
- ├── src/ # Main simulation code
- │ ├── run.py # Core simulation logic
- │ ├── ....py # Helper files
- │
- │
- ├── results/ # Already geneated results
- │ ├── ... # Example run folder
- │ │ ├── dataframe
- │ │ └── ...
- │ └── ...
- │
- ├── plot.py # Python script to visualize results
- │
- │
- └── README.md

## 🖥️ System Requirements

The experiments included in this project were conducted on the following machine:

### Operating System

- **OS:** Ubuntu 22.04.5 LTS (Jammy Jellyfish)
- **Kernel:** Linux 5.15.0-126-generic (x86_64)

### Hardware

- **CPU:** AMD EPYC 7313 (64 vCPUs, 16-core physical architecture)
- **CPU Frequency:** 1.50 GHz (min), up to 3.73 GHz (max)
- **Memory:** 1.1 TiB RAM
- **Swap:** 8 GiB

### Python Environment

- Python ≥ 3.x
- Dependencies listed in `requirements.txt`

## 🚀 Usage

Run a Simulation python run.py --json_config default_amazon_ecommerce.json
