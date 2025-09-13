
# 📘 LLM Text Analyzer

A tool for **summarization, tokenization analysis, cost estimation, sentiment analysis, and writing style detection** using Large Language Models (LLMs).  
Built with **Gradio**, **Hugging Face Transformers**, and **Google Gemini API**.

---

## 🚀 Features
- 🔹 Text Summarization (Gemini & Mistral)
- 🔹 Tokenization & Token Usage Analysis (Hugging Face tokenizers)
- 🔹 Cost Estimation per model
- 🔹 Sentiment Analysis (positive, negative, neutral)
- 🔹 Writing Style Analysis (formal/informal, complexity)
- 🔹 Exportable Results (JSON/CSV planned)
- 🔹 Interactive Gradio UI

---

## 📂 Project Structure
```

Text\_Summarizer/
│── data/
│   ├── sample\_texts/       # Example texts for testing
│── utils/
│   ├── llm\_helpers.py      # Summarization, sentiment, style detection
│   ├── tokenizer\_helpers.py # Tokenization & cost estimation
│── main.py                 # Main Gradio app
│── requirements.txt        # Dependencies
│── README.md               # Project overview


## ⚡ Installation
Clone the repo and install dependencies:
```bash
git clone https://github.com/your-username/Text_Summarizer.git
cd Text_Summarizer
pip install -r requirements.txt
````

---

## ▶️ Usage

Run the Gradio app:

```bash
python main.py
```

This will open a local Gradio UI in your browser.


## 📊 Example Inputs

You can test with these:

* News Article (300-500 words)
* Academic Abstract (150-200 words)
* Social Media Post (50-100 words)
* Technical Documentation (400-600 words)
* Creative Writing (200-300 words)

See **docs/usage\_examples.md** for detailed examples.

---

## 📌 Requirements

* Python 3.9+
* Hugging Face `transformers`
* Gradio
* Torch
* google-generativeai

(Install automatically via `requirements.txt`)

---

## 🤝 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss your idea.

---

## 📜 License

This project is licensed under the MIT License.

```
