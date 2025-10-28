# QR-generator

A small Python project to generate QR codes. It provides a simple CLI/script (`main.py`) that creates QR images using the packages listed in `requirements.txt`.

## Screenshots
1. container built:
![alt text](images/Screenshot_20251027_204213.png)

## Quick start

1. Create and activate a virtual environment (recommended):

```bash
python3 -m venv .venv
source .venv/bin/activate
```

2. Install dependencies:

```bash
python -m pip install -r requirements.txt
```

3. Run the script (example):

```bash
python main.py
```

## What is included

- `main.py` — entry point for generating QR codes.
- `requirements.txt` — pinned dependencies used by the project.

## Development & tests

Run tests with pytest after installing dev dependencies:

```bash
pytest -q
```

## Notes

- Tested with Python 3.13 in a local virtual environment. Adjust the Python version to match your environment.
- If you hit permission or SSL errors during install, ensure pip is up-to-date: `python -m pip install --upgrade pip`.

## License

This repository is provided as-is. Add a license file if you plan to share it publicly.
