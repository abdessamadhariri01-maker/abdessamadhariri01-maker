# Abdessamad Hariri

Master's student in **Data Science & Information Systems Security** at USMS, Béni Mellal. I build ML systems with a focus on network security and applied data science — currently working on intrusion detection and traffic analysis pipelines.

---

## Projects

### DDoS Detection System
`Python` `FastAPI` `Scikit-learn` `Streamlit` `CIC-DDoS2019`

ML-based DDoS attack detection system with a REST API backend serving pre-trained Random Forest and SVM classifiers, paired with a real-time Streamlit dashboard.

Trained on the CIC-DDoS2019 dataset (77 network flow features), the system classifies incoming traffic as **BENIGN** or **DDoS** across three detection modes: manual single-input, CSV batch upload, and live traffic simulation.

**What I built:**
- FastAPI backend with 6 REST endpoints — model health checks, single and batch predictions, feature schema retrieval, detection statistics, and event history export
- Pydantic-based request validation that auto-aligns partial inputs to the full 77-feature schema (missing fields default to 0)
- Confidence scoring layer — `predict_proba` for Random Forest, sigmoid-mapped `decision_function` for SVM
- Streamlit dashboard with Plotly real-time charts, DDoS alert banners, detection history table, and CSV export for predictions, events, and raw feature vectors

[View repository →](https://github.com/abdessamadhariri01-maker/DDoS-Detection)

---

### Regularization in Machine Learning
`Python` `Scikit-learn` `Ridge` `Lasso` `ElasticNet`

Comparative analysis of L2 (Ridge), L1 (Lasso), and ElasticNet regularization on an energy efficiency dataset (200 observations, 24 variables) to evaluate how each technique handles overfitting when 10 of 23 features are pure noise.

**Key findings:**
- **Lasso (λ=1)** achieved the strongest generalization — 24.4% reduction in test MSE vs. the unregularized baseline, while automatically selecting only **4 out of 23 features** and zeroing out all noise variables
- **ElasticNet (λ=0.1)** offered a balanced trade-off at 5.4% MSE improvement, keeping 21 features
- **Ridge (λ=10)** provided marginal improvement (1.0%) by uniformly shrinking all coefficients without feature elimination

The baseline model showed clear overfitting (train MSE 18.4 vs. test MSE 42.2). Lasso was the only technique to fully close that gap, bringing test MSE down to 31.9 while maintaining a much smaller train-test spread (25.2 vs. 31.9).

[View repository →](https://github.com/abdessamadhariri01-maker/Regularisation-ML)

---

## Experience

**Data Science Intern** — INADRE SARL AU *(Rabat, Sep 2024 – Dec 2024)*
- Processed and analyzed national project datasets using Python and SQL (Marché n. 67/EAJ23)
- Built data pipelines to support structured decision-making

**Web Development Intern** — Para CDR Pharm *(Béni Mellal, Apr 2023 – Jun 2023)*
- Designed and developed a responsive corporate website end-to-end

**IT Intern** — RADEET *(Béni Mellal, Aug 2022 – Sep 2022)*
- Maintained information systems and assisted with network infrastructure operations

---

## Education

| Program | Institution | Period |
|:---|:---|:---|
| Master's (Excellence Track) — Data Science & Information Systems Security | USMS, Faculté Polydisciplinaire de Béni Mellal | 2025 – Present |
| Licence d'Excellence — Data Science & Information Systems Security | USMS, Faculté Polydisciplinaire de Béni Mellal | 2024 – 2025 |
| DUT — Génie Informatique | USMS, École Supérieure de Technologie de Béni Mellal | 2021 – 2023 |

---

## Contact

[abhariri2001@gmail.com](mailto:abhariri2001@gmail.com) · [LinkedIn](https://www.linkedin.com/in/abdessamad-hariri) · [GitHub](https://github.com/abdessamadhariri01-maker)