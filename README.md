# 👋 Hi, I'm Vageesh Goswami

<p align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00D9FF&center=true&vCenter=true&width=600&lines=AI+Developer+%7C+ML+Engineer;Building+Intelligent+Systems;Transforming+Ideas+into+AI+Solutions" alt="Typing SVG" />
</p>

---

## 🚀 About Me

🎓 **AI/ML Enthusiast** passionate about building intelligent systems that make a real-world impact, currently learning agentic AI and trying to gain expertise in autonomous AI systems  
💼 **AI Research Intern @ Vivid AI** – Working on identity-preserving generative models and AI agents  
🤖 **Core Developer @ Xananoids Robotics Club (JECRC)** – Integrating AI with robotics  
🏆 **Hackathon Participant** – Smart India Hackathon and multiple national AI competitions  
🌱 Currently diving deeper into **Agentic AI, LLMs, RAG systems, and fine-tuning techniques**  
⚡ Fun fact: I bridge ancient wisdom with modern AI!

---

## 🛠️ Tech Stack

### Languages
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

### AI/ML & Data Science
![Agentic AI](https://img.shields.io/badge/Agentic_AI-FF6B6B?style=for-the-badge&logo=robot&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-121212?style=for-the-badge&logo=chainlink&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![Scikit Learn](https://img.shields.io/badge/Scikit_Learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white)

### Vector Databases & Tools
![FAISS](https://img.shields.io/badge/FAISS-0467DF?style=for-the-badge&logo=meta&logoColor=white)
![Pinecone](https://img.shields.io/badge/Pinecone-000000?style=for-the-badge&logo=pinecone&logoColor=white)
![ChromaDB](https://img.shields.io/badge/ChromaDB-FF6584?style=for-the-badge)

### Development & Deployment
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white)

---

## 🚀 Featured Projects

### 🤖 [AI Customer Support Agent](https://github.com/vageeshgos/AI-CUSTOMER-SUPPORT-AGENT)
**Intelligent AI agent for automated customer support with RAG-based knowledge retrieval**
- Multi-turn conversational agent with context awareness
- RAG implementation using LangChain and vector databases
- Smart knowledge base integration for quick resolutions
- AI-powered response suggestions for support agents
- **Tech Stack:** Python, NLP, Machine Learning, Streamlit

### ❤️ [Heart Disease Prediction](https://github.com/vageeshgos/Heart-Disease-Prediction)
**ML-powered cardiovascular disease risk assessment system**
- Predictive model using ensemble learning techniques
- Comprehensive feature engineering from clinical parameters
- Achieves high accuracy in early disease detection
- **Tech Stack:** Scikit-learn, Pandas, NumPy, Matplotlib, Python

### 🏠 [House Price Prediction](https://github.com/vageeshgos/house-price-predicton-by-linear-regration)
**Real estate price prediction using advanced regression techniques**
- Linear regression model with feature selection and engineering
- Handles multiple property attributes for accurate valuation
- Data preprocessing pipeline for robust predictions
- **Tech Stack:** Scikit-learn, Pandas, NumPy, Matplotlib, Python

### 📱 [Resume Builder](https://github.com/vageeshgos/RESUME-BUILDER)
**Interactive web application for creating professional resumes**
- User-friendly interface for resume creation and customization
- Multiple templates and export options
- Real-time preview and editing capabilities
- **Tech Stack:** Web Technologies, JavaScript, HTML/CSS

---

## 📝 Research & Learning Notes

> *Documenting my journey through AI research and hands-on experimentation*

### 🔍 **Types of RAG (Retrieval-Augmented Generation)**

**📌 Naive RAG**  
The simplest form - retrieve relevant documents, concatenate, and feed to LLM. Great for getting started but limited by context window and relevance.

**📌 Advanced RAG**  
Enhances retrieval with:
- **Pre-retrieval optimization:** Query rewriting, HyDE (Hypothetical Document Embeddings)
- **Better chunking strategies:** Semantic chunking, sliding windows with overlap
- **Hybrid search:** Combining dense (embeddings) + sparse (keyword) retrieval

**📌 Modular RAG**  
Breaks down the pipeline into customizable modules:
- Routing layer to select appropriate knowledge sources
- Reranking retrieved documents for better relevance
- Iterative retrieval for complex queries
- Self-reflection mechanisms for answer validation

**📌 Agentic RAG**  
LLM acts as an agent that *decides* when and what to retrieve:
- Query planning and decomposition
- Tool use for multiple knowledge sources
- Self-correction based on retrieved context

---

### 🧠 **How LLMs Work: From Tokens to Intelligence**

**1️⃣ Tokenization**  
Text is broken into tokens (subwords). "ChatGPT" might become ["Chat", "G", "PT"]. Each token gets a unique ID from the model's vocabulary.

**2️⃣ Embeddings**  
Token IDs are converted into high-dimensional vectors (e.g., 768 or 1024 dimensions) that capture semantic meaning.

**3️⃣ Transformer Architecture**  
The magic happens through:
- **Self-Attention:** Each token "looks at" all other tokens to understand context
- **Multi-Head Attention:** Multiple attention mechanisms running in parallel
- **Feed-Forward Networks:** Process the attention outputs
- **Layer Normalization & Residual Connections:** Stabilize training

**4️⃣ Next Token Prediction**  
The model outputs probabilities for every possible next token. Temperature controls randomness:
- Low temperature (0.1-0.3): Deterministic, focused
- High temperature (0.8-1.0): Creative, diverse

**5️⃣ Training**  
- **Pre-training:** Learn language patterns from massive text corpora
- **Fine-tuning:** Adapt to specific tasks (instruction following, conversation)
- **RLHF:** Reinforcement Learning from Human Feedback for alignment

---

### ⚙️ **RAG Working Process: Step-by-Step**

```
📥 USER QUERY
    |
    v
🔄 Query Preprocessing
   - Query understanding & expansion
   - Keyword extraction
   - Intent classification
    |
    v
🔍 Retrieval Phase
   1. Convert query to embedding (same model as documents)
   2. Vector similarity search in database (FAISS/Pinecone/Chroma)
   3. Fetch top-k most relevant chunks (typically k=3-10)
    |
    v
📊 Optional: Reranking
   - Use cross-encoder to rerank results
   - Filter out low-relevance chunks
   - Diversify results
    |
    v
🧩 Context Construction
   - Format retrieved chunks
   - Add metadata (source, timestamp)
   - Truncate if exceeding context window
    |
    v
🤖 LLM Generation
   - Construct prompt: [System] + [Context] + [Query]
   - LLM generates response grounded in retrieved context
   - Citation extraction (optional)
    |
    v
✅ Post-Processing
   - Hallucination detection
   - Source attribution
   - Response formatting
    |
    v
📤 FINAL ANSWER
```

**🎯 Key Advantages:**
- ✅ Up-to-date information without retraining
- ✅ Reduces hallucinations with grounded context
- ✅ Explainable with source citations
- ✅ Domain-specific knowledge integration

**⚠️ Challenges:**
- 🔸 Retrieval quality is critical
- 🔸 Context window limitations
- 🔸 Latency from retrieval step
- 🔸 Chunking strategy impacts performance

---

## 🏆 Achievements

🥇 Top 10 Finalist of JECRC Smart India Hackathon 2024  
🏅 Participated in multiple college-level hackathons

---

## 📫 Let's Connect!

<p align="center">
  <a href="https://linkedin.com/in/vageesh-goswami" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
  </a>
  <a href="mailto:vageeshgoswami@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
  </a>
  <a href="https://github.com/vageeshgos" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
  </a>
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=vageeshgos&color=00D9FF&style=flat-square&label=Profile+Views" alt="Profile Views" />
</p>

---

<p align="center">
  <i>"The only way to do great work is to love what you do."</i><br/>
  – Steve Jobs
</p>
