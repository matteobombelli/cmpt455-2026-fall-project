# Preempting Hard Drive Failures

CMPT 455/459 Data Mining, Fall 2026.
Predicting hard drive failures within 3, 7 and 30 days from Backblaze Drive Stats SMART telemetry.

## Data

Backblaze Drive Stats (Q2 2026 release):
https://www.backblaze.com/cloud-storage/resources/hard-drive-test-data

The raw data is not stored in this repository. Download it and place the daily CSV files in `data/raw/`. Notebook 01 creates a smaller sampled Parquet file in `data/`.

## How to run

Open the notebooks in `notebooks/` in numerical order, in Google Colab or Kaggle. Each notebook states which file it needs and which file it produces.

1. `01_load_and_sample.ipynb`
2. `02_eda.ipynb`
3. `03_preprocessing.ipynb`

Install dependencies with `pip install -r requirements.txt`.

## Team

- Matteo Bombelli
- Huang Pan
- Mujtaba Fatah Mohammed
