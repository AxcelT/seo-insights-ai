# SEO Insights AI

An AI-driven SEO optimization platform tailored for insurance and digital marketing. This tool audits websites, detects technical and content-related SEO issues, and recommends AI-generated improvements using models like OpenAI.

---

## 🚀 Features

- 🔍 Full SEO audit (keywords, meta tags, heading structure, broken links)
- 📊 Dashboard displaying performance metrics
- 🧠 AI-generated meta descriptions and content suggestions (via OpenAI/Gemini)
- 📈 Keyword and topic trend suggestions via Google Search Console
- ⚙️ API integrations (Search Console, SEMrush, Ahrefs - optional)

---

## 🛠️ Tech Stack

- **Frontend**: HTML/CSS/JavaScript (or React)
- **Backend**: Python (FastAPI or Flask)
- **AI/ML**: OpenAI API, Scikit-learn, TensorFlow (optional)
- **SEO Data**: Google Search Console API
- **Database**: SQLite or PostgreSQL

---

## 🔧 Setup & Installation

```bash
# Clone the repo
git clone https://github.com/yourusername/seo-insights-ai
cd seo-insights-ai

# Create virtual environment
python -m venv venv
source venv/bin/activate  # or .\venv\Scripts\activate on Windows

# Install requirements
pip install -r requirements.txt

# Run the app (FastAPI example)
uvicorn app.main:app --reload
