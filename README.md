# 🤖 Autonomous AI Business Engine

A multi-agent AI architecture built with **CrewAI** designed to handle high-value operational and financial workflows: **Business Acquisition Due Diligence** and **Automated Service Estimating**.# 🤖 Autonomous AI Business Engine

A multi-agent AI architecture built with **CrewAI** designed for high-value financial and operational workflows: **M&A Business Acquisition Due Diligence** and **Automated Service Estimating**.# 🤖 Autonomous AI Business Engine

A multi-agent AI architecture built with **CrewAI** designed for high-value financial and operational workflows: **M&A Business Acquisition Due Diligence** and **Automated Service Estimating**.

---

## 📂 Repository Structure

```text
ai-business-engine/
├── deal_sourcing_agent/    # CrewAI M&A pipeline for auditing & scoring business targets
│   ├── main.py             # Multi-agent scraper, financial auditor, & deal scorer
│   └── requirements.txt
├── estimator_agent/        # Autonomous service & project estimating agent
│   └── main.py             # Lead qualification, quote calculation, & scheduling workflow
├── assets/                 # Execution screenshots and workflow proof
└── README.md
# Clone repository
git clone [https://github.com/YOUR_USERNAME/ai-business-engine.git](https://github.com/YOUR_USERNAME/ai-business-engine.git)
cd ai-business-engine

# Install dependencies
pip install -r requirements.txt

# Set Environment Variables
export OPENAI_API_KEY="your-openai-key"

# Run Deal Sourcing Agent Pipeline
python deal_sourcing_agent/main.py

# Run Estimator Agent Pipeline
python estimator_agent/main.py
The Autonomous AI Business Engine is a dual-pipeline system built on CrewAI that bridges autonomous multi-agent orchestration with real-world business monetization and operational efficiency.

The repository houses two primary production workflows:

1. M&A Deal Sourcing & Financial Auditor
An autonomous multi-agent system built to evaluate small business acquisition targets (Private Equity / Search Fund model):
- Deal Scraper Agent: Ingests unstructured marketplace listings and broker disclosures from URLs using web scraping tools.
- Financial Auditor Agent: Audits seller disclosures, identifies non-recurring owner add-backs, and normalizes cash flow into True SDE (Seller's Discretionary Earnings) and realistic EBITDA multiples.
- Operations Auditor Agent: Scans business operational notes to identify paper-based bottlenecks and calculates post-acquisition margin expansion potential from AI integration.
- Deal Principal Agent: Synthesizes financial and operational metrics into an automated 0-100 Deal Score and investment thesis.

2. Closed-Loop Service & Project Estimator
An autonomous intake and quoting pipeline designed for contractors and local service businesses:
- Lead Intake & Parameter Extraction: Parses incoming customer inquiry data, dimensions, and scope requirements.
- Automated Costing Engine: Applies standardized pricing rules to estimate material, labor, and profit margins.
- CRM & Calendar Integration: Qualifies leads, prepares instant formal estimates, and schedules site visits directly into the booking funnel.

Tech Stack:
- Framework: CrewAI (Sequential & Stateful Agent Orchestration)
- Language: Python 3.10+
- Schema Validation: Pydantic (Strict JSON & Type Enforcement)
- Tools: CrewAI ScrapeWebsiteTool, LangChain, OpenAI GPT-4o
