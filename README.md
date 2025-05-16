
# Solar Challenge Week 1

## Objective

Get comfortable with version control and set up a consistent Python development environment with CI before working with data.

---

## Setup Instructions (Windows – Git Bash)

### 1. Clone the Repository

```bash
git clone https://github.com/YOUR_USERNAME/solar-challenge-week1.git
cd solar-challenge-week1

# Create virtual environment
python -m venv .venv

# Activate in Git Bash (Windows)
source .venv/Scripts/activate

pip install -r requirements.txt

pip freeze > requirements.txt

# Create and switch to setup branch
git checkout -b setup-task

# Stage and commit important setup files
git add .gitignore
git commit -m "init: add .gitignore"

git add requirements.txt
git commit -m "chore: venv setup"

git add .github/workflows/ci.yml
git commit -m "ci: add GitHub Actions workflow"

# Push to GitHub
git push origin setup-task


name: Python CI

on: [push, pull_request]

jobs:
  build:
    runs-on: ubuntu-latest

    steps:
      - name: Checkout code
        uses: actions/checkout@v3

      - name: Set up Python
        uses: actions/setup-python@v4
        with:
          python-version: '3.10'

      - name: Install dependencies
        run: pip install -r requirements.txt

      - name: Verify Python version
        run: python --version

solar-challenge-week1/
├── .vscode/
│   └── settings.json               # VS Code Python interpreter config
├── .github/
│   └── workflows/
│       └── ci.yml                  # GitHub Actions workflow
├── .gitignore                      # Ignore env, data, etc.
├── requirements.txt               # Python packages
├── README.md                      # Project guide
├── src/                           # Source code
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── scripts/
│   ├── __init__.py
│   └── README.md
└── tests/
    └── __init__.py
# Python
__pycache__/
*.py[cod]
*.egg-info/

# Virtual Environments
.venv/
myvenv/

# Jupyter
.ipynb_checkpoints/

# Data
data/
*.csv
=======
# Solar Challenge Week 1

## How to set up the environment

1. Clone the repository:
```bash
#git clone https://github.com/your-username/solar-challenge-week1.git
#cd solar-challenge-week1

1 Create and activate virtual environment:
#python -m venv venv
#source venv/Scripts/activate  # Windows

3.Install dependencies:
#pip install -r requirements.txt


4 You're good to go!


Then:
```bash
#git add README.md
#git commit -m "docs: add README with setup instructions"



