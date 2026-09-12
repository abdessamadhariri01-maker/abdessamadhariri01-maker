# Abdessamad Hariri

**Master's Student — Data Science & Information Systems Security (D3SI, Excellence Track)**
Université Sultan Moulay Slimane · Béni Mellal, Morocco

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdessamad-hariri)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abhariri2001@gmail.com)

---

Master's student focused on **machine learning applied to network security**. I build end-to-end detection systems: data processing, model training, REST APIs and interactive dashboards.

- **Focus** — intrusion and DDoS detection, traffic analysis pipelines
- **Coursework** — Deep Learning, NLP, Big Data Analytics, AI for Cybersecurity, Cloud Computing
- **Open to** — PFE internship (Feb – Jun 2027) in Data Science or Cybersecurity

---

## Projects

### [DDoS-Detection](https://github.com/abdessamadhariri01-maker/DDoS-Detection)

ML-powered DDoS attack detection system · `Python` `FastAPI` `Scikit-learn` `Streamlit` `CIC-DDoS2019`

REST API backend serving trained Random Forest and SVM classifiers, paired with a real-time Streamlit dashboard. Trained on the CIC-DDoS2019 dataset (77 network flow features); classifies traffic as BENIGN or DDoS across three detection modes: manual single-input, CSV batch upload, and live traffic simulation.

- FastAPI backend with 6 REST endpoints — health checks, single and batch predictions, feature schema retrieval, detection statistics, event history export
- Pydantic-based validation auto-aligning partial inputs to the full 77-feature schema
- Confidence scoring — `predict_proba` for Random Forest, sigmoid-mapped `decision_function` for SVM
- Streamlit dashboard with Plotly real-time charts, alert banners and CSV export

### [shuttle-rl-project](https://github.com/abdessamadhariri01-maker/shuttle-rl-project)

Adaptive Reinforcement Learning system · `Python` `Reinforcement Learning`

RL system for university shuttle operations at USMS Beni Mellal — mini-project for the *Apprentissage par Renforcement* course (M122, DS-G04, MD3SI).

### [Regularisation-ML](https://github.com/abdessamadhariri01-maker/Regularisation-ML)

Ridge vs Lasso vs ElasticNet · `Python` `Scikit-learn` `Jupyter`

Comparative analysis of L1, L2 and ElasticNet regularization on an energy-efficiency dataset (200 observations, 24 variables), evaluating overfitting when 10 of 23 features are pure noise.

- Lasso (λ=1): best generalization — 24.4% reduction in test MSE, selecting 4 of 23 features and zeroing all noise variables
- ElasticNet (λ=0.1): balanced trade-off, 5.4% MSE improvement with 21 features kept
- Ridge (λ=10): marginal improvement (1.0%) by uniform coefficient shrinkage

---

## Experience

**Data Science Intern — INADRE SARL AU** · Rabat · Sep 2024 – Dec 2024
- Processed and analyzed national project datasets using Python and SQL (Marché n. 67/EAJ23)
- Built data pipelines to support structured decision-making

**Web Development Intern — Para CDR Pharm** · Béni Mellal · Apr 2023 – Jun 2023
- Designed and developed a responsive corporate website end-to-end

**IT Intern — RADEET** · Béni Mellal · Aug 2022 – Sep 2022
- Maintained information systems and assisted with network infrastructure operations

---

## Education

| Program | Institution | Period |
|:---|:---|:---|
| Master — Data Science & Information Systems Security (Excellence Track) | Université Sultan Moulay Slimane, Béni Mellal | 2025 – 2027 |
| Licence d'Excellence — Data Science & Information Systems Security | Université Sultan Moulay Slimane, Béni Mellal | 2024 – 2025 |
| DUT — Génie Informatique | École Supérieure de Technologie, Béni Mellal | 2021 – 2023 |

---

## Stack

**Languages** — Python, SQL
**ML & Data** — scikit-learn, pandas, NumPy, Jupyter
**Backend & Apps** — FastAPI, Streamlit, Plotly
**Tools** — Git, Linux

---

## GitHub

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=abdessamadhariri01-maker&layout=compact&hide_border=true&langs_count=8" alt="Top Languages"/>
