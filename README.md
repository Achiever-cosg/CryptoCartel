<div align="center">

# Crytpo Cartel

A React.js application that fetches and displays the current market cap and 24-hour market cap change of the top cryptocurrencies

</div>

## 🚀 Features

- Displays real-time market cap of top cryptocurrencies
- Shows 24-hour percentage change in market cap
- Mobile-friendly UI
- Uses CoinGecko API for crypto data
- React Hooks for state management

## 🛠️ Tech Stack

- React.js (Frontend framework)
- CoinGecko API (Crypto data source)
- CSS/Tailwind (For styling)

## 📦 Installation

1. Clone the repository:
```shell
git clone https://github.com/Achiever-cosg/CryptoCartel
cd CryptoCartel
```

2. Install dependencies:
```shell
npm install
```

3. Start the development server:
```shell
npm start
```

4. Open http://localhost:3000/ in your browser.

## 🔄 How It Works

- Fetches real-time market cap data from CoinGecko API
- Displays the top cryptocurrencies ranked by market cap
- Shows the percentage change in market cap over the last 24 hours

## 📡 API Used

We use the CoinGecko API to fetch crypto data:

### Example API Request:
```js
GET https://api.coingecko.com/api/v3/coins/markets?vs_currency=usd&order=market_cap_desc
```

## 🛠 Deployment

To deploy the application, use Vercel, Netlify, or GitHub Pages:

### Deploy with Vercel
```shell
npm build
vercel
```

## 📌 TODOs / Future Enhancements

- ✅ Add search functionality for specific coins
- ✅ Implement live updates every few seconds
- 🚀 Support for more fiat currencies
- 🚀 Add historical market cap trends

## 🙌 Contributing

1. Fork this repository
2. Create a new branch (feature-branch)
3. Commit your changes (git commit -m 'Add new feature')
4. Push to your branch (git push origin feature-branch)
5. Create a Pull Request 🚀