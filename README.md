# Hi, I'm Zijie Ren

I am an MSc Data Science graduate based in the UK, with experience in machine learning, clinical data processing, applied LLM/RAG workflows, and robotics simulation experiments.

My current portfolio spans three areas:

- **Robotics and learning in simulation** — human demonstration retargeting, MuJoCo manipulation, PPO experiments, and action-conditioned state prediction
- **Clinical and healthcare data science** — privacy-preserving data pipelines, gait analysis, time-series processing, and interpretable feature engineering
- **Applied AI and LLM systems** — retrieval-augmented generation, document-grounded question answering, FastAPI backends, and Streamlit interfaces

## Featured Portfolio

For a structured overview of my selected projects, please visit:

[Zijie Ren - Data Science & AI Portfolio](https://github.com/RogerRen0824/zijie-ren-portfolio)

## Selected Projects

### Human Demonstrations to Robot Pushing

20 personally recorded phone videos inform a simulated robot's pushing directions. The project combines approximate trajectory calibration, a fixed contact controller, PPO residual learning, and small state world models.

- Goal-weighted guidance and PPO each achieved 5/5 successes on reserved single-obstacle layouts; PPO did not meaningfully improve the guide
- Linear state prediction achieved 18.4 mm RMSE over five recursively predicted macro-actions
- Random 0–2 obstacle scenes and a curriculum PPO pilot are included as ongoing experiments; reliable learned multi-obstacle avoidance is not yet achieved
- Prepared data, checkpoints, frozen protocols and failures are documented

Uses simulator-state observations and simplified geometry; visual obstacle recognition and whole-arm safety are not established. AI tools assisted implementation and experiment execution; I collected the recordings.

Repository: [Robotic_arm_sim](https://github.com/RogerRen0824/Robotic_arm_sim)

### Clinical Gait Data Pipeline

A local-only Python package for privacy-preserving clinical gait data ETL and biomechanical feature engineering.

- Modular Python package structure
- Local processing of sensitive clinical gait data
- Walking-zone segmentation
- Biomechanical feature extraction including speed, cadence, stride length, and range of motion
- Clear separation between data processing and modelling workflows

Repository: [Gait_Data_Pipeline](https://github.com/RogerRen0824/Gait_Data_Pipeline)

### LLM Research Intelligence System

An end-to-end Retrieval-Augmented Generation application for document-grounded question answering over user-provided PDF documents.

- PDF ingestion and text preprocessing
- Embedding-based retrieval with FAISS
- FastAPI backend for retrieval and answer generation
- Streamlit frontend for interactive document Q&A
- DeepSeek API integration through an OpenAI-compatible client
- Source citation and retrieved evidence display

Repository: [llm-research-intelligence-system](https://github.com/RogerRen0824/llm-research-intelligence-system)

## Technical Skills

**Languages & Data Science:** Python, pandas, NumPy, scikit-learn, machine learning, feature engineering, model evaluation

**Robotics & Learning:** PyTorch, MuJoCo, Gymnasium, Stable-Baselines3, PPO, OpenCV, state dynamics modelling

**AI & LLM Applications:** RAG, embeddings, vector search, prompt engineering, FastAPI, Streamlit, FAISS, DeepSeek API

**Healthcare & Research Data:** clinical data processing, gait analysis, time-series processing, privacy-preserving local workflows, interpretable AI

**Visualisation & Reporting:** Matplotlib, data storytelling, stakeholder-focused reporting

## Contact

- LinkedIn: [Zijie Ren](https://www.linkedin.com/in/zijie-ren-742335363/)
- Portfolio: [zijie-ren-portfolio](https://github.com/RogerRen0824/zijie-ren-portfolio)
