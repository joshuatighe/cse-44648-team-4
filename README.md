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
.
├── data/
│   ├── crypto/
│   │   ├── raw/
│   │   ├── interim/
│   │   └── processed/
│   └── dropout/
│       ├── raw/
│       ├── interim/
│       └── processed/
├── notebooks/
│   ├── phase-1/
│   │   ├── crypto.ipynb
│   │   └── dropout.ipynb
│   └── phase-2/
│       ├── crypto.ipynb
│       └── dropout.ipynb
├── src/
│   ├── crypto/
│   │   ├── cleaning.py
│   │   ├── features.py
│   │   └── models.py
│   ├── dropout/
│   │   ├── cleaning.py
│   │   ├── features.py
│   │   └── models.py
│   └── utils.py
├── requirements.txt
├── README.md
└── .gitignore
```
