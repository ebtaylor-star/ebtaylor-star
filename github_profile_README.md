# Hi, I'm Dr. Elizabeth (Liz) Taylor

**Data Scientist · AI Governance Researcher · DBA**

M.S. Data Science, Utica University (August 2026) · Doctor of Business Administration 

---

## 🔬 What I Work On

I build machine learning systems where the stakes are real — algorithmic fairness audits, fraud detection, and decision models that have to be explainable and legally defensible, not just accurate.

My work lives at the intersection of technical rigor and ethical accountability. I care as much about *why* a model predicts what it does as whether the numbers look good — and whether those predictions survive regulatory scrutiny.

---

## 📌 Featured Project

### [Dual-Axis Fragility in Algorithmic Hiring](https://github.com/ebtaylor-star/dual-axis-fragility-hiring)

**MSDS Capstone · Utica University · August 2026**

Most audits of automated hiring tools ask one question: does the system discriminate? This research asks a second: *can it be gamed?* A dual-axis framework evaluates both risks on a single dataset so the findings are directly comparable.

**Axis 1 — Structural Exclusion (fairness):** Fairlearn's Demographic Parity Ratio against the EEOC four-fifths threshold.  
- Biased label: DPR = 0.329 — **FAILS** (men 35.7% selected vs. women 11.8%)  
- After AIF360 Reweighing mitigation: DPR = 0.813 — **PASSES** (1.3-pt accuracy cost)

**Axis 2 — Adversarial Exploitability (gaming):** Custom flip-threshold search, 2-step budget.  
- Model Fragility Index: **85.0%** of rejected candidates flippable within 2 mutable-feature edits  
- The fairer reweighed model: MFI rises to **88.4%** — *the fairer model is more gameable, not less*

**Core finding:** Fixing structural exclusion worsened adversarial exploitability. Both axes must be tested together for a procurement risk assessment to be meaningful.

**Procurement verdict: HIGH RISK** — DPR < 0.70 OR MFI > 60% → do not procure

`Random Forest` · `Fairlearn` · `AIF360` · `SHAP` · `scikit-learn` · `FairCVdb (N=24,000)`

---

## 🗂️ Projects

| Project | Description | Stack |
|---|---|---|
| [Dual-Axis Fragility in Algorithmic Hiring](https://github.com/ebtaylor-star/dual-axis-fragility-hiring) | MSDS Capstone: dual-axis audit framework for ATS procurement risk (structural exclusion + adversarial exploitability) | Fairlearn, AIF360, SHAP, scikit-learn |
| [Bank Account Fraud Detection](https://github.com/ebtaylor-star/fraud-detection-adaboost) | AdaBoost on 1M-record NeurIPS 2022 BAF dataset; accuracy paradox (99% accuracy, recall = 0.03), feature ethics | scikit-learn, pandas, numpy |
| [RAG Pipeline for LAION-5B](https://github.com/ebtaylor-star/rag-laion-pipeline) | Retrieval-Augmented Generation with Sentence Transformer embeddings and FAISS index | LangChain, FAISS, HuggingFace |
| [LLM-Powered Research Assistant](https://github.com/ebtaylor-star/llm-research-assistant) | Local RAG pipeline using DeepSeek-r1:7b via Ollama + LangChain + Chroma | Ollama, LangChain, ChromaDB |
| [Smartphone Adoption Forecasting](https://github.com/ebtaylor-star/smartphone-adoption-arima) | OLS vs. Lasso vs. ARIMA(1,1,1) on global adoption data; Lasso RMSE 145.60 vs. OLS 173.62 | statsmodels, scikit-learn |
| [Neural Network Decision Boundaries](https://github.com/ebtaylor-star/neural-net-pytorch) | PyTorch MLP (1→128→3), ReLU, decision boundary visualization, hidden layer hooks | PyTorch, matplotlib |

---

## 📄 Research & Writing

- **[Dual-Axis Fragility in Algorithmic Hiring: An Empirical Audit of Structural Exclusion and Adversarial Vulnerabilities in Automated Recruitment Pipelines](https://github.com/ebtaylor-star/dual-axis-fragility-hiring)** — MSDS Capstone. Develops and validates a dual-axis procurement audit framework. Advisor: Dr. Michael McCarthy. *Utica University, August 2026.*

- **[Mitigating Intersectional Bias in Text-to-Image Generative AI](https://github.com/ebtaylor-star/ai-bias-research)** — Proposes α-Fairness Regularization Framework (A-FRF): LoRA fine-tuning with KL Divergence penalty for Stable Diffusion models. *DSC-654, Utica University, 2025.*

- **[LLM Bias in Automated Resume Screening](https://github.com/ebtaylor-star/llm-hiring-bias-litreview)** — Literature review of An et al. (2025, *PNAS Nexus*); 361K synthetic resumes across GPT-3.5, GPT-4, Gemini, Claude, Llama 3. All models showed measurable bias against Black male candidates. *DSC-654, Utica University, 2025.*

---

## 🛠️ Skills

**Languages:** Python, R, SQL  
**ML/DL:** scikit-learn, TensorFlow/Keras, PyTorch, Random Forest, AdaBoost, Lasso/Ridge, K-Means  
**AI Fairness & Governance:** Fairlearn, AIF360, SHAP (TreeExplainer), Demographic Parity Ratio, EEOC four-fifths rule, Model Fragility Index · *AI & ML Microcredential, Utica University (May 2026)*  
**NLP/GenAI:** LangChain, Ollama, RAG pipelines, FAISS, Sentence Transformers, Stable Diffusion  
**Data:** pandas, numpy, matplotlib, seaborn, statsmodels  
**Regulatory context:** Mobley v. Workday (2024), NYC Local Law 144, EU AI Act  

---

## 🎓 Education & Credentials

- **M.S. Data Science** — Utica University 
- **Doctor of Business Administration (DBA)
- **AI & Machine Learning Microcredential** — Utica University, School of Business & Justice Studies *(May 2026)* · [Verify](https://www.utica.edu/badge/pdf/5135D6BEFA306F98E065025056B34C62)

---

## 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-lizbtaylor-blue?style=flat&logo=linkedin)](https://linkedin.com/in/lizbtaylor/)  
[![GitHub](https://img.shields.io/badge/GitHub-ebtaylor--star-black?style=flat&logo=github)](https://github.com/ebtaylor-star)

---

*"A tool that is fair but easy to trick, or hard to trick but discriminatory, is still a legal liability."*
