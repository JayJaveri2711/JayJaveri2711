# Hi, I'm Jay Javeri

I'm a B.S./M.S. Computer Science student at Georgia Tech, focusing on intelligence, machine learning, systems, and mathematical foundations. I’m interested in building AI and data systems that move beyond demos: systems that are evaluated carefully, grounded in real workflows, and useful in domains where reliability matters.

My work spans multimodal AI, financial data pipelines, applied machine learning, backend/data workflows, and teaching. I’ve worked on projects involving vision-language models, world-model embeddings, financial ML, market data ingestion, brokerage workflow automation, and large-scale algorithm education as a Senior TA for Georgia Tech’s Design and Analysis of Algorithms course.

---

## Areas I’m interested in

* AI systems that combine model capability with evaluation, uncertainty, and guardrails
* Financial data, market infrastructure, and quantitative research tooling
* Backend and data systems for real-world operational workflows
* Multimodal learning, vision-language models, and spatial reasoning
* Distributed systems, governance, and mechanism design
* Teaching, mentoring, and making technical ideas easier to understand

---

## Selected projects and work

### Vision-language-world model fusion

**Repo:** [`theworld`](https://github.com/JayJaveri2711/theworld)

Explored the fusion of vision-language models with world-model embeddings for spatial and temporal reasoning. The project combined Gemma-style language modeling with Cosmos-style latent representations and involved training, evaluation, ablations, and failure-mode analysis.

**What I worked on:**

* Multimodal model architecture and projection design
* PyTorch/Hugging Face training workflows
* Spatial reasoning evaluation and baseline comparisons
* Ablation studies and analysis of why early-fusion approaches can fail
* Lessons around representation mismatch, catastrophic forgetting, and evaluation design

---

### Prediction market data pipeline

**Repo:** [`cse-6242-prediction-market-analysis`](https://github.com/JayJaveri2711/cse-6242-prediction-market-analysis)

Built a framework for collecting and analyzing Polymarket and Kalshi prediction-market data, including market metadata collection, trade-history collection, API/blockchain data ingestion, Parquet-based storage, automatic progress saving, and reproducible analysis workflows.

**What I worked on:**

* External API and blockchain data collection
* Resumable data ingestion and progress checkpointing
* Structured storage using Parquet
* Market-level and trade-level analysis workflows
* Foundations for studying pricing, liquidity, and prediction-market behavior

---

### Financial workflow automation

Automated operational reporting workflows at Javeri Fiscal Services, a BSE-member brokerage. The work included end-of-day holdings reports and multi-trade average price calculations using Python and shell scripting.

**Impact:**

* Reduced manual processing from roughly 1 to 2 hours per day to about 2 minutes
* Improved consistency and reduced operational errors in recurring financial workflows
* Built practical automation for people working with real brokerage data and time-sensitive reporting needs

---

### Financial ML and data pipelines

Worked across financial data research projects involving Compustat, CRSP, earnings-call transcripts, accounting signals, volatility prediction, and earnings-change forecasting.

**Highlights:**

* Engineered Python/R workflows for 50+ years of financial statement and market data
* Worked with Compustat/CRSP data, CAPM beta estimation, and Fama-French industry categorization
* Built ML pipelines over large financial datasets with structured accounting features and NLP-derived signals
* Processed earnings-call transcripts and studied predictive signals for financial outcomes

---

### AI workflow with deterministic guardrails

**Repo:** [`Hippocratic-AI-Take-Home`](https://github.com/JayJaveri2711/Hippocratic-AI-Take-Home)

Built a Flask application that generates children’s bedtime stories using an LLM-based storyteller and judge. The system includes deterministic safety and quality gates, bounded revision attempts, structured parsing, mocked tests, and a safe fallback path.

**What I worked on:**

* LLM application orchestration
* Separating prompts, external clients, domain schemas, and app routes
* Deterministic validation around model outputs
* Fail-closed behavior when generated content does not satisfy constraints
* Testing AI-assisted workflows with mocked model calls

---

### K-Memes: multimodal meme sentiment classification

Built a machine learning pipeline for classifying meme sentiment using image and text representations. The project explored multimodal feature extraction with ResNet-style image encoders, BERT-style text encoders, supervised classifiers, and unsupervised clustering.

**What I worked on:**

* Multimodal feature extraction
* Sentiment classification over image-text data
* Supervised and unsupervised model comparisons
* Evaluation and iteration on noisy internet-scale content

---

### Senior TA: Design and Analysis of Algorithms

I serve as a Senior TA for Georgia Tech’s CS 3510, Design and Analysis of Algorithms. In this role, I mentor students across algorithmic problem solving, proof techniques, dynamic programming, graph algorithms, greedy algorithms, reductions, and complexity analysis.

**What this taught me:**

* Explaining difficult technical ideas clearly
* Debugging students’ reasoning, not just their code
* Designing examples and feedback that help people build intuition
* Communicating precisely under time pressure

---

## Technical toolkit

**Languages:** Python, Java, C/C++, SQL, TypeScript, JavaScript, R, Bash
**AI/ML:** PyTorch, TensorFlow, scikit-learn, Hugging Face, Transformers, CNNs, VLMs, LLM evaluation
**Data:** pandas, NumPy, Parquet, Spark, financial datasets, transcript processing, feature engineering
**Backend:** Flask, FastAPI, REST APIs, PostgreSQL, Streamlit, Selenium
**Infrastructure:** Git, Docker, Linux, shell scripting, cloud/HPC environments, distributed training basics
**Concepts:** algorithms, probability, statistics, linear algebra, machine learning, deep learning, data pipelines, evaluation

---

## How I think about building

I like building systems that are simple at the core, carefully evaluated, and honest about their failure modes.

Some principles I care about:

* Start with a clear source of truth.
* Make data transformations reproducible.
* Treat evaluation as part of the system, not an afterthought.
* Use AI where it adds leverage, but validate outputs when correctness matters.
* Prefer simple, inspectable workflows before adding complexity.
* Design for messy real-world data, partial failures, and iteration.

---

## Currently exploring

* Production AI systems and model evaluation
* Financial ML, market data, and quantitative research infrastructure
* Multimodal reasoning and world-model representations
* Backend/data systems for workflow automation
* Distributed systems, mechanism design, and governance-inspired computing

---

## Connect

* [LinkedIn](https://www.linkedin.com/in/jay-javeri)
* [GitHub](https://github.com/JayJaveri2711)
* Email: [jayjaveri03@gmail.com](mailto:jayjaveri03@gmail.com)
