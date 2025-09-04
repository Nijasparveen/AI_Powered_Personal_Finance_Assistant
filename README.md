# 💰 AI-Powered Personal Finance Assistant

An **AI-powered tool** that analyzes your **UPI/Bank statements** and provides financial insights such as **income, expenses, savings, unnecessary spending, and recommendations**.  
Built using **Streamlit**, **Google Gemini API**, and deployed on **Hugging Face Spaces**.  

👉 **Live Demo on Hugging Face Spaces:**  
[Click here to try the app](https://huggingface.co/spaces/Nijasparveen/AI_Personal_Finance_Assistant)

---

## ✨ Features
- 📂 Upload **PDF statements** (Bank / GPay / Paytm / PhonePe).  
- 🔍 Automatically extracts transaction details.  
- 📊 Provides:
  - Monthly **Income & Expense summary**  
  - **Savings percentage** calculation  
  - **Spending trend analysis**  
  - **Unnecessary expense detection**  
  - **Personalized cost control recommendations**  
- 🎨 Simple and interactive **Streamlit UI**.  

---

## 🛠️ Tech Stack
- **Python 3.10+**  
- **Streamlit** – for UI  
- **Google Gemini API** – for LLM financial analysis  
- **PyPDF2** – for text extraction from PDFs  
- **Hugging Face Spaces** – for deployment  
- **Langflow (Optional)** – for LLM workflow orchestration  

---

## 📂 Installation (Run Locally)

1. Clone the repository:
```bash
git clone https://github.com/your-username/finance-assistant.git
cd finance-assistant
Install dependencies:

2. Install dependencies:
Copy code
pip install -r requirements.txt
Add your Gemini API key in the code:

3. Add your Gemini API key in the code:
Copy code
GEMINI_API_KEY = "your_api_key_here"
Run the app:

4. Run the app:
Copy code
streamlit run app.py

📌 How to Use
Upload your bank or UPI statement in PDF format.

Wait for the AI model to extract and analyze your data.

Get a detailed financial insights report with recommendations.


📊 Project Flow

This project also supports Langflow integration for LLM orchestration.
You can design a flow with:

File Loader → Parser → Prompt → Gemini/Cohere → Python REPL → Chat Output.

👩‍💻 Author: Nijas Parveen Sulaimankhan
