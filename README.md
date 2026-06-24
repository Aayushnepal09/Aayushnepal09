<h1 align="center">Hi, I'm Aayush Nepal 👋</h1>

### 🎓 MS Engineering Science (AI & Data Innovation) @ University at Buffalo
I'm a software engineer and AI researcher who likes building things that actually make it to production, from the data pipelines and models down to the apps people use. My work has spanned **Predictive Analytics**, **LLM Agents**, **Computer Vision**, **Autonomous Systems**, and **Neuroscience Research**.

🔭 **Currently:** looking for new **Software Engineering** and **AI/ML** roles.

---

### 🚀 Technical Highlights
* **AI/ML:** Generative AI (**Anthropic Claude**, Google Gemini, OpenAI), LLM agents & prompt engineering, **Model Context Protocol (MCP)**, XGBoost / LightGBM / scikit-learn, deep learning from scratch (NumPy), Computer Vision (YOLOv5, TensorFlow, TensorRT, OpenCV).
* **MLOps & Data:** MLflow, Optuna, SHAP, Spark / Databricks (Delta Lake), FastAPI, Streamlit, SciPy, NLTK.
* **Cloud & Full-Stack:** AWS, DigitalOcean & Render, containerized with Docker; MERN Stack, Django, Flask, and Flutter.

---

### 📂 Top Projects

#### 🏦 [Loan Default Prediction](https://github.com/Aayushnepal09/loan_default_prediction)
**Production ML pipeline on LendingClub loan data**
* Trained an **XGBoost** model that reached **0.73 AUC-ROC** on a 314K-loan 2017 holdout, tuned with **Optuna** and tracked in **MLflow**, with a time-ordered split so future data never leaked into training.
* Ran the data pipeline on **Spark / Databricks** across bronze/silver/gold **Delta** tables, and used **SHAP** to explain what actually drove each prediction.
* Shipped it as a **Streamlit** app plus an **MCP server**, so you can query the model straight from **Claude Desktop**.

#### 🔎 [PDF Provenance Classifier](https://github.com/Aayushnepal09/pdf-provenance-classifier)
**Figuring out which tool made a PDF, and how well that holds up**
* Built a pipeline that tells whether a PDF came from **Word, Google Docs, or ReportLab** from its rendered image, working from **894** images expanded to **4,470** with **5 kinds of distortion**.
* Trained and compared **4 classifiers**, then measured how much accuracy each one loses as the images get worse.
* The interesting part wasn't peak accuracy, it was seeing which models stayed reliable once the inputs got messy.

#### 🧠 [Neural Network from Scratch](https://github.com/Aayushnepal09/neural-network-from-scratch)
**Backprop by hand, in plain NumPy**
* Wrote a two-layer MLP entirely in NumPy, no PyTorch or TensorFlow. The forward pass, backprop, and gradient descent are all derived and coded by hand.
* Got it to **93.2%** accuracy telling MNIST digits apart as even vs. odd, straight from the raw 784 pixels.
* Checked the gradients numerically to confirm the math was right (matched to about 1e-7).

#### 🤖 [QueryMind AI](https://github.com/Aayushnepal09/QueryMind_LLM)
**Ask your database a question in plain English**
* Built a tool that turns natural-language questions into SQL using **Google Gemini Pro**, with the schema fed into the prompt.
* It runs the generated query live and shows the results back in a clean table.
* Wrapped the whole thing in a **Streamlit** app.

#### ✈️ [Airline Satisfaction Predictor](https://github.com/Aayushnepal09/airline-passenger-satisfaction)
**End-to-end ML classification, served behind an API**
* Built a **scikit-learn** pipeline on a **100K+**-row dataset and logged F1-scores for every run in **MLflow / DagsHub**.
* Served predictions through a **FastAPI** endpoint with a **Streamlit** front end, all running in **Docker Compose**.
* Set it up so data prep, training, and evaluation run as one reproducible flow.

#### 🏎️ [Autonomous Vehicle Prototype](https://github.com/Aayushnepal09/Autonomous-vehicle)
**Computer vision on an edge device**
* Ran real-time object detection (**YOLOv5**, **92% mAP**) on an **NVIDIA Jetson TX2**.
* Used **TensorRT** (FP16) to cut perception latency by **40%**, down to under **50 ms** (~**30 FPS**).
* Added sensor fusion for obstacle avoidance. This one ended up becoming my undergraduate thesis.

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

### 📬 Connect with me
* **LinkedIn:** [linkedin.com/in/aayush7830/](https://www.linkedin.com/in/aayush7830/)
* **Email:** [nepal3491@gmail.com](mailto:nepal3491@gmail.com)
