# 👋 Hi, I'm Stella

Welcome to my space on GitHub.

I'm a passionate AI student from Northern Italy, currently enrolled at the Mathematik Fakultät at Humboldt Universität zu Berlin for the full 2025/2026 academic year (fully taught in German). I am a student enrolled in the Artificial Intelligence course at University of Pavia.

I’m seeking **internship / Werkstudent opportunities in Berlin** to contribute to real-world products while I study.

## Current Projects

- **[Multi-Input Multi-Output Neural Network](https://github.com/ialwayslikedgrime/deep_learning_exam_implementation)** – Designed and implemented a **multi-modal sentiment analysis system** for hotel reviews.  
  - Combined **NLP (LSTM branch)** with **structured metadata (categorical branch)** using the Keras Functional API.  
  - Tackled **multi-task learning**: simultaneous **classification (positive/negative)** and **regression (review score prediction)**.  
  - Built a **full preprocessing pipeline** (text cleaning, tokenization, categorical encoding, temporal/geographic features).  
  - Explored **hyperparameter optimization** (random search over learning rates, dropout, architecture size) and achieved robust performance across tasks.  
  - Repo includes clear documentation of design choices, architecture visualization, and notebook implementation.

- **[Airbnb Price Prediction](https://github.com/ialwayslikedgrime/airbnb-milan-price-prediction)** – End-to-end machine learning pipeline using real-world Airbnb data (23K+ listings across 88 neighborhoods) with comprehensive data cleaning, feature engineering on classic tabular features and geospatial engineering with GeoPandas (neighborhood encoding, spatial joins), EDA, and model selection, optimization and validation. Interpretability through **SHAP** to surface business drivers (location, property type, amenities). Test performance XGBoost: **R² = 0.587**. Used **software engineering principles applied to data science** through modular code and clear folder organization (inspired by [cookiecutter data science](https://github.com/drivendataorg/cookiecutter-data-science)). **Libraries:** pandas • NumPy • scikit-learn • XGBoost • GeoPandas • Shapely • matplotlib • SHAP


- **[Particle Swarm Optimization](https://github.com/ialwayslikedgrime/Particle_Swarm_Optimization)**
Particle Swarm Optimization (PSO) – From-scratch implementation of a swarm intelligence algorithm, part of the broader family of evolutionary and genetic-inspired optimization techniques. Vectorized with NumPy and engineered with OOP principles. 


- **[Whisper Transcription App](https://github.com/ialwayslikedgrime/transcription-app-prototype)** – A Next.js web application that integrates Hugging Face Transformers with OpenAI Whisper for local AI transcription.

  - Built to streamline my study workflow by wrapping Python AI scripts in a user-friendly web interface.
  - Handles **YouTube URLs, audio file uploads, and live microphone recording** with real-time progress tracking.
  - **Technical stack**: Next.js, TypeScript, React, Tailwind CSS, Node.js, Python, Hugging Face Transformers, PyTorch for local Whisper inference, yt-dlp for YouTube processing, FFmpeg for audio handling.  
  - Currently learning **full-stack deployment**: scaling from local execution to cloud architecture with user authentication (Clerk), database integration (PostgreSQL), and payment processing through Stripe API.




### 🔒 Current Projects I am working on (private)

These repos are private while I finalize them.

- **NLP — Aspect-Based Sentiment Analysis (ABSA)**
  - **Classical pipeline:** tokenization, stemming, TF-IDF, bag-of-words.
  - **Modern pipeline:** fine-tuning **BERT**; exploring (a) **sequence labeling** for term extraction (BIO/BIOES) with sentiment and (b) **question-answering–style** formulations; experimenting with custom multi-task heads.
  - **Data I am using:** **SemEval 2014 Restaurants** → transfer learning to **Amazon Reviews** (with the goal of generalizing to other review domains and building useful review-analytics components).

- **AI Agents**
  - Prototyping agents both with **LangChain** and from-scratch Python implementations.