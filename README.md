# CSE 44648 Team 4

### Installation Instructions
1. Clone the repository

```bash
git clone git@github.com:joshuatighe/cse-44648-team-4.git
cd cse-44648-team-4
```

2. Create a virtual environment

Mac/Linux
```bash
python3 -m venv .venv
source .venv/bin/activate
```

Windows
```bash
python -m venv .venv
.venv\Scripts\activate
```

3. Install dependencies

```bash
pip install -r requirements.txt
```

4. Run the code blocks in `notebooks/test.ipynb` to ensure everything is working correctly

### Directory Structure

```
└── cse-44648-team-4/
    ├── data/             # Datasets live in here
    │   ├── raw/          # Raw datasets
    │   └── processed/    # Cleaned, processed datasets
    ├── notebooks/        # .ipynb notebooks for analysis, exploratory work, etc.
    └── src/              # .py files containing pipelines, utility functions, etc.
```
