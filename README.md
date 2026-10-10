
# Data

This project uses the Online Retail dataset from the
UCI Machine Learning Repository.

Dataset:
https://archive.ics.uci.edu/dataset/352/online+retail

## Download Instructions

1. Download the Online Retail dataset from UCI.
2. Save the original ZIP archive in this directory.
3. Rename the ZIP file to `online+retail.zip`.
4. Run the Jupyter notebook from the `notebooks` directory.

## Data Availability

The original dataset is not included in this repository.

The notebook loads the Excel workbook directly from
the ZIP archive. No manual extraction is required.

### Notebook Execution and Outputs

The original UCI Online Retail dataset is maintained locally as `data/online+retail.zip` and loaded directly from the ZIP archive. The source data is not modified during processing.

Run the notebook from the `notebooks/` directory, executing the cells sequentially. The notebook requires the Python packages listed in `requirements.txt`, including `openpyxl` for reading the Excel workbook.

Visualizations are displayed within the notebook and saved as PNG files in `outputs/figures/`. The notebook automatically creates this directory if it does not already exist. Saved figures can be used in the repository README, project documentation, or presentations.

The analysis progresses from data understanding and cleaning through exploratory analysis, RFM feature engineering, clustering, and business interpretation.

### Generated Outputs
The notebook saves PNG figures in the `outputs/figures/`.

