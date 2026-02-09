# 🚀 CRYPTO ANALYSIS AI ASSISTANT 🚀

## Project Description

CRYPTO ANALYSIS AI ASSISTANT is an intelligent assistant for cryptocurrency analysis that leverages LLMs (Large Language Models) and various tools to provide up-to-date information and analytics on the cryptocurrency market.

## Features

- 📊 **Cryptocurrency Price Analysis** - fetching current prices and historical data
- 🔥 **Trend Tracking** - analyzing trending coins on the market
- 🔍 **Information Search** - searching for cryptocurrencies by name or symbol
- 📈 **DeFi Protocol Analysis** - retrieving TVL and protocol performance data
- 💧 **Liquidity Analysis** - exploring liquidity pools across various DEXs
- 📑 **Historical Analysis** - studying historical token data
- 👥 **Holder Analysis** - token distribution among holders
- 📰 **Crypto News** - fetching the latest news (in development)

## Requirements and Installation

### Technical Requirements
- Python 3.9+
- API access: OpenAI, CoinGecko, Bitquery

### Installation

```bash
# Clone the repository
git clone https://github.com/yourusername/crypto_agent.git
cd crypto_agent

# Create a virtual environment
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

## Environment Setup

1. Create a `.env` file in the project root directory:

```
OPENAI_API_KEY=your_openai_api_key
COINGECKO_API_KEY=your_coingecko_api_key
BITQUERY_API_KEY=your_bitquery_api_key
```

2. Some features may work without API keys, but with limitations.

## Usage

Run the main script:

```bash
python src/main.py
```

### Example Queries

- "What is the current price of Bitcoin?"
- "Show me trending cryptocurrencies"
- "Analyze the Uniswap protocol"
- "Find information about the PEPE token"
- "Analyze Ethereum historical data for the last 90 days"
- "Explore SHIB holder distribution"

## Project Structure

```
crypto_agent/
├── src/
│   ├── config/              # Configuration and settings
│   ├── core/                # Core logic and agents
│   ├── models/              # Data models
│   ├── tools/               # Cryptocurrency analysis tools
│   ├── ui/                  # User interface
│   └── main.py              # Main application file
├── test/                    # Tests and examples
├── .env                     # Environment variables (do not commit!)
├── .gitignore               # Ignored files
├── requirements.txt         # Project dependencies
└── README.md                # Documentation
```

## Technologies and Tools

- **LangChain & LangGraph** - building LLM chains and graphs
- **OpenAI API** - natural language processing
- **Rich** - beautiful text-based interface
- **CoinGecko API** - cryptocurrency data
- **Bitquery API** - blockchain data analysis
- **DeFiLlama API** - DeFi protocol data
- **GeckoTerminal API** - liquidity pool analysis

## Security

⚠️ **Important:** Never commit files containing API keys or other secrets. Use environment variables or files listed in `.gitignore`.

## License

This project is distributed under the MIT License.

## Roadmap

- Integration with new data sources
- Improved analysis and recommendations
- Web interface and API for convenient access
- Extended forecasting capabilities

---

Made with 💜 for crypto enthusiasts and analysts.
