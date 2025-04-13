# 🧠 AI Text Summarizer (Groq-Powered)

A powerful, lightweight AI summarization app that allows you to instantly summarize text, PDF, and DOCX documents using Groq’s blazing-fast inference engine with the **LLaMA 3.3 70B** model. Built with Python and Streamlit.

## 🚀 Features

- 📂 Upload **PDF** or **DOCX** files for instant summarization
- 📝 Paste or type text directly for summarization
- ⚡ Uses **Groq AI** for ultra-fast and accurate results
- 🎯 Generates a clear, neutral, single-sentence summary
- 💾 Download the summary as a `.txt` file
- 🎨 Minimal and clean UI with custom styling

## 🌐 Streamlit Interface

![image](https://github.com/user-attachments/assets/1bfba163-8b9c-4167-917e-0e38c2e55287)
  


## 🛠 Tech Stack

- **Frontend & UI:** Streamlit
- **AI Inference:** Groq API using LLaMA 3.3-70B Versatile
- **PDF Parsing:** PyPDF2
- **DOCX Parsing:** python-docx
- **Environment Management:** python-dotenv
- **HTTP Requests:** requests

## 📥 Installation

1. **Clone the repository**

```bash
git clone https://github.com/1sahmuel/ai-text-summarizer.git
cd ai-text-summarizer
```
2. **Set up a virtual environment**

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
3. **Install the dependencies**
``` bash
pip install -r requirements.txt
```
4.  **Create a `.env` file in the project root**
```bash
GROQ_API_KEY=your_groq_api_key_here
```

## **▶️ Usage**
Run streamlit app
```bash
streamlit run groq_model.py
```

## **📂 Project Structure**

```bash
ai-text-summarizer/
│
├── groq_model.py       # Main Streamlit app for groq model
├──  Ollama model.py    # Main Streamlit app for ollama model  
├── .env                # Contains the Groq API key (not tracked by Git)
├── requirements.txt    # Python dependencies
└── README.md           # Project documentation
```
##  🔮 Future Improvements

📑 Support for summarizing HTML or web URLs

🎙️ Integration with speech-to-text summarization

🧠 Add multiple summarization modes (bullet points, TL;DR, etc.)

🌐 Multilingual support


