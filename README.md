# 📄 Groq-Powered Document Chatbot 🤖

An interactive chatbot built with Groq + LLaMA3 that deeply understands a 100+ page document and answers questions with context, tone, personality, and visuals — all inside a Google Colab notebook.

---

 🎯 Objective

Create a high-performance chatbot that:
- Understands large documents
- Supports conversation, tone, persona
- Includes summarization and explain-like-I’m-5 mode
- Adds relevant page visuals

---

 📚 Document Used
- Title: **India - A Comprehensive Geography** its about geography of india
- Format: PDF (100+ pages)
- Uploaded in Colab as: `ind_geo.pdf`

---

#💡 Features

| Feature                    | Status |
|---------------------------|--------|
| ✅ Free-form Q&A          | Yes    |
| ✅ Summarization          | Yes    |
| ✅ Explain like I'm 5     | Yes    |
| ✅ Multi-turn memory      | Yes    |
| ✅ Persona & Tone switch  | Yes    |
| ✅ Visual grounding       | Yes (images from PDF pages) |
| ✅ Confidence Score       | Yes (Token based logic)     |

---

⚙️ Stack

- 🧠 Groq (LLaMA3-70B-8192)
- 🧱 LangChain (ConversationalRetrievalChain)
- 📄 PDF Reader: PyPDF2
- 🧩 Embeddings: HuggingFace
- 🔍 Vector Store: ChromaDB
- 📸 Visuals: pdf2image + poppler
- 🧠 Memory: ConversationBufferMemory
- 🧰 UI: ipywidgets (Colab)

---

 🖼 Screenshot

| UI Preview | |
|------------|--|
| ![Chat](images/page_1.png) | Sample Visual Page |

---

 🧠 Evaluation Metrics

| Metric              | Description |
|---------------------|-------------|
| ✅ Confidence Score | Based on token length |
| ✅ Source Preview   | Chunks shown with source |
| ✅ Visual Match     | Page images based on metadata |
| ✅ Prompt strategy  | Persona, tone, style toggles |

---

 🔗 Colab Notebook  https://colab.research.google.com/drive/11ps9Z-E5dW5ELwE053Y6rLuNUede5nx_?usp=sharing



---

## 📝 How to Run
1. Upload your `ind_geo.pdf` in Colab
2. Run all cells (takes ~2-3 mins)
3. Ask questions in the widget interface
4. Optionally add your own PDF to try

 

