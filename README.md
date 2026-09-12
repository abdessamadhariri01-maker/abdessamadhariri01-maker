# Abdessamad Hariri

**Master's Student — Data Science et Sécurité des Systèmes d'Information (D3SI, Parcours Excellence)**
Université Sultan Moulay Slimane · Béni Mellal, Morocco

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/abdessamad-hariri)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:abhariri2001@gmail.com)

---

Master's student at the crossroads of **Data Science and Cybersecurity**. I build end-to-end ML systems — data processing, model training, REST APIs and interactive dashboards — with a strong focus on the security and resilience of information systems.

- **Focus** — Machine Learning, Deep Learning, Cybersécurité
- **Core stack** — Python, FastAPI, scikit-learn
- **Open to** — PFE internship (Feb – Jun 2027) in Data Science or Cybersecurity

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
| Master — Data Science et Sécurité des Systèmes d'Information (D3SI, Parcours Excellence) | FSA Beni Mellal — USMS | 2025 – En cours |
| Licence d'Excellence — Data Science & Sécurité des Systèmes d'Information | FSA Beni Mellal — USMS | nov. 2024 – juil. 2025 |
| Sciences Économiques | FEG Beni Mellal — USMS | 2023 – 2024 |
| DUT — Génie Informatique | EST Beni Mellal — USMS | 2021 – 2023 |

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

## Stack

**Languages** — Python, SQL
**ML & Data** — scikit-learn, pandas, NumPy, Jupyter
**Backend & Apps** — FastAPI, Streamlit, Plotly
**Tools** — Git, Linux

---

## GitHub

<p>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=abdessamadhariri01-maker&v=2" alt="Languages per repository"/>
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=abdessamadhariri01-maker&v=2" alt="Most committed languages"/>
</p>
