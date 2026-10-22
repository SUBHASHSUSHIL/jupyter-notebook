# Jupyter Notebook Exploration

A hands-on reference notebook for learning and exploring Jupyter Notebook fundamentals — from Markdown formatting to Python data visualization with NumPy and Matplotlib.

---

## Table of Contents

- [Overview](#overview)
- [Prerequisites](#prerequisites)
- [Setup & Installation](#setup--installation)
- [Running the Notebook](#running-the-notebook)
- [Notebook Contents](#notebook-contents)
- [Key Concepts Covered](#key-concepts-covered)
- [Project Structure](#project-structure)
- [Keyboard Shortcuts Reference](#keyboard-shortcuts-reference)

---

## Overview

`explore-jupyternb.ipynb` is a beginner-friendly notebook designed to document and demonstrate core Jupyter Notebook features including:

- Writing and rendering **Markdown** cells
- Executing **Python code** cells
- Importing and using **NumPy** and **Matplotlib**
- Generating basic **data visualizations** (e.g., sine wave plots)
- Understanding **Jupyter keyboard shortcuts** for efficient navigation

---

## Prerequisites

Make sure you have the following installed on your system:

| Requirement | Minimum Version |
|---|---|
| Python | 3.8+ |
| pip | 21.0+ |
| Jupyter Notebook or JupyterLab | Latest stable |
| NumPy | 1.21+ |
| Matplotlib | 3.4+ |

---

## Setup & Installation

### 1. Clone or Download the Repository

```bash
git clone <your-repo-url>
cd jupyter-notebook
```

### 2. (Recommended) Create a Virtual Environment

Using `venv`:

```bash
python -m venv venv

# Activate on Windows
venv\Scripts\activate

# Activate on macOS/Linux
source venv/bin/activate
```

Using `conda`:

```bash
conda create -n jupyter-explore python=3.10
conda activate jupyter-explore
```

### 3. Install Dependencies

```bash
pip install notebook numpy matplotlib
```

Or install from a requirements file if provided:

```bash
pip install -r requirements.txt
```

### 4. Verify Installation

```bash
python -c "import numpy, matplotlib; print('Dependencies OK')"
```

---

## Running the Notebook

### Option A — Classic Jupyter Notebook

```bash
jupyter notebook
```

This opens a browser tab at `http://localhost:8888`. Navigate to `explore-jupyternb.ipynb` and open it.

### Option B — JupyterLab (modern interface)

```bash
pip install jupyterlab
jupyter lab
```

### Option C — VS Code

1. Install the [Jupyter extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter) for VS Code.
2. Open `explore-jupyternb.ipynb` directly in the editor.
3. Select your Python kernel from the top-right kernel picker.

---

## Notebook Contents

### Cell 1 — Markdown Syntax Demo

Demonstrates Jupyter Markdown formatting:

- Heading levels (`#`, `##`, `###`)
- Normal text paragraphs
- Horizontal rules (`---`)
- Unordered lists

### Cell 2 — Basic Python Output

```python
print("Hello World")
print("Double d press in delete cell")
```

Introduces code cell execution and standard output.

### Cell 3 — Library Imports

```python
import numpy as np
import matplotlib.pyplot as plt
```

Imports the core data science libraries used in subsequent cells.

### Cell 4 — Data Visualization

Generates a plot using NumPy and Matplotlib (e.g., a sine wave). Demonstrates how to create, configure, and render charts directly inside the notebook.

---

## Key Concepts Covered

| Concept | Description |
|---|---|
| Markdown cells | Use `#` for headings, `-` for lists, `---` for dividers |
| Code cells | Python executed in the kernel; output rendered inline |
| NumPy | Numerical computing library for array operations |
| Matplotlib | Plotting library for 2D charts and visualizations |
| Cell execution | `Shift + Enter` runs a cell and moves to the next |
| Kernel | The Python process that runs the notebook's code |

---

## Project Structure

```
jupyter-notebook/
├── explore-jupyternb.ipynb   # Main exploration notebook
└── README.md                 # Project documentation (this file)
```

---

## Keyboard Shortcuts Reference

These shortcuts are demonstrated and documented inside the notebook.

### Command Mode (press `Esc` to enter)

| Shortcut | Action |
|---|---|
| `Enter` | Switch to Edit mode |
| `Shift + Enter` | Run cell, move to next |
| `Ctrl + Enter` | Run cell, stay on current |
| `A` | Insert cell above |
| `B` | Insert cell below |
| `D D` | Delete current cell |
| `M` | Convert cell to Markdown |
| `Y` | Convert cell to Code |
| `↑ / ↓` | Navigate between cells |

### Edit Mode (press `Enter` to enter)

| Shortcut | Action |
|---|---|
| `Esc` | Switch to Command mode |
| `Shift + Enter` | Run cell, move to next |
| `Ctrl + Enter` | Run cell, stay on current |
| `Tab` | Code completion / indent |
