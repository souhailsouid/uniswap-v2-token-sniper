# Uniswap V2 Token Sniper Bot

This project is a sniping bot that listens to liquidity events on Uniswap V2 and attempts to buy tokens as soon as liquidity is added.

## Features
- Monitors `PairCreated` events.
- Detects liquidity for token pairs.
- Executes buy transactions on liquidity addition.

## Installation
1. Clone this repository: `git clone https://github.com/yourusername/uniswap-v2-token-sniper.git`
2. Install dependencies: `npm install`
3. Set up your environment variables (e.g., Alchemy API key, wallet private key).
4. Run the bot: `node index.js`

## Usage
- Configure thresholds for liquidity in the code.
- Modify the logic as needed to fit different token sniping strategies.

## License
MIT License
