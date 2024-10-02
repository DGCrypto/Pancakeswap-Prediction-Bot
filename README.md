# Pancakeswap-Prediction-Bot
Pancakeswap Prediction Bot using RSI crossover trading strategy.

Disclaimer of Liability:

By using this program, scripts, code, or repository, you acknowledge and agree to the following:

All investment strategies and investments inherently involve risks, including the potential for financial loss. Nothing contained within this program, scripts, code, or repository should be interpreted as financial or investment advice, nor should it serve as a recommendation to make any specific financial decision. Any references to past or potential investment performance are for informational purposes only and do not guarantee any particular result or outcome. You assume full responsibility for any decisions or actions taken based on your use of this program, and you acknowledge that you are solely responsible for any financial outcomes, whether positive or negative. The developers of this program, as well as any contributors, collaborators, or affiliates, disclaim any and all liability related to the use, performance, or outcomes of this program. By using this program, you agree to hold harmless the developers and any associated parties from any claims, losses, damages, or liabilities, financial or otherwise, arising from your use of this program or any reliance on the information or functionality provided. Use of this program constitutes your full acceptance of these terms.

npm i web3 axios dotenv readline

Node index.js

Place private key and wallet address in ENV File and Save-as ".env"

PRIVATE_KEY=# indent to new line and add WALLET_ADDRESS WALLET_ADDRESS=#

.env file

Fill out .env file with account address, privkey.

NPM and node.js is needed to install and run.

Instructions!

Download index.js
"npm i web3 axios dotenv readline"
Fill out env file! Save as .env
Use command "Node index.js"
npm i web3 axios dotenv readline

Node index.js

Rsi thresholds for crossover are up to user discretion.

Recommend starting program with 1 minute before next round as oracle timing isn't implemented yet.

Bot has had stratrgies average up to 60% win rate in limited testing.

10% of profit from usage goes to development of script.
