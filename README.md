# Fitness Tracker

A simple Python script to generate an Excel-based fitness tracker workbook.

## What it does

When run, `fitness_tracker.py` creates `Fitness_Tracker.xlsx` with three sheets:

- `Workout Tracker` — log workout date, training split, exercises, sets, reps, weight, and remarks
- `Measurements` — record physical measurements, body composition, and notes
- `Diet Tracker` — track meals, food items, macros, calories, hydration, vitamins/minerals, and remarks

## Requirements

- Python 3.14 (or compatible Python 3.x)
- `openpyxl`

## Setup

1. Create python virtual environment:

```bash
python -m venv TrackFitness
```

2. Activate the existing virtual environment:

```bash
source bin/activate
```

3. Install dependencies if needed:

```bash
pip install openpyxl
```

4. Deactivate the environment after usage

```bash
deactivate
```

## Usage

Run the script from the project root:

```bash
python fitness_tracker.py
```

After running, `Fitness_Tracker.xlsx` will be created in the current directory.


## Notes

- The workbook is generated with header rows only; add workout, measurement, and diet entries manually inside Excel.
- You can extend `fitness_tracker.py` to add data import, editing, or templating functionality.
