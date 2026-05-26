# AI Financial Data Agent: Text-to-SQL & Automated Storytelling
> **Level N5 (Master 2) Project | Data Engineering & Generative AI**

## Overview
This project features an intelligent Data Assistant capable of bridging the gap between natural language and complex financial databases. Using **LangChain** and **Llama 3.3 (Groq)**, the agent translates human questions into optimized SQL queries, executes them on a **PostgreSQL** database, and provides narrative financial insights.

## Key Features
- **Autonomous Text-to-SQL:** Converts complex questions (e.g., "Which index had the highest volume in April 2024?") into valid SQL.
- **Self-Correction (Chain of Thought):** The agent identifies schema errors in real-time and automatically rewrites joins to find the correct data.
- **Automated Storytelling:** Beyond raw numbers, the agent acts as a Senior Financial Analyst, explaining economic phenomena like inflation-driven price records or market liquidity risks.
- **High Performance:** Powered by the **Groq LPU Inference Engine** for near-instant response times.

## Tech Stack
- **Framework:** LangChain (SQL Agent & Tool Calling)
- **LLM:** Meta Llama 3.3-70B via Groq API
- **Database:** PostgreSQL (Star Schema: Fact & Dimension tables)
- **Language:** Python 3.10+
- **Libraries:** SQLAlchemy, Pandas, Psycopg2

## Proof of Concept
### 1. Self-Correction Demo

<img width="1142" height="770" alt="image" src="https://github.com/user-attachments/assets/7f183660-9980-4971-8c7f-dccefad4efe6" />


### 2. Strategic Insights

<img width="1101" height="378" alt="image" src="https://github.com/user-attachments/assets/b4517707-19b1-4470-8557-49818a44d64f" />


## Business Impact
- **80% Reduction** in time spent by non-technical managers to access data.
- **Zero-Code Analytics:** Empowers decision-makers to query live data without knowing SQL.
- **Contextual Intelligence:** Transforms raw logs into actionable strategic recommendations.
