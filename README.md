## AI Engineer Starter Kit

A simple AI pipeline project connecting an external REST API with Hugging Face Transformers.

## 📌 Project Overview
This project fetches external data via an API call and passes it through a Hugging Face `sentiment-analysis` pipeline to perform AI inference on the retrieved text.

## 🚀 How to Run

1.**Clone the repository:**
   ```bash
   git clone https://github.com/zeinababdo546/starter_kit.git
   cd starter_kit

```

2.**Set up and activate virtual environment:**
```bash
# Create environment
python -m venv ai-env

# Activate (Windows Git Bash)
source ai-env/Scripts/activate

```

3.**Install dependencies:**
```bash
pip install -r requirements.txt
pip install torch --index-url https://download.pytorch.org/whl/cpu

```

4.**Run the Notebook:**
Open `notebook.ipynb` in VS Code, select your active kernel environment (`ai-env`), and execute all cells.

```

