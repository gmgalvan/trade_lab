# Jupyter Data Science Template Starter

A streamlined template for data science projects using Jupyter notebooks with Python virtual environments.

## Prerequisites

- Python 3.8 or higher
- PowerShell (for Windows users)

## Quick Start

### Windows PowerShell Setup

Follow these steps to set up your data science environment:

```powershell
# 1. Create an isolated virtual environment
python -m venv .venv

# 2. Activate the environment (you'll see (.venv) in your prompt)
.\.venv\Scripts\Activate.ps1

# 3. If you encounter a policy error, run this one-time command:
Set-ExecutionPolicy -Scope Process -ExecutionPolicy Bypass

# 4. Install and upgrade dependencies
pip install --upgrade pip
pip install -r requirements.txt

# 5. Launch Jupyter Notebook
jupyter notebook
# Alternative: Use Jupyter Lab for a more modern interface
# jupyter lab
```

### LaTeX Support (Optional)

For PDF export and mathematical notation rendering, install MiKTeX:

1. Download from [miktex.org/download](https://miktex.org/download)
2. Follow the installation wizard
3. Restart your terminal after installation