# Email Cleaning Pipeline

This project implements an automated pipeline in Python to identify and extract non-existent email addresses from a delivery dataset. The pipeline is based on analyzing the `failure_message` column in a `.csv` file and filtering entries that indicate the email address does not exist.

---

## Files Included

- `main.ipynb`: Jupyter Notebook containing the full email cleaning pipeline, modularized with well-documented functions.
- `non-existent-emails.csv`: Output file listing emails that are classified as non-existent.
- `deliveries.csv`: Input file (must be provided in the same directory).

---

## Features

- Modular code with clean, reusable functions.
- Detection of bounced emails using text search on the `failure_message` column.
- Output saved to a `.csv` file with comma-separated values.
- Easily extensible for additional filtering rules.

---

## Requirements

- Python 3.7+
- Pandas

You can install the required library with:

```bash
pip install pandas

