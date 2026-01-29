# EE4216 – Image Processing and Computer Vision

This repository contains lecture materials, lab notebooks, examples, and supporting resources for the module:

**EE4216 – Image Processing and Computer Vision**  
BSc (Hons) Engineering – Mechatronics / Electronic & Telecommunication  
CINEC Campus

---

## Mandatory Software Setup

All students must follow the same software setup.

Do NOT:
- Use system Python
- Use the base Conda environment
- Mix libraries across environments

---

## 1. Required Software

- Anaconda (Python Distribution)
- Python 3.10 (via Conda environment)
- OpenCV
- Jupyter Notebook

---

## 2. Install Anaconda

Download and install Anaconda (Python 3.x):

https://www.anaconda.com/download

Use default installation options.

---

## 3. Create a Dedicated Environment

Open Anaconda Prompt (Windows) or Terminal (Linux/macOS).

Type commands manually. Do NOT copy–paste from Word or PDFs.

Create the environment:
```bash
conda create --name ee4216 python=3.10
```

Activate the environment:
```bash
conda activate ee4216
```

You should see:
```
(ee4216)
```

---

## 4. Install Required Libraries

Ensure the ee4216 environment is active.

```bash
conda install numpy matplotlib scipy
pip install opencv-python
```

Required libraries:

NumPy – numerical arrays and matrix operations

OpenCV – image processing and computer vision

Matplotlib – image display and plotting

SciPy – scientific utilities

---

## 5. Install Jupyter Notebook and Kernel

```bash
conda install jupyterlab ipykernel
```

Register the kernel:
```bash
python -m ipykernel install --user --name ee4216 --display-name "EE4216 (Python)"
```

---

## 6. Verify Jupyter Setup

Launch Jupyter Notebook:
```bash
jupyter notebook
```

Create a new notebook and select kernel:
```
EE4216 (Python)
```

All lab work and submissions must use this kernel.