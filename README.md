## AI Engineer Starter Kit

###  Project Overview
This project fetches external text data via a REST API call and processes it through a Hugging Face `sentiment-analysis` pipeline to perform AI inference on the retrieved text.

###  How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/zeinababdo546/starter_kit.git
cd starter_kit
```

### 2. Set Up and Activate Environment

**Option A (Using Conda - Recommended):**

```bash
conda create -n ai-env python=3.10 -y
conda activate ai-env

```

**Option B (Using venv):**

* **Windows (PowerShell):**
```powershell
python -m venv ai-env
.\ai-env\Scripts\Activate.ps1

```


* **Git Bash / Linux / macOS:**
```bash
python -m venv ai-env
source ai-env/Scripts/activate

```



### 3. Install Dependencies

```bash
pip install -r requirements.txt

```

### 4. Run the Notebook

Open `notebook.ipynb` in VS Code or Jupyter Notebook, select the `ai-env` kernel, and run all cells.

