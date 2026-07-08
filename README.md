# Titanic Python Refresher Notebook

This project contains a beginner-friendly Jupyter Notebook for an NTI machine learning course refresher. It focuses on Python syntax and data analysis basics using a real Titanic dataset.

## Project Contents

- `Recap.ipynb` — lecture notebook covering variables, data types, conditionals, loops, functions, collections, and loading the Titanic dataset with `pandas`.
- `titanic.csv` — dataset used by the notebook.
- `.venv/` — Python virtual environment for running the project.
- `requirements.txt` — exact Python dependencies installed in the environment.

## Setup Instructions

1. Open the project folder in VS Code.
2. Activate the virtual environment:
   - PowerShell: `.\.venv\Scripts\Activate.ps1`
   - Command Prompt: `.\.venv\Scripts\activate.bat`
3. Install dependencies if needed:
   - `python -m pip install -r requirements.txt`
4. Launch Jupyter Notebook:
   - `python -m notebook`
5. Open `Recap.ipynb` in your browser and run the cells.

## Required Packages

The notebook requires:

- `pandas`
- `ipykernel`
- `notebook`

The full dependency list is available in `requirements.txt`.

## Notes

- The environment is created with Python 3.14.
- `.venv/` is ignored by Git to keep the repository lightweight.
- Use the notebook to explore Python basics interactively.
