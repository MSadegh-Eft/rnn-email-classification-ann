# RNN Email Classification

Persian email text classification with RNN, LSTM, BiLSTM, and CNN-LSTM models,
using Hazm for preprocessing.

Built for an Artificial Neural Networks course assignment.

## What this project covers

- Persian text normalization, tokenization, and vocabulary building
- Simple RNN, LSTM, and bidirectional LSTM classifiers
- Hyperparameter sensitivity analysis (sequence length, embedding size, etc.)
- Hybrid CNN-LSTM architecture and prediction error analysis

## Project layout

| File | Description |
|------|-------------|
| `main.ipynb` | Preprocessing, models, and experiments |
| `data/README.md` | Dataset setup instructions |
| `Project_Description.pdf` | Assignment brief |
| `Report.pdf` | Report |
| `requirements.txt` | Python dependencies |

## Quick start

```bash
python -m venv .venv
.venv\Scripts\activate          # macOS/Linux: source .venv/bin/activate
pip install -r requirements.txt
jupyter notebook main.ipynb
```

Place `data/emails.csv` (columns: `text`, `label`) before re-running training cells. Notebook outputs are saved so results render on GitHub.
