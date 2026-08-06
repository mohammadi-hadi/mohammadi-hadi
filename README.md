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

### Evaluation

- [EvalMORAAL](https://github.com/mohammadi-hadi/EvalMORAAL) — chain-of-thought plus LLM-as-judge evaluation of moral alignment, benchmarking 20 LLMs across 64 countries against the World Values Survey and PEW ([\*SEM 2026](https://aclanthology.org/2026.starsem-conference.34/)).
- [trajectory-judge](https://github.com/mohammadi-hadi/trajectory-judge) — how much an LLM judge misses when an agent reaches the right answer the wrong way: a tool-using environment with injected faults, five judge designs compared on detection, step localisation, calibration and cost.
- [judgekit](https://github.com/mohammadi-hadi/judgekit) — audit an LLM judge before you trust it: position, verbosity, self-preference and calibration probes with bootstrap intervals, where qwen2.5:14b picks whichever answer is shown first 77% of the time.
- [judgepanel](https://github.com/mohammadi-hadi/judgepanel) — estimate how accurate your judges are without any gold labels: Dawid–Skene EM over the disagreement pattern alone, which exposes a flag-everything judge exactly (estimated specificity 0.000).
- [abkit](https://github.com/mohammadi-hadi/abkit) — audit an A/B-test readout before you ship the decision: sample-ratio mismatch, peeking, multiple testing and winner's-curse probes, applied to 4,873 real Upworthy tests where 16% fail the sample-ratio check.

### Ranking and production

- [spark-search-ranking](https://github.com/mohammadi-hadi/spark-search-ranking) — counterfactual learning-to-rank for marketplace search logs in PySpark: position-bias estimation, IPS-weighted training, NDCG evaluation with a full test suite.
- [rankkit](https://github.com/mohammadi-hadi/rankkit) — ranking metrics with error bars, and click metrics that survive position bias: on the bundled example, counting raw clicks rejects a ranker that is genuinely better and correcting for position reverses the verdict.
- [dynamic-pricing-dashboard](https://github.com/mohammadi-hadi/dynamic-pricing-dashboard) — dynamic-pricing simulator with Thompson sampling demand learning and forward-looking customers, running fully in the browser via WebAssembly ([live demo](https://mohammadi.cv/dynamic-pricing-dashboard/)).

### Curated

- [awesome-explainable-nlp](https://github.com/mohammadi-hadi/awesome-explainable-nlp) — 145 papers, tools, datasets, tutorials and venues on explainability for NLP and LLMs, with weekly automated link checking. Contributions welcome.

Also maintained: [MAP-PO](https://github.com/mohammadi-hadi/MAP-PO) and [RA-DPO](https://github.com/mohammadi-hadi/RA-DPO) (preference optimization under annotator disagreement), [raterkit](https://github.com/mohammadi-hadi/raterkit) · [calikit](https://github.com/mohammadi-hadi/calikit) · [abeval](https://github.com/mohammadi-hadi/abeval) · [arenakit](https://github.com/mohammadi-hadi/arenakit) · [judgewatch](https://github.com/mohammadi-hadi/judgewatch) · [explainkit](https://github.com/mohammadi-hadi/explainkit) (evaluation and audit libraries), [ml-foundations](https://github.com/mohammadi-hadi/ml-foundations) · [modern-ai-engineering](https://github.com/mohammadi-hadi/modern-ai-engineering) (from-scratch ML and production LLM notes), and guides to [ML learning paths](https://github.com/mohammadi-hadi/ml-learning-paths), [European summer schools](https://github.com/mohammadi-hadi/ml-summer-schools-europe) and [Dutch AI master's programmes](https://github.com/mohammadi-hadi/ai-masters-netherlands).

Elsewhere: [FBB Sustainability Analysis](https://github.com/Firmbackbone/fbb-sustainability-analysis-cli) — an environmental-impact analysis CLI on a Dutch firm panel, built for the Firmbackbone research infrastructure.

Everything else is in the [repositories tab](https://github.com/mohammadi-hadi?tab=repositories).

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
