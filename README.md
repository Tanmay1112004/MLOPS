# 📌 Iris Classification with MLflow (MLOps Project)

## 🌟 Overview

This project demonstrates **end-to-end MLOps practices** using the classic **Iris dataset**.
We implement, track, and manage machine learning models with **MLflow** — covering model training, experiment tracking, artifact logging, and model registry.

The project highlights:

* ✅ Model training (Logistic Regression & Random Forest)
* ✅ Automated logging of metrics, parameters, and confusion matrices
* ✅ Model versioning & registry with MLflow
* ✅ Artifact storage (plots, metrics, trained models)
* ✅ Reproducible training pipeline wrapped in a **Python class**

---

## 🛠️ Tech Stack

* **Language:** Python 3.8+
* **ML Frameworks:** Scikit-learn, Seaborn, Matplotlib
* **MLOps Tooling:** MLflow (tracking, logging, registry)
* **IDE:** GitHub Codespaces / VS Code

---

## 📂 Project Structure

```
📦 mlops-iris-classification
 ┣ 📜 class.py                           # Main training & logging pipeline
 ┣ 📜 requirements.txt                   # Python dependencies
 ┣ 📜 experiment.ipynb                   # 1st experiment – EDA & baseline models
 ┣ 📜 2nd_mlflow_binaryclassification.ipynb   # 2nd experiment – MLflow binary classification workflow
 ┣ 📜 3rd_mlflow_model_registiration.ipynb    # 3rd experiment – Model registration with MLflow
 ┣ 📂 artifacts/                         # Auto-generated confusion matrix images
 ┣ 📂 mlruns/                            # MLflow local run storage (auto-created)
 ┗ 📜 README.md                          # Project documentation

```

---

## ⚡ Quickstart

### 1️⃣ Clone the repo

```bash
git clone https://github.com/<your-username>/<your-repo>.git
cd <your-repo>
```

### 2️⃣ Install dependencies

```bash
pip install -r requirements.txt
```

### 3️⃣ Run training

```bash
python class.py
```

This will:

* Train **Logistic Regression** & **Random Forest** models
* Log metrics, parameters & confusion matrices into MLflow
* Save confusion matrix images under `artifacts/`
* Attempt to register models into the MLflow Model Registry

### 4️⃣ Launch MLflow UI (optional)

```bash
mlflow ui --host 0.0.0.0 --port 5000
```

Forward port **5000** in GitHub Codespaces → open browser → explore runs, metrics, and artifacts.

---

## 📊 Example Output

* **Confusion Matrix (Random Forest):**
  ![Confusion Matrix Example](artifacts/random_forest_conf_matrix.png)

* **MLflow UI Screenshot:**
  *(Insert screenshot of your MLflow UI after first run)*

---

## 🚀 MLOps Features

* 📌 **Experiment Tracking** → logs metrics/params automatically
* 📌 **Reproducibility** → same pipeline, different experiments
* 📌 **Model Registry Ready** → supports versioning of models
* 📌 **Artifact Management** → confusion matrices & models stored for each run

---

## 👨‍💻 Author

**Tanmay Kshirsagar**
📩 [tanmaykshirsagar001@gmail.com](mailto:tanmaykshirsagar001@gmail.com)
🔗 [Portfolio](https://tanmayportfolio.ccbp.tech/) | [LinkedIn](https://www.linkedin.com/in/tanmay-kshirsagar) | [GitHub](https://github.com/Tanmay1112004)

---

## 📌 Future Improvements

* [ ] Add **Docker support** for full reproducibility
* [ ] Deploy models via **MLflow Serving / FastAPI**
* [ ] Integrate with **cloud MLflow Tracking Server** (AWS/GCP/Azure)
* [ ] Automate CI/CD pipeline with **GitHub Actions**

---

🔥 With this project, you not only train ML models but also follow proper **MLOps principles** — experiment tracking, artifact management, and model lifecycle handling.

---
