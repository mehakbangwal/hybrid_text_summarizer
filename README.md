# 📘 Hybrid Text Summarizer

This project is a **Hybrid Text Summarization Web App** built using **Gradio**, **Hugging Face Transformers**, **NLTK**, and **PyMuPDF**. It supports both **Extractive** and **Abstractive** summarization techniques for uploaded `.pdf` or `.txt` files, and optionally evaluates the summaries using **ROUGE metrics**.

---

## 🚀 Features

- 🔍 **Extractive Summarization** using TextRank (from `sumy`)
- ✨ **Abstractive Summarization** using a T5 transformer model (`t5-small`)
- 📂 Supports **PDF** and **TXT** file uploads
- 📊 **ROUGE Evaluation** of both summaries (Precision, Recall, F1-Score)
- 🧠 Sentence count customization for extractive summaries
- 🖥️ Clean, interactive **Gradio UI**
  
---

## 📦 Tech Stack

- `Python`
- `Gradio`
- `Hugging Face Transformers`
- `NLTK`, `sumy`, `PyMuPDF`, `BeautifulSoup`
- `ROUGE Scorer` from `rouge-score`

---

## 📁 How to Use

### ✅ Option 1: Run in Google Colab
1. Clone or upload this code in Google Colab.
2. Run all cells to launch the Gradio interface.
3. Upload a `.pdf` or `.txt` file.
4. Click **Summarize Now** to view the extractive and abstractive summaries.
5. Optionally, view **ROUGE evaluation scores**.

### ✅ Option 2: Run Locally

```bash
pip install gradio transformers sumy nltk rouge-score PyMuPDF beautifulsoup4
python app.py  # or the filename of your script
