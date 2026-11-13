<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:7F00FF,50:E100FF,100:00C9FF&height=190&section=header&text=Chandini%20Pradhan&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=AI%20Engineer%20%C2%B7%20Agentic%20systems%20that%20ship%20with%20measured%20results&descAlignY=58&descSize=16" width="100%"/>
</p>

<p align="center">
  <a href="https://chandni-ai-portfolio.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-Visit-A855F7?style=for-the-badge&logo=vercel&logoColor=white"/></a>
  <a href="https://www.linkedin.com/in/chandni-pradhan-67aa91324/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="mailto:mlexpnew@gmail.com"><img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white"/></a>
  <img src="https://img.shields.io/badge/Open%20to-AI%20Engineer%20roles-22C55E?style=for-the-badge"/>
</p>

Agentic AI Engineer at **Zetheta Algorithms**, Bengaluru. I build AI products for finance, compliance and hiring, and I hold them to one rule: **every claim in a README is a number CI can reproduce.** Each project below ships with a benchmark, a held-out test it was never tuned on, and a quality gate that fails the build if scores drop.

---

## Flagship projects

| Project | Problem it solves | Measured result |
|---|---|---|
| [**InvoiceIQ**](https://github.com/mlexpnew/invoiceiq) | GST invoice checks and GSTR-2B reconciliation before claiming input tax credit | 100% extraction and error detection on 160 invoices · unseen layout: 0 wrong postings, 60/60 sent to LLM fallback |
| [**FairShortlist**](https://github.com/mlexpnew/fairshortlist) | Blind, explainable resume screening for recruiters | Ranking 100% vs 42% TF-IDF and 30% keyword ATS · swapping name and gender changes scores by 0 |
| [**ChurnShield**](https://github.com/mlexpnew/churnshield) | Which bank customers will leave, why, and who to call within budget | ROC-AUC 0.864 on held-out customers · €406,848 retained value vs €111,726 random targeting |
| [**Clausewise**](https://github.com/mlexpnew/clausewise) | HR and policy helpdesk that quotes the exact clause, says "not covered" instead of guessing | 0 HR-only leaks vs 16 for a typical RAG · held-out 82% vs 39% · version-aware |
| [**ClearMIS**](https://github.com/mlexpnew/clearmis) | Monthly MIS from a raw Shopify, Tally or Excel sales export, every number verified | Exact revenue where the raw export is up to 14% too high · right driver 12/12 months · no AI-written code runs |
| [**WorkBridge Compliance AI**](https://github.com/mlexpnew/WorkBridge_Compliance_AI_System) | Anti-money-laundering monitoring for Indian NBFCs, banks and payment companies | 128 alerts vs 35,143 from threshold rules · every planted case caught for the right reason · 46 of top 50 cases real |
| [**BalanceBook**](https://github.com/mlexpnew/balancebook) | Tax-aware portfolio rebalancing for Indian advisers, with adviser approval | Same risk control as band rebalancing · 50% less tax (78% on a held-out market) · 10-year backtest |
| [**TickTrust**](https://github.com/mlexpnew/ticktrust) | Crypto reference prices a payment gateway can safely quote on, with feed-integrity alerts | 0 bad quotes vs 2,870 from a single API on held-out data · 58/58 feed faults caught, 0 false alerts |
| [**ProofPost**](https://github.com/mlexpnew/proofpost) | Real customer reviews to compliant social posts every week (n8n + FastAPI) | 0 problem posts vs 606 with naive reposting · verbatim quotes · DPDP-aware redaction |
| [**RegLens**](https://github.com/mlexpnew/reglens) | Cited answers to SEBI regulation questions | LangGraph planner, analyst and compliance checker · recall@4 100% · eval-gated releases |
| [**ArchitectAI**](https://github.com/mlexpnew/architectai) | Plain-English requirements to a working FastAPI backend | 8/8 generated apps boot · 112/112 CRUD checks pass in CI |
| [**SupportPilot**](https://github.com/mlexpnew/supportpilot-ingestion) | Production ticket triage API | 1M records ingested in 9.4 s · PII redaction · API keys and rate limiting · on-call runbook |

## More work

- [**Product Pricing ETL**](https://github.com/mlexpnew/product-pricing-airflow-etl): daily Airflow pipeline into PostgreSQL, fully Dockerized
- [**Trader Sentiment Analysis**](https://github.com/mlexpnew/primetrade-trader-sentiment-analysis): Fear and Greed regimes vs trader performance · [live dashboard](https://primetrade-trader-sentiment-analysis.streamlit.app/)

---

## How I build

| Practice | Why it matters |
|---|---|
| Benchmarks with a held-out set | A perfect score on data you tuned against proves nothing |
| CI quality gates | Regressions fail the build instead of reaching users |
| Fail closed | Uncertain outputs are blocked or sent for review, never silently accepted |
| Fairness tested, not asserted | Counterfactual swaps and segment metrics, reported in the README |
| Honest limitations | Every project says what it cannot do yet |

## Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,fastapi,postgres,docker,githubactions,git,linux&perline=7" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square&logo=langchain&logoColor=white"/>
  <img src="https://img.shields.io/badge/CrewAI-FF5A50?style=flat-square"/>
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=flat-square&logo=googlegemini&logoColor=white"/>
  <img src="https://img.shields.io/badge/Groq-F55036?style=flat-square"/>
  <img src="https://img.shields.io/badge/ChromaDB-FF6F00?style=flat-square"/>
  <img src="https://img.shields.io/badge/FAISS-0467DF?style=flat-square&logo=meta&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikitlearn&logoColor=white"/>
  <img src="https://img.shields.io/badge/Pydantic-E92063?style=flat-square&logo=pydantic&logoColor=white"/>
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apacheairflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white"/>
</p>

---

<p align="center">
  <b>Open to AI Engineer, Agentic AI and GenAI Engineer roles · Bengaluru or remote · available now</b><br/>
  <a href="https://www.linkedin.com/in/chandni-pradhan-67aa91324/">LinkedIn</a> · <a href="mailto:mlexpnew@gmail.com">Email</a> · <a href="https://chandni-ai-portfolio.vercel.app/">Portfolio</a>
</p>
