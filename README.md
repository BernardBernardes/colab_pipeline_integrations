# 🔌 OpenDSS + Google Colab Integration with py_dss_interface

This repository provides a ready-to-use Google Colab notebook that integrates the OpenDSS simulation engine with the Python package `py_dss_interface`. It enables you to run OpenDSS simulations entirely in the cloud — no local installation required.

## 📘 Features

- ✔️ Install `py_dss_interface` on Google Colab
- ✔️ Clone and run official OpenDSS example circuits (EPRI)
- ✔️ Execute power flow simulations directly from Python
- ✔️ Extract and export results (e.g., `Export Result`)
- ✔️ Visualize power flow with custom matplotlib-based plotting (similar to `Plot Circuit Power`)

## 🚀 How to Use

1. Open the notebook in Google Colab:
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nfPcNcUmx9rN725Zji_WSOsklgj2tDOv#scrollTo=FtkWCPUc1tqo)

2. Follow the steps to:
   - Install the library
   - Load the example circuits
   - Run simulations
   - Visualize the results

> ⚠️ Important: The notebook automatically restarts the runtime after installing native dependencies. Be sure to re-run all cells after restart.

## 📂 File Structure

.

├── py_dss_interface_google_colab_integration.ipynb  # Main notebook with OpenDSS integration

├── README.md                                         # Repository description and instructions

## 📦 Requirements

The notebook will install everything needed on its own. No local setup required.

## 🛠️ Based On

- [`py_dss_interface`](https://github.com/PauloRadatz/py_dss_interface)
- [OpenDSS Examples by EPRI](https://github.com/BernardBernardes/EPRI-OpenDSS-Examples)

---

## 📈 Sample Output

The notebook includes plots like this:

---

## 🤝 Contributions

Pull requests and improvements are welcome — especially new utilities for OpenDSS visualization and result export.


