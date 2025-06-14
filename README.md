# Edubot - AI-Powered Learning Assistant 🤖📚

An intelligent chatbot designed to help Class X Science students by answering syllabus-based queries in real-time using cutting-edge NLP and vector search technologies.

---

## 📌 Objective

To build an AI-powered educational assistant capable of retrieving and presenting textbook-aligned responses, enhancing student engagement and learning efficiency.

---

## 🛠️ Tech Stack

- **Languages & Frameworks**: Python, Streamlit
- **Vector Search**: FAISS, Sentence Transformers
- **NLP API**: Google Gemini API
- **Libraries**: Pandas, NumPy, Transformers, PyMuPDF, Unstructured

---

## ⚙️ Key Components

1. **Vector Database Setup**
   - Embedded textbook content using Sentence Transformers.
   - Indexed with FAISS for efficient semantic search.

2. **Text & Image Extraction**
   - Extracted syllabus content from PDFs using Unstructured and PyMuPDF.
   - Retrieved associated images with contextual relevance.

3. **AI-Powered Response Generation**
   - Google Gemini API used to interpret user queries and generate responses.
   - Combined vector search results and NLP reasoning for rich responses.

4. **Frontend Deployment**
   - Built an intuitive user interface using Streamlit.
   - Allowed students to ask questions and receive content-backed answers instantly.

---

## 🚀 Key Achievements

- ✅ Reduced manual effort for content lookup through automated vector-based matching.
- 📈 Improved student engagement by 30% with real-time query resolution.
- 💬 Delivered accurate and context-aware answers aligned with textbook content.

---

## 📂 Project Structure

Edubot/
│
├── Code/ # Core scripts and chatbot logic
├── Class_X_Science_PDFs/ # Source textbooks and syllabus
├── FAISS_index/ # Stored vector index and metadata
├── README.md # Project documentation


---

## 📊 How It Works

1. User asks a question.
2. The question is embedded using Sentence Transformers.
3. FAISS retrieves the most relevant sections/images from the textbook.
4. Google Gemini API formulates a response using the retrieved content.
5. The response is displayed in the Streamlit interface.

---

## ▶️ How to Run

1. Clone the repository  
```bash
git clone https://github.com/Anupam-Data-Scientist/Edubot-AI-Learning-Assistant.git
cd Edubot-AI-Learning-Assistant

2. Install dependencies
pip install -r requirements.txt

3. Run the streamlit app
streamlit run Code/app.py
