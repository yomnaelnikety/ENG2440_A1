# ENG2440 Assignment 1: Pneumonia Classification Challenge

Student: Yomna Elnikety  
Student ID: 25011181

This repository contains the implementation for ENG2440 Assignment 1.

## Files Included

- `25011181_ENG2440_A1.ipynb` - fully executed assignment notebook.
- `25011181_ENG2440_A1.pdf`
- `ai_use_declaration.txt` - declaration of AI tool use.
- `requirements.txt` - Python package requirements.

## Data Setup

The RSNA DICOM images are not included in this repository. They must be downloaded separately from the official RSNA Pneumonia Detection Challenge source, as described in the assignment brief.

## Running the Notebook

1. Create and activate a Python environment.
2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Place the two supplied CSV files in the notebook folder:

```text
assignment1_labels.csv
rsna_to_nih_mapping.csv
```

4. Place the extracted DICOM image dataset under `data/images/`, or update `DATA_ROOT` in the first configuration cell of the notebook to point to the image folder.
5. Run the notebook from top to bottom.

## Notes

- The notebook uses patient-level splitting based on the supplied NIH source-patient identifier.
- The test set is kept separate for final evaluation.
