# Multimodal Sentiment & Outlier Analysis using BERT and CLIP

This repository contains the source code and methodology for a university research project focused on analyzing the sentiment of online news articles (Headlines + Images).

## 📌 Project Overview
The goal of this study is to identify discrepancies between textual sentiment and visual sentiment (outliers), specifically detecting "Neutral" text articles paired with "Offensive" or "Violent" images.

### Key Features:
- **Text Sentiment Analysis:** Implemented using **BERT** (Positive, Negative, Neutral).
- **Image Sentiment Analysis:** Implemented using **OpenAI's CLIP**.
- **Intercoder Agreement:** Validated with **Cohen’s Kappa (0.43)** and **Krippendorff’s Alpha (0.32)**.

## 🛠️ Technical Stack
- **Environment:** Google Colab (Python 3)
- **Models:** BERT, CLIP
- **Libraries:** Transformers, PyTorch, Pandas, Seaborn.

## 📁 Repository Structure
- `analysis_notebook.ipynb`: Complete Jupyter Notebook with code and visualizations.
- `cleaned_dataset.xlsx`: Processed data with sentiment scores and outlier tags.

---
*Developed as part of a University Thesis. For inquiries regarding the methodology, please contact the repository owner.*
