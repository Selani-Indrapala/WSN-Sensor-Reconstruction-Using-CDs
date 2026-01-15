# CD-Based Sensor Data Reconstruction

This repository contains the code and datasets for reproducing the experiments in **WSN sensor data reconstruction using Chromatic Derivatives (CD)** for both the Intel Lab and Molene datasets.

## Repository Structure

- `CD_Reconstruction_IntelLabDataset.ipynb`  
  - Script for running the reconstruction on the **Intel Lab dataset** for **one trial**.  
  - Contains all code to run the CD-based method and compare it with classical baseline methods.

- `CD_Reconstruction_MoleneDataset.ipynb`  
  - Script for running the reconstruction on the **Molene dataset** for **n trials**.  
  - Computes the **mean performance** of CD-based reconstruction compared to other methods.  
  - Saves a **CSV file** containing standard deviation and reconstruction errors.

- `Datasets/`  
  - Contains the relevant datasets required for running the scripts.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/your-repo.git
   ```

2. Install the required dependencies (if any).

3. Open the relevant Jupyter notebook (.ipynb) for your dataset and run the cells sequentially.
