<div align="center">

# Hadi Mohammadi

**Senior AI & Data Science Expert** at [AcademicTransfer](https://www.academictransfer.com)<br>
**PhD in Explainable NLP** — [Utrecht University](https://www.uu.nl/staff/HMohammadi), 2026

*Production LLM & ranking systems · LLM evaluation & explainability research*

[![Website](https://mohammadi.cv/assets/badges/website.svg)](https://mohammadi.cv)
[![CV](https://mohammadi.cv/assets/badges/cv.svg)](https://mohammadi.cv/assets/docs/HadiMohammadiCV.pdf)
[![Google Scholar](https://mohammadi.cv/assets/badges/scholar.svg)](https://scholar.google.com/citations?user=w4Jt-FAAAAAJ)
[![ORCID](https://mohammadi.cv/assets/badges/orcid.svg)](https://orcid.org/0000-0003-0860-9200)
[![LinkedIn](https://mohammadi.cv/assets/badges/linkedin.svg)](https://www.linkedin.com/in/mohammadi-hadi/)
[![Email](https://mohammadi.cv/assets/badges/email.svg)](mailto:hadi.mohammadi@outlook.com)

</div>

---

## What I do

**Industry — AcademicTransfer.** I lead AI and data-science work across CV–vacancy matching and ranking, LLM content optimisation, recruiter analytics, and end-to-end ML tooling for the two-sided Dutch academic-jobs marketplace (22 research universities and university medical centres).

**Research — Utrecht University.** My doctoral thesis develops explainable NLP across the full LLM life cycle, from token-level SHAP analysis to cross-cultural moral-alignment evaluation of LLMs. Recent work centers on LLM evaluation: LLM-as-judge frameworks (EvalMORAAL) and preference optimization under annotator disagreement (RA-DPO, MAP-PO).

I work where engineering rigor meets explainability research — shipping models that deliver in production *and* expose why they make each decision.

---

## Doctoral research

<div align="center">
  <img src="assets/thesis-wrap-cover.png" alt="Let Me Explain! — wrap cover" width="820"/>
</div>

### *Let Me Explain! Explainable NLP for Understanding Large Language Models*

Utrecht University, 2026

A six-chapter empirical thesis on explainability across the full LLM life cycle: a survey of XAI for NLP, a transparent BERT pipeline for online sexism detection, SHAP-driven probing of AI-text-detector robustness, content-vs-demographic explanations for LLM annotators, cross-cultural moral-alignment evaluation of 26 LLMs against the World Values Survey and PEW, and the **EvalMORAAL** chain-of-thought-plus-LLM-as-judge framework benchmarking 20 LLMs across 64 countries.

### Publications & code

Each chapter has a paper and a public companion repository with citation metadata and a tagged release.

| # | Paper | Venue | Links |
|---|---|---|---|
| 1 | Explainability in Practice: A Survey of Explainable NLP Across Various Domains | under review | [arXiv](https://arxiv.org/abs/2502.00837) · [code](https://github.com/mohammadi-hadi/xnlp-survey) |
| 2 | A Transparent Pipeline for Online Sexism Detection Based on the Combination of Explainable AI, Feature Selection, and Ensemble Learning | *Applied Sciences*, 2024 | [doi](https://doi.org/10.3390/app14198620) · [code](https://github.com/mohammadi-hadi/Explainable-Sexism-Detection) |
| 3 | Explainability-Based Token Replacement on LLM-Generated Text | arXiv, 2025 | [arXiv](https://arxiv.org/abs/2506.04050) · [code](https://github.com/mohammadi-hadi/Token-Replacement) |
| 4 | Assessing the Reliability of LLM Annotations in the Context of Demographic Bias and Model Explanation | GeBNLP @ ACL 2025 | [doi](https://doi.org/10.18653/v1/2025.gebnlp-1.9) · [page](https://mohammadi.cv/ACL2025/) · [code](https://github.com/mohammadi-hadi/Explainable_Annotations_Reliability) |
| 5 | Exploring Cultural Variations in Moral Judgments with Large Language Models | *CLIN Journal* 15, 2026 | [journal](https://clinjournal.org/clinj/article/view/238) · [arXiv](https://arxiv.org/abs/2506.12433) · [code](https://github.com/mohammadi-hadi/cultural-moral-judgments-llms) |
| 6 | EvalMORAAL: Interpretable Chain-of-Thought and LLM-as-Judge Evaluation for Moral Alignment in Large Language Models | \*SEM 2026 | [paper](https://aclanthology.org/2026.starsem-conference.34/) · [arXiv](https://arxiv.org/abs/2510.05942) · [code](https://github.com/mohammadi-hadi/EvalMORAAL) |

Full publication list on [mohammadi.cv](https://mohammadi.cv/publications/) and [Google Scholar](https://scholar.google.com/citations?user=w4Jt-FAAAAAJ).

---

## Industry projects

### AcademicTransfer — production AI for academic recruitment (2024–present)

LLM and ML systems serving the Dutch academic job market, end to end: data pipelines, model serving, monitoring, and recruiter-facing tools.

- Semantic CV-to-vacancy matching and LLM-assisted priority ranking of applicants, evaluated with A/B tests, uplift analysis, and bandit simulations
- LLM-based job-description optimisation and vacancy-text rewriting (OpenAI API)
- Recruiter analytics and model-monitoring dashboards
- CRM and workflow automation for recruitment teams

Internal repositories at [@academictransfer](https://github.com/academictransfer) (private; access on request):

| Repository | What it does |
|---|---|
| `at-ai` | Core AI/NLP services behind CV ranking and job-description optimisation |
| `at-cv-matcher` | Semantic CV-to-vacancy matching service |
| `at-cv-sorter` | Production CV priority-sorting pipeline |
| `at-vacature-rewriter` | LLM-based vacancy-text rewriting for recruiters |
| `at-concept-extractor` | Concept extraction from CVs and job descriptions |
| `at-dashboard` | Internal analytics and ML-monitoring dashboard |
| `at-crm` | CRM and ML integration for recruiter workflows |
| `at-elearning` | Recruiter training and onboarding platform |

### Bdood.bikes — bike-sharing operations intelligence (2019–2020)

As Head of Data Science & BI I built the operations-intelligence layer for a city-scale bike-sharing fleet: [bicycle-transportation-intelligence](https://github.com/mohammadi-hadi/bicycle-transportation-intelligence) — a Streamlit dashboard on live Oracle fleet data, with GeoPandas geofencing and H3 spatial indexing plus folium maps to plan rebalancing and collection.

Earlier: Senior Data Scientist at SnowaTec (2021–2023) — details on [mohammadi.cv](https://mohammadi.cv/experience/).

---

## Open source

- [raterkit](https://github.com/mohammadi-hadi/raterkit) — audit a labeled dataset before you trust it: chance-corrected reliability, rogue raters, label bias, guideline drift, train/test leakage and stale gold, each with a bootstrap confidence interval and validated on synthetic projects with implanted defects — plus an audit of the 211,225 raw GoEmotions crowd ratings where 27 of 28 emotions fall below the 0.667 reliability floor and the 3.6 raters per comment would need to be ~13 to reach 0.8-reliable labels.
- [abkit](https://github.com/mohammadi-hadi/abkit) — audit an A/B-test readout before you ship the decision: sample-ratio mismatch, contamination, outlier fragility, peeking, multiple testing, novelty decay and winner's-curse probes, validated on synthetic experiments with implanted defects — plus an audit of 4,873 real Upworthy headline tests where 16% fail the sample-ratio check and the median significant winner overstates its lift by 1.27x.
- [judgekit](https://github.com/mohammadi-hadi/judgekit) — audit an LLM judge before you trust it: position, verbosity, self-preference, compression, calibration and stability probes with bootstrap confidence intervals, validated on synthetic judges with implanted defects the audit must recover exactly — plus real local-model audits where qwen2.5:14b picks whichever answer is shown first 77% of the time and llama3.1:8b rewards length instead of correctness.
- [trajectory-judge](https://github.com/mohammadi-hadi/trajectory-judge) — how much an LLM judge misses when an agent reaches the right answer the wrong way: a synthetic tool-using environment with injected faults, five judge designs compared on detection, step localisation, calibration and cost, with every raw verdict committed so the tables rebuild offline. Published on [PyPI](https://pypi.org/project/trajectory-judge/).
- [judgepanel](https://github.com/mohammadi-hadi/judgepanel) — estimate how accurate your LLM judges are without any gold labels: Dawid–Skene EM recovers each judge's confusion matrix, the prevalence, and quality-weighted labels from the disagreement pattern alone, validated on a real five-judge panel where it exposes a flag-everything judge exactly (estimated specificity 0.000) and honestly documents the correlated-judge failure mode it inherits (a self-consistency ensemble agreeing with its base judge at kappa 0.96 inflates both estimates by up to +0.14).
- [ml-foundations](https://github.com/mohammadi-hadi/ml-foundations) — machine learning fundamentals implemented from scratch in numpy, each one checked against an independent reference, with every number in the six lessons regenerated from the code by CI so the prose can never drift from what the code does.
- [modern-ai-engineering](https://github.com/mohammadi-hadi/modern-ai-engineering) — field notes on production LLM systems: structured outputs, RAG, agents and MCP, LoRA/DPO/GRPO, LLM-as-judge evaluation, and serving with vLLM.
- [spark-search-ranking](https://github.com/mohammadi-hadi/spark-search-ranking) — counterfactual learning-to-rank for marketplace search logs in PySpark: position-bias estimation, IPS-weighted training, NDCG evaluation with a full test suite.
- [dynamic-pricing-dashboard](https://github.com/mohammadi-hadi/dynamic-pricing-dashboard) — interactive dynamic-pricing simulator: demand learning with Thompson sampling, forward-looking customers, and advertising effects, running fully in the browser via WebAssembly ([live demo](https://mohammadi.cv/dynamic-pricing-dashboard/)).
- [ml-summer-schools-europe](https://github.com/mohammadi-hadi/ml-summer-schools-europe) — practical guide to European ML summer schools: deadlines, funding, and application tips from four attended schools.
- [ml-learning-paths](https://github.com/mohammadi-hadi/ml-learning-paths) — the best ML courses organized into five career paths (ML scientist, ML engineer, LLM engineer, data engineer, data scientist), each ordered and argued.
- [ai-masters-netherlands](https://github.com/mohammadi-hadi/ai-masters-netherlands) — every AI and data science master's programme at Dutch research universities, with admissions, costs, and how to choose.
- [awesome-explainable-nlp](https://github.com/mohammadi-hadi/awesome-explainable-nlp) — curated list of 145 papers, tools, datasets, tutorials, and venues on explainability for NLP and LLMs, with weekly automated link checking. Contributions welcome.
- [better-than-bing](https://github.com/mohammadi-hadi/better-than-bing) — dense retrieval on the BEIR FiQA benchmark with Pyserini, sentence-transformer embeddings, and a FAISS HNSW index.
- [RA-DPO](https://github.com/mohammadi-hadi/RA-DPO) — reliability-aware preference optimization and selective prediction for subjective labelling: annotator agreement and model confidence combine into one score that weights DPO training pairs and decides when to abstain, evaluated on EXIST 2023 and EDOS across three backbones with per-instance results committed.
- [MAP-PO](https://github.com/mohammadi-hadi/MAP-PO) — perspectivist sexism detection on EXIST 2024: annotators clustered by labeling behavior, one agent per cluster trained with SFT / DPO / GRPO on two backbones, and the team's disagreement kept as an uncertainty signal; individual-only DPO polarizes the outer agents in every setting, a team reward repairs it, and CI rebuilds every results table from the committed artifacts.
- [Recommendation-System-Using-Autoencoders](https://github.com/mohammadi-hadi/Recommendation-System-Using-Autoencoders) — movie recommendation with autoencoders on the MovieLens 1M dataset.
- [Exist-2023](https://github.com/mohammadi-hadi/Exist-2023) — EXIST 2023 shared-task experiments, archived on Zenodo ([10.5281/zenodo.8144300](https://doi.org/10.5281/zenodo.8144300)).
- [FBB Sustainability Analysis](https://github.com/Firmbackbone/fbb-sustainability-analysis-cli) — environmental-impact analysis CLI on a Dutch firm panel.

More — from fraud detection to retrieval and time-series forecasting — in the [repositories tab](https://github.com/mohammadi-hadi?tab=repositories).

---

## Toolbox

| | |
|---|---|
| **Languages** | Python · R · SQL · Bash · LaTeX |
| **ML / DL** | PyTorch · TensorFlow · scikit-learn · XGBoost · Keras |
| **LLMs & NLP** | Hugging Face Transformers · OpenAI API · LangChain · spaCy |
| **Explainability** | SHAP · LIME · Captum |
| **Data engineering** | pandas · NumPy · Polars · DuckDB · Spark · PostgreSQL |
| **MLOps** | Docker · Kubernetes · GitHub Actions · MLflow · Weights & Biases |
| **Cloud & HPC** | AWS · Google Cloud · Azure · SURF Snellius |
| **Serving & viz** | FastAPI · Flask · Streamlit · Plotly · Matplotlib |

---

## Get in touch

Open to applied AI roles and consulting in NL / EU, and to research collaboration on explainability, LLM evaluation, and cultural alignment.

[mohammadi.cv](https://mohammadi.cv) · [LinkedIn](https://www.linkedin.com/in/mohammadi-hadi/) · [ORCID](https://orcid.org/0000-0003-0860-9200) · [hadi.mohammadi@outlook.com](mailto:hadi.mohammadi@outlook.com)

---

<div align="center">
<sub>Industry work lives in private AcademicTransfer repositories · research code is open at the chapter repos linked above.</sub>
</div>
