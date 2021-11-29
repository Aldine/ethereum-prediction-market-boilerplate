# `ethereum-prediction-market-boilerplate`

This Project is a fork of [Ethereum Boilerplate](https://github.com/ethereum-boilerplate/ethereum-boilerplate) and demostrates how you can build your own Ethereum Prediction Market. This project of course work on any EVM-compatible blockchain such as Polygon, Avalanche, Binance Smart Chain and other such chains.

<!-- ![dapp3](https://user-images.githubusercontent.com/78314301/140418251-18b4b3bc-2241-4174-886d-daafe9d6ad3b.gif) -->

# ⭐️ `Star us`
If this boilerplate helps you build Ethereum dapps faster - please star this project, every star makes us very happy!

# 🚀 Quick Start

📄 Clone or fork `ethereum-prediction-market-boilerplate`:
```sh
git clone https://github.com/ethereum-boilerplate/ethereum-prediction-market-boilerplate`.git
```
💿 Install all dependencies:
```sh
cd ethereum-prediction-market-boilerplate
yarn install 
```
✏ Rename `.env.example` to `.env` in the main folder and provide your `appId` and `serverUrl` from Moralis ([How to start Moralis Server](https://docs.moralis.io/moralis-server/getting-started/create-a-moralis-server)) 
Example:
```jsx
REACT_APP_MORALIS_APPLICATION_ID = xxxxxxxxxxxx
REACT_APP_MORALIS_SERVER_URL = https://xxxxxx.grandmoralis.com:2053/server
moralisApiKey = xxx
moralisApiSecret = xxx
```
🚴‍♂️ Run your App:
```sh
yarn start
```
