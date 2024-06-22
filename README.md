# 🚀 Pump.Fun Bump Bot: Automate Your Trading on Pump.fun & Raydium! 🚀

Free to use bump bot for your pump fun tokens.

This bot buy and sell automatically on pump.fun and raydium
 
it can be used to be displayed on the main page of pump.fun
# 📺 Demo
See the Pump.Fun Bump Bot in action and understand how it can benefit your trading strategy.
 [Youtube]

[![Demo](https://img.youtube.com/vi/9QUKFEqnRuU/0.jpg)](https://www.youtube.com/watch?v=9QUKFEqnRuU) 
  

🚀 Pump.Fun Bump Bot: Automate Your Trading on Pump.fun & Raydium! 🚀
Welcome to the Pump.Fun Bump Bot repository! This bot automates buying and selling on Pump.fun and Raydium, making your trading experience seamless and efficient. Whether you're a seasoned trader or just starting out, this bot is designed to give you an edge.

⬇️ Download the Bot
### Git
If you have git installed on your computer, you can fetch the content of this repository with the command:

git clone https://github.com/BOT-web3/Pump.FunBumpBot.git

### 📦 ZIP
Alternatively, you can download the repository as a ZIP file here.

### 💻 Replit
You can also use this bot on Replit, an online coding platform. Simply fork the repository and start coding without any setup hassle. Try it on Replit.

🔧 Environment Setup
You need to install Node.js:

- **Windows:** Download Node.js https://nodejs.org/dist/v22.2.0/node-v22.2.0-x64.msi
- **MacOS:** Download Node.js   https://nodejs.org/dist/v22.2.0/node-v22.2.0.pkg
- **Linux:** Execute in a terminal: 

curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.7/install.sh | bash
nvm install 22

To check if Node.js is installed, run the following command in your terminal or command prompt:

node -v
It should return the version of Node.js.

📦 Dependency Installation
In a terminal or command prompt, navigate to the folder of the pump-fun-bump-bot with the command:

cd /path/to/the/folder

Then, install all the dependencies with:

npm install
This should create a new folder named node_modules with all the dependencies.

⚙️ Setup Configuration in index.js
You have three things to set up:

- **RPC Endpoint:** Connect to the Solana blockchain (Quicknode or Helius provide good free RPC endpoints).
- **Private Key:** The private key of the wallet that will buy and sell.
- **Token Address:** The contract address of the token you want to bump.

The variables are at the top of the script:

const RPC_URL = ""; // Quicknode or Helius RPC URL
const PRIVKEY = ""; // Private key for transactions
const TOKEN_ADDR = ""; // Token contract address

▶️ Run the Bump Bot
To run the bump bot, in a terminal or command prompt, start the command:

node index.js
The bot will buy 4 times, then sell all the balance.

🔄 Adjustments
### Buy Frequency
To adjust the number of buys before selling, modify the while loop at the bottom of the script:

// Buy
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));

For example, to buy only 2 times, remove 2 lines:

// Buy
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));
promises.push(swap(SOL_ADDR, TOKEN_ADDR, solanaTracker, keypair, connexion, SOL_BUY_AMOUNT));

### Buy Amount
Adjust the amount of SOL to buy at the top of the script:

const SOL_BUY_AMOUNT = 0.011; // Adjust buy amount

### Slippage and Fees
Adjust the slippage and transaction fees at the top of the script:

const SLIPPAGE = 20; // Adjust slippage
const FEES = 0.0005; // Adjust fees

🔗 Links

- **Replit:** Try it on Replit https://replit.com/
- **helius:** https://helius.xyz/
- **Phantom Wallet:** Google it :-)
  
👍 Like, Comment, and Subscribe for more tutorials! 👍

Happy bumping and happy trading! 🚀💰

DONTATION SOL : 8oHBLten4hH8BoRngqi9NaBkGE7E5hs9qtVSW4rQ4Mj9









![visits](https://visit-counter.vercel.app/counter.png?page=https%3A%2F%2Fgithub.com%2FBOT-web3%2FPump.FunBumpBot&s=17&c=00ff00&bg=00000000&no=2&ff=digi&tb=&ta=)
