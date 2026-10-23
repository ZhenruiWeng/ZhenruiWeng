### Hi, I'm Zhenrui Weng (翁振瑞) 👋

Applied Mathematics undergraduate (Y2) at **Xi'an Jiaotong-Liverpool University** (XJTLU), passionate about **machine learning, Bayesian deep learning, and physics-informed models**.

<p align="center">
  <a href="https://www.kaggle.com/zhenruiweng"><img src="https://img.shields.io/badge/Kaggle-Competitions_Gold_Medalist-FFBF00?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle Competitions Gold Medalist"></a>
  <a href="https://www.kaggle.com/zhenruiweng"><img src="https://img.shields.io/badge/Kaggle-Competitions_Expert-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle Competitions Expert"></a>
  <a href="https://www.kaggle.com/zhenruiweng"><img src="https://img.shields.io/badge/Kaggle-Datasets_Expert-20BEFF?style=flat-square&logo=kaggle&logoColor=white" alt="Kaggle Datasets Expert"></a>
  <a href="https://github.com/ZhenruiWeng/bpinn-rl-overtaking-system"><img src="https://img.shields.io/badge/SURF-Research_Fellow-7B2D43?style=flat-square" alt="SURF Research Fellow"></a>
  <a href="https://github.com/ZhenruiWeng"><img src="https://img.shields.io/badge/XJTLU-BSc_Applied_Math-17324E?style=flat-square" alt="XJTLU BSc Applied Mathematics"></a>
</p>

- 🏆 Kaggle **Competitions Gold Medalist** (individual) — rank 11/3,482, March Machine Learning Mania 2026
- 🎯 Kaggle **Competitions Expert** — top 2.7% with a single-model FT-Transformer (rank 89/3,355, LB 0.95059)
- 📦 Kaggle **Datasets Expert** — rank 274/11,981 · three bronze-medal datasets
- 🔬 **SURF research fellow** — Bayesian physics-informed neural networks: uncertainty quantification and probabilistic trajectory modeling
- 🧴 **L'Oréal Beauty Tech Hackathon** — built "SuiYan AI": label-free skin quantification (ITA° tone, wrinkle density, shine ratio) + RAG recommendation with anti-hallucination guardrails over a 23-SKU product base
- Interests: uncertainty quantification · probabilistic modeling · tabular & time-series ML · physics-informed ML · AI for Science

#### Tech Stack

`Python` `PyTorch` `JAX/Flax` `LightGBM/XGBoost/CatBoost` `scikit-learn` `Optuna` `LangChain/Chroma` `Streamlit` `Git`

#### 🏆 Competition Solutions

| Project | Highlights |
|---|---|
| [March Machine Learning Mania 2026](https://github.com/ZhenruiWeng/Kaggle-March-Machine-Learning-Mania-2026) | Kaggle **Gold** (11/3,482) — XGB+LGB+LR ensemble, 19 features, time-series CV, seed blending |
| [Student Health Risk — FT-Transformer](https://github.com/ZhenruiWeng/Kaggle-Student-Health-Risk-Prediction-top-2.7-rank-89-3-355-LB-0.95059) | Top 2.7% single model — PLR numerical embeddings, leak-free CV, fold-wise re-fitting |
| [EV Purchase — 83-Engine Grand Prix Blend](https://github.com/ZhenruiWeng/Kaggle-EV-Purchase-Prediction-top-4.4-rank-158-3576) | Top 4.4% (158/3,576) — CPU-only 83-engine ensemble: probit normalization, nested Caruana hill climb, DeLong-verified gains, public LB 0.94659 |
| [WiDS 2026 — Wildfire Survival Stack](https://github.com/ZhenruiWeng/WiDS-2026-Wildfire-Survival-Stack-rank-275-1754) | Top 15.7% (275/1,754) — small-sample survival modeling: 5 km distance-gated zone decoupling, three-model survival stack with seed bagging, IPCW censorship-safe calibration |

#### 🔬 Research — Physics-Informed & Bayesian ML

| Project | Highlights |
|---|---|
| [BPINN + RL Overtaking System](https://github.com/ZhenruiWeng/bpinn-rl-overtaking-system) | SURF research — JAX/Flax BPINN, MC-Dropout uncertainty quantification, rolling-window closed-loop decision making |
| [Laurent PINN — Singularity Splitting](https://github.com/ZhenruiWeng/laurent-pinn-mitigating-gradient-explosion) | Gradient-explosion fix — u(x) = MLP(x) + A/(x−x_s) with a hand-derived pole derivative; 120× error reduction vs vanilla PINN on a tan(x) singularity benchmark |
| [PINN Vehicle Trajectory Prediction](https://github.com/ZhenruiWeng/pinn-vehicle-trajectory-prediction) | Physics-informed trajectory prediction on NGSIM — dual data/physics losses, kinematic residual constraints |

#### 📦 Curated Datasets — Kaggle Datasets Expert (3 bronze)

| Dataset | Highlights |
|---|---|
| [TCM Herb Toxicity Dataset](https://github.com/ZhenruiWeng/tcm-herb-toxicity-dataset) | 229 herbs × 31 columns — 4-level toxicity labels hand-completed from classical materia medica, cross-linked to 5 TCM databases |
| [Eastern China Heavy Rainfall 2025](https://github.com/ZhenruiWeng/eastern-china-heavy-rainfall-2025) | 92 days of daily reanalysis (Copernicus C3S) for heavy-rain-day classification — 62% positive rate |
| [Madrid Air Quality Dataset](https://github.com/ZhenruiWeng/madrid-air-quality-dataset) | 30,627 synchronized IoT readings from 15 Madrid stations — 6 pollutants + meteorology + GPS grid |

#### 🛠️ Methodology & Engineering

| Project | Highlights |
|---|---|
| [Beyond R²: From a Skeptical Review to a Production System](https://github.com/ZhenruiWeng/beyond-r2-bmw-price-pipeline) | Three-act arc on one BMW pricing dataset — Act I: community review challenging a "93.5% R²" claim (exchange archived); Act II: leakage-free re-implementation, GroupKFold OOF 0.8904, honest fold mean 0.81 ± 0.10; Act III: 4-layer production system — SHA-256 lineage chain, small-sample-hardened PSI monitoring (3 simulated deployment weeks), ingestion validation, human-gated collection agent; honest split-scheme audit: 0.933 single-split vs 0.86 ± 0.16 near-dup-controlled |
| [TCM Herb Toxicity Prediction](https://github.com/ZhenruiWeng/tcm-herb-toxicity-prediction) | TF-IDF/SVD/K-Means semantic clustering + non-parametric hypothesis tests + RF/HGB baselines — statistically grounded negative results |
| [ML Modeling RAG Assistant](https://github.com/ZhenruiWeng/ml-modeling-rag-assistant) | LangChain + Chroma + Qwen + Streamlit — grounded Q&A over a curated ML knowledge base |
| [ML Experiments](https://github.com/ZhenruiWeng/machine-learning-experiments) | Bronze-medal Kaggle notebooks, tabular model benchmarks, CNN/PINN practice |

#### Find me

[![Kaggle](https://img.shields.io/badge/Kaggle-zhenruiweng-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/zhenruiweng)

<!--
**ZhenruiWeng/ZhenruiWeng** is a ✨special✨ repo: its README.md appears on your GitHub profile.
-->
