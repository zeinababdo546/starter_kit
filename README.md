## AI_Engineer_Starter_Kit

### 📌 Project Overview
This project fetches external data via an API call and passes it through a Hugging Face `sentiment-analysis` pipeline to perform AI inference on the retrieved text.

---

### 🚀 How to Run

**1.** **Clone the repository:**
```bash
git clone [https://github.com/zeinababdo546/starter_kit.git](https://github.com/zeinababdo546/starter_kit.git)
cd starter_kit

```

**2.** **Set up and activate environment:**

* **Option A (Using Conda - Recommended):**

```bash
conda create -n ai-env python=3.10 -y
conda activate ai-env

```

* **Option B (Using venv):**

```bash
python -m venv ai-env
# Windows (PowerShell):
.\ai-env\Scripts\Activate.ps1
# Git Bash / Linux / macOS:
source ai-env/Scripts/activate

```

3. **Install dependencies:**

```bash
pip install -r requirements.txt

```

4. **Run the Notebook:**
Open `notebook.ipynb` in VS Code or Jupyter Notebook, select the `ai-env` kernel, and run all cells.

