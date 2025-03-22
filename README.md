## Introduction

This tutorial is part of a workshop presented at [HackAZ](https://hack.arizona.edu/), the University of Arizona’s annual hackathon.  
It is designed to introduce participants to the basics of quantum computing using [Qiskit](https://qiskit.org/), IBM's open-source quantum SDK.  
By the end of this tutorial, you'll have built and run simple quantum circuits in a Jupyter Notebook environment.

The notebook used in this workshop is `hackaz_quantum_tutorial.ipynb`.

---

## Run It Online (Recommended for Beginners)

You can run this tutorial directly in your browser using Binder, with **no installation required**:

[![Launch on Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/RohanBali/HackAZTutorial/HEAD)

> If you prefer to run everything locally on your computer, follow the instructions below.

---

## Running Locally on Your Computer

Follow these steps if you want to run the notebook on your own machine.

---

## Prerequisites

Before installing Qiskit and running the notebook locally, ensure you have the following:

- Python 3.7 or higher
- pip (Python package installer)

### How to Check

#### Check Python Version

**Windows (PowerShell):**

```powershell
python --version
```

If that doesn't work:

```powershell
py --version
```

**macOS / Linux (Terminal):**

```bash
python3 --version
```

You should see output like:

```
Python 3.8.10
```

If your version is lower than 3.7 or Python is not found, install it from:  
https://www.python.org/downloads/

---

#### Check pip Version

**Windows (PowerShell):**

```powershell
pip --version
```

If that doesn't work:

```powershell
py -m pip --version
```

**macOS / Linux (Terminal):**

```bash
pip3 --version
```

If pip is not installed, follow the official guide:  
https://pip.pypa.io/en/stable/installation/

---

## Installation

Once Python and pip are ready, follow these steps:

### 1. Clone the Repository

```bash
git clone https://github.com/RohanBali/HackAZTutorial.git
cd HackAZTutorial
```

### 2. Create a Virtual Environment

**Windows (PowerShell):**

```powershell
python -m venv venv
.\venv\Scripts\activate
```

**macOS / Linux (Terminal):**

```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies

Install all required packages using the `requirements.txt` file:

```bash
pip install -r requirements.txt
```

### 4. Verify Qiskit Installation

```bash
python -c "import qiskit; print(qiskit.__qiskit_version__)"
```

---

## Running the Tutorial Locally

### 1. Install and Configure Jupyter Kernel

```bash
python -m ipykernel install --user --name=hackaz-qiskit
```

This creates a dedicated Jupyter kernel named `hackaz-qiskit`.

### 2. Launch Jupyter Notebook

```bash
jupyter notebook
```

Then open `hackaz_quantum_tutorial.ipynb` in your browser.

### 3. Select the Correct Kernel

In the notebook interface:

- Click `Kernel` > `Change kernel`
- Select `hackaz-qiskit`

---

## Acknowledgments

- Built using [Qiskit](https://qiskit.org/)
- Part of the workshop at [HackAZ](https://hack.arizona.edu/)

---

## Feedback

Feel free to open an issue or submit a pull request if you have suggestions or improvements.
