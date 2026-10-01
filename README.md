<h1 align="center">Hi 👋, I'm Chandan Rudrappa</h1>
<h3 align="center">🤖 AI Engineer · Data Scientist · ML Engineer | RAG pipelines, LLM evaluation, predictive modeling 🚀</h3>

<p align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGt4bGx0NjEweWZtczJtbWtxdWptd29tdnI1cjNuZHByaWhxOHhkaSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/Gwwg7fBSUQ6WmpjKEo/giphy.gif" width="30%"/>
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExb3Bzc2x6aDE1amE1NTY3OXZvZHBkbnl4M3RxeDRmdnlka2VvOWRweiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/4TtTVTmBoXp8txRU0C/giphy.gif" width="54%"/>
</p>

---

### 🌟 **About Me**
- 🧠 I work across the full data science stack, from **statistical modeling on messy real-world data** to **LLM systems in production**.
- 🔬 What ties it together is **evaluation**: RAG pipelines with traceable retrieval, classifiers that report their own confidence, and every model benchmarked against a real baseline before it ships.
- 🏛️ Currently a **Research Analyst at UT Arlington's School of Social Work**, building AI systems that automate Medicaid 1915(c) waiver policy analysis.
- 🎓 **MS in Data Science, UT Arlington** (GPA 4.0/4.0) · BE in Electronics & Communication, Ramaiah Institute of Technology.
- 📜 **Microsoft Certified:** Operationalizing Machine Learning and Generative AI Solutions (AI-300), 2026.
- 📍 Based in the **New York City metro area** and open to relocation.
- 💼 Open to **Data Scientist, AI Engineer, and Machine Learning Engineer** roles.

---

### 💼 **Experience**

**🔹 Research Analyst, Applied AI & LLM Systems** · *UT Arlington, School of Social Work* · Jul 2025 – Present
- Built an **LLM classification pipeline on the Anthropic Claude API** that tags waiver sections with confidence scores and evidence-backed rationales. Piloted on 20 themes, it **cut analyst coding time by 60%**, and prompt caching keeps API cost down.
- Scaled the pilot to the full **57-theme codebook** with a **RAG system** that embeds **1,300+ human-coded MAXQDA segments** in **LanceDB** and retrieves the nearest examples to ground and trace every prediction.
- Benchmarked a multi-label **TextCNN** and a **fine-tuned BERT** classifier on micro/macro-F1 as a reproducible offline baseline, to check that the LLM approach really was the better one.
- Built a **Streamlit** tool that diffs waiver filings section by section and exports HTML reports, **saving the team 40+ hours of manual review every month**.

**🔹 Graduate Teaching Assistant** · *UT Arlington* · Jan 2025 – May 2025
- Mentored **100+ students** in Probability, Statistics, and Calculus, raising test scores by an average of **20%**. Also cleaned and validated community datasets for service-learning projects.

**🔹 Data Scientist** · *Analyttica Datalab (LEAPS)* · Mar 2022 – Jul 2023
- Delivered **150+ reusable data science functions** for the LEAPS no-code analytics platform, including migrating legacy R time-series libraries to Python, and shipped them through **Docker, Kubernetes, and Jenkins** CI/CD.
- Wrote the column-type-to-function recommendation logic for **1,400+ functions**, which powered a **Neo4j**-backed suggestion engine.
- Built **60+ end-to-end ML workflows and case-study notebooks** and turned **80+ static plots into interactive Plotly dashboards**, cutting front-end delivery cycles by **25%**.
- Led ML demo sessions for enterprise clients including **Siemens** and **Aditya Birla Group**.

---

### 🚀 **Featured Projects**

#### ☁️ [CFPB Complaint Classifier: Serverless Inference on AWS](https://github.com/chandan-00/aws-complaint-classifier)
- Fine-tuned **DistilBERT** for six-class consumer-complaint classification and deployed it as an event-driven AWS pipeline (**API Gateway → SQS → Lambda → DynamoDB**), provisioned with **Terraform**, using least-privilege IAM and a dead-letter queue.
- Quantized the model to **INT8 ONNX**, shrinking it **75% (268 → 67 MB)** with no observed macro-F1 drop on an 810-example held-out test set.
- Benchmarked Lambda memory tiers in CloudWatch: **3008 MB reached 170 ms warm p95** and cut median duration **31%** compared with 2048 MB, at roughly the same estimated cost.
- Curated an **8,100-example** balanced dataset with dedup and conflicting-label removal done before splitting. A **TF-IDF + logistic regression baseline beat DistilBERT on macro-F1 (0.893 vs 0.874)**, which is exactly why baselines matter.

