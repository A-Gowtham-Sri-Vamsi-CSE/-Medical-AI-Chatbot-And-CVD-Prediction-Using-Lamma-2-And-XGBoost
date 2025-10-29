# -Medical-AI-Chatbot-And-CVD-Prediction-Using-Lamma-2-And-XGBoost
🩺 Medical AI Chatbot & Cardiovascular Disease Prediction

An intelligent Medical AI Assistant that combines Natural Language Processing (NLP) and Machine Learning to assist users in understanding medical concepts and predicting the risk of Cardiovascular Disease (CVD).

This project integrates an LLM-powered chatbot with a predictive analytics pipeline, offering an interactive interface for healthcare-related insights and disease risk assessment.

🚀 Key Features

🧠 Medical Chatbot – Built with LLaMA (via CTransformers) and orchestrated using LangChain, enabling natural and context-aware medical conversations.

💬 NLP Pipeline – Uses Sentence Transformers and FAISS for efficient semantic search and question-answering.

📄 Document Handling – Supports PDF and directory loading through PyPDFLoader and DirectoryLoader, allowing ingestion of medical literature or clinical notes.

⚙️ Disease Prediction – Employs an XGBoost model trained for Cardiovascular Disease (CVD) prediction.

💡 Embeddings – Powered by HuggingFace’s all-MiniLM-L6-v2 for high-quality text vectorization.

💻 User Interface – Interactive front end built with Chainlit for real-time chat and prediction results.

🐍 Tech Stack – Developed in Python, leveraging Pandas for data preprocessing and management.

🧩 Tech Stack Overview
Component	Technology
LLM	LLaMA (via CTransformers)
NLP Pipeline	LangChain + Sentence Transformers
Vector Store	FAISS
Embeddings	HuggingFace (all-MiniLM-L6-v2)
Document Loader	PyPDFLoader, DirectoryLoader
Prediction Model	XGBoost (CVD Prediction)
Interface	Chainlit
Backend Language	Python
Data Handling	Pandas
🏁 Future Enhancements

Integration with real-time patient data (EHR/IoT).

Improved explainability for model predictions.

Deployment via Docker or Streamlit Cloud.

Fine-tuning the LLM for medical domain adaptation.
