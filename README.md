# QA Analysis in Medical and Legal Domains: A Survey of Data Augmentation in Low-Resource Settings

## 📝 Abstract

Large Language Models (LLMs) have revolutionized Natural Language Processing (NLP), yet their success remains largely confined to high‑resource, general‑purpose domains. Applying LLMs to **low‑resource, domain‑specific QA** is challenging because of limited data, domain drift, and strict terminology constraints. This survey:

1. **Assesses dataset coverage** by comparing specialised QA sets against large‑scale “ParentQA” corpora.
2. **Reviews data‑centric boosts** such as synthetic task generation, retrieval‑augmented generation, and corpus restructuring.
3. **Discusses evaluation & ethics**, including bias, privacy, and scalability.

Code and notebooks are provided for full reproducibility.

---

## 📂 Repository Layout

```
├── codes/                 
│   ├── medical.ipynb     # Experiments in the biomedical domain
│   └── legal.ipynb       # Experiments in the legal domain
```

## 🚀 Quick‑start

```bash
# 1. Clone the repo
$ git clone https://github.com/kentrachmat/survey-da.git
$ cd survey-da

# 2. Create env & install deps (Python ≥3.9)
$ python -m venv .venv && source .venv/bin/activate
$ pip install -r requirements.txt

# 3. Launch the notebooks
$ jupyter lab codes/medical.ipynb
```
 
## 📰 News

- Paper accepted at (Poster Session) [**RJCRI ’25**](https://coria-taln-2025.lis-lab.fr/), Marseille
- Paper accepted at (Poster Session) [**ACL‑SRW ’25**](https://acl2025-srw.github.io/), Vienna

<!-- ## 📚 Citation

If you use this survey in your work, please cite:

TBA -->