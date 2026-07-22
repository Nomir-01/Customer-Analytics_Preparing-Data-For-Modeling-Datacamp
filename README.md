# Customer Analytics: Preparing Data for Modeling

A data-preparation case study focused on making a customer analytics dataset more suitable for machine learning. The notebook converts inefficient data types, encodes categorical structure, applies business filters, and compares memory usage before and after transformation.

## Tasks covered

- Convert binary categories to Boolean values.
- Downcast integer and floating-point columns where appropriate.
- Represent nominal and ordinal columns as categorical data.
- Apply a meaningful order to ordinal categories.
- Filter candidates using experience and company-size criteria.
- Compare the memory footprint of the original and transformed datasets.

## Tools

- Python
- pandas
- Jupyter Notebook

## Repository contents

- `notebook.ipynb` — transformation workflow and memory comparison
- `customer_train.csv` — source dataset
- `hr-image-small.png` — project cover image
- `requirements.txt` — Python dependencies

## Run locally

```bash
python -m venv .venv
python -m pip install -r requirements.txt
jupyter lab notebook.ipynb
```

## Project context

This is a personal learning project completed as guided DataCamp coursework. It demonstrates practical dtype selection, categorical modeling, filtering, and memory-conscious data preparation.
