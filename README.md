# Hi, I'm Dimitrios Diamantidis

**Data & ML Engineer. I build data pipelines and LLM powered applications.**

I take problems from raw, messy data through to working systems. Pipelines that move and model data, machine learning models, and apps built on top of large language models. The part I care about most is making sure a result is actually correct before anyone trusts it.

Based in the Netherlands. Originally from Greece.
MSc in Applied Data Science, Utrecht University.

[LinkedIn](https://www.linkedin.com/in/dimitrios-diamantidis-8a9346228/) · dimitridiamantidi@gmail.com

## Tools

**Languages:** Python, SQL, R
**ML:** scikit-learn, XGBoost, PyTorch (Graph Neural Networks)
**LLM and AI:** LangChain, OpenAI API, RAG, prompt engineering, retrieval
**Data engineering:** ETL and ELT pipelines, Airflow, BigQuery, dimensional modeling
**Cloud and tooling:** GCP (BigQuery, Vertex AI), Docker, Streamlit, Git

## Projects

### Biomedical RAG with evaluation. Question answering over PubMed papers
A retrieval augmented generation system that answers questions about biomedical literature, grounded in real PubMed abstracts. It retrieves the most relevant passages, then answers using only those. The focus is on measuring whether it works: retrieval metrics (hit@k, MRR) and answer checks for keyword recall and groundedness, to catch hallucination.
`RAG · sentence-transformers · FAISS · OpenAI`
[View project](https://github.com/dimitrisdiam/biomedical-rag)

### Company SQL Chatbot. Natural language questions over a database
An assistant that connects an OpenAI model to a SQLite company database through a LangChain SQL agent. You ask a question in plain English, it writes and runs the SQL, and returns the answer. It also has an evaluation script that measures how often the answers are correct.
`LangChain · OpenAI · SQLite · Streamlit`
[View project](https://github.com/dimitrisdiam/company-chatbot-sql)

### GreenPlates. Food waste analytics pipeline
An end to end SQL pipeline on restaurant IoT data, built in BigQuery. It covers ingestion, a dimensional model, and KPIs for tracking waste. Shows how I structure a warehouse and turn raw events into metrics people can act on.
`BigQuery · dimensional modeling · KPIs`
[View project](https://github.com/dimitrisdiam/greenplates-food-waste-analytics)

### Master's Thesis. Graph Neural Networks for fertility prediction
Research applying Graph Neural Networks to predict fertility intentions from social network structure. It covers the modeling, the network analysis, and how social influence was represented in the graph.
`PyTorch · GNNs · network analysis`
[View project](https://github.com/dimitrisdiam/Optimizing-Graph-Neural-Networks-for-Predicting-Fertility-Intentions-in-Social-Networks)

### Predicting Student Scores. Supervised regression
A regression project in a competition style format. Feature engineering plus model comparison across Ridge and XGBoost, tuned to reduce error on a held out set.
`scikit-learn · XGBoost · feature engineering`
[View project](https://github.com/dimitrisdiam/Supervised-Learning-Competition)

### Real Estate Price Tracker. Web scraping and automation
A scraper that collects listing prices and writes them to Google Sheets on a schedule. A small, working data ingestion tool rather than a one off script.
`Python · Selenium · automation`
[View project](https://github.com/dimitrisdiam/Real_Estate_Scraping)

## What I'm working on now

- Stricter evaluation for the biomedical RAG project, using an LLM as a judge and adding a reranker
- Combining LangChain with PySpark for querying larger datasets
- Dashboards for sustainability analytics

## Get in touch

If you are hiring or want to talk about data and ML, reach out.

dimitridiamantidi@gmail.com · [LinkedIn](https://www.linkedin.com/in/dimitrios-diamantidis-8a9346228/)
