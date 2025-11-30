# 👋 Welcome to my Repo!

## 🌟 About Me

### I'm love building projects integrating AI that people can use in their everyday lives, with a Master's in Information Systems (Data Science) and a background in Computer Science, I enjoy working at the intersection of software engineering and machine learning.

I have worked on things like an AI summarization agent for form reviews, a natural language “data analyst” that answers questions on top of CSV data, a multimodal chatbot that runs locally, and a content moderation system that understands algo-speak. I like taking messy data or workflows and turning them into simple products.

I am especially interested in LLM applications, RAG pipelines, agent-style workflows, and local/offline AI. Most days you will find me coding, reading AI papers, trying new open source models, or writing and sharing what I learn.

---

## 🔧 Technologies & Tools I Work With

### 🧠 AI & Machine Learning

![LangChain](https://img.shields.io/badge/LangChain-000000?style=for-the-badge)
![LangGraph](https://img.shields.io/badge/LangGraph-111827?style=for-the-badge)
![OpenAI%20API](https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-0F766E?style=for-the-badge)
![ChromaDB](https://img.shields.io/badge/ChromaDB-22C55E?style=for-the-badge)
![FAISS](https://img.shields.io/badge/FAISS-0F172A?style=for-the-badge)
![Qdrant](https://img.shields.io/badge/Qdrant-4F46E5?style=for-the-badge)
![Hugging%20Face](https://img.shields.io/badge/Hugging_Face-FFD21F?style=for-the-badge&logo=huggingface&logoColor=000000)
![Llama%203.2](https://img.shields.io/badge/Llama_3.2-9333EA?style=for-the-badge)
![Qwen2.5](https://img.shields.io/badge/Qwen2.5-0369A1?style=for-the-badge)
![QLoRA](https://img.shields.io/badge/QLoRA-7C3AED?style=for-the-badge)

---

### 📊 Data Science

![scikit-learn](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-FF6600?style=for-the-badge)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![Polars](https://img.shields.io/badge/Polars-000000?style=for-the-badge)
![Prophet](https://img.shields.io/badge/Prophet-0F766E?style=for-the-badge)
![Neo4j](https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white)

---

### 💻 Languages

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=FFD43B)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=000000)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![HTML](https://img.shields.io/badge/HTML-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS%20%2F%20Tailwind](https://img.shields.io/badge/CSS_/_Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)

---

### ☁️ Web & Cloud

![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![AWS%20Bedrock](https://img.shields.io/badge/AWS_Bedrock-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=for-the-badge&logo=postgresql&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI_CD-111827?style=for-the-badge&logo=githubactions&logoColor=white)




## Featured Projects

### KnowFlow
**Tech:** FastAPI, Playwright, Ollama, Llama 3.2 (4-bit), ChromaDB, HuggingFace, GCP TTS  
- Built a multimodal AI chatbot using quantized Llama 3.2 for fully local inference.  
- Implemented a RAG pipeline with ChromaDB to support document question answering across six file formats.  
- Added support for text, image, and voice interactions so users can work with content in different ways.  
- Repo: https://github.com/zeroinfinity03/knowflow-beta1.0.git  

---

### Algospeak-Aware Content Moderation
**Tech:** FastAPI, Qwen2.5-3B, QLoRA, Polars, Next.js  
- Designed a two stage moderation system: JSON algospeak normalizer plus a QLoRA tuned Qwen2.5-3B classifier.  
- Fine tuned on a 52k sample built from the Jigsaw toxicity dataset.  
- Built a hot reload JSON normalizer that covers 100+ algospeak variants like character swaps, phonetics, and euphemisms.  
- Repo: https://github.com/zeroinfinity03/Algospeak-Aware-Content-Moderation  

---

### SQLite3 MCP Server
**Tech:** FastAPI, FastMCP, MCP SDK, Gemini 2.0 Flash, SQLite3, Python  
- Built a local Model Context Protocol (MCP) server exposing eight read only database tools for LLMs.  
- Let LLMs inspect schemas and run safe SQL queries over SQLite3 databases.  
- Integrated Gemini 2.0 Flash through the MCP Python SDK to enable natural language database exploration.  
- Repo: https://github.com/zeroinfinity03/sqlite3-mcpserver  

---

### Breast Cancer Classification
**Tech:** Python, TensorFlow, Keras, Scikit learn, Matplotlib  
- Trained a deep learning model on the Wisconsin Breast Cancer dataset and reached 93.86 percent accuracy.  
- Used StandardScaler and correlation analysis to clean features and reduce false negatives.  
- Visualized training curves and model behavior using Matplotlib for better debugging.  
- Repo: https://github.com/zeroinfinity03/Breastcancer  

---

### Credit Card Fraud Detection
**Tech:** Python, Scikit learn, XGBoost, CatBoost, SMOTE  
- Built ensemble models on 284k plus transactions to detect rare fraudulent activity.  
- Handled strong class imbalance (about 0.17 percent fraud) with SMOTE oversampling.  
- Tuned thresholds to focus on recall and reduce missed fraud cases while keeping stable ROC AUC.  
- Repo: https://github.com/zeroinfinity03/credit-card-fault_detection  

---

### Customer Churn Prediction
**Tech:** Python, Scikit learn, Random Forest, Pandas  
- Trained a churn classifier that outperformed logistic regression baselines and reached 86 percent accuracy.  
- Engineered features like collect to redeem ratio to capture customer engagement.  
- Used feature importance to give the business clear signals on which behaviors drive churn.  
- Repo: https://github.com/zeroinfinity03/customer_churn_prediction  

---

### Movies Recommendation System
**Tech:** Python, Streamlit, TMDB API, Scikit learn, NLP  
- Built a content based movie recommender using TF IDF vectors and cosine similarity.  
- Combined overview, genres, keywords, cast, and crew into a single text feature space.  
- Deployed as a Streamlit app with TMDB API for live posters and used Pickle for fast model loading.  
- Repo: https://github.com/zeroinfinity03/MoviesRecommendation  

---

## Certifications

- Machine Learning Specialization – Stanford  
  https://coursera.org/verify/specialization/437QUM0RYAZB  

- Mathematics for ML and Data Science – DeepLearning.AI  
  https://coursera.org/verify/specialization/6EDLBA40SFZ1  

- IBM Data Science Professional Certificate  
  https://coursera.org/verify/professional-cert/UE1MUECTEX07  

- Google Advanced Data Analytics Certificate  
  https://coursera.org/verify/professional-cert/H4RSHKEWG8XT  
---

## 🏆 Achievements

![GitHub Trophies](https://github-profile-trophy.vercel.app/?username=zeroinfinity03\&theme=radical\&no-frame=true)

---

## 📩 Connect with Me

* **LinkedIn**: [Surya Singh](https://www.linkedin.com/in/surya-singh-412564233/)
* **Email**: [vik03surya@gmail.com](mailto:vik03surya@gmail.com)
* **GitHub**: [ZeroInfinity](https://github.com/zeroinfinity03)






