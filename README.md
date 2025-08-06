# 🧠 On-Chain Portfolio GPT+

## 💡 AI-Powered Web3 Portfolio Advisor

> A real-time AI agent that analyzes your Ethereum wallet, evaluates your portfolio health, gives personalized crypto investment suggestions, and alerts you to risks — all by just entering your wallet address.

---

## 🚀 Why This Project?

Crypto users often hold assets across tokens but lack a clear understanding of:
- Their overall portfolio performance
- How diversified or risky their holdings are
- When to rebalance, and what to rebalance into

**On-Chain Portfolio GPT+** combines **blockchain data**, **real-time prices**, and **AI-powered reasoning** to offer users a smarter way to manage crypto assets — like a financial advisor for Web3.

---

## 🧩 Key Features

| Feature | Description |
|--------|-------------|
| 🔗 **Live Blockchain Data** | Fetches token balances from any Ethereum wallet |
| 💵 **Real-Time Price Analysis** | Uses live market data to calculate total USD value |
| 🤖 **GPT-Powered Portfolio Insights** | AI summarizes your portfolio, detects risks, and gives tailored suggestions |
| 📊 **Portfolio Health Score** | AI assigns a score (0–100) based on diversification and exposure |
| 🧠 **Investor Personality Type** | Classifies you (e.g. "Degen", "Hodler", "Stable Strategist") |
| ⚖️ **Rebalancing Suggestions** | Intelligent recommendations to reduce risk or increase growth |
| 🔔 **Smart Alerts (Optional)** | Detects dangerous concentrations or market volatility |
| 📉 **Sentiment Analysis** | Shows market sentiment of your major holdings using news & price action |
| 🧾 **Tax Estimation** | Simulated gain/loss estimate based on wallet age and token history |

---

## 🧱 Tech Stack

| Layer | Tool |
|------|------|
| 🧠 AI Agent | OpenAI GPT-4 API (or Ollama for local LLM) |
| 🔗 Blockchain Data | Covalent API / Moralis / Alchemy |
| 💰 Token Prices | CoinGecko API |
| 🐍 Backend | Python (Flask / CLI) |
| 🖥️ UI (Optional) | React.js / Streamlit |
| 📈 Charts | Plotly or Chart.js |

---

## 🛠️ How It Works (Architecture)

User enters Wallet Address
↓
🛰️ Covalent API → Token Balances
↓
📈 CoinGecko API → Live Prices
↓
🧮 Python → Total Value, % Split, Categories
↓
🤖 GPT → Summarized Advice + Scoring
↓
🖥️ CLI/Web UI → Display + Follow-up Chat


---

## ✅ Example Output

> **Wallet:** `0x1234...abcd`  
> **Total Value:** $7,450  
> **Top Holding:** ETH (75%)  
> **Portfolio Health Score:** 78/100  
> **Personality:** Balanced Strategist  
> **AI Suggestion:** "Consider reducing your ETH exposure slightly and allocating into DeFi blue chips like UNI or AAVE."

---

## 📦 How to Run (CLI Version)

```bash
# 1. Clone repo
git clone https://github.com/yourname/onchain-portfolio-gpt.git
cd onchain-portfolio-gpt

# 2. Install dependencies
pip install -r requirements.txt

# 3. Add your API keys
# .env file: COVALENT_API_KEY, COINGECKO_URL, OPENAI_API_KEY

# 4. Run the CLI tool
python portfolio_analyzer.py

[Your Name] — AI Agent + Prompt Design

[Member 2] — Blockchain API Integration

[Member 3] — UI/UX & Frontend

[Member 4] — Project Pitch + Deployment