#### 🤖 Maverick Rover: Autonomous Navigation · *UT Arlington*
- Built **ArUco marker** and **LiDAR** object-detection pipelines for a ground-up Mars-rover build, integrated the ZED stereo SDK, and tuned the vision stack for on-board inference on an **NVIDIA Jetson TX2**.

#### 🚦 Road Accident Severity Analysis: UK STATS19
- Analyzed **300K+ UK road records** in Python and Tableau, and built a **Folium spatial danger metric** to flag high-risk corridors for infrastructure-policy insights.

---

### 🛠️ **Tech Stack & Tools**

#### 🧠 **Generative AI & LLMs**
![Claude API](https://img.shields.io/badge/Claude%20API-D97757?style=for-the-badge&logo=anthropic&logoColor=white)
![RAG](https://img.shields.io/badge/RAG-6A5ACD?style=for-the-badge)
![LanceDB](https://img.shields.io/badge/LanceDB-FF5A1F?style=for-the-badge)
![LangChain](https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-1C3C3C?style=for-the-badge&logo=langgraph&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

#### 🤖 **Machine Learning & NLP**
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Scikit-Learn](https://img.shields.io/badge/Scikit%20Learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white)
![spaCy](https://img.shields.io/badge/spaCy-09A3D5?style=for-the-badge&logo=spacy&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white)

#### 💻 **Languages & Databases**
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=postgresql&logoColor=white)
![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=for-the-badge&logo=googlebigquery&logoColor=white)
![Neo4j](https://img.shields.io/badge/Neo4j-4581C3?style=for-the-badge&logo=neo4j&logoColor=white)

#### ☁️ **Cloud & MLOps**
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white)
![Azure](https://img.shields.io/badge/Azure%20ML-0078D4?style=for-the-badge&logo=microsoftazure&logoColor=white)
![Terraform](https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=terraform&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![MLflow](https://img.shields.io/badge/MLflow-0194E2?style=for-the-badge&logo=mlflow&logoColor=white)
![ONNX](https://img.shields.io/badge/ONNX%20Runtime-005CED?style=for-the-badge&logo=onnx&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

#### 📈 **Big Data & Visualization**
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)
![Hadoop](https://img.shields.io/badge/Hadoop-66CCFF?style=for-the-badge&logo=apachehadoop&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Tableau](https://img.shields.io/badge/Tableau-E97627?style=for-the-badge&logo=tableau&logoColor=white)

---

### 📊 **GitHub Stats**

<p align="center">
  <a href="https://github.com/chandan-00">
    <img align="center" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chandan-00&theme=vision-friendly-dark" alt="Top Languages" />
  </a>
  <a href="https://github.com/chandan-00">
    <img align="center" src="https://github-readme-stats.vercel.app/api?username=chandan-00&show_icons=true&theme=vision-friendly-dark&rank_icon=github" alt="GitHub Stats" />
  </a>
  <a href="https://github.com/chandan-00">
    <img align="center" src="https://github-readme-streak-stats.herokuapp.com/?user=chandan-00&theme=vision-friendly-dark" alt="GitHub Streak" />
  </a>
</p>

---

### 🌍 **Connect With Me**
<p align="left">
<a href="mailto:chandanrudrappa00@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white"></a>
<a href="https://www.linkedin.com/in/chandanrudrappa/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white"></a>
<a href="https://chandan-00.github.io" target="_blank"><img src="https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=githubpages&logoColor=white"></a>
</p>

---

### 💡 **What I Care About**
🎯 **Evaluation over vibes.** If it hasn't beaten a baseline, it hasn't shipped.  
🔍 **Systems that explain their outputs.** Every prediction should be traceable.  
🤝 **Clean handoffs between research and production.**  
⚙️ *A model is only as useful as the hardware it actually runs on.*

---

### 📢 **Want to Collaborate?**
If you're working on **LLM systems, applied ML, or data science** problems where getting the evaluation right matters, let's connect! 🚀
