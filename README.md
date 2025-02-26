# 🚀 MLOps - Pipeline d'Automatisation pour le Machine Learning

Ce projet implémente un pipeline MLOps pour automatiser l'entraînement, l'évaluation et le déploiement d'un modèle de Machine Learning.

## 📌 Fonctionnalités
- 📂 **Préparation des données** (`make prepare`)
- 🏋️ **Entraînement du modèle** (`make train`)
- 📊 **Évaluation du modèle** (`make evaluate`)
- 🚀 **Déploiement avec FastAPI** (`make run-api`)
- 🔬 **Suivi des expériences avec MLflow** (`make run-mlflow`)
- 🐳 **Conteneurisation avec Docker** (`make docker-build && make docker-run`)
- 🔄 **CI/CD avec GitHub Actions** (`.github/workflows/mlops-pipeline.yml`)

---

## ⚙️ Installation

### 1️⃣ **Cloner le repo**
```sh
git clone https://github.com/amenihosni/MLOps.git
cd MLOps
