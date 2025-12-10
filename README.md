# Highridge Payment System

This project automates the weekly payment processing for workers at Highridge Construction Company.

## Files in this project
- `main.py` — Python implementation
- `main.R` — R implementation
- `slips/` — Folder containing generated payment slips

## Python Instructions
1. Install Python 3.
2. Run: `python main.py`
3. Slips will appear in the `slips/` folder.

## R Instructions
1. Install R.
2. Run: `source("main.R")`
3. Slips will appear in the `slips/` folder.

## Employee Level Rules
- Female employees with salary > 7,500 and < 30,000 → **A5-F**
- Employees with salary > 10,000 and < 20,000 → **A1**
- All others → **B**

## Error Handling
- Invalid salary values raise an exception.
- Slip creation errors are handled safely.
