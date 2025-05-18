
# B5W0: Solar Data Discovery

This repository contains analysis of solar farm data from **Benin**, **Sierra Leone**, and **Togo**. It is part of the **solar-challenge-week1** project.

---

## 🔧 Setup Instructions

Follow these steps to set up the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/emegua19/solar-challenge-week1.git
cd solar-challenge-week1
```

### 2. Create a Virtual Environment

```bash
python -m venv .venv
```

### 3. Activate the Virtual Environment

* **Windows (PowerShell):**

  ```powershell
  .venv\Scripts\Activate.ps1
  ```

* **Windows (CMD):**

  ```cmd
  .venv\Scripts\activate.bat
  ```

* **macOS/Linux:**

  ```bash
  source .venv/bin/activate
  ```

### 4. Install Dependencies

```bash
pip install -r requirements.txt
```

---

## You're All Set!

Once the setup is complete, you can begin working with the project.

To commit your setup progress:

```bash
git add README.md
git commit -m "docs: add README with setup instructions"
```

---

##  Project Structure

```
solar-challenge-week1/
├── .vscode/
│   └── settings.json            # VS Code Python interpreter config
├── .github/
│   └── workflows/
│       └── ci.yml               # GitHub Actions workflow
├── .gitignore                   # Ignore virtual environment, data, etc.
├── requirements.txt             # Python dependencies
├── README.md                    # Project documentation
├── src/                         # Source code
├── notebooks/
│   ├── __init__.py
│   └── README.md
├── scripts/
│   ├── __init__.py
│   └── README.md
└── tests/
    └── __init__.py
```
