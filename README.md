🪙 Crypto Automation Project
- This project collects and analyzes live cryptocurrency data using the CoinMarketCap API, 
storing it over time to track price movements, volatility, and market trends.

📌 What I Did
✅ API Automation

- Connected to the CoinMarketCap API using Python (requests, json, pandas).

- Collected data on the top 100 cryptocurrencies by market cap.

- Scheduled repeated API calls and stored timestamped data.

🧹 Data Wrangling

- Flattened complex JSON structures using pd.json_normalize().

- Added a live timestamp to each snapshot to allow time-based analysis.

- Saved results to a CSV file, appending new data while avoiding duplicates.

📊 Exploratory Data Analysis (EDA)

- Queried top coins like Bitcoin and Ethereum.

- Visualized price changes over time using seaborn and matplotlib.

- Compared 24h, 7d, and 30d percent changes to see market momentum.

- Calculated price volatility to understand which coins are most unstable.

