# Stock Vision
A comprehensive financial dashboard that consolidates stock market data, portfolio management, and social sentiment analysis into a single, user-friendly interface for traders and investors.

## Features
- **Portfolio Management**: Track your stock investments with real-time price updates, percentage changes, and total portfolio value calculations
- **Custom Watchlist**: Monitor favorite stocks with live price feeds and percentage change indicators
- **Interactive Stock Charts**: Visualize historical price trends with dynamic Highcharts integration and real-time stock information
- **Real-Time News Integration**: Stay informed with personalized news feeds for specific stock tickers powered by Bing News API
- **Reddit Sentiment Analysis**: Discover relevant Reddit discussions with customizable sorting (Trending, Most Upvoted, Most Recent)
- **Persistent Data Storage**: Automatic saving of portfolio and watchlist data using localStorage
- **Stock Search & Selection**: Quick ticker search functionality with input validation and error handling

## Technologies and Languages Used
**Languages**: JavaScript, HTML, CSS, JSX  
**Libraries/Frameworks**: React, Axios, Highcharts  
**APIs**: Twelve Data API, Bing News API, Reddit API

## How to Run the Project

```bash
npm install
npm start
```

This will:
- Launch the dashboard
- Load saved portfolio and watchlist from browser storage
- Enable real-time stock price tracking
- Fetch news and Reddit discussions for selected tickers
- Display interactive charts with historical data
- Allow adding/removing stocks from portfolio and watchlist

## Dependencies

Install required packages:

```bash
npm install
```

Required packages:
- react >= 18.3.1
- react-dom >= 18.3.1
- axios >= 1.7.9
- highcharts >= 11.4.8
- highcharts-react-official >= 3.2.1
- chart.js >= 4.4.7
- react-chartjs-2 >= 5.3.0
- react-scripts >= 5.0.1

![Stock Vision Dashboard](https://github.com/user-attachments/assets/c66eed0a-315a-470c-b6ee-931e38821679)
![Portfolio Management](https://github.com/user-attachments/assets/e08e9e1a-ebaa-49f3-9f5f-38d0cd7a2d64)
