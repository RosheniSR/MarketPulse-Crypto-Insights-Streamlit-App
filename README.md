# MarketPulse-Crypto-Insights-Streamlit-App
Real-time crypto insights dashboard using Streamlit and Binance API
---
---

# MarketPulse - Crypto Insights

MarketPulse is a real-time cryptocurrency analytics dashboard built with Streamlit. It provides live price tracking, sentiment analysis using LLM summarization, and trend visualization using Binance API data.

## Features

- Real-time cryptocurrency price tracking (via Binance API)
- LLM-based news summarization for crypto sentiment
- Interactive price trend charts with Matplotlib
- Modular architecture with clean UI
- Easy-to-use Streamlit interface

## Technologies Used

- Python
- Streamlit
- LangChain
- Llama.cpp (Local LLM)
- Matplotlib
- Binance API
- Requests, Pandas, dotenv

## Folder Structure

MarketPulse/
│
├── app.py                 # Main Streamlit app
├── crypto_core.py         # Core logic (API, plot, LLM integration)
├── requirements.txt       # All dependencies
├── .env                   # Environment variables
└── README.Rmd             # You are here!

## 🔧 Setup Instructions

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/MarketPulse.git
   cd MarketPulse

2. Install dependencies:

   pip install -r requirements.txt

3.  Set your environment variables in a .env file:

   BINANCE_API_KEY=your_api_key_here

4. Run the app:

   streamlit run app.py

## License
This project is licensed under the MIT License.

---

   


