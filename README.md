# Quick intro

This repository uses the dataset file `pcos_data_base_ml.xlsx` (Excel) for the ML project. Place the file in the repository root (or update paths in code).

## Setup (recommended)

Windows (PowerShell / CMD)
```powershell
python -m venv .venv
.venv\Scripts\activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

macOS / Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
python3 -m pip install --upgrade pip
pip install -r requirements.txt
```

If you don't have a requirements.txt yet, create one after installing packages:
```bash
pip freeze > requirements.txt
```