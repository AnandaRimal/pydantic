# pydantic - examples and guides

This repository contains a small collection of example scripts and a Jupyter notebook demonstrating usage patterns for Pydantic (v1/v2 concepts). It's intended as a learning playground rather than a packaged library.

Contents

- `1_pydantic_why.py` — short introduction and motivation
- `2_field_validator.py` — examples of field-level validators
- `3_model_validator.py` — model-level validation examples
- `4_computed_fields.py` — computed/derived fields examples
- `5_nested_models.py` — working with nested models
- `6_serialization.py` — serialization and parsing examples
- `pydantic.ipynb` — interactive Jupyter notebook covering samples

Requirements

- Python 3.8+ (3.10+ recommended)
- pydantic (the version you want to experiment with; examples may use either v1 or v2 API)

Optional developer tools

- Jupyter / JupyterLab (to run the notebook)

Quick start (PowerShell)

# create a venv and activate it
python -m venv .venv; .\.venv\Scripts\Activate.ps1

# install pydantic and jupyter optionally
python -m pip install --upgrade pip
python -m pip install pydantic jupyter

# run the example scripts
python .\1_pydantic_why.py
python .\2_field_validator.py

# run the notebook (optional)
jupyter notebook pydantic.ipynb

Notes

- The examples are intentionally small. If you want a reproducible environment, add a `requirements.txt` or `pyproject.toml` and I'll help create one.
- If you want the README expanded with API notes or migration tips between Pydantic v1 and v2, tell me which version you target and I'll update it.

Next steps

- Add a `requirements.txt` with pinned dependencies
- Add GitHub Actions CI to run a lint and tests
- Expand the notebook with runnable cells and a short tutorial

License

Add your preferred license (MIT, Apache-2.0, etc.) — currently none included.
