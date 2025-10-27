# 🤖 RaghavGPT — Your Context-Aware AI Assistant

RaghavGPT is a **context-aware GenAI chatbot** that learns from your own content  your GitHub READMEs, LinkedIn bio, notes, or documents  and answers questions *in your own voice*.  
Built using **RAG (Retrieval-Augmented Generation)**, **FAISS**, and **Streamlit**, it shows how personal AI assistants can truly understand context instead of guessing.

---

## 🧠 What It Does
- Reads and indexes your personal files (like `.txt` or `.md`)
- Creates embeddings and stores them locally using **FAISS**
- Lets you chat through an intuitive **Streamlit** interface
- Retrieves the most relevant context for every query and responds using **LLMs** (Gemini / OpenAI)
- Optionally deployable on **Streamlit Cloud** or **Hugging Face Spaces**

---

## ⚙️ Tech Stack
| Component | Tool |
|------------|------|
| Frontend | Streamlit |
| Backend | Python |
| LLM | OpenAI GPT or Gemini API |
| Embeddings | OpenAI Embeddings / Gemini Embeddings |
| Vector DB | FAISS |
| Env Management | python-dotenv |
| Text Handling | LangChain |

---

## 🚀 Setup & Run Locally

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/RaghavGPT.git
cd RaghavGPT


### 2. Install Dependencies
```bash
pip install -r requirements.txt 



### 3. Run the App
```bash
streamlit run app.py



