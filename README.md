# 📘 L3 Data Certificate — Notebooks

This repository hosts the notebooks and supporting files for the **L3 Data Certificate** course.  
It’s designed to run smoothly in a reproducible environment using [Binder](https://mybinder.org).

---

## 🚀 Quick Start

### 🟢 Launch on Binder
Click below to run the notebooks interactively in your browser (no installation required):

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/FrankieN-data/l3-data-certificate/main?urlpath=%2Fdoc%2Ftree%2Fnotebooks%2Funit2-question4-data-bias.ipynb)


> Binder will automatically install all required dependencies from `requirements.txt` and set the Python runtime according to `runtime.txt`. The first launch can take a few minutes before launching.

---

## 🧩 Local Installation (optional)

If you prefer to run the notebooks locally:

```bash
# Clone the repository
git clone https://github.com/FrankieN-data/l3-data-certificate.git
cd l3-data-certificate

# Create and activate a virtual environment (recommended)
python -m venv .venv
.\.venv\Scripts\activate     # On Windows
# source .venv/bin/activate  # On macOS/Linux

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Lab
jupyter lab
