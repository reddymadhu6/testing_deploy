Crypto_Data_Tracker

This project is a Node.js application that fetches cryptocurrency data (Bitcoin, Matic, and Ethereum) from CoinGecko, stores it in MongoDB, and provides various endpoints to retrieve and analyze this data.

Features

- Fetches real-time cryptocurrency data from CoinGecko (price, market cap, 24h change) every 2 hours.
- Provides an API `/stats` to get the latest data for a specified cryptocurrency.
- Provides an API `/deviation` to calculate the standard deviation of the price for a cryptocurrency based on the last 100 records in the database.

Installation

Prerequisites

1. **Node.js**: Ensure that you have Node.js installed on your system. You can download it from [nodejs.org](https://nodejs.org/).
2. **MongoDB**: You need a MongoDB instance running. You can use either a local MongoDB instance or a cloud-based MongoDB like MongoDB Atlas.

Setup

1. Clone the repository:
   ```bash
   git clone <repository-url>
