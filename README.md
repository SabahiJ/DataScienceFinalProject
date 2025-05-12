
---

## Technologies & Methods

- **Language model**: [FinBERT](https://huggingface.co/ProsusAI/finbert)
- **NLP pipeline**: Text cleaning, tokenisation, rule-based filtering
- **Sentiment labeling**: FinBERT classification (`positive`, `neutral`, `negative`)
- **Manual validation**: Manually labeled headlines for model evaluation
- **Market data**: Daily open/close prices from Nasdaq (YFinance and external sources)
- **Evaluation metrics**: Accuracy, precision, recall, F1-score, and market alignment
- **Visualisations**: 15+ charts including word clouds, bar plots, timelines, and correlation visuals

---

## Key Results

- **FinBERT classification accuracy**: 76.7% (vs. manual labels)
- **Market movement alignment**: 42.86% of days correctly predicted
- **Insight**: Sentiment provides directional signals but is insufficient alone for full market prediction
- **Tools used**: Python, Jupyter, Pandas, Matplotlib, Seaborn, HuggingFace Transformers

---

## How to Reproduce

1. Clone this repository  
2. Ensure you have Python ≥3.8  
3. Install dependencies:  
   ```bash
   pip install -r requirements.txt

