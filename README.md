# GenAI-Powered Sales Data Analysis Assistant

Welcome to the **GenAI-Powered Sales Data Analysis Assistant**, a modern, AI-driven business intelligence solution designed to empower non-technical users with seamless access to complex sales data through natural language queries.

***

## 🚀 Project Overview

This project presents a cutting-edge **Generative AI** system that transforms plain English questions into accurate, efficient **SQL queries** for deep sales data exploration and analysis. Built using state-of-the-art AI and modern web technologies, it drastically reduces decision-making time while democratizing access to enterprise data.

***

## 🌟 Key Features

- **Natural Language to SQL Translation**  
  Harnesses OpenAI’s GPT-4o-mini model with *schema-aware prompt engineering* for 92.3% accuracy in converting natural language queries to SQL.

- **Automated Data Preprocessing**  
  Full pipeline for cleaning, standardization, feature engineering, and numeric normalization of raw sales data for better analytical consistency.

- **Interactive Dual-Mode Interface**  
  Combines conversational AI query input with traditional BI dashboards via Streamlit, supporting guided exploration and free-form querying.

- **Real-Time Visualization**  
  Dynamic charts (bar, line, pie, and tables) generated with Plotly, offering intuitive, interactive insights with filtering and customization.

- **Fast & Scalable Backend**  
  Powered by FastAPI with robust error handling, caching, and optimized MySQL database integration ensuring sub-10-second response times.

- **Seamless BI Integration**  
  Export analytics results easily to Power BI and other platforms via CSV and direct database connections.

***

## 🎯 Project Impact

- **Accelerates Decision-Making**  
  Cuts report generation time from 24–48 hours to just 12 minutes — a 96% improvement in agility.

- **Boosts User Adoption**  
  Achieved 73% user adoption in the first week, with 91% of queries resolved without IT help.

- **Enhances Analytical Efficiency**  
  Reduces data analyst workload by 67%, letting experts focus on advanced insights rather than routine queries.

- **Delivers High User Satisfaction**  
  Net Promoter Score of 62 and an overall 4.3/5 customer satisfaction rating highlight exceptional user experience.

***

## 🛠️ Technology Stack

| Layer            | Technology                      |
|------------------|--------------------------------|
| Backend          | Python 3.8+, FastAPI, MySQL    |
| Frontend         | Streamlit, Plotly               |
| AI Integration   | OpenAI GPT-4o-mini API          |
| Data Processing  | Pandas, Scikit-learn (StandardScaler) |

***

## 🏗️ System Architecture

The system follows a **three-tier architecture** for robust performance and scalability:

- **Data Tier:** Optimized MySQL star schema with strong indexing and connection pooling.
- **Application Tier:** FastAPI REST layer with real-time schema introspection and dynamic prompt construction.
- **Presentation Tier:** Streamlit frontend offering both conversational AI and traditional BI dashboards with interactive visualizations.

***

## 🔍 Evaluation Highlights

| Metric                          | Result                     | Target / Benchmark            |
|--------------------------------|----------------------------|------------------------------|
| SQL Generation Accuracy         | 92.3%                      | Industry Average: 77-85%      |
| API Response Time               | 1.3 seconds                |  60%                       |
| Customer Satisfaction Score     | 4.3 / 5                    | > 4.0                       |
| Net Promoter Score              | 62                         | > 50                        |
| Self-Service Query Success Rate | 91%                        | Industry Standard: 60-70%    |
| Power BI Integration Success    | 97.2%                      | —                            |

***

## 💡 Innovation & Contributions

- Real-time dynamic schema awareness for up-to-date AI query generation.
- Hybrid interface combining AI conversational querying and traditional dashboards.
- Intelligent chart recommendation engine rated 86.2% by end users.
- Cost-efficient design enabling advanced BI capabilities at $0.12 per analytical session versus costly traditional BI licenses.

***

## ⚠️ Limitations & Future Directions

- Improvements planned for complex multi-table query accuracy (currently 8.7% failure rate).
- Enhancements in multi-turn conversational context preservation (currently 85.7% success).
- Enterprise-grade security and governance additions including SSO, RBAC, and data compliance.
- Expansion with multimodal AI, voice-based querying, real-time streaming, and predictive analytics.

***

## 💼 Who Should Use This?

- Business analysts craving faster, simpler data access.
- Sales and marketing managers looking for quick, on-demand insights.
- Data teams aiming to reduce support demands and empower broader workforce.
- Organizations that want to democratize data with minimal technical barriers.

***

## 📂 Repository Content

- **Data Preprocessing:** ETL pipeline scripts and normalization workflows.
- **Backend API:** FastAPI services with schema introspection and query generation logic.
- **Frontend UI:** Streamlit app source with dual-mode interface and interactive charts.
- **Documentation:** API specs, system architecture diagrams, and user guides.
- **Evaluation Reports:** Detailed performance metrics and business impact analysis.

***

## 🚀 Getting Started

To explore the power of natural language-driven BI for your sales dataset, simply deploy the integrated FastAPI + Streamlit app and start asking business questions in plain English — get SQL-powered insights delivered instantly!

***

Unlock the full potential of your sales data with the GenAI-Powered Sales Data Analysis Assistant — where enterprise analytics meets AI simplicity.

***

*For more details, refer to the complete project report.*

[1] https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/86641044/f1b13568-968c-443f-8340-fc1456a7753f/NL2SQL-Data-Explorer.pdf
