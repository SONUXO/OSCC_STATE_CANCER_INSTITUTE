# Oral Squamous Cell Carcinoma:
This project demonstrates an how to detect OSCC with various CNN model, in addition to that we have proposed a semgentation model which to detect and segment cancerous cell from clinical slides.

## Publication details:
[Link](https://link.springer.com/chapter/10.1007/978-981-97-3604-1_4)
---


## 📦 Pipeline Stages (from `dvc.yaml`)

Each stage is modular and reproducible:

1. **Data Ingestion** – Load and split raw data.
2. **Data Preprocessing** – Clean and tokenize data.
3. **Feature Engineering** – Convert text to vectorized format using `TfidfVectorizer`.
4. **Model Building** – Train a classification model.
5. **Model Evaluation** – Evaluate metrics (accuracy, precision, recall) and log with MLflow.
6. **Model Registration** – Register the best model version with MLflow.

---

## 🛠 Tech Stack

| Area | Tool/Service |
|------|--------------|
| Programming | Python, Flask |
| Pipeline Orchestration | DVC |
| Model Tracking | MLflow |
| CI/CD | GitHub Actions |
| Data & Model Storage | AWS S3 |
| Containerization | Docker + AWS ECR |
| Deployment | AWS EKS |
| Monitoring | Prometheus + Grafana on EC2 |
