# Sachin Mahajan

**Backend & AI Engineer | LangGraph • FastAPI • Redis | Open source: TensorFlow, pandas, Podman**

B.Tech CSE (AI/ML), Lovely Professional University, expected 2027.

I build LLM pipelines, multi-agent systems, and backend services, and I contribute fixes to open-source projects.

---

## Open source contributions

- **TensorFlow (Google):** Fixed float32 underflow in `tf.math.sign` for small complex inputs using a stable magnitude computation in C++. [PR #116986](https://github.com/tensorflow/tensorflow/pull/116986), merged.
- **TensorFlow (Google):** Replaced `exp(x)-1` with `expm1(x)` in ELU/SELU kernels for better precision on small inputs. [PR #116947](https://github.com/tensorflow/tensorflow/pull/116947), approved, pending merge.
- **pandas (NumFOCUS):** Fixed `Categorical.map` with a defaultdict, which replaced missing values with NaN instead of using the default factory. [PR #65413](https://github.com/pandas-dev/pandas/pull/65413), merged into the pandas 3.1 milestone.
- **Podman (Red Hat):** Fixed Quadlet service generator handling of missing keys so volumes are recreated on container restart. Added integration tests and documentation. [PR #29375](https://github.com/containers/podman/pull/29375), merged.

---

## Projects

### AutoOutreach
Multi-agent startup discovery built with LangGraph, FastAPI, and Redis. Finds founder contacts, drafts short pitches, and sends them through Gmail. Redis-backed rate limiting (10 requests per minute) and a fallback enrichment pipeline.
- Discovery latency reduced from 18s to 4.8s
- **Stack:** Python, LangGraph, FastAPI, Redis, AsyncIO, Docker, Azure
- [Repository](https://github.com/Mahajan-Sachin/AutoOutreach)

### MediScan AI
Multi-agent lab report analysis. A 7-node LangGraph pipeline with ChromaDB RAG and a self-correcting CrewAI judge loop.
- MD5 caching reduced response time from 69s to under 1s
- **Stack:** Python, LangGraph, CrewAI, FastAPI, ChromaDB, Groq, Docker
- Deployed on Hugging Face Spaces with GitHub Actions CI/CD
- [Repository](https://github.com/Mahajan-Sachin/MediScan-AI)

### Skill-matcher (Skill-Based Job Recommendation Engine)
Recommends jobs from resume skills and identifies skill gaps using an LLM for resume parsing.
- Handles 75+ jobs and 60+ skills in the seed data
- **Stack:** Django, PostgreSQL, Groq API, Docker
- Deployed on Render with GitHub Actions
- [Repository](https://github.com/Mahajan-Sachin/Skill-matcher)

### Phishing URL Detection
XGBoost classifier for phishing URLs, trained on 11,000+ URLs with 58 features.
- 91.38% accuracy, 0.97 ROC-AUC
- **Stack:** Python, XGBoost, scikit-learn, Streamlit, Docker
- Streamlit app with GitHub Actions CI/CD
- [Repository](https://github.com/Mahajan-Sachin/phishing-detection)

---

## Models

### Llama 3.2 1B Creative Writing (Representation Edited)
A Llama 3.2 1B Instruct model fine-tuned with QLoRA using Unsloth Studio on a 2,000-example creative writing dataset, then studied and edited with representation-level behavioral editing.
- Base model: meta-llama/Llama-3.2-1B-Instruct
- [Hugging Face model page](https://huggingface.co/Sachin903/llama-3.2-1b-creative-writing-ablated)

---

## Tech stack

**Languages:** Python, C++, Go, SQL
**AI and LLM:** LangGraph, LangChain, CrewAI, RAG, ChromaDB, Groq API, QLoRA fine-tuning, TensorFlow, scikit-learn
**Backend:** FastAPI, Django, Redis, PostgreSQL, AsyncIO, JWT authentication, REST APIs
**DevOps:** Docker, GitHub Actions, Azure, Render, Hugging Face Spaces

---

## Connect

- LinkedIn: [linkedin.com/in/sachin-mahajan-cse](https://www.linkedin.com/in/sachin-mahajan-cse)
- X: [@SachinMaha22611](https://x.com/SachinMaha22611)
- Email: sachinmahajan903@gmail.com
