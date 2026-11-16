# Vijay Nagargoje — Portfolio

**AI Engineer (primary) | Data Scientist (secondary)**

Personal portfolio of **Vijay Bhagwat Nagargoje**, a final-year B.Tech student in Artificial Intelligence & Data Science at Maharashtra Institute of Technology, Chhatrapati Sambhajinagar.

**Portfolio:** [vijaynagargoje.me](https://vijaynagargoje.me/)  
**GitHub:** [AI-Vijay](https://github.com/AI-Vijay)  
**LinkedIn:** [vijay-nagargoje](https://linkedin.com/in/vijay-nagargoje)

## About

I focus on practical AI engineering projects, including Generative AI, retrieval-augmented generation (RAG), document intelligence, machine learning, and natural-language processing. Data Science is my second career focus, with interests in predictive analytics, data pipelines, and business intelligence.

## Featured Project: FinRag

### [FinRag — AI-Powered Financial Document Intelligence](https://github.com/AI-Vijay/FinRag)

FinRag is a FastAPI-based platform for exploring company financial reports. It includes:

- Financial PDF ingestion and conversion to Markdown
- Report text chunking and Azure OpenAI embeddings
- Azure AI Search indexing for report content and vectors
- AI-assisted financial questions and answers
- Financial metric extraction and PostgreSQL persistence
- An interactive financial intelligence dashboard

**Stack:** Python, FastAPI, Azure OpenAI, Azure AI Search, PostgreSQL, Jinja2, HTML, CSS, JavaScript.

The current report retrieval flow uses Azure AI Search text search; embeddings are generated and stored during ingestion. See the [FinRag repository](https://github.com/AI-Vijay/FinRag) for implementation details and setup instructions.

## Other Projects

- [Real-Time Weather ETL Pipeline & Power BI Dashboard](https://github.com/AI-Vijay/PowerBI-Weather-ETL-Dashboard) — weather API ingestion, data modeling, Power Query and DAX.
- [Air Quality Monitoring Using Python](https://github.com/AI-Vijay/AQM-using-Python) — ESP32 sensor readings, REST API integration and Streamlit monitoring.
- Smart Attendance System — BLE and facial recognition; IoT Arena Hackathon winner.
- NLP and ML experiments — summarization, job-requirement prediction, fake-news classification and other applications.

## Skills

| Focus | Technologies |
| --- | --- |
| AI Engineering | Generative AI, RAG, Azure OpenAI, Azure AI Search, prompt engineering, embeddings |
| Backend and data | Python, FastAPI, PostgreSQL, SQL, REST APIs |
| Machine Learning and NLP | Scikit-learn, Transformers, BART, PEGASUS, T5, NLP, OCR |
| Analytics | Pandas, NumPy, Power BI, Power Query, DAX, Snowflake |
| Tools | Docker, Git, GitHub, Linux, Azure |

## Portfolio Website

This repository contains a static HTML/CSS/JavaScript website designed to work with GitHub Pages. No build process is required.

```text
Vijay_Nagargoje.github.io-main/
├── index.html           # Website and responsive styles/scripts
├── CNAME                # Custom domain configuration
├── Readme.md            # Repository documentation
└── Vijay-Resume.pdf     # Existing resume (not modified in this update)
```

### Run locally

Open `index.html` in your browser, or run a small static server in this directory:

```bash
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

### Publish

Copy the changed files into the existing GitHub Pages repository and push to its configured branch. Keep `CNAME` unchanged if the custom domain remains active. In repository **Settings → Pages**, verify the branch and folder match your repository's setup.

## Contact

- **Email:** [nagargojevijay24@gmail.com](mailto:nagargojevijay24@gmail.com)
- **LinkedIn:** [Vijay Nagargoje](https://linkedin.com/in/vijay-nagargoje)
- **GitHub:** [AI-Vijay](https://github.com/AI-Vijay)

---

*Developed and maintained by Vijay Nagargoje.*
