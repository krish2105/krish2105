<!-- Profile README for github.com/krish2105 Requires two files committed alongside this one: assets/header.svg assets/pipeline.svg Both are animated. GitHub renders SMIL animation inside <img>, so they move on the live profile. Repo links below use current repo names. GitHub auto-redirects after a rename, so these keep working once you rename to project-wafa, wasl-ai etc. --> <p align="center"> <img src="https://raw.githubusercontent.com/krish2105/krish2105/main/assets/header.svg?v=4" alt="Krishna Mathur, applied AI and machine learning for business decisions, Dubai UAE" width="100%"> </p> <p align="center"> <a href="https://portolio-krishna.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-0F172A?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio"></a> <a href="https://www.linkedin.com/in/krishnamathurmay/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a> <a href="mailto:krishnamathur008@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a> </p> <p align="center"> <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3400&pause=900&color=38BDF8&center=true&vCenter=true&width=700&lines=Agentic+RAG+over+UAE+public+data;Multilingual+NLP+for+customer+operations;Risk%2C+fraud+and+capital+decision+systems" alt="Agentic RAG, multilingual NLP, risk and capital decision systems"> </p>
What I build

I build machine learning systems that sit inside a business decision rather than next to it. The pattern is usually the same. Take operational data that nobody has cleaned, build something that is honest about what it does not know, then wrap it in an interface where a non-technical reviewer can approve, edit or reject what the system proposed.

Three lines of work:

Agentic retrieval and reasoning systems over public and enterprise data, where the answer has to be traceable to a source rather than asserted.
Multilingual NLP for customer operations, where the same complaint arrives in English, Arabic, Hindi and Tagalog and still has to be triaged consistently.
Risk, fraud and capital decision models for finance teams who need a number they can defend in a room full of people who did not build the model.

The constraint I design around is what the system must not do. Nationality excluded as a training feature and audited. Destructive SQL impossible by construction. Refusals published rather than hidden. Human approval before anything reaches a customer.

<p align="center"> <img src="https://raw.githubusercontent.com/krish2105/krish2105/main/assets/pipeline.svg?v=4" alt="How I build: messy data, trained model, guardrails, human approval, logged decision" width="100%"> </p>
Who I build it for
Banks and fintechs that need churn, fraud and retention scoring they can explain to a regulator, not just to a data scientist.
Finance and strategy functions that need a model translated back into a number, a recommendation and a stated confidence level.
Government and public-sector teams working with open data where answers must cite their source.
Operators in the GCC building bilingual, Gulf-specific systems where off-the-shelf English-only tooling breaks.

Based in Dubai, completing an MSc in AI for Business at SP Jain School of Global Management.

Selected work
Project	What it does	Stack
Masar AI	Agentic RAG over Dubai RTA open data. A 14-agent LangGraph orchestration with a corrective retrieval loop, hybrid search across pgvector and Postgres full-text, Text-to-SQL, and deterministic fare arithmetic so money is never computed by a language model. Bilingual English and Arabic.	Python, LangGraph, pgvector, PostgreSQL, FastAPI, Next.js
Project Wafa — live demo →	Retention intelligence for a UAE bank. Triages multilingual customer messages into churn risk, then drafts a retention action a human must approve. Fairness audited, nationality excluded as a feature, every decision written to an append-only log.	Python, scikit-learn, DistilBERT, Streamlit
Ashraq	Capital budgeting for a 1.2 MWp rooftop solar investment for a Dubai cold-chain operator, compared across four ownership structures. Deterministic finance engine, so every figure traces back to a stated assumption.	TypeScript, Next.js, financial modelling
Wasl AI	Scores how legible a business is to AI agents on a 100-point index, then generates the MCP server that makes it legible. Cited evidence for every score, and refusals published rather than silently dropped.	Python, MCP, FastAPI, Next.js
Learners WinBack Engine	Ranks lapsed education leads by expected recoverable revenue rather than engagement, and blocks the ones that must not be contacted.	TypeScript, Next.js, Tailwind
SQLGuard	Dialect-aware safety guard for LLM-generated SQL. Makes destructive and exfiltrating queries impossible by construction rather than by prompt.	Python, sqlglot
Tech stack

Languages

Python, TypeScript, SQL

Agentic systems and retrieval

LangGraph multi-agent orchestration, corrective RAG loops
Hybrid retrieval: pgvector dense search plus Postgres full-text
Text-to-SQL with schema, structural and semantic guardrails
MCP server design

Machine learning

scikit-learn, TensorFlow, Keras
LSTM, GRU, 1D-CNN, autoencoders for sequence and anomaly work
Class imbalance handling, cross validation, fairness auditing

NLP

Hugging Face Transformers, DistilBERT, spaCy
TF-IDF and classical baselines, NER, zero-shot classification
Bilingual and multilingual pipelines across English, Arabic, Hindi and Tagalog

Apps and delivery

Next.js 15, React 19, Tailwind, FastAPI, Streamlit
PostgreSQL, AWS RDS, DynamoDB, EMR, PySpark
Git, GitHub Actions, Jupyter

Business layer

DCF, capital budgeting, unit economics
Power BI, Excel financial modelling
Currently
Building an evaluation layer for Project Wafa: a hand-labelled multilingual test set, a published baseline comparison, and an error analysis of what the model gets wrong.
Deploying Masar AI and Ashraq to public URLs.
Open to AI/ML Analyst, Business Analyst and AI Associate roles in the UAE.
Activity
<p align="center"> <img src="https://github-readme-stats-rp5q.vercel.app/api?username=krish2105&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0B1220&title_color=38BDF8&icon_color=2DD4BF&v=4" alt="GitHub stats" height="165"> <img src="https://github-readme-stats-rp5q.vercel.app/api/top-langs/?username=krish2105&layout=compact&langs_count=6&theme=tokyonight&hide_border=true&bg_color=0B1220&title_color=38BDF8&v=4" alt="Top languages" height="165"> </p> <p align="center"> <img src="https://github-readme-activity-graph.vercel.app/graph?username=krish2105&theme=tokyo-night&hide_border=true&bg_color=0B1220&color=E2E8F0&line=38BDF8&point=F59E0B&area=true" alt="Contribution activity graph" width="100%"> </p> <p align="center"> <img src="https://raw.githubusercontent.com/krish2105/krish2105/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation" width="100%"> </p>
Get in touch

The fastest way to reach me is email: krishnamathur008@gmail.com

I reply to everything, and I am happy to walk through the code or the reasoning behind any project above.

<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" alt="" width="100%">
