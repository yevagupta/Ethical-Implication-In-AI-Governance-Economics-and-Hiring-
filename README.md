# Ethical Implications of AI in Finance, Economics, Governance & Hiring

This research project investigates the ethical implications of Artificial Intelligence (AI) in critical sectors — including finance, economics, governance, and hiring — by combining academic literature analysis, social media sentiment mining, and policy evaluation.

---

###  Objectives

- Identify recurring ethical concerns in AI implementation across public and private domains
- Understand how public discourse aligns with academic and institutional insights
- Examine India’s evolving regulatory response to sector-specific AI risks

---

### 🧪 Methodology

#### 1. Thematic Literature Review
- Analyzed 200+ academic papers using **Latent Dirichlet Allocation (LDA)**
- Conducted a thematic breakdown into four core concerns:
  - **Fairness & Bias**
  - **Transparency & Explainability**
  - **Security & Privacy**
  - **Human Oversight & Autonomy**
- Mapped themes to real-world AI use-cases: credit scoring, loan approvals, automated hiring, and black-box algorithms in governance

#### 2.  Public Discourse & Sentiment Analysis
- Scraped and analyzed 1000+ Reddit posts using:
  - `PRAW` for data collection
  - `NLTK` for preprocessing
  - `VADER` for sentiment classification
- Applied **LDA** to 250+ negatively classified posts to extract five dominant user concerns:
  - AI governance & government trust
  - Privacy & Big Tech
  - AI collapse & human risk
  - Model safety & OpenAI criticism
  - Control over personal data

#### 3. 🇮🇳 Regulatory Policy Evaluation
- Assessed India’s AI governance landscape
- Highlighted the RBI’s formation of the **FREE-AI** committee as a financial-sector milestone
- Compared India’s current efforts to the **EU AI Act** and **UK's CDEI**, emphasizing the need for a unified, risk-based AI law


### Tools & Technologies

- Python: `NLTK`, `VADER`, `gensim`, `PRAW`, `matplotlib`, `seaborn`  
- NLP: **Latent Dirichlet Allocation (LDA)**, VADER Sentiment Analysis  
- Data Sources: Reddit (via PRAW), Scopus-indexed academic literature, RBI & policy documents


