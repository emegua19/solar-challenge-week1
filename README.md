# Solar Challenge Week 1

##  Setup Instructions


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



