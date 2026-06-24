<h1 align="center">Hi, I'm Aayush Nepal 👋</h1>

### 🎓 MS Engineering Science (AI & Data Innovation) @ University at Buffalo
I am a Software Engineer and AI Researcher focused on building intelligent systems that bridge the gap between complex data and user-centric applications. My work spans **Predictive Analytics**, **LLM Agents**, **Computer Vision**, **Autonomous Systems**, and **Neuroscience Research**.

🔭 **Currently:** exploring new roles & opportunities in **Software Engineering** and **AI/ML**.

---

### 🚀 Technical Highlights
* **AI/ML:** Generative AI (**Anthropic Claude**, Google Gemini, OpenAI), LLM agents & prompt engineering, **Model Context Protocol (MCP)**, XGBoost / LightGBM / scikit-learn, deep learning from scratch (NumPy), Computer Vision (YOLOv5, TensorFlow, TensorRT, OpenCV).
* **MLOps & Data:** MLflow, Optuna, SHAP, Spark / Databricks (Delta Lake), FastAPI, Streamlit, SciPy, NLTK.
* **Cloud & Full-Stack:** AWS, DigitalOcean & Render on Docker; MERN Stack, Django, Flask, and Flutter.

---

### 📂 Top Projects

#### 🏦 [Loan Default Prediction](https://github.com/Aayushnepal09/loan_default_prediction)
**End-to-End ML on LendingClub data**
* Engineered an **XGBoost** classifier (**AUC-ROC 0.73** on a 314K-loan 2017 holdout), tuned with **Optuna**, tracked in **MLflow**, using a chronological split to prevent leakage.
* Built a scalable **Spark / Databricks** pipeline (bronze→silver→gold **Delta** tables) and surfaced key drivers with **SHAP** explainability.
* Deployed the model as a **Streamlit** app and an **MCP server** for conversational querying from **Claude Desktop**.

#### 🔎 [PDF Provenance Classifier](https://github.com/Aayushnepal09/pdf-provenance-classifier)
**Which tool made this PDF — and how robust is the answer?**
* Built an image pipeline detecting a PDF's source tool (**Word / Google Docs / ReportLab**) from **894** rendered images, augmented to **4,470** across **5 distortion types**.
* Trained and benchmarked **4 classifiers**, then quantified **accuracy degradation** as inputs were progressively corrupted.
* Designed it as a robustness study — not just a model — to measure real-world reliability under image noise.

#### 🧠 [Neural Network from Scratch](https://github.com/Aayushnepal09/neural-network-from-scratch)
**Backprop, by hand, in pure NumPy**
* Implemented a two-layer MLP **from first principles in pure NumPy** — hand-derived forward pass, backpropagation, and gradient descent (**no PyTorch / TensorFlow**).
* Achieved **93.2%** test accuracy classifying MNIST digits (even vs. odd) on raw 784-pixel inputs.
* Validated correctness with **numerical gradient checking** (agreement to ~1e-7).

#### 🤖 [QueryMind AI](https://github.com/Aayushnepal09/QueryMind_LLM)
**LLM-Powered SQL Engine**
* Built a natural-language-to-SQL engine using **Google Gemini Pro** with schema-aware prompting.
* Executes generated queries live against the database and renders results in a clean table.
* Shipped as a **Streamlit** app for real-time, conversational data retrieval.

#### ✈️ [Airline Satisfaction Predictor](https://github.com/Aayushnepal09/airline-passenger-satisfaction)
**End-to-End Machine Learning Pipeline**
* Built a **scikit-learn** classification pipeline on a **100K+**-record dataset, tracking F1-scores across experiments in **MLflow / DagsHub**.
* Served predictions via a **FastAPI** inference API with a **Streamlit** UI, **containerized with Docker Compose**.
* Automated the full data → preprocessing → training → evaluation flow as a reproducible pipeline.

#### 🏎️ [Autonomous Vehicle Prototype](https://github.com/Aayushnepal09/Autonomous-vehicle)
**Computer Vision & Robotics**
* Deployed real-time object detection (**YOLOv5**, **92% mAP**) on an **NVIDIA Jetson TX2** edge device.
* Cut perception latency **40%** (to **<50 ms**, ~**30 FPS**) via **TensorRT** FP16 optimization.
* Integrated sensor fusion for dynamic obstacle avoidance; formed the basis of my undergraduate thesis.

---

### 🛠️ Languages & Tools
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
![Claude](https://img.shields.io/badge/Claude-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![Google Gemini](https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991?style=for-the-badge&logo=openai&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-000000?style=for-the-badge&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)
![XGBoost](https://img.shields.io/badge/XGBoost-189FDD?style=for-the-badge&logo=xgboost&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-%23FF6F00.svg?style=for-the-badge&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-%238CAAE6.svg?style=for-the-badge&logo=scipy&logoColor=white)
![OpenCV](https://img.shields.io/badge/opencv-%235C3EE8.svg?style=for-the-badge&logo=opencv&logoColor=white)
![MLflow](https://img.shields.io/badge/mlflow-%230194E2.svg?style=for-the-badge&logo=mlflow&logoColor=white)
![Spark](https://img.shields.io/badge/apache%20spark-%23E25A1C.svg?style=for-the-badge&logo=apachespark&logoColor=white)
![FastAPI](https://img.shields.io/badge/fastapi-%23009688.svg?style=for-the-badge&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/streamlit-%23FF4B4B.svg?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)
![React](https://img.shields.io/badge/react-%2320232a.svg?style=for-the-badge&logo=react&logoColor=%2361DAFB)
![Node.js](https://img.shields.io/badge/node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Django](https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white)
![Flask](https://img.shields.io/badge/flask-%23000000.svg?style=for-the-badge&logo=flask&logoColor=white)
![Flutter](https://img.shields.io/badge/flutter-%2302569B.svg?style=for-the-badge&logo=flutter&logoColor=white)
![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-%23FF9900.svg?style=for-the-badge&logo=amazon-aws&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/postgres-%23316192.svg?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-%234ea94b.svg?style=for-the-badge&logo=mongodb&logoColor=white)

---

### 📬 Connect with me:
* **LinkedIn:** [linkedin.com/in/aayush7830/](https://www.linkedin.com/in/aayush7830/)
* **Email:** [nepal3491@gmail.com](mailto:nepal3491@gmail.com)

---
*"Turning data into innovation, one query at a time."*
